<template>
    <div class="dropdown-container">
      <BDropdown id="dropdown-1" text="image type" class="m-md-2">
        <BDropdownItem>logo</BDropdownItem>
        <BDropdownItem>wallpaper</BDropdownItem>
        <BDropdownItem>background image</BDropdownItem>
      </BDropdown>
    </div>
  </template>
  
  <script>
  export default {
    name: 'DropdownComponent'
  }
  </script>
  
  <style scoped>
  .dropdown-container {
    position: absolute;
    left: 21%;
    top: 30%;
    display: inline-block;
  }
  /* Add any component-specific styles here */
  </style>
  