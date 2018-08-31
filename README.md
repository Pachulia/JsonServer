# JsonServer

//修改LocalHost为ip地址
jecJsonServer\node_modules\json-server\lib\cli\index.js
 host: {
      alias: 'H',
      description: 'Set host',
      default: '0.0.0.0'
    },
    
//修改启动项 
JsonServer\package.json
{
  "name": "jsonserver",
  "version": "1.0.0",
  "description": "test restful api",
  "main": "index.js",
  "scripts": {
    "json:server": "json-server --watch db.json" //配置启动.json文件 
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "json-server": "^0.14.0"
  }
}

启动命令
npm run json:server
