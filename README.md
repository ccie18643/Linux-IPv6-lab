# Linux IPv6 lab

With this project i would like to achieve three goals.
- Implement lightweight network lab solution based solely on Linux network namespaces and OVS. Needs to be automated as much as possible.
- Learn more about IPv6 operations by examining packet exchange captures of various IPv6 mechanisms.
- Get better understanding of OSPFv3 protocol.

### Lets start with creating our lab environment.
1. Install OVS. This can be easilly done using apt. Not going to cover details here.
2. Come up with base network namespace / interface setup. 
 - Each of namespaces will contain single trunk interface that will be plugged into OVS.
