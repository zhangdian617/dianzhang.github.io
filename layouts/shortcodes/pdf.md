{{- .Scratch.Set "basedir" "https://zhangdian617.github.io/site/content/publication/" -}}
{{- .Scratch.Set "path" (.Get 0) -}}
# Reports whether the given string begins with the given prefix.
{{- if hasPrefix (.Scratch.Get "path") "/" -}}
  {{- .Scratch.Set "path" (slicestr (.Scratch.Get "path") 1) -}}
{{- end -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
# Add folder name
# {{- .Scratch.Add "basedir" "/(.Scratch.Get "path")" -}}
# {{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
# {{- .Scratch.Add "basedir" ".pdf" -}}
# Returns an absolute URL with a language prefix, if any.
{{- .Scratch.Get "basedir" | absLangURL -}}
