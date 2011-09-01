# xmlsec-ruby

Currently working on getting a basic signature verification 
(for SAML purposes) working, in the least hacky way possible.

## Version History

Version 0.0.6
Less hacky way of grabbing ID attributes.

Version 0.0.5
Took out init/deinit of crypto libraries - this should already done
when we require openssl, and we don't want to wantonly destroy 
all that state.
