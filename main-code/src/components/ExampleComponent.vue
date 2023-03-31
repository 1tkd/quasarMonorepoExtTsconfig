<template>
  <div>
    <p>mainComp {{ func1() }}</p>
    <LIbComp1></LIbComp1>
  </div>
</template>

<script setup lang="ts">

import LIbComp1 from 'lib/LibComp.vue'
import {func1} from  'lib/utilcode'


</script>
