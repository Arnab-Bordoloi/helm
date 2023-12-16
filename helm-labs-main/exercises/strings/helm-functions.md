# Helm functions

- concatenated: {{ print $testString $testString | quote }}
- containsCat: {{ $testString | contains "cat" }}
- trimmed: {{ $testString | trim | quote }}
- indentedTwo: {{ $testString | indent 2 | quote }}
- quotedText: {{ $testString | toString | quote }}
- appNameAndVersion: {{ $testString | kebabcase | printf "%v-1.0.0" |quote }}
