# Week 10: The Front End

The back-end-y front-end, and the front-end-y front-end.

-----

## Backbone (Classroom 2)

### Models and Collections (1)

- Describe the benefits of using a front end framework
- Explain how libraries differ from frameworks.
- Define a new backbone model and create instances
- Perform CRUD actions on a backbone model

### Models and Collections (2)

- Explain what a collection is in backbone
- Define a new backbone collection
- Use the backbone collection to store models
- Perform CRUD on a collection
- Install backbone into a rails application
- Associate a backbone model and collection with a rails backend
- Perform CRUD actions using backbone's RESTful API
- Compare BB models with AR models


### Views and Events: Models
- Define the role of a View in a Backbone app
- Define the role of an `el` in a Backbone View
- Differentiate between an "assigned" `el` and a "constructed" `el`
- Use a Backbone View to render a Model's data in the browser
- Use handlebars templates in BB to simplify rendering a view
- Make a View "listen for" and respond to DOM events
- Make a View "listen for" and respond to Model events

### Views and Events: Collections
- Define the role of a Collection View in a Backbone app
- Write a View that renders several Models' data in the browser
- Make a view "listen for" and respond to events generated by multiple models

### Routers (1)
- Explain what role a router plays in a front-end application.
- Identify the router's role in the Backbone MVC model.
- List the responsibilities of the Backbone router.
- Define static routes, actions and initialize a router.
- Define dynamic routes.
- Give examples of using :params in routes and actions.
- Recall the order in which routes are matched.
- Differentiate between `pushState : true` and `pushState : false`
- Describe of `trigger` as it applies to actions and routes

### Routers (2)

-----

## Front-end design (Classroom 1)

### Sass (1)
- Explain what a preprocessor is and what problem it solves
- Contrast sass and scss format
- Use variables and nesting to dry up CSS
- Use color functions to create dynamic color schemes
- Explain what `&` is and why we use it
- Use @include and @extend to create mixins and inherit from other rules


### Sass (2)
- Use control directives for conditionals (@if)
- Use control directives for loops (@for, @each and @while)
- Use pure Sass functions to make reusable logic
- Create a Pull Request to sass


### Bootstrap
- Explain the benefits (and shortcomings) of using a design framework.
- Describe the use cases for using Bootstrap as a library versus as a framework.
- List 10 useful classes from the Bootstrap library.
- Compare and contrast Bootstrap with other front-end frameworks (e.g., Foundation and Material Design).

### Foundation

- List 3 ways Foundation is different from Bootstrap
- Describe a situation in which using Foundation might be preferable to using Bootstrap, and a situation in which the reverse is true
- Explain what is meant by "breadcrumbs"
- Explain the concepts of graceful degradation and progressive enhancement.

### Leaflet and Map APIs
- While using the leaflet JS library:
  - create a map using
  - create markers on a map
  - create popups
  - handle events on a map
- Explain what geoJSON is and how map apis like leaflet utilize it.

### Flex-box
- ** what problem does it solve? **
- Given a desktop-first webpage, make it look presentable on mobile devices (and vice-versa) with as little CSS as possible
- Contrast Flex Containers and Flex Items
- Determine browser compatability and appropriate vendor prefixing.
- Draw a diagram that includes: Flex Container, Flex Item, Main and Cross Axes, Starts and Ends for all Axes, and Main and Cross Sizes
- Contrast `align-items` and `align-self`
- Explain what is meant by the "Holy Grail Layout"

### jQuery Plug-ins

- Define what a jQuery plugin is
- Describe where to find existing jQuery Plugins (and how to install them)
- Research and utilize a published jQuery Plugin
- Describe the basic structure of a jQuery Plugin
- Write your own jQuery Plugin
- Utilize an Immediately Invoked Function Expression (IIFE) to locally scope jQuery

### Pseudo-selectors and pseudo-elements

- Describe what pseudo means in the context of CSS
- Describe how to select even and odd elements on a page
- Make a page multi-paginated without using Javascript
- Create custom radio buttons and drop-down menus using CSS
