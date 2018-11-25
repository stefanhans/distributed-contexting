
### RFCs and Reference Implementations

- [Contextinformation Routing Network (CRN)](https://github.com/stefanhans/golang-contexting/blob/master/RFC/CRN_Concepts.txt)
- [Contextinformation Packet (CIP)](https://github.com/stefanhans/golang-contexting/blob/master/RFC/CIP_Specification.txt)
- [Reference Implementation in Go](https://godoc.org/github.com/stefanhans/golang-contexting/ctx)
- TBD: Contextinformation Routing (CIR)


---

### Implementation as a protocol

- as simple as possible but not simpler |
- as an hourglass protocol |
- isomorphic, i.e. no server/client distinction |
- SWIM(++) protocol <br> for different membergroups |

---

### SWIM(++) protocol

- scalable |
- weakly-consistent |
- infection-style |
- process group membership protocol |
- ++, piggybacking and suspicion mechanism |
- memberlist: HashiCorp's Go implementation |

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

![IPFS Waist](assets/image/ipfs-projects.png)

---

![IPFS Multiformats](assets/image/ipfs-multiformats.jpg)

###### What about multicontext?

---

### go-libp2p and go-libp2p-examples

[... to be continued ...](http://127.0.0.1:3999/slides/libp2p/go-libp2p.slide#1)

---

![party](assets/image/giphy-3.gif)

### thank you
