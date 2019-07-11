# nod-log

Log for Nodejs

#Use

```
const nl = require('nod-log);

myfunction = ()=>{
  nl.register('INFO','My Message')
  return 'hello world'
}

myfunction()
//DateTime[2019-07-11T17:00:00];File['/myfile.js'];NumberLine[11];Method[myfunction];Type[INFO];My Message

```