## A mock configdir for building software collections for EL6

Usage:

1. `git clone git@github.com:skottler/scl-mock-config.git`
2. `sudo mock -r epel-6-scl-x86_64 --configdir=scl-mock-config <your SRPM> --define "scl <your SCL>`
