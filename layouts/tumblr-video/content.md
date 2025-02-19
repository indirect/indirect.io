
{{ range last 1 .Params.tumblr.player }}
<div class="vidblock">{{ .embed_code | safeHTML }}</div>
{{ end }}
<div class="caption">{{ .Params.tumblr.caption | safeHTML }}</div>

