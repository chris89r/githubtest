# Windows 8 App for ownCloud

## Content
1. Overview
2. Architecture
3. File structure
4. Design principles and hints

## 1. Overview
The windows app was originally developed by a Bachelor project seminar team at the University of Münster as a prototype for a cloud storage frontend.
The initial concept used a flexible approach concerning backends and frontends which is reflected in the architecture decisions as described below.

## 2. Architecture
The general architecture of the app includes 3 layers:
1. The server component
2. A framework with interfaces to frontend and backend. It is written in JavaScript and part of the app package.
3. The frontend view of 

As can be seen in the diagram, the original layout included multiple frontends and backends. Apart from the focus on ownCloud, Sharepoint (more precisely: Office 365 libraries) was supported as possible backend with a more limited scope of functions. Other frontends for mobile apps were developed as proof-of-concept, but are currently not further developed (there are alternatives like the native ownCloud apps).
![windows8 app architecture overview](https://github.com/chris89r/raw/master/res/images/architecture_overview.png "Windows 8 app architecture overview")

