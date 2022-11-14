# Angular Best Practices

## Project and folder organization
## Basic coding best practices
## Component and services best practice
## Important performance best practices
## Angular module organization


## Required Prerequisites

##### Basic TypeScript
https://app.pluralsight.com/library/courses/typescript/

##### Basic HTML
https://app.pluralsight.com/paths/skills/html

#####  Fundamental Angular
https://app.pluralsight.com/library/courses/angular
fundamentals/



## Project and Folder Organization

- File Naming
- Folder Structure
- One Item per File


## File and Folder Structure

# LIFT

**L**ocate code quickly

**I**dentify code at a glance

**F**lattest structure possible

**T**ry to be DRY

# File Naming : Component


*  File name should be in lowercase
*  Name should match with the name used in routing
*  Multipart name should be separated by ‘
*  Style file as well as the HTML file should also be given the same name

##### Example:

- Component Name  : item supervision.component.ts
- Style File Name (for css)  : item supervision.component.css
- HTML File Name  : item supervision.component.html

##### Best Practice:
* Always use Angular CLI to create a component
* ng g c initialization/item supervision
* g - short form of ‘generate’
* c - short form of component

# File Naming : Module, Service, Directive, pipe & Others

- File name should be in lowercase
- Multipart name should be separated by ‘
- Name should be followed by the item (.service / .directive / .pipe)

##### Example:

Module : initialization.module.ts
Service : initialization.service.ts
Directive : access check.directive.ts
pipe : uom conversion.pipe.ts

##### Best Practice:
- Always use Angular CLI to create...
- ng g m initialization
- ng g s initialization/initialization
- ng g d access check
- ng g p uom conversion

# Folder Structure : Considerations

- Easy to Find
- Scalability
- Multiple Team / People

##### Example:
- Component : Should have it’s own folder and contains all 4 files related to the component.(Refer
- Feature : Feature module should have its own folder and contains the component, service and route

##### Exception  : Component Folder - 
- If there are not many components in a feature module then each component need not to have it’s own folder.
- Flattest Structure Possible
- Maximum 7 files per Folder

# One Item Per File

- Easy to Locate the file
- Multiple Team / People

##### Example: 
- Component, Service, pipe, directive... : All Should have it’s own file. Should not be written inside another component’s / service’s …

# General Coding Best Practice

## Single Responsibility Principle
## Symbol naming
## Preferring immutability
## Using Small Functions
## Reactive Form Validators