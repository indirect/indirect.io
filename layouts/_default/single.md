---
{{ if .Aliases }}aliases: {{ .Aliases | jsonify }}{{ end }}
{{- if .Title }}title: {{ .Title }}{{ end }}
date: '{{ .Date.Local.Format "2006-01-02T15:04:05Z0700" }}'
{{- if .Params.Tumblr.slug }}
slug: {{ .Params.Tumblr.slug }}{{ end }}
{{- if .Params.Tumblr.tags }}
tag: {{ delimit .Params.Tumblr.tags "," }}{{ end }}
tumblr_id: {{ .Params.id }}
tumblr_path: {{ index .Params.aliases 0 }}
---
{{ .Render "content" }}
