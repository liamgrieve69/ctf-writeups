#  picoCTF 2019 mus1c
# Liam Grieve 03/05/22
-------------------------------------------------------------------------------------------------------------------

# I wrote you a song. Put it in the picoCTF{} flag format.

```
picoCTF{rrrocknrn0113r}
```
if you look at the most 2 common words they are 'shout' and 'put' and if you type them with program lanuage on google it come up with rockstar program lanuage after we get ascii encoded numbers 
```1337
114
114
114
111
99
107
110
114
110
48
49
49
51
114
```
so i wrote a python script to decode them
```python
#!/usr/bin/env python3

ascii="""114
114
114
111
99
107
110
114
110
48
49
49
51
114
"""
for c in ascii.split():
     print(chr(int(c)), end='')
```
this gives us 'rrrocknrn0113r' which is the flag 'picoCTF{rrrocknrn0113r}'