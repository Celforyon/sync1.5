## Overview
A simple container with Firefox Sync1.5 server.

## Environments

### Mandatory
- PUBLIC\_URL

### Important
- SECRET
You can generate one with `head -c 20 /dev/urandom|sha1sum` (from Firefox documentation)
- SQLURI (defaults to sqlite:////tmp/syncserver.db)
- ALLOW\_NEW\_USERS (defaults to false)

### Optional
- PORT (defaults to 5000)
- WORKERS (defaults to 1)
- TIMEOUT (defaults to 30, unit: seconds)
- FORCE\_WSGI\_ENVIRON (defaults to false)
