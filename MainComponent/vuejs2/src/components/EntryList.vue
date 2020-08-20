<template>
    <div>
        <entry 
            v-for="entryName in entriesListData" 
            :name="entryName.name" 
            :key="entryName.id"
        />
    </div>
</template>

<script>
import entry from './Entry'

export default {
    props: {
        entriesListData: {
            type: Array
        }
    },
    components: {
        entry
    }
}

</script>