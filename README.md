### Hi there 👋

<p align="left">
  <a href="https://github.com/junkurihara/junkurihara/">
    <img src="https://komarev.com/ghpvc/?username=junkurihara" alt="junkurihara" />
  </a>
  <a href="https://github.com/junkurihara">
    <img height="20" src="https://img.shields.io/github/followers/junkurihara?label=follow&logo=github&style=flat" />
  </a>
</p>

I am Jun Kurihara, a research engineer in the area of distributed systems and networking in Japan and sometimes in US. I am really interested in developing novel software and networking products/services written in various languages on various infrastructures. You can reach me via my [LinkedIn](https://www.linkedin.com/in/junkurihara/) or [WebSite](https://junkurihara.github.io).

---

### rpxy and rpxy-l4

`rpxy` [ahr-pik-see] is an implementation of simple and lightweight reverse-proxy with some additional features. The project is (always and endless) work-in-progress, but being used in numbers of production environment. `rpxy` supports the brand-new HTTP/3 standard,  ACME with TLS-ALPN-01 out-of-the-box, and the TLS post-quantum key exchange by default.

- Source: [https://github.com/junkurihara/rust-rpxy](https://github.com/junkurihara/rust-rpxy)

- Website: [https://rpxy.io/](https://rpxy.io)

`rpxy` is an HTTP, i.e., layer-7, reverse proxy. On the other hand, `rpxy-l4` is a brand-new layer-4 (TCP/UDP) reverse proxy with protocol multiplexer functions, e.g., IETF-QUIC, TLS, SSH, Wireguard, etc. `rpxy-l4` is also being developed along with `rpxy` and designed from the philosophy of `rpxy`, i.e., simple and lightweight.

- Source: [https://github.com/junkurihara/rust-rpxy-l4](https://github.com/junkurihara/rust-rpxy-l4)

---

### Mutualized Oblivious DNS (μODNS)

Currently I am really interested in the enhancement of privacy-preserving DNS architectures. As one of my research activities, I am actively developing **Mutualized Oblivious DNS** by extending existing sophisticated encrypted and anonymized DNS protocols.

#### Publications

- Extended journal paper:
  > Jun Kurihara, Toshiaki Tanaka, and Takeshi Kubo, "μODNS: A Distributed Approach to DNS Anonymization with Collusion Resistance," *Computer Networks*, Elsevier, vol. 237, p. 110078, Dec. 2023. [Online] Available at [https://doi.org/10.1016/j.comnet.2023.110078](https://doi.org/10.1016/j.comnet.2023.110078).

- Initial concept paper:
  > Jun Kurihara and Takeshi Kubo, "Mutualized oblivious DNS (μODNS): Hiding a tree in the wild forest," [https://arxiv.org/abs/2104.13785v3](https://arxiv.org/abs/2104.13785v3), Jun. 2021

#### Web page
> https://junkurihara.github.io/dns/

#### Server/Proxy/Client PoC implementations
##### Based on Oblivious DNS over HTTPS

- Server/Relay
  > https://github.com/junkurihara/modoh-server
- Client:
  > https://github.com/junkurihara/doh-auth-proxy
- (Optional) Authentication server
  > https://github.com/junkurihara/rust-token-server

##### Based on DNSCrypt

- Server/Relay:
  > https://github.com/junkurihara/encrypted-dns-server-modns
- Client:
  > https://github.com/junkurihara/dnscrypt-proxy-modns
- Experimental Resolvers based on DNSCrypt
  > https://github.com/junkurihara/experimental-resolvers

---

<!--
<p align="left">
 <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=junkurihara&theme=tokyonight&layout=compact" />

 <img align="left" src="https://github-readme-stats.vercel.app/api?username=junkurihara&count_private=true&show_icons=true&theme=tokyonight"/>
</p>
-->

<!--
**junkurihara/junkurihara** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
