<template>
    <div class="mb-6 p-6 bg-white dark:bg-gray-900 rounded-lg shadow-md">
      <h4 class="text-xl font-semibold mb-2 dark:text-white">{{ title }}</h4>
      <p class="text-lg text-gray-600">{{ description }}</p>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      title: String,
      description: String,
    },
  };
  </script>
  