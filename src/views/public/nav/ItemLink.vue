<template>
  <li class="nav-item" ref="li">
    <router-link class="nav-link" :to=link><slot></slot></router-link>
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
