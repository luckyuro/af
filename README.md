# Anonymous Forum

use asymmetric cryptography to determine user in anonymous forum
all posts' digest will be signed by user determine the user

## repo structure
1. *af_common* a rust lib shared code for both fe/be, like
    - api interfaces
    - digest calculation
    - sign algrithms
2. *af_client* a rust lib for client code
3. *af_server* a rust binary for server
    - actix web
    - sqlx

## TODO
### Basic
- [ ] build skeleton
- [ ] ecc sign/check function

### Server Api
- [ ] Register
- [ ] Post
- [ ] Reply
### Client
- [ ] rust to wasm/... as lib

## Other
Should support current pgp servers for identification ?