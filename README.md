# fishmlserv

## deploy
![image](https://github.com/user-attachments/assets/43a21ca7-53e0-4eb8-bc33-b984d0d25093)

## Run
- dev
- http://127.0.0.1:8000/docs
```bash
# uvicorn --help
$ uvicorn src.fishmlserv.main:app --reload
```
- prd
```bash
$ uvicorn src.fishmlserv.main:app --host 0.0.0.0 --port 8949
```
### Docker
```bash
$ sudo docker build -t fishmlserv:0.4.0 .
$ sudo docker run -d --name fmlserv-040 -p 8877:8765 fishmlserv:0.4.0
```

### Ref
- https://curlconverter.com/python
