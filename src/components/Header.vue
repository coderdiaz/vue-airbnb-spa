<template>
  <header class="header">
    <div class="container mx-auto">
      <nav class="flex justify-between">
        <div class="flex items-center flex-no-shrink">
          <span>Airbnb SPA</span>
        </div>
        <div class="w-auto block flex-grow">
          <ul class="list-reset flex justify-end">
            <li class="mr-4">
              <a href="#">Home</a>
            </li>
            <li class="mr-4">
              <a href="#">About</a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>
