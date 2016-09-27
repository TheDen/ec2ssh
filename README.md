# ec2ssh

Script to quickly SSH into EC2 instances. It's portable (POSIX), so it ought to work on any *nix machine.

Useful when you have 1000s of instances and many identity keys that need access.

Caches each instance so only one API call is needed per instance.
