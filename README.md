# fetchUtils


## Install

```shell
$ npm install git+ssh://git@github.com:heineiuo/fetchUtils --save-dev 
```

## Usage

``` javascript
import {Mock, POSTUrlencodeJSON, POSTRawJSON} from '@heineiuo/fetch-utils'

```

use with webpack & babel: 

```javascript
 {
    test: /(\.js|\.jsx)$/,
    exclude: /(node_modules\/)?!\@heineiuo)/, 
    loader: 'babel',
    query: {
      presets: ['es2015', 'stage-0', 'react']
    }
 }

```



