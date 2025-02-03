# Kali Linux Lab Commands

This project provides a structured web page displaying essential Kali Linux lab commands.

## Lab Commands Overview
### LAB 1: Basic Commands
- whoami
- date
- uname
- ls
- history
- pwd
- nano file.txt
- cat file.txt
- head file.txt
- head -n3 file.txt
- tail.txt
- tail -n3 file.txt
- cal
- cal 2024
- man cal
- cp file1.txt file2.txt
- tac file1.txt //reverse the order of data
- tuch file.txt
- mkdir newfolder
- rmdir newfolder
- rm fil2.txt
- vi text.txt //escape > shift + : > wq >enter
- wc file.txt
- wc -l file.txt
- wc -c file.txt
- wc -w file.txt
- free
- mv file1.txt file2.txt
- sort file.txt
- sort -r file.txt

### LAB 2: Information Gathering
- dnsenum facebook.com
- dnsenum --dnsserver 8.8.8.8 facebook.com
- dnsrecon -h
- dnsrecon -d Instagram.com -c insta.csv

### LAB 3: Network Mapper (nmap)
- nmap facebook.com
- nmap 172.217.27.174
- nmap 172.217.27.174-100
- nmap 103.76.228.*
- nmap -v facebook.com
- nmap <ip> <ip> <ip>
- sudo nmap -sA 192.68.0.50

### LAB 4: Vulnerability Analysis (Nikto)
- nikto -h rlsbca.edu.in
- nikto -h rlsbca.edu.in -ssl
- nikto -h rlsbca.edu.in -port 80,44,22
- nikto -h rlsbca.edu.in -no404

### LAB 5: Advanced Google Dorks
- allintitle:cyber security essentials
- allinurl:cyber security hacker
- cache:courses.stationx.net
- define:reconnaissance
- ext:php site:microsoft.com
- filetype:pdf site:apple.com
- info:apple.com -site:apple.com
- intext:munira tom site:goodreads.com
- intitle:google site:github.com
- inurl:stationx -site:stationx.net
- link:kali.org "kali purple"
- map:Shivaji Colony, Tilakwadi, Belagavi
- phonebook:555-555-5555
- site:github.com nmap

### LAB 6: Social Engineering Toolkit
- Refer lab manual

### LAB 7: Password Attacks (John The Ripper)
- Generate Hash from MD5 website
- Copy SHA1 hash code

#### 1st way
- create new file vi pass.txt
- enter hash code
- run john pass.txt --format=RAW-SHA1

#### 2nd way
- vim words.txt // insert some pass key
- vim pass.txt //enter hash code
- run john --wordlist=word.txt pass.txt --format=RAW-SHA1

### LAB 8: Sniffing & Spoofing (Wireshark)
- Open Wireshark
- Click on any
- Open browser > search any site
- In Wireshark > Edit > Find Packet
- In Window > Display Filter > Set Type = String
- Enter 'git' in the empty box

## Contributing
Feel free to contribute by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.
