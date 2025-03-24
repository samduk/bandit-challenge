```
ssh -p 2220 bandit6@bandit.labs.overthewire.org
```

Password: 
- HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

Command:
```
find / -type f -name "*" -user bandit7 -group bandit6 -size 33c 2>/dev/null

cat /var/lib/dpkg/info/bandit7.password
```

Found: 
- morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
