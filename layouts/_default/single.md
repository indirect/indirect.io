---
{{- if .Title }}title: {{ .Title }}{{ end }}
date: '{{ .Date | safeHTML }}'
{{- if .Params.Tumblr.slug }}
slug: {{ .Params.Tumblr.slug }}{{ end }}
{{- if .Params.Tumblr.tags }}
tags: {{ delimit .Params.Tumblr.tags "," }}{{ end }}
---
{{ .Render "content" }}
