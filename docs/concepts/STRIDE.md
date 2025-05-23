# Overview
STRIDE is a thread modeling methodology used in cybersecurity to identify and categorize potential threats to a system. the acronym STRIDE stands for:

- **S**poofing: pretending to be something or someone else.
- **T**ampering: unauthorized modification of data or systems.
- **R**epudiation:denying an action or transaction without a way to prove otherwise.
- **I**nformation Disclosure: exposing information to unauthorized parties.
- **D**enial of Service: Disrupting or denying access to services.
- **E**levation of privilege: gaining unauthorized access or permission.

STRIDE helps security professionals systematically analyze and address security risks during system design and development.

## STRIDE threats and Violated Security Properties
| Threat        | Property violated | Description                          |
| :----------   | :-----------------|:----------------------------------- |
| `Spoofing`    | authentication| pretending to be something or someone other than yourself|
| `Tampering`   | Integrity| modifying something on disk, network, memory, or elsewhere|
| `Repudiation` | Non-repudiation| claiming that you didn't do something or we're not responsible. can be honest or false|
| `Information disclosure`|confidentiality| providing information to someone not authorized to access it.|
| `Denial of service`| Availability| exhausting resources needed to provide service.|
| `Elevation of privilege`| authorization| allowing someone to do something they are not authorized to do.| 

Applying STRIDE methodology can identify all the threat vectors which are closely associated with cyber security properties.
