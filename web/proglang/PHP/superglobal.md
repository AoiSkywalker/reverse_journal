# PHP

## Superglobals

Superglobals = Always accessiable, regardless of scope.

| Superglobals | Meaning | Note |
| ------------ | ------- | ---- | 
|`$GLOBALS`| array contains ref to global script variables | `$GLOBALS['x']`, `global $x` |
|`$_SERVER`| info about web server (headers, paths, script locations) | `$_SERVER['HTTP_HOST']` |
|`$_REQUEST`| array contains data from `$_GET`, `$_POST`, `$_COOKIE` superglobals |  |
|`$_POST`| array of variables received via the HTTP POST method |
|`$_GET`| array of variables received via the HTTP GET method |
|`$_FILES`| array of items uploaded to the current script via HTTP POST method (filename, type, size) |
|`$_ENV`| Holds environment variables passed to the current script |
|`$_COOKIE`| Array of variables passed to the current script via HTTP Cookies |
|`$_SESSION`| Array of session variable |

## $_SERVER

| Element | Description |
| ------------ | ------- |
| `$_SERVER['PHP_SELF']` | Returns the filename of the currently executing script |
| `$_SERVER['GATEWAY_INTERFACE']` | Returns the version of the Common Gateway Interface (CGI) the server is using |
| `$_SERVER['SERVER_ADDR']` | Returns the IP address of the host server |
| `$_SERVER['SERVER_NAME']` | Returns the name of the host server |
| `$_SERVER['SERVER_SOFTWARE'] 	` | Returns the server identification string |
| `$_SERVER['SERVER_PROTOCOL']` | Returns the name and revision of the information protocol |
| `$_SERVER['REQUEST_METHOD']` | Returns the request method used to access the page |
| `$_SERVER['REQUEST_TIME']` | Returns the timestamp of the start of the request |
| `$_SERVER['QUERY_STRING']` | Returns the query string if the page is accessed via a query string |
| `$_SERVER['HTTP_ACCEPT']` | Returns the Accept header from the current request  |
| `$_SERVER['HTTP_ACCEPT_CHARSET']` | Returns the Accept_Charset header from the current request  |
| `$_SERVER['HTTP_HOST']` | Returns the Host header from the current request  |
| `$_SERVER['HTTP_REFERER']` | Returns the complete URL of the current page |
| `$_SERVER['HTTPS']` | Script queried through a secure HTTP protocol |
| `$_SERVER['REMOTE_ADDR']` | Returns the IP address from where the user is viewing the current page |
| `$_SERVER['REMOTE_HOST']` | Returns the Host name from where the user is viewing the current page |
| `$_SERVER['REMOTE_PORT']` | Returns the port being used on the user's machine to communicate with the web server |
| `$_SERVER['SCRIPT_FILENAME']` |  	Returns the absolute pathname of the currently executing script |
| `$_SERVER['SERVER_ADMIN']` | Returns the value given to the SERVER_ADMIN directive in the web server configuration file |
| `$_SERVER['SERVER_PORT']` | Returns the port on the server machine being used by the web server for communication |
| `$_SERVER['SERVER_SIGNATURE']` | Returns the server version and virtual host name which are added to server-generated pages |
| `$_SERVER['PATH_TRANSLATED']` | Returns the file system based path to the current script |
| `$_SERVER['SCRIPT_NAME']` | Returns the path of the current script |
| `$_SERVER['SCRIPT_URI']` | Returns the URI of the current page |














