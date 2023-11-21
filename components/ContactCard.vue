<template>
    <a :href="link" target="_blank" rel="noopener noreferrer"
      class="w-64 bg-white dark:bg-gray-800 p-4 rounded-lg shadow-md flex items-center">
      <Icon :name="icon" class="text-2xl w-8 h-8" />
      <div class="ml-3">
        <p class="font-semibold text-lg">{{ title }}</p>
        <p class="text-gray-600 text-sm">{{ content }}</p>
      </div>
    </a>
  </template>
  
  <script>
  export default {
    props: {
      title: String,
      icon: String,
      link: String,
      content: String,
    },
  };
  </script>
  