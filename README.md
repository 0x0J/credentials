Credentials package is a helper class that can be imported to ease credential handeling.

Currently it only support 3 types,
Ssh
BasicAuth
Database

Each credential type contains a validator to make sure all required information is available.

The current loadCredentials only accepts an []byte with json data inside.
Future support for protobuf will be added
at a later stage.

