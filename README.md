# realmd
straight forward configuration of network authentication

## Introduction
realmd is an on demand system DBus service, which allows callers to configure network authentication and domain membership in a standard way. realmd discovers information about the domain or realm automatically and does not require complicated configuration in order to join a domain or realm.

realmd configures sssd or winbind to do the actual network authentication and user account lookups.

realmd has been integrated into kickstart and GNOME control center, and is being integrated into other spots too.

