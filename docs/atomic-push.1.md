% ATOMIC(1) Atomic Man Pages
% Dan Walsh
% April 2015
# NAME
atomic-push - push Image to repository

# SYNOPSIS
**atomic push**
[**--pulp**]
[**--satellite**]
[**-h**]
IMAGE

# DESCRIPTION
**atomic push** will push the image to the repository.  Defaults to docker repository; can also push to satellite or pulp repository.

# OPTIONS:
**--pulp**
  Push using the pulp protocol; defaults to using docker push

**--satellite**
  Push using the satellite protocol; defaults to using docker push

**--help**
  Print usage statement

# HISTORY
April 2015, Originally compiled by Daniel Walsh (dwalsh at redhat dot com)
July 2015, Edited by Jenny Ramseyer (jramseye at redhat dot com)
