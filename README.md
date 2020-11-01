# NoProfile
NoProfile - FIrefox addon for blocking psychological profiling through javascript

Blocks javascript functions used for psychological profiling and tracking.
For better security, use the tampermonkey script https://pastebin.com/raw/WUkCaF64 in addition to this addon!!!

These UBlock Origin rules will block portscans, which could also be a problem:

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
