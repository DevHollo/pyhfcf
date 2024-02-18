# Hollo's Fun Config File
Hollo's Fun Config File is a config file that I made because I was bored and it was fun to do!<br/>

.hfcf file example:
```properties
;; this is a comment
a=Hello World!
```

Python Module Usage:
```py
from hfcf import HFCF

conf = HFCF("DAT")

a = conf.get('a;1')

print(a) # output: Hello World!
```

Expaination:<br/>
`conf.get('attributeName;lineItsOn')`<br/>
say you want to get the `g` attribute on line 4. You would do:<br/>
`conf.get('g;4')`