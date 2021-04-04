# JSch - implement OpenSSH multiplexing

## Motivation
JSch is a popular java implementation of the SSH2 protocol.
Applications, including several IDEs, rely on it.
Unfortunatelly a common complaint is that it does not support some vendor specific extensions.
One of these extensions is the ["multiplexing protocol used by ssh's
ControlMaster connection-sharing"](https://github.com/openssh/openssh-portable/blob/master/PROTOCOL.mux)


## Instructions

- study the [SSH protocol](https://www.openssh.com/specs.html)
- study the architecture of [JSch](https://github.com/is/jsch)
- fork JSch and implement [PROTOCOL.mux](https://github.com/openssh/openssh-portable/blob/master/PROTOCOL.mux)
- discuss your results and findings