# NASA_PROJECT_FS
User can launch, abort rocket mission.
 
# Install Dependencies
```
    "install-server": "npm install --prefix server",
    "install-client": "npm install --prefix client",
    "install": "npm run install-server && npm run install-client",
```

# Start Project
```
    "server": "npm run watch --prefix server",
    "client": "npm start --prefix client",
    "watch": "npm run server & npm run client",
    "deploy": "npm run build --prefix client && npm start --prefix server",
    "test": "npm run test --prefix server && npm run test --prefix client"
```
