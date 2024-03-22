{{- .Scratch.Set "basedir" "https://zhangdian617.github.io/site/content/publication/" -}}
{{- .Scratch.Set "path" (.Get 0) -}}
{{- if hasPrefix (.Scratch.Get "path") "/" -}}
  {{- .Scratch.Set "path" (slicestr (.Scratch.Get "path") 1) -}}
{{- end -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
# Returns an absolute URL with a language prefix, if any.
{{- .Scratch.Get "basedir" | absLangURL -}}
