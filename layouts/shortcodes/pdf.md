 {{- .Scratch.Set "path" (.Get 0) -}}

 {{- if hasPrefix (.Scratch.Get "path") "/" -}}
   {{- .Scratch.Set "path" (slicestr (.Scratch.Get "path") 1) -}}
   {{- end -}}
  
{{- .Scratch.Set "basedir" (lower .Scratch.Get "path") -}}

{{- .Scratch.Add "basedir" "/" -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
{{- .Scratch.Add "basedir" ".pdf" -}}

{{- .Scratch.Get "basedir" | relURL -}}

