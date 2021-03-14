# DDos Flood
#### A SYN flood (half open attack) is a type of denial of service (DDoS) attack that attempts to make a server unavailable for legitimate traffic by consuming all of its available resources. By repeatedly sending initial connection request (SYN) packets, the attacker can overload all available ports on the attacked server, causing the device to respond to legitimate traffic very slowly or even not respond at all.

## Installation:
- `apt update && apt upgrade -y`
- `apt install python -y`
- `apt install python3 -y`
- `apt install git -y`
- Clone the repository: `git clone https://github.com/Balta-Python/DDos-Flood.git`
- Install pip requirements: `pip3 install -r requirements.txt`
- Usage: `python3 ddos-flood.py [-h] [-u USER_AGENTS] -t TARGET -tr THREADS -s SLEEP`
- Example: `python3 ddos-flood.py -u user_agents.txt -t http://example.com -tr 1000 -s 200`

#### Disclaimer
This project is fully implemented for educational purposes only and I am not responsible by any means for any misuse.
