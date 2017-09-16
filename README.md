## Prerequisites
Node.js and npm are essential to Angular development.

<a href="https://docs.npmjs.com/getting-started/installing-node" target="_blank" title="Installing Node.js and updating npm">
Get it now</a> if it's not already installed on your machine.

**Verify that you are running at least node `v4.x.x` and npm `3.x.x`**
by running `node -v` and `npm -v` in a terminal/console window.
Older versions produce errors.

We recommend [nvm](https://github.com/creationix/nvm) for managing multiple versions of node and npm.

## Install npm packages
After you have cloned the repository, install the npm packages described in the `package.json` and verify that it works:

```shell
npm install
npm install -g @angular/cli
npm start
```

>Doesn't work in _Bash for Windows_ which does not support servers as of January, 2017.

The `npm start` command first compiles the application,
then simultaneously re-compiles and runs the `lite-server`.
Both the compiler and the server watch for file changes.

Shut it down manually with `Ctrl-C`.

You're ready to view the application in your browser by navigating to the address

```shell
localhost:4200
```

# Other Kendo UI Sample Projects for Angular

|Sample Project Repository                                        |Sample Project Documentation |
|:---                                                             |:---                         |
|[Using Kendo UI with the Angular CLI](https://github.com/telerik/kendo-angular-quickstart-cli) |[Get Started](http://www.telerik.com/kendo-angular-ui/getting-started/)|
|[Using Kendo UI for Angular with Angular Seed](https://github.com/telerik/kendo-angular-quickstart-seed)  |Not documented        |
|[Using Kendo UI for Angular with Angular Universal](https://github.com/telerik/kendo-angular-universal-demo) |[Universal Rendering](http://www.telerik.com/kendo-angular-ui/components/framework/universal/)|
|[Using Kendo UI for Angular with UI for ASP.NET Core](https://github.com/telerik/kendo-angular-demo-aspnetcore-data/tree/master) |[UI for ASP.NET Core Integration](http://www.telerik.com/kendo-angular-ui/components/dataquery/mvc-integration/)|
|[Using Kendo UI for Angular with NativeScript](https://github.com/telerik/ng2-dashboard)                     |Not documented   |
|[Translating the custom messages of the Kendo UI components for Angular](https://github.com/telerik/kendo-angular-i18n-sample) |[Translation of Messages](http://www.telerik.com/kendo-angular-ui/components/localization/messages/)|