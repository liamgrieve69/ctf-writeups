Anonymous tryhackme ctf
Liam Grieve 18/08/22
--------------------------
export IP=10.10.198.141

## Notes
# Open ports
```
21
22
139
445
```

## Task 1 - Pwn
1. Enumerate the machine.  How many ports are open?
```
4
```
2. What service is running on port 21?
```
ftp
```
3. What service is running on ports 139 and 445? 
```
smb
```
4. There's a share on the user's computer.  What's it called?
```
pics
```
5. user.txt
```
90d6f992585815ff991e68748c414740	
```
6. root.txt
```
4d930091c31a622a7ed10f27999af363
```