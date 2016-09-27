# ec2ssh

Portable (POSIX, so it ought to work on any *nix machine) script for quickly SSH into EC2 instances.

Useful when you have 1000s of instances and many identity keys that may need access.

Cache's each instance's so only one API call is needed per new instance.
