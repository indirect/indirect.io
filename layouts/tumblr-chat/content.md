
<dl class="conversation">
{{ range .Params.tumblr.dialogue }}
<div class="line">
{{ with .name }}
<dt class="person">{{ . }}</dt>
{{ end }}
<dd class="person-said">{{ .phrase }}</dd>
</div>
{{ end }}
</dl>

