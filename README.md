# Hipster Whisky Drink
thoughtbot's Bourbon and Bitters Sass Libraries combined with a Flexbox Grid System

## Getting Started
##### Base Styles
* `@import "hipster-whisky-drink/app-base";`

##### Variables, Mixins, Functions Only
* Ensure that the sass file includes `@import "hipster-whisky-drink/core";` at the top.

##### Class Based Flexbox Grid
* 12 column based grid
* App must be wrapped in `.l-grid` element
* Immediate children of `.l-grid` element should be `.l-rows`
* Immediate children of `.l-rows` should be `.l-col-#`
  * `#` being the column width you desire (1 - 12)

```html
<div class="l-grid">

  <div class="l-row">
    <div class="l-col-6"></div>
      <!-- Content.... -->
    <div class="l-col-6">
      <!-- Content.... -->
    </div>
  </div>

  <div class="l-row">
    <div class="l-col-4">
      <!-- Content.... -->
    </div>
    <div class="l-col-4">
      <!-- Content.... -->
    </div>
    <div class="l-col-4">
      <!-- Content.... -->
    </div>
  </div>

</div>
```

##### There are some helpers and shit I don't have time to document right now.... you figure it out
