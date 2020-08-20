# Plan/roadmap/strategies

## Centralized component to use in everywhere

Defining *everywhere*:

* Desktop application
* Web application

This is possible only by adopting a language that is used both by a framework development that is designed for web and for desktop application as well.

The answer for this is *javascript*. We already have the frameworks developed as well. 

Lets create a central component that is responsible for:
* Configure credential data for AWS
* Manage interactions
* Theming system

Then requires it in the web application or by **Electron.js**, which will be used to create desktop applications for Windows, Linux and Mac OS.

Let's also make the use of the **Vue.js 2** for easy development of component. Let's call it as **MainComponent**.
