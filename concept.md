[![bernie.enp](http://christian-bernstein.de/cdn/bernie/enp-github-banner.png)

<div align="center">
    <h1>Edge-Net-Protocol</h1>
<!--
    <a href="https://www.npmjs.com/package/prisma"><img src="https://img.shields.io/npm/v/prisma.svg?style=flat" /></a>
    <a href="https://github.com/prisma/prisma/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" /></a>
    <a href="https://github.com/prisma/prisma/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-blue" /></a>
    <a href="https://slack.prisma.io/"><img src="https://img.shields.io/badge/chat-on%20slack-blue.svg" /></a>
    <br />
    <br />
-->
<!--
    <a href="https://www.prisma.io/docs/getting-started/quickstart">Quickstart</a>
    <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
-->
    <a href="https://github.com/prisma/prisma-examples/">Wiki</a>
    <br />
    <br />
    <a href="https://www.prisma.io/docs/getting-started/quickstart">enp-java</a>
    <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
    <a href="https://www.prisma.io/">enp-rust</a>
    <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
    <a href="https://www.prisma.io/docs/">enp-typescript</a>
    <br />
    <hr />
</div>

# Edge-Net-Protocol (ENP)

ENP is used for standardized communication within a trusted software infrastructure cluster.
Edge-Net is a member of the application layer.  

---
## Control-layer / Implementation-layer

---
## Conversations

---
## Language-Inheritance

Like classes or interfaces in programming languages, ENP-Languages can also inherit from other ENP-Languages.
Multiple 

---
## Endpoint-to-Transport-Gate-IMUX

ENP utilizes an IMUX[^IMUX] to hot-swap transport gates without causing the endpoint to close. 
<br>
*Tip: The IMUX can be used as a clientside*

### Specification
- select(id: string)
- unselect()
- add-channel(id: string, bus: `DBus-Specification`)
- remove-channel(id: string)

---
## DBus

### Specification
- pub(msg: byte[])
- sub((msg: byte[]) -> void)

[^IMUX]: Inverse multiplexer ([Wikipedia](https://en.wikipedia.org/wiki/Inverse_multiplexer))
]()
