## Use the TimeMachine image

*Changes*

```
$ git show cd9df81d5c883e4b62249114a5190ad3e6efd483
```

**LINKS** https://github.com/rootkiter/samba-for-timemachine/commit/cd9df81d5c883e4b62249114a5190ad3e6efd483

*How To Build*:

```
docker build -t r00kiter/samba-for-timemachine:v1.0 .
```

*Use My Image*

```
docker run -itd --rm -p 445:445 -e "USER=samba" -e "PASS=secret" -v "/home/example:/storage" r00kiter/samba-for-timemachine:v1.0
```

