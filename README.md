# express_notes

### Install express
```javascript
npm install express --save
```

### Use express
```javascript
const express=require('express')
const app=express()
```

### routing methods
```javascript
app.get('<path>',function (request,response) {
  res.send(...) // From server to client
})
```

### Running in browser
```javascript
app.listen(<desaired port number>)
```
