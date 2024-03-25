{{- .Scratch.Set "path" (.Get 0) -}}
{{- .Scratch.Set "basedir" (lower .Scratch.Get "path") -}}

{{- .Scratch.Add "basedir" "/" -}}
{{- .Scratch.Add "basedir" (.Scratch.Get "path") -}}
{{- .Scratch.Add "basedir" ".pdf" -}}

{{- .Scratch.Get "basedir" | relURL -}}

