---
{{- if .Title }}title: {{ .Title }}{{ end }}
date: '{{ .Date.Local.Format "2006-01-02T15:04:05Z0700" }}'
{{- if .Params.Tumblr.slug }}
slug: {{ .Params.Tumblr.slug }}{{ end }}
{{- if .Params.Tumblr.tags }}
tag: {{ delimit .Params.Tumblr.tags "," }}{{ end }}
---
{{ `<!--` | safeHTML -}}
{{ dict "tumblr_id" .Params.Id "tumblr_path" (index .Params.Aliases 0) | jsonify }}
{{- `-->` | safeHTML }}

{{ .Render "content" }}
