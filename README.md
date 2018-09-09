# srv-json
Lab for async test restful api - json-server.  
ref:
[https://github.com/typicode/json-server](https://github.com/typicode/json-server)

### Install
```
git clone https://github.com/ZeviLiao/srv-json.git
```

### Configuration file json-server.json
* delay 1 sec to respond.
```
"delay": 1000
```

### Run
```
cd srv-json
json-server --watch db.json
```

### Browser url
```
http://localhost:3000/posts
```
