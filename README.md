Credentials package is a helper class that can be imported to ease credential handling.

Currently it only support 3 types,
Ssh,
BasicAuth
and
Database

Each credential type contains a validator to make sure all the required information is available.

The current loadCredentials only accepts an []byte with json data inside.
Future support for protobuf will be added
at a later stage.

