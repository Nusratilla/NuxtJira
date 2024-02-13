<script lang="ts" setup>
const doc = 'Documentation'
const route = useRoute()
</script>

<template>
  <div>
    <div>
      <h1>
        {{ doc }} id: 17.55 {{ route.params.slug }}
      </h1>
    </div>
  </div>
</template>



<style lang="scss" scoped></style>