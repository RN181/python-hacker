1- frist scenario 
=
py.py
```
fp = open ('test.txt').read()
exec(fp)
```

pyinstaller.py -F py.py
 
sometimes when you want to compile exe maybe pyinstaller has error --> use vnruntime140.dll --> C:\USERS\your user\appdata\rooming\pyinstaller\(select python version)

Pack with UPX
=
```
upx.exe --best --ultera-brute --all-method <file>
```

2- second scenario 
=

 
