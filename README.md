##  StackExchange API Convertigo Connector

API documentation: https://api.stackexchange.com/docs

Project Symbols:

| NAME | DESCRIPTION |
|------|-------------|
| lib_stackexchange.client_id | This Id identifies your application to the Stack Exchange API. Your application client id is not secret, and may be safely embeded in distributed binaries. |
| lib_stackexchange.client_secret.secret | This must be kept secret. Do not embed it in client side code or binaries you intend to distribute. |
| lib_stackexchange.key | Pass this as key when making requests against the Stack Exchange API to receive a higher request quota. This is not considered a secret, and may be safely embed in client side code or distributed binaries. |
| lib_stackexchange.redirect_uri | Whenever a redirect occurs during an authentication sessions (as specified by redirect_uri) it must reside under this domain. |
| lib_stackexchange.scope | With an empty scope, authentication will only allow an application to identify a user via the /me method. In order to access other information, different scope values must be sent. Multiple values may be sent in scope by comma or space delimitting them (read_inbox, no_expiry, write_access, private_info). |
