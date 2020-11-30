# httpstatus
A simple module for using HTTP codes as constants.

Install package: 

`npm i @slpv/httpstatus`

Include package:
 
`const HTTPStatus = require('@slpv/httpstatus');`

Example using express.js framework

```
app.post("/", (req, res)) => {
    // TODO: Create method
    res
        .status(HTTPStatus.CREATED.code)
        .send(JSON.stringify({"message": "Created"}));
})
```
