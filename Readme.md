# multer usage in express
### multer is a NPM package Used to upload Files in Nodejs
Installation
<br>
```npm install --save multer```

inside Form 
```
<form action="/profile" method="post" enctype="multipart/form-data">
  <input type="file" name="avatar" />
</form>
```

Inside index.js Files
  dest means Destination
```
const multer  = require('multer')
const upload = multer({ dest: 'uploads/' })
```

