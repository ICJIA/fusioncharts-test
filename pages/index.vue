<template>
  <section class="container">
    <no-ssr>
    <div id="chart-container">
            <fusioncharts
            type="illinois"
            width="550"
            height="350"
            dataFormat="json"
            ></fusioncharts>
        </div>
    </no-ssr>
  </section>
</template>

<script>

export default {
  components: {
    
  },
  data () {
    return {
      "type": "illinois",
            "renderAt": "chart-container",
            "width": "550",
            "height": "350",
            "dataFormat": "json",
    }
  }
}
</script>

<style>


</style>
