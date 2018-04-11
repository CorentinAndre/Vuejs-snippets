[![Installs!](https://img.shields.io/apm/dm/vuejs2-snippets.svg?style=flat-square)](https://atom.io/packages/vuejs2-snippets)
[![Version!](https://img.shields.io/apm/v/vuejs2-snippets.svg?style=flat-square)](https://atom.io/packages/vuejs2-snippets)
[![License](https://img.shields.io/apm/l/vuejs2-snippets.svg?style=flat-square)](https://github.com/CorentinAndre/Vuejs-snippets/blob/master/LICENSE)

# Vuejs-snippets

Collection of Vue.js snippets for version 2.0+.
Also supports Vuex, vue-router still missing.

Feel free to contribute to this package by submitting a PR!

## Usage

Just press `TAB` or `ENTER` to unfold a snippet

### Single file template

```html
template          <!--Single file component template-->
```

### HTML snippets

```html
router-view       <!--Vuejs router-view component-->
router-link       <!--Vuejs router-link component with named route-->
component         <!--Include component in HTML-->
sccomponent       <!--Include self closed component in HTML-->
i18n              <!--Include internationalization component-->
```

### HTML tags

```html
v-for             <!--Vuejs binding for list rendering-->
v-if              <!--Vuejs binding for if conditional rendering-->
v-else-if         <!--Vuejs binding for else if rendering-->
v-else            <!--Vuejs binding for else conditional rendering-->
v-show            <!--Vuejs binding for show conditional rendering-->
v-model           <!--Vuejs binding for model binding-->
vClassObj         <!--Vuejs binding for class as an object-->
vClassArr         <!--Vuejs binding for class as an array-->
```

### Javascript

```javascript
beforeCreate; // Vuejs instance lifecycle hook for beforeCreate
created; // Vuejs instance lifecycle hook for created
beforeMount; // Vuejs instance lifecycle hook for beforeMount
mounted; // Vuejs instance lifecycle hook for mounted
beforeUpdate; // Vuejs instance lifecycle hook for beforeUpdate
updated; // Vuejs instance lifecycle hook for updated
beforeUpdate; // Vuejs instance lifecycle hook for beforeUpdate
updated; // Vuejs instance lifecycle hook for updated
beforeDestroy; // Vuejs instance lifecycle hook for beforeDestroy
destroyed; // Vuejs instance lifecycle hook for destroyed
beforeRouteEnter; // Vue-router instance lifecycle hook for beforeRouteEnter
beforeRouteUpdate; // Vue-router instance lifecycle hook for beforeRouteUpdate
beforeRouteLeave; // Vue-router instance lifecycle hook for beforeRouteLeave
vwatch; // Vuejs way to watch instance properties
methods; // Vuejs methods event handlers
components; // Use it when you want to add child components to parent component.
props; // Vuejs way to pass data to child components
vprops; // Vuejs way to pass data to child components with validation
vcomputed; // Vuejs computed property
```

### Vuex

```javascript
vstore; // Vuex template for a complete store with state,getters,actions and mutations
vmut; // Vuex mutation snippet
vact; // Vuex action snippet
vget; // Vuex getter snippet
vtype; // Vuex constant type snipppet
```
