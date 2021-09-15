# gRPC

### What is it?
an RPC frameworked built with Google protobuff.

### Pros
- Protobuff encodes the data sent, so smaller message than SOAP, REST
- Built on HTTP/2, offers bidirectional connection,streaming. For now, REST is not implemented in HTTP/2 yet.
- Suitable for microservice. gRPC standardizes contract, reduces use of client library.

### Cons
- Still new, need more tooling, support
- Mostly works with GKE for now. Other platforms need support.
- Lack of common practices, anti-pattern. Need time.

### Compared to similar tools
Defines messages, encodes it, so the interface is well-defined and messages are smaller.