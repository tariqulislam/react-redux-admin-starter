# REACT REDUX ADMIN STARTER
Build for newbie and student to help, how to develop administrator protal for every site. how easily developer can ``` Learn about react redux``` and Implemented it to their site. This is not good starter kit who are looking for CMS(content management system). This Starter kit is good for who want to learn react redux from scratch.

# Table of Contents
- [Project Structure](#Project_structure)
- [Installation and Configure](#Installation_and_Configure)
- [Node and NPM commands and Scripts](#Node_and_NPM_commands_and_Scripts)
- [New Module development](#New_Module_development)
- [Redux Implementation for New Module](#Redux_Implementation_for_New_Module)
- [Simple CRUD operation](#Simple_CRUD_operation)
- [Testing with jest](#Testing_with_jest)
- [Web deployment](#Web_deployment)
   - [Apache](#Apache)
   - [Nginx](#Nginx)
   - [Node Server](#Node_Server)
- [Docker Implementation](#Docker_Implementation)

# Project_structure
-------------------------------------------------------------------------------------------------------------
|--build
|--config
|--public (static file to load in this starter kit)
|---- favicon.ico
|---- index.html
|---- mainfest.json
|--script
|---- build.js
|---- start.js
|---- test.js
|--src
|---- asset
|------ [cssfile.scss]
|------ [Static Image Files]
|---- component
|------ [Global Component Folder]
|------ [Global Component(.js)]
|---- container
|------ [Global Smart Component Folder]
|------ [Global Smart File(.js)]
|---- core
|------ initializeStore.js
|------ rootReducer.js
|------ withReducer.js
|---- reducers
|------ [Global Reducer Folder for Redux]
|------ [Global Reducer File(.js)]
|---- routes
|------ [Module Folder]
|-------- asset
|---------- [modulecssfile.scss]
|---------- [Static Image Files]
|-------- component
|---------- [Module Component Folder]
|---------- [Module Component File(.js)]
|-------- container
|---------- [Module smart component Folder]
|---------- [Module smart component File (.js)]
|-------- reducer
|---------- [Module Reducer File for Redux]
|-------- index.js (connect all the container and component for module wise redux store Lazy loading)
|---- routeSplit.js (Appling the code spliting to Each Module)
|---- shared
|------- [Global Shared Function File]
|---- test
|------- [React Test file(.test.js)]
|--.eslintrc
|--.gitignore
|--package-lock.json
|--package.json
|--postcss.config.js
------------------------------------------------------------------------------------------------------------------------
