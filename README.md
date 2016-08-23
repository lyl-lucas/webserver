# webserver
learn how web serves works from http://ruslanspivak.com/lsbaws-part2/

## run webserver2.py
```
$ python webserver2.py flaskapp:app 
```

## run webserver2+.py
```
$ python webserver2+.py flaskapp:app
```
open another terminal and run client.py
```
$ client.py --max-clients=300 --max-conns=1 
```
