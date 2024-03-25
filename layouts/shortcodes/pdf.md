 {{- .Scratch.Set "basedir" "https://zhangdian617.github.io/site/publication/" -}}
 {{- .Scratch.Set "path" (.Get 0) -}}

 {{- if hasPrefix (.Scratch.Get "path") "/" -}}
   {{- .Scratch.Set "path" (slicestr (.Scratch.Get "path") 1) -}}
   {{- end -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}

{{- .Scratch.Add "basedir" "/" -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
{{- .Scratch.Add "basedir" ".pdf" -}}

<a href={{- .Scratch.Get "basedir" | relURL -}} /a>

