<template>
  <div>
    <div id="he-plugin-simple" />
  </div>
</template>

<script>
export default {
  mounted() {
    window.WIDGET = {
      'CONFIG': {
        'modules': '10234',
        'background': '1',
        'tmpColor': 'FFFFFF',
        'tmpSize': '16',
        'cityColor': 'FFFFFF',
        'citySize': '16',
        'aqiColor': 'FFFFFF',
        'aqiSize': '16',
        'weatherIconSize': '24',
        'alertIconSize': '18',
        'padding': '10px 10px 10px 10px',
        'shadow': '0',
        'language': 'auto',
        'borderRadius': '5',
        'fixed': 'false',
        'vertical': 'top',
        'hover': 'true',
        'horizontal': 'left',
        'key': '46b1748c9dfa458eaa6a83c9d3da890e'
      }
    };
    (function(d) {
      var c = d.createElement('link')
      c.rel = 'stylesheet'
      // c.href = '../static/css/he-simple.css';
      c.href = 'https://widget.heweather.net/simple/static/css/he-simple.css?v=1.4.0'
      var s = d.createElement('script')
      // s.src = '../static/js/he-simple.js';
      s.src = 'https://widget.heweather.net/simple/static/js/he-simple.js?v=1.4.0'
      var sn = d.getElementsByTagName('script')[0]
      sn.parentNode.insertBefore(c, sn)
      sn.parentNode.insertBefore(s, sn)
    })(document)
  }
}
</script>

<style scoped>

</style>
