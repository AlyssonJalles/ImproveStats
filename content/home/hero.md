+++
# Hero widget.

date = 2017-10-15
draft = false

title = "Ciência de dados"
widget = "hero"

# Order that this section will appear in.
weight = 3

# Overlay a color or image (optional).
#   Deactivate an option by commenting out the line, prefixing it with `#`.
[header]
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/pensando.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

# Call to action button (optional).
#   Activate the button by specifying a URL and button label below.
#   Deactivate by commenting out parameters, prefixing lines with `#`.
[cta]
  url = "./01/12/2017/iniciando-na-ciência-de-dados/"
  label = '<i class="fa fa-book"></i> Iniciando na ciência de dados'
+++

Arte de transformar dados em informações valiosas na era do big data :pager: :1234: :chart_with_upwards_trend: :bar_chart:
<br>
<small><a id="academic-release" href="https://github.com/alyssonjalles/ImproveStats/">Contribua no github!</a></small>
<br><br>
<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=alyssonjalles&amp;repo=ImproveStats&amp;type=star&amp;count=true&amp;size=large" scrolling="0" width="160px" height="30px" frameborder="0"></iframe>
<iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=alyssonjalles&amp;repo=ImproveStats&amp;type=fork&amp;count=true&amp;size=large" scrolling="0" width="158px" height="30px" frameborder="0"></iframe>

<script type="text/javascript">
  (function defer() {
    if (window.jQuery) {
      jQuery(document).ready(function(){
        GetLatestReleaseInfo();
      });
    } else {
      setTimeout(function() { defer() }, 50);
    }
  })();  
  function GetLatestReleaseInfo() {
    $.getJSON('https://api.github.com/repos/alyssonjalles/ImproveStats/tags').done(function (json) {
      let release = json[0];
      // let downloadURL = release.zipball_url;
      $('#academic-release').text('última atualização ' + release.name);  
    });    
}  
</script>
