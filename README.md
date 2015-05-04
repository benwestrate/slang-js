gulp-slang
==============

Curl files to running JCR

## Install

```shell
    npm install node-slang --save-dev
```

## Example
```js
    var slang = require('gulp-slang');

    slang( { path : "path/to/your/file" } , { port : 4502 } );
    
```

## Options
### host
Type: `string`
Default: `localhost`

hostname to running sling instance.
### port
Type: `number`
Default: `4502`

Port for running sling instance.
### username
Type: `string`
Default: `admin`

Username for authentication.
### password
Type: `string`
Default: `admin`

Password for authentication.
