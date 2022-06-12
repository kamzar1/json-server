```
mkdir json-server && cd json-server
npm init -y
npm install -g json-server
#npm install axios # no need
json-server --watch db/db.json --port 3004
json-server --watch ./src/json/db.json --port 3001
curl http://127.0.0.1:3004/posts/1
```
