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
