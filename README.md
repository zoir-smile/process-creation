Первая программа:
```
gcc -o f getProcessID.c && ./f
```

Вторая прорамма: 
```
gcc -o s selfcopy.c && ./s
```

Третья программа: 
```
gcc -o c execChild.c && gcc -o p execParent.c && ./p
```
