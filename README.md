# sfmail - simplistic, lightweight and fast C command-line mail client

**!! WARNING: sfmail is currently on the earliest development stage so there are many missing features !!**

## Installation / Use
For use on windows or linux simply download one of our binaries from the releases page and use that,
alternatively build from source (instructions below).

run `sfmail` and a command-line interface should fire up.
From here you can:

 - Add/Remove accounts
 - Set options for individual accounts
 - View/Synchronize (reload) mail
 - Send mail
 
To sync mail via command line all you need to do is run `sfmail sync "account@service.com" "optionally a password if you haven't disabled it in settings"`


## How to build from source
The classical routine applies:
  1. `./configure`
  2. `make`
  3. `make install` (as superuser)
  
## Contributing / Comments
Feel free to request new features, cover bugs and possible code quality improvements in the Issues section, and creating Pull Requests when needed.
