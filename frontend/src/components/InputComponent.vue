<script>
export default {
  name: 'InputComponent',
  data() {
    return {
      inputValue: ''
    }
  }
}
</script>

<template>
  <div class="input-container">
    <input 
      type="text" 
      class="form-control" 
      placeholder="Enter your imagination here..."
      v-model="inputValue"
    />
  </div>
</template>

<style scoped>
.input-container {
  position: absolute;
  left: 21%;
  top: 45%;
  width: 300px;
}

.form-control {
  width: 100%;
  padding: 8px 12px;
  border: 1px solid #ced4da;
  border-radius: 4px;
  font-size: 16px;
}

.form-control:focus {
  outline: none;
  border-color: #80bdff;
  box-shadow: 0 0 0 0.2rem rgba(0,123,255,.25);
}
</style>