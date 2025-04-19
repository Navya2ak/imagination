<script>
export default {
  name: 'ImageHolderComponent',
  data() {
    return {
      imageUrl: ''
    }
  }
}
</script>


<template>
  <div class="image-holder">
    <div class="image-container">
      <img v-if="imageUrl" :src="imageUrl" alt="Generated image" class="preview-image" />
      <div v-else class="placeholder">
        <span>Image will appear here</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.image-holder {
  position: absolute;
  right: 21%;
  top: 10%;
  width: 400px;
}

.image-container {
  width: 100%;
  height: 400px;
  border: 2px dashed #ced4da;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f8f9fa;
}

.placeholder {
  color: #6c757d;
  font-size: 16px;
  text-align: center;
}

.preview-image {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
</style>