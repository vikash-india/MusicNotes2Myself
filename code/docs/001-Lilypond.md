# Description: Install Lilypond

### Install Lilypond
* Download [Lilypond Install Script](http://lilypond.org/unix.html)
```bash
# Install Lilypond
chmod +x lilypond-2.18.2-1.linux-64.sh
sudo sh lilypond-2.18.2-1.linux-64.sh
```

### Uninstall Lilypond
```bash
uninstall-lilypond
```

### Write Lilypond Scripts in any Text Editor 
Add the following code in a text file `test.ly`.
```
\version "2.18.2"
{
  c' e' g' e'
}
```

### Compile the Lilypond Scripts
```bash
# Compile to a PDF
lilypond test.ly

# Compile to a PNG
lilypond --format=png test.ly
```
