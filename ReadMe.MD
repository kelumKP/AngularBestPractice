# Angular Best Practices

##### Project and folder organization
##### Basic coding best practices
##### Component and services best practice
##### Important performance best practices
##### Angular module organization


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

Locate code quickly

Identify code at a glance

Flattest structure possible

Try to be DRY

File Naming : Component


- File name should be in lowercase
- Name should match with the name used in routing
- Multipart name should be separated by ‘
- Style file as well as the HTML file should also be given the same name

Example:
Component Name: item supervision.component.ts
Style File Name (for css): item supervision.component.css
HTML File Name: item supervision.component.html

Best Practice:
- Always use Angular CLI to create a component
- ng g c initialization/item supervision
- g - short form of ‘generate’
- c - short form of component