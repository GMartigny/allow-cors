# allow-cors

Allow cross-origin access on your server responses


## Install

    npm install allow-cors


## Usage

```js
import allow from "allow-cors";

http.createServer((request, response) => {
    allow(response);
    response.end();
});
```


## License

[MIT](license)
