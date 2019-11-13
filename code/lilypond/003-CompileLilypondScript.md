# Description: Compile a Lilypond Script

### Write Code in an Editor 
Add the following code in a text file `test.ly`
```
\version "2.18.2"
{
  c' e' g' e'
}
```

### Compile the Code
```bash
# Compile to a PDF
lilypond test.ly

# Compile to a PNG
lilypond --format=png test.ly
```
