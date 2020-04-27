<template>
  <div>
    <!-- content -->
    search Page

    <search-box></search-box>
    <result-list></result-list>
  </div>
</template>

<script>
import SearchBox from '../components/SearchBox'
import ResultList from '../components/ResultList'

export default {
  components: {
    SearchBox,
    ResultList
  }
  // name: 'PageName',
}
</script>
