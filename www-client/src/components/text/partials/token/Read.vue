<template>
  <span>{{ token.value }}<slot name='post'></slot></span>
</template>

<script>
import Base from './Base.vue';

export default {
  extends: Base
};
</script>
