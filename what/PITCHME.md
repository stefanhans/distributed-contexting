
### RFCs and Reference Implementations
@ul
- [Contextinformation Routing Network (CRN)](https://github.com/stefanhans/golang-contexting/blob/master/RFC/CRN_Concepts.txt)
- [Contextinformation Packet (CIP)](https://github.com/stefanhans/golang-contexting/blob/master/RFC/CIP_Specification.txt)
- [Reference Implementation in Go](https://godoc.org/github.com/stefanhans/golang-contexting/ctx)
- TBD: Contextinformation Routing (CIR)
@ulend

---

### Implementation as a protocol

- as simple as possible but not simpler |
- as an hourglass protocol |
- isomorphic, i.e. no server/client distinction |
- SWIM(++) protocol for different membergroups |

---

### SWIM(++) protocol

- scalable |
- weakly-consistent |
- infection-style |
- process group membership protocol |
- ++, i.e. piggybacking and suspicion mechanism |
- "memberlist": Go implementation from HashiCorp |

---

### Additional network challenges

- different protocols and versions |
- NAT and firewalls |
- IPFS stack helps | 

---

![IPFS Stack](assets/image/ipfs-stack.jpg)

---

![IPFS Waist](assets/image/ipfs-thin-waist.jpg)

---

![IPFS Multiformats](assets/image/ipfs-multiformats.jpg)

### What about multicontext?

---

### go-libp2p and go-libp2p-examples

... to be continued ...

---

### ... but the most important concept is ...

---

### ... fun ...

![party](assets/image/giphy-2.gif)

---

![party](assets/image/giphy-3.gif)

### thank you
