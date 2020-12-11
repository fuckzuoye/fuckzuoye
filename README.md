### Hi,这里是保温杯的Github!😁
{% raw %}
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
<script>
  fetch('https://v1.hitokoto.cn')
    .then(response => response.json())
    .then(data => {
      const hitokoto = document.getElementById('hitokoto_text')
      hitokoto.href = 'https://hitokoto.cn/?uuid=' + data.uuid
      hitokoto.innerText = data.hitokoto
    })
    .catch(console.error)
</script>
{% endraw %}
<p id="hitokoto"><span href="#" id="hitokoto_text">:D 获取中...</span></p>
***
<span id="busuanzi_container_site_pv">本站总访问量<span id="busuanzi_value_site_pv"></span>次</span>
