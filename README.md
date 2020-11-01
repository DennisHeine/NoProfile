# NoProfile
NoProfile - FIrefox addon for blocking psychological profiling through javascript

Blocks javascript functions used for psychological profiling and tracking.
For better security, also use the tampermonkey script https://pastebin.com/raw/WUkCaF64 !!!

https://www.tampermonkey.net/

In adition, these UBlock Origin rules will block portscans, which could also be a problem. Please add them to your UBlock settings:
you can remove the third-party part to block more, but that can break website compatibility.

    ||localhost^$important,third-party
    
    ||127.*^$important,third-party
    
    ||[::1]^$important,third-party
    
    ||10.*^$important,third-party
    
    ||172.16.*^$important,third-party
    
    ||172.17.*^$important,third-party
    
    ||172.18.*^$important,third-party
    
    ||172.19.*^$important,third-party
    
    ||172.20.*^$important,third-party
    
    ||172.21.*^$important,third-party
    
    ||172.22.*^$important,third-party
    
    ||172.23.*^$important,third-party
    
    ||172.24.*^$important,third-party
    
    ||172.25.*^$important,third-party
    
    ||172.26.*^$important,third-party
    ||172.27.*^$important,third-party
    ||172.28.*^$important,third-party
    ||172.29.*^$important,third-party
    ||172.30.*^$important,third-party
    ||172.31.*^$important,third-party
    ||192.168.*^$important,third-party
