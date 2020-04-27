<template>
  <div>
    My Menu Page!

    <q-btn
      @click="goSearch"
    >
    검색
    </q-btn>
  </div>
</template>

<script>
export default {
  // name: 'PageName',
  methods: {
    goSearch () {
      this.$router.push({ path: '/search' })
    }
  }
}
</script>
