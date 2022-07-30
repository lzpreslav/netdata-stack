# netdata-stack

[Netdata](https://www.netdata.cloud/) stack based on the official Docker image.

| ENV var      | Value                                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------------- |
| SECURITY_OPT | `apparmor:unconfined` for Ubuntu (default), `seccomp:unconfined` for Raspbian (or missing libseccomp2 setups) |
