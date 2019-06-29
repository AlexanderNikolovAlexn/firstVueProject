<template>
  <form v-if="!loading" class="form" v-on:submit="onSubmit">
    <div class="input-field">
      <label for="title">Title</label>
      <input type="text" name="title" v-model="title" class="validate">
      <span class="helper-text" data-error="Title must not be empty"></span>
    </div>
    <div class="input-field">
      <label for="body">Body</label>
      <input type="text" name="body" v-model="body" class="validate">
      <span class="helper-text" data-error="Body must not be empty"></span>
    </div>
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
</style>

