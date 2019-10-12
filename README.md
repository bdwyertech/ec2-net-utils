# ec2-net-utils
ec2-net-utils contains a set of utilities for managing elastic network interfaces on Amazon EC2.

These utilites do not play nice with CNI, e.g. if you're running EKS.  The CNI and the functions within this package conflict!
