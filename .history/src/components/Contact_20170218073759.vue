<template>
  <div class="contact app-viewport">
    <md-sidenav class="md-left md-fixed" ref="sidebar">
    <md-toolbar>
    <h1 class="md-title" style="flex: 1">My Title</h1>
    <md-button class="md-icon-button">
      <md-icon>more_vert</md-icon>
    </md-button>
  </md-toolbar>
  
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
  </div>
</template>

<script>
  export default {
    name: 'contact'
  }
</script>
