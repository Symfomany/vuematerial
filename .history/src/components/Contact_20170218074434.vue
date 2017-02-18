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


   <md-card class="md-primary" md-theme="blue" md-with-hover>
      <md-card-media>
        <img src="http://placekitten.com/200/300" alt="People">
      </md-card-media>

      <md-ink-ripple></md-ink-ripple>

      <md-card-actions>
        <md-button class="md-icon-button">
          <md-icon>favorite</md-icon>
        </md-button>

        <md-button class="md-icon-button">
          <md-icon>bookmark</md-icon>
        </md-button>

        <md-button class="md-icon-button">
          <md-icon>share</md-icon>
        </md-button>
      </md-card-actions>
    </md-card>



  <!--end page layout-->
  </div>

  <!--end app-->
  </div>
</template>

<script>
  export default {
    name: 'contact'
  }
</script>
