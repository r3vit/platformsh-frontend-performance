<template>
  <footer class="footer">
    <!-- This should be `0 items left` by default -->
    <span class="todo-count"
      ><strong>{{ length }}</strong> items</span
    >
    <!-- Remove this if you don't implement routing -->
    <!-- <ul class="filters">
      <li>
        <a class="selected" href="#/">All</a>
      </li>
      <li>
        <a href="#/active">Active</a>
      </li>
      <li>
        <a href="#/completed">Completed</a>
      </li>
    </ul> -->
    <!-- Hidden if no completed items are left ↓ -->
    <!-- <button class="clear-completed">Clear completed</button> -->
  </footer>
</template>

<script>
export default {
  name: "controls",
  props: {
    length: Number
  }
};
</script>
