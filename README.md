# Push

```
$ npm init

$ npm install --save-dev serverless

$ echo "PATH_add $PWD/node_modules/.bin/" > .envrc # direnv 설정 (serverless cli에 대한 path 설정)

$ direnv allow

$ serverless create --template aws-nodejs
```