# picoCTF 2019 plumbing
# Liam Grieve 03/05/22
-------------------------------------------------------------------------------------------------------------------

# Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to jupiter.challenges.picoctf.org 4427.

```
picoCTF{digital_plumb3r_5ea1fbd7}
```

we found the flag by piping it into grep to find the flag by using the command 'nc jupiter.challenges.picoctf.org 4427| grep picoCTF'