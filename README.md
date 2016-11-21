# url-parse

ALL credit for this component belongs here: https://github.com/unshiftio/url-parse

I had to fork to consolidate some things, strip out others and go down a new path, they did the heavy lifting, thanks.

```javascript



//in this example, all of the properties were created from "v"

var strUrl='http://www.li-dermakine.com.tr/2064b8bd5aa918686b54d846d5611da8/update.html';
var objUrl = new URL(strUrl);
console.log(objUrl);
/*
  {
    "slashes": true,
    "protocol": "http:",
    "hash": "",
    "query": "",
    "pathname": "/2064b8bd5aa918686b54d846d5611da8/update.html",
    "auth": "",
    "host": "www.li-dermakine.com.tr",
    "port": "",
    "hostname": "www.li-dermakine.com.tr",
    "password": "",
    "username": "",
    "origin": "http://www.li-dermakine.com.tr",
    "href": "[object Object]"
  }
*/

``


## License

[MIT](LICENSE)
