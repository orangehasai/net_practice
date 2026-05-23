*This project has been created as part of the 42 curriculum by stonegaw.*

# NetPractice

## Description

NetPractice is an introductory networking project from the 42 curriculum. Its goal is to practice the basics of computer networking by fixing small simulated networks.

Across 10 levels, the project requires configuring valid IPv4 addresses, subnet masks, default gateways, and static routes so that hosts can communicate correctly through switches and routers.

## Instructions

No compilation is required. The training interface is a local web application served with `python3`.

To run the official interface included in this directory:

```bash
cd net_practice
./run.sh
```

If `run.sh` does not work, you can launch the server manually:

```bash
cd net_practice
python3 -m http.server 49242
```

Then open `http://localhost:49242` in your browser.

How to use the training interface:

1. Enter your 42 login to load your personal configuration.
2. Open a level and fix the unshaded fields.
3. Use `Check again` to validate the configuration.
4. Use `Get my config` to export the level result.
5. Repeat this for all 10 levels.

Exported configuration files in this directory:

- `level1.json`
- `level2.json`
- `level3.json`
- `level4.json`
- `level5.json`
- `level6.json`
- `level7.json`
- `level8.json`
- `level9.json`
- `level10.json`

## Resources

### Networking concepts studied

- IPv4 and TCP/IP addressing
- CIDR notation and subnet masks
- Default gateways
- Static routing
- Routers and switches
- Local and remote network communication
- Basic OSI model perspective on network communication

### References

No external networking references were consulted while solving the exercises. The levels were completed from prior knowledge and by using the NetPractice interface and its validation logs.

The following references are included as classic background material and further reading for the topics covered by the project:

- RFC 791, *Internet Protocol*: <https://datatracker.ietf.org/doc/html/rfc791>
- RFC 792, *Internet Control Message Protocol*: <https://datatracker.ietf.org/doc/html/rfc792>
- RFC 950, *Internet Standard Subnetting Procedure*: <https://datatracker.ietf.org/doc/html/rfc950>
- RFC 1918, *Address Allocation for Private Internets*: <https://datatracker.ietf.org/doc/html/rfc1918>
- RFC 4632, *Classless Inter-domain Routing (CIDR)*: <https://datatracker.ietf.org/doc/html/rfc4632>
- Wikipedia, *Default gateway*: <https://en.wikipedia.org/wiki/Default_gateway>
- Wikipedia, *Router (computing)*: <https://en.wikipedia.org/wiki/Router_(computing)>
- Wikipedia, *Network switch*: <https://en.wikipedia.org/wiki/Network_switch>
- Wikipedia, *OSI model*: <https://en.wikipedia.org/wiki/OSI_model>

### AI usage

AI was used to draft and structure this `README.md`, summarize the subject requirements, and check that the exported files matched the required submission layout.

AI was not used as a substitute for understanding the exercises themselves.
