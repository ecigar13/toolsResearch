# HTTP/2

### What is it?
Superseeding HTTP/1.1 standard. No longer text-based protocol

### Pros
- Smaller message size because it's binary data, header compression.
- Less connection pool usage: multiplexing streams. HTTP/1.1 uses 1 TCP connection for each file. HTTP/2 can do multiple things in 1 connection.
- Flow control from both side, server push.

### Cons
- Very new, no browser support unencrypted for now.
- Backward compatibility seems to create security breach

### Compared to similar tools
It's the future, for now.