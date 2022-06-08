Rootme TryHAckMe 
> Liam Grieve 08/06/22 
export IP=10.10.224.210
--------------------------------

## Task 1 Deploy the machine

1. No answer needed

## Task 2 Reconnaissance

1. Scan the machine, how many ports are open?

```
2
```
2. What version of Apache is running?

```
2.4.29
```

3. What service is running on port 22?

```
ssh
```
4. Find directories on the web server using the GoBuster tool.

```
NO ANSWER NEEDED
```

5. What is the hidden directory?

```
/panel/
```
## Task 3  Getting a shell

1.	user.txt

```
THM{y0u_g0t_a_sh3ll}	
```

## Task 4  Privilege escalation

1. Search for files with SUID permission, which file is weird?
```
 /usr/bin/python
id


```
2. NO ANSWER NEEDED

3. root.txt
```
THM{pr1v1l3g3_3sc4l4t10n}
```


```python
python -c "import pty;pty.spawn('/bin/bash')"
```