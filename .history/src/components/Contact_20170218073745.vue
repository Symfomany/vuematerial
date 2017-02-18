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
<style>
html,
body,
.app-viewport {
  height: 100%;
  overflow: hidden;
}

.app-viewport {
  display: flex;
  flex-flow: column;
}

.main-toolbar {
  position: relative;
  z-index: 10;
}

.md-fab {
  margin: 0;
  position: absolute;
  bottom: -20px;
  left: 16px;
  z-index: 10;
}
.md-fab .md-icon {
  color: #fff;
}

.md-title {
  padding-left: 8px;
  color: #fff;
}

.main-content {
  position: relative;
  z-index: 1;
  overflow: auto;
}

.md-list-action .md-icon {
  color: rgba(0, 0, 0, 0.26);
}

.md-avatar-icon .md-icon {
  color: #fff !important;
}

.md-sidenav .md-list-text-container > :nth-child(2) {
  color: rgba(255, 255, 255, 0.54);
}

.md-account-header .md-list-item:hover .md-button:hover {
  background-color: inherit;
}
.md-account-header .md-avatar-list .md-list-item-container:hover {
  background: none !important;
}


</style>
