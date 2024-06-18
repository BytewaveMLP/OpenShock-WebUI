<template>
  <li class="nav-item" ref="li">
    <a class="nav-link" :href=link><slot></slot></a>
  </li>
</template>

<script>
export default {
  props: ["link"],
  mounted() {

  },
  methods: {

  }
}
</script>
