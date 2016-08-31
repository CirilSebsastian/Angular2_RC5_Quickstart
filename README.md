# Angular2_RC5_Quickstart
Intro to NgModule.. An Hello world app


Prerequisite: Install Node.js
Step 1: Create the app’s project folder and define package dependencies and special project setup
Step 2: Create the app’s Angular root component
Step 3: Create an Angular Module
Step 4: Add main.ts, identifying the root component to Angular
Step 5: Add index.html, the web page that hosts the application
Step 6: Build and run the app

The @NgModule decorator defines the metadata for the module. We'll take an intuitive approach to understanding the metadata and fill in details as we go.

This metadata imports a single helper module, BrowserModule, the module every browser app must import.

BrowserModule registers critical application service providers. It also includes common directives like NgIf and NgFor which become immediately visible and usable in any of this modules component templates.

The declarations list identifies the application's only component, the root component, the top of this app's rather bare component tree.

The @NgModule.bootstrap property identifies "AppComponent" as the bootstrap component. When Angular launches the app, it places the HTML rendering of AppComponent in the DOM, inside the <my-app> element tags of the index.html
