<template>
  <div>
    <b-row>
      <b-col cols="12">
        <CompanyTabs />
      </b-col>
    </b-row>
  </div>
</template>

<script>

import {
  BRow,
  BCol,
  VBTooltip,
} from 'bootstrap-vue'

import CompanyTabs from './CompanyTabs.vue'

export default {
  name: 'CompanyView',
  components: {
    BRow,
    BCol,
    CompanyTabs,
  },
  directives: {
    'b-tooltip': VBTooltip,
  },
  data() {
    return {
    }
  },
  created() {},
  methods: {},
}
</script>

<style>
/*  */
</style>
