<template>
  <div class="contact">

    <md-toolbar>
      <h1 class="md-title" style="flex: 1">My Title</h1>
      <md-button class="md-icon-button">
        <md-icon>more_vert</md-icon>
      </md-button>
    </md-toolbar>
  
  <div class="page-layout">

    <md-list>
        <md-list-item>
          <md-checkbox class="md-primary md-list-action"></md-checkbox>
          <span class="item-text">French bread</span>
        </md-list-item>

        <md-list-item>
          <md-checkbox :value="true" class="md-primary md-list-action"></md-checkbox>
          <span class="item-text">Brazilian Cheese Bread</span>
        </md-list-item>

        <md-list-item>
          <md-checkbox class="md-primary md-list-action"></md-checkbox>
          <span class="item-text">Italian Bread</span>
        </md-list-item>
      </md-list>

  <md-theme md-name="teal">
    <md-button class="md-primary">Primary Button</md-button>
    <md-button class="md-accent">Accent Button</md-button>
    <md-button class="md-raised md-primary">Raised Primary Button</md-button>
  </md-theme>
  
  <md-theme md-name="purple">
    <md-button class="md-primary">Primary Button</md-button>
    <md-button class="md-accent">Accent Button</md-button>
    <md-button class="md-raised md-primary">Raised Primary Button</md-button>
  </md-theme>

  <!--end page layout-->
  </div>

  </div>
</template>

<script>
  export default {
    name: 'contact'
  }
</script>
