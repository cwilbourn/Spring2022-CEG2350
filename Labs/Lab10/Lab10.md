## Lab 10

- Name:Christian Wilbourn
- Email:wilbourn.2@wright.edu

## Part 1 Answers

1. The hostname: "DESKTOP-KH02SJ9"
2. The IP address: "192.168.150.133"
3. The MAC address using that IP address: "10-63-C8-57-AB-8B"
4. The subnet mask: "255.255.224.0"
5. The gateway address: "192.168.128.1"
6. The DHCP server address: "192.168.128.1"
7. The DNS server address: "192.168.128.1"
8. How packets reach the Internet:
"Tracing route to DESKTOP-KH02SJ9 [192.168.150.133]
over a maximum of 30 hops:

  1    <1 ms    <1 ms    <1 ms  DESKTOP-KH02SJ9 [192.168.150.133]

Trace complete. "

## Part 2 Answers

1. How to find hostname for `3.228.104.170`: Typed command "nslookup 3.228.104.170"
2. Port scan command: "nmap -Pn 3.228.104.170"
   - List of open ports:
"PORT     STATE SERVICE
22/tcp   open  ssh
4242/tcp open  vrml-multi-use"
3. How to view webpage: "I can view the webpage using the curl command and the URL of the website that I am on to view it"
4. Command to find SSH version: "ssh -v 3.228.104.70"
   - Version information:"Remote protocol version 2.0, remote software version OpenSSH_7.6p1 Ubuntu-4ubuntu0.6
debug1: match: OpenSSH_7.6p1 Ubuntu-4ubuntu0.6 pat OpenSSH_7.0*,OpenSSH_7.1*,OpenSSH_7.2*,OpenSSH_7.3*,OpenSSH_7.4*,OpenSSH_7.5*,OpenSSH_7.6*,OpenSSH_7.7* compat 0x04000002

## Part 3 Answers

1. Command(s) to install `python3` and `pip3`: python3: "sudo apt-get install python3.8" pip3"sudo apt-get -y install python3-pip" 
3. Run web server
4. Command:"sudo lsof -nP -iTCP -sTCP:LISTEN"
5. Command:"sudo kill 2368"
