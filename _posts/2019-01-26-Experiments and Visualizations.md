
<h1 class="section-front-header-module__title">Python Visualizations</h1>


<br />
<h1 class="section-front-header-module__title">Tableau Visualizations</h1>  
  <body>
    .module {
  background-image: url(https://public.tableau.com/javascripts/api/viz_v1.js);
}
  const el = document.querySelector("#module");

el.addEventListener("mousemove", (e) => {
  el.style.backgroundPositionX = -e.offsetX + "px";
  el.style.backgroundPositionY = -e.offsetY + "px";
});
  <div class="module" id="module">
  <div class='tableauPlaceholder' id='viz1552855890012' style='position: static' scrolling="yes"><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fu&#47;FuturesTrend&#47;YieldSearch&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FuturesTrend&#47;YieldSearch' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fu&#47;FuturesTrend&#47;YieldSearch&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1552855890012');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height='991px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
</div>
</body>