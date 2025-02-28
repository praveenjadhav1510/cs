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
- dnsrecon -d Instagram.com -c insta.csv
- dnsrecon -h

### LAB 3: Network Mapper (nmap)
- nmap facebook.com
- nmap 172.217.27.174
- nmap 172.217.27.174-100
- nmap 103.76.228.*
- nmap -v facebook.com
- nmap 103.76.228.224 157.240.98.35 172.217.27.174
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
#### Method 1 tamplate
<a href="https://drive.google.com/file/d/1Qjvpq43L4JzfwA-VGtxibQWiF3hZQD3h/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/Watch%20Video-Click%20Here-blue?style=for-the-badge">
</a>

#### Method 2 url clone
<a href="https://drive.google.com/file/d/160p_CPwef3tldOQ8euVw6sgHZ7XvoRZU/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/Watch%20Video-Click%20Here-blue?style=for-the-badge">
</a>

### LAB 7: Password Attacks (John The Ripper)
<a href="https://drive.google.com/file/d/1wCxkZHE3Md72mHoLIKl2jIxu1nbyCmY_/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/Watch%20Video-Click%20Here-blue?style=for-the-badge">
</a>

### LAB 8: Sniffing & Spoofing (Wireshark)
<a href="https://drive.google.com/file/d/1TI00KaNUqci8vGKxoBYTIrglrhl4cVmI/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/Watch%20Video-Click%20Here-blue?style=for-the-badge">
</a>


## Contributing
Feel free to contribute by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.
