<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Peer-Reviewed Publications</h2>


<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.ref }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.abstract %} 
      <a href="{{ link.abstract }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Abstract</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.doi %} 
      <a href="{{ link.doi }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">doi</a>
      {% endif %}
      {% if link.preprint %} 
      <a href="{{ link.preprint }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Preprint</a>
      {% endif %}
      {% if link.tool %} 
      <a href="{{ link.tool }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Tool</a>
      {% endif %}
      {% if link.artifact %} 
      <a href="{{ link.artifact }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Artifact</a>
      {% endif %}
      {% if link.video %} 
      <a href="{{ link.video }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Video</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>


{% endfor %}

</ol>
</div>

<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Other Works <temp style="font-size:15px;"></temp></h2>


<div class="publications">
<ol class="bibliography">

{% for link in site.data.preprint.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.ref }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Abstract</a>
      {% endif %}
      {% if link.abstract %} 
      <a href="{{ link.abstract }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.doi %} 
      <a href="{{ link.doi }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">doi</a>
      {% endif %}
      {% if link.preprint %} 
      <a href="{{ link.preprint }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Preprint</a>
      {% endif %}
      {% if link.tool %} 
      <a href="{{ link.tool }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Tool</a>
      {% endif %}
      {% if link.artifact %} 
      <a href="{{ link.artifact }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">artifact</a>
      {% endif %}
      {% if link.video %} 
      <a href="{{ link.video }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Video</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>



<br>


{% endfor %}

</ol>
</div>





