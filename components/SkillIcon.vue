<template>
    <div class="flex items-center mb-4">
      <Icon :name="icon" class="text-4xl mr-2" />
      <span class="text-lg">{{ title }}</span>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      icon: String,
      title: String,
    },
  };
  </script>
  