# Extensions

Over time, as various clients and servers for RAC were developed, users introduced their own protocol extensions. These additions were created independently of Mr. Sugoma and are designed to enhance the protocol's capabilities while maintaining compatibility with existing RAC versions.

## User agents

User agents in RAC is the way how to get know from what client the message was sent. It works by just checking the message text throught regex.

Here are listed the most common clients, and their common names colors in the chat.

| Client        | Format        | Regex     | Color     |
|    :----:     |    :----:     |    :----: |  :----:   |
| [bRAC](https://github.com/MeexReay/bRAC) | 리㹰<{name}> {text} | `\uB9AC\u3E70<(.*?)> (.*)` | green
| [CRAB](https://gitea.bedohswe.eu.org/pixtaded/crab) | ═══<{name}> {text} | `\u2550\u2550\u2550<(.*?)> (.*)` | light red
| [Mefidroniy](https://github.com/OctoBanon-Main/mefedroniy-client) | °ʘ<{name}> {text} | `\u00B0\u0298<(.*?)> (.*)` | light magenta
| [cRACk](https://github.com/pansangg/cRACk) | ⁂<{name}> {text} | `\u2042<(.*?)> (.*)` | gold
| [Snowdrop](https://github.com/Forbirdden/Snowdrop) | ඞ<{name}> {text} | `\u0D9E<(.*?)> (.*)` | light green
| clRAC | <{name}> {text} | `<(.*?)> (.*)` | cyan

## Server info packet

Client sends:

- Byte `0x69`

Server sends:

- (nothing or closes socket if server doesn't support this feature)
- Protocol version:
    - Byte `0x01` for RACv1 
    - Byte `0x02` for RACv1.99
    - Byte `0x03` for RACv2
- Server name