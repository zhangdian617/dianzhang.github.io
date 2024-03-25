{{- .Scratch.Set "basedir" "/" -}}
{{- .Scratch.Set "path" (.Get 0) -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path" | lower) -}}

{{- .Scratch.Add "basedir" "/" -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
{{- .Scratch.Add "basedir" ".pdf" -}}

{{- .Scratch.Get "basedir" | relURL -}}

