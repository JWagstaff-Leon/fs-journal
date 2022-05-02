# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The page brought up on the base route (<domain>/#/)
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A page is a component that is routed to instead of being nested, a component is nested inside a page or component
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for with unique keys
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template>
<script>
<style>
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle; a parent class should be able to be substituted by a child class
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
<router-view>
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState can be accessed by any component, while the component state is only valid for its repective component
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
To process requests from the controllers (components), communicate with external resources, and update the appstate.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
1. style
2. scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
computed()
```