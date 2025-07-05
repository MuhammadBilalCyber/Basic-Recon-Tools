# Using Nmap in Termux (Android)

## Install Nmap
pkg update
pkg install nmap

## Sample Scan
nmap -sV scanme.nmap.org

## Output:
- Open ports: 22 (SSH), 80 (HTTP)
- Detected Apache web server

Tool useful for scanning networks via mobile.
