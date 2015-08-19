#### Level 0
login as : bandit0  
Password : bandit0 

#### level 0 to Level 1
login as : bandit0  
Password : bandit0  

###### Procedure
bandit0@melinda:~$ ls  
readme  
bandit0@melinda:~$ cat readme  
boJ9jbbUNNfktd78OOpsqOltutMc3MY1 

#### level 1 to Level 2
login as : bandit1  
Password : boJ9jbbUNNfktd78OOpsqOltutMc3MY1 

###### Procedure
bandit1@melinda:~$ ls
\-  
bandit1@melinda:~$ cat ./\-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9 

#### level 2 to Level 3
login as : bandit2  
Password : CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9  

###### Procedure
bandit2@melinda:~$ ls  
spaces in this filename  
bandit2@melinda:~$ cat ./spaces\ in\ this\ filename  
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK  

#### level 3 to Level 4
login as : bandit3  
Password : UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK  

###### Procedure
bandit3@melinda:~$ ls  
inhere  
bandit3@melinda:~$ cd inhere  
bandit3@melinda:~/inhere$ ls  
bandit3@melinda:~/inhere$ ls -al  
total 12  
drwxr-xr-x 2 root    root    4096 Nov 14  2014 .  
drwxr-xr-x 3 root    root    4096 Nov 14  2014 ..  
-rw-r----- 1 bandit4 bandit3   33 Nov 14  2014 .hidden  
bandit3@melinda:~/inhere$ cat .hidden  
pIwrPrtPN36QITSp3EQaw936yaFoFgAB  

#### level 4 to Level 5
login as : bandit4  
Password : pIwrPrtPN36QITSp3EQaw936yaFoFgAB  

###### Procedure
bandit4@melinda:~$ ls  
inhere  
bandit4@melinda:~$ cd inhere  
bandit4@melinda:~/inhere$ ls  
-file00  -file02  -file04  -file06  -file08  
-file01  -file03  -file05  -file07  -file09  
bandit4@melinda:~/inhere$ for f in ./*; do cat $f; done;  
;▒-▒(▒▒z▒▒У▒▒ޘ▒▒8鑾?▒@c  
                       O8▒L▒c▒Ч7▒zb~▒▒ף▒▒U▒▒g▒f▒4▒6+>"▒▒B▒Vx▒▒d▒▒;de▒O▒:n▒▒▒▒8S▒▒Ѕ[▒/q▒(▒▒@▒▒M▒.▒t▒▒▒▒+▒▒5▒`▒¶R  
▒1*6C▒u#Nr▒▒▒hZ▒▒▒P▒邚▒▒▒{#▒TP▒▒6▒]▒▒X:▒▒▒!▒>P▒  
d{▒▒▒▒ҏH▒▒▒xX|▒koReBOKuIDDepwhWk7jZC0RTdopnAYKh 
[:*▒▒▒?▒▒j▒▒▒U▒ 

#### level 5 to Level 6
login as : bandit5  
Password : koReBOKuIDDepwhWk7jZC0RTdopnAYKh  

###### Procedure
bandit5@melinda:~$ ls  
inhere  
bandit5@melinda:~$ cd inhere  
bandit5@melinda:~/inhere$ ls  
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16  
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17  
maybehere02  maybehere06  maybehere10  maybehere14  maybehere18  
maybehere03  maybehere07  maybehere11  maybehere15  maybehere19  
bandit5@melinda:~/inhere$ find -readable -size 1033c ! -executable  
./maybehere07/.file2  
bandit5@melinda:~/inhere$ cat ./maybehere07/.file2  
DXjZPULLxYr17uwoI01bNLQbtFemEgo7  

#### level 6 to Level 7
login as : bandit6  
Password : DXjZPULLxYr17uwoI01bNLQbtFemEgo7  

###### Procedure
bandit6@melinda:~$ ls  
bandit6@melinda:~$ find / -user bandit7 -group bandit6 -size 33c 2>&1 | grep -v -F Permission  
/var/lib/dpkg/info/bandit7.password  
bandit6@melinda:~$ cat /var/lib/dpkg/info/bandit7.password  
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs  

#### level 7 to Level 8
login as : bandit7  
Password : HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs  

###### Procedure
bandit7@melinda:~$ ls  
data.txt  
bandit7@melinda:~$ grep millionth data.txt  
millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV  

#### level 8 to Level 9
login as : bandit8  
Password : cvX2JJa4CFALtqS87jk27qwqGhBM9plV  

###### Procedure
bandit8@melinda:~$ ls  
data.txt  
bandit8@melinda:~$ sort data.txt | uniq --count | grep "1 "  
      1 UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR  

#### level 9 to Level 10
login as : bandit9  
Password : UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR  

###### Procedure
bandit9@melinda:~$ ls  
data.txt  
bandit9@melinda:~$ strings data.txt | grep "="  
epr~F=K  
7?YD=  
?M=HqAH  
/(Ne=  
C=_" 
I========== the6  
z5Y=  
`h(8=`  
n\H=;  
========== password  
========== ism  
N$=&  
l/a=L)  
f=C(  
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  
ie)=5e  

#### level 10 to Level 11
login as : bandit10  
Password : truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  

###### Procedure  
bandit10@melinda:~$ ls 
data.txt  
bandit10@melinda:~$ cat data.txt  
VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg==  
bandit10@melinda:~$ base64 --decode data.txt  
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR  

#### level 11 to Level 12
login as : bandit11  
Password : IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR  

###### Procedure
bandit11@melinda:~$ ls  
data.txt  
bandit11@melinda:~$ cat data.txt  
Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh  
bandit11@melinda:~$ alias rot13="tr a-zA-Z n-za-mN-ZA-M"  
bandit11@melinda:~$ cat data.txt | rot13  
The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu  

#### level 12 to Level 13
login as : bandit12  
Password : 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu  

###### Procedure
bandit12@melinda:~$ ls  
data.txt  
bandit12@melinda:~$ mkdir -p /tmp/simple-plan/  
bandit12@melinda:~$ cp data.txt /tmp/simple-plan/  
bandit12@melinda:~$ cd /tmp/simple-plan/  
bandit12@melinda:/tmp/simple-plan$ xxd -r data.txt > banditfile  
bandit12@melinda:/tmp/simple-plan$ file banditfile  
banditfile: gzip compressed data, was "data2.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression  
bandit12@melinda:/tmp/simple-plan$ mv banditfile banditfile.gz  
bandit12@melinda:/tmp/simple-plan$ gzip -d banditfile.gz  
bandit12@melinda:/tmp/simple-plan$ file banditfile  
banditfile: bzip2 compressed data, block size = 900k  
bandit12@melinda:/tmp/simple-plan$ mv banditfile banditfile.bz2  
bandit12@melinda:/tmp/simple-plan$ bzip2 -d banditfile.bz2  
bandit12@melinda:/tmp/simple-plan$ file banditfile  
banditfile: gzip compressed data, was "data4.bin", from Unix, last modified: Fri Nov 14 10:32:20 2014, max compression  
bandit12@melinda:/tmp/simple-plan$ mv banditfile banditfile.gz  
bandit12@melinda:/tmp/simple-plan$ gzip -d banditfile.gz  
bandit12@melinda:/tmp/simple-plan$ file banditfile  
banditfile: POSIX tar archive (GNU)  
bandit12@melinda:/tmp/simple-plan$ tar -xvf banditfile  
data5.bin  
bandit12@melinda:/tmp/simple-plan$ file data5.bin  
data5.bin: POSIX tar archive (GNU)  
bandit12@melinda:/tmp/simple-plan$ tar -xvf data5.bin  
data6.bin  
bandit12@melinda:/tmp/simple-plan$  file data6.bin  
data6.bin: bzip2 compressed data, block size = 900k  
bandit12@melinda:/tmp/simple-plan$ mv data6.bin banditfile.bz2  
bandit12@melinda:/tmp/simple-plan$ bzip2 -d banditfile.bz2  
bandit12@melinda:/tmp/simple-plan$ file banditfile  
banditfile: POSIX tar archive (GNU)  
bandit12@melinda:/tmp/simple-plan$ tar -xvf banditfile  
data5.bin  
bandit12@melinda:/tmp/simple-plan$  
bandit12@melinda:/tmp/simple-plan$ file data5.bin  
data5.bin: POSIX tar archive (GNU) 
bandit12@melinda:/tmp/simple-plan$ mv data5.bin data8.gz ; gzip -d data8.gz 
bandit12@melinda:/tmp/simple-plan$ file data8  
data8: ASCII text 
bandit12@melinda:/tmp/simple-plan$ file data8  
The password is 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL  

#### level 13 to Level 14
login as : bandit13  
Password : 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL  

###### Procedure
bandit13@melinda:~$ ls  
sshkey.private 
bandit13@melinda:~$ cat sshkey.private 
-----BEGIN RSA PRIVATE KEY----- 
MIIEpAIBAAKCAQEAxkkOE83W2cOT7IWhFc9aPaaQmQDdgzuXCv+ppZHa++buSkN+
gg0tcr7Fw8NLGa5+Uzec2rEg0WmeevB13AIoYp0MZyETq46t+jk9puNwZwIt9XgB
ZufGtZEwWbFWw/vVLNwOXBe4UWStGRWzgPpEeSv5Tb1VjLZIBdGphTIK22Amz6Zb
ThMsiMnyJafEwJ/T8PQO3myS91vUHEuoOMAzoUID4kN0MEZ3+XahyK0HJVq68KsV
ObefXG1vvA3GAJ29kxJaqvRfgYnqZryWN7w3CHjNU4c/2Jkp+n8L0SnxaNA+WYA7
jiPyTF0is8uzMlYQ4l1Lzh/8/MpvhCQF8r22dwIDAQABAoIBAQC6dWBjhyEOzjeA
J3j/RWmap9M5zfJ/wb2bfidNpwbB8rsJ4sZIDZQ7XuIh4LfygoAQSS+bBw3RXvzE
pvJt3SmU8hIDuLsCjL1VnBY5pY7Bju8g8aR/3FyjyNAqx/TLfzlLYfOu7i9Jet67
xAh0tONG/u8FB5I3LAI2Vp6OviwvdWeC4nOxCthldpuPKNLA8rmMMVRTKQ+7T2VS
nXmwYckKUcUgzoVSpiNZaS0zUDypdpy2+tRH3MQa5kqN1YKjvF8RC47woOYCktsD
o3FFpGNFec9Taa3Msy+DfQQhHKZFKIL3bJDONtmrVvtYK40/yeU4aZ/HA2DQzwhe
ol1AfiEhAoGBAOnVjosBkm7sblK+n4IEwPxs8sOmhPnTDUy5WGrpSCrXOmsVIBUf
laL3ZGLx3xCIwtCnEucB9DvN2HZkupc/h6hTKUYLqXuyLD8njTrbRhLgbC9QrKrS
M1F2fSTxVqPtZDlDMwjNR04xHA/fKh8bXXyTMqOHNJTHHNhbh3McdURjAoGBANkU
1hqfnw7+aXncJ9bjysr1ZWbqOE5Nd8AFgfwaKuGTTVX2NsUQnCMWdOp+wFak40JH
PKWkJNdBG+ex0H9JNQsTK3X5PBMAS8AfX0GrKeuwKWA6erytVTqjOfLYcdp5+z9s
8DtVCxDuVsM+i4X8UqIGOlvGbtKEVokHPFXP1q/dAoGAcHg5YX7WEehCgCYTzpO+
xysX8ScM2qS6xuZ3MqUWAxUWkh7NGZvhe0sGy9iOdANzwKw7mUUFViaCMR/t54W1
GC83sOs3D7n5Mj8x3NdO8xFit7dT9a245TvaoYQ7KgmqpSg/ScKCw4c3eiLava+J
3btnJeSIU+8ZXq9XjPRpKwUCgYA7z6LiOQKxNeXH3qHXcnHok855maUj5fJNpPbY
iDkyZ8ySF8GlcFsky8Yw6fWCqfG3zDrohJ5l9JmEsBh7SadkwsZhvecQcS9t4vby
9/8X4jS0P8ibfcKS4nBP+dT81kkkg5Z5MohXBORA7VWx+ACohcDEkprsQ+w32xeD
qT1EvQKBgQDKm8ws2ByvSUVs9GjTilCajFqLJ0eVYzRPaY6f++Gv/UVfAPV4c+S0
kAWpXbv5tbkkzbS0eaLPTKgLzavXtQoTtKwrjpolHKIHUz6Wu+n4abfAIRFubOdN
/+aLoRQ0yBDRbdXMsZN/jvY44eM+xRLdRVyMmdPtP8belRi2E2aEzA==  
-----END RSA PRIVATE KEY-----  
bandit13@melinda:~$ ssh -i ./sshkey.private bandit14@localhost  
Could not create directory '/home/bandit13/.ssh'.  
The authenticity of host 'localhost (127.0.0.1)' can't be established.  
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.  
Are you sure you want to continue connecting (yes/no)? yes  
bandit14@melinda:~$ cat /etc/bandit_pass/bandit14  
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e  

#### level 14 to Level 15
login as : bandit14  
Password : 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e  

###### Procedure
bandit14@melinda:~$ echo 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e | nc -v localhost 30000         
Connection to localhost 30000 port [tcp/*] succeeded!  
Correct!  
BfMYroe26WYalil77FoDi9qh59eK5xNr  

#### level 15 to Level 16
login as : bandit15  
Password : BfMYroe26WYalil77FoDi9qh59eK5xNr  

###### Procedure
bandit15@melinda:~$ echo BfMYroe26WYalil77FoDi9qh59eK5xNr | openssl s_client -quiet -connect localhost:30001  
depth=0 CN = li190-250.members.linode.com  
verify error:num=18:self signed certificate  
verify return:1  
depth=0 CN = li190-250.members.linode.com  
verify return:1  
Correct!  
cluFn7wTiGryunymYOu4RcffSxQluehd  

#### level 16 to Level 17
login as : bandit16  
Password : cluFn7wTiGryunymYOu4RcffSxQluehd  

###### Procedure
bandit16@melinda:~$ nmap -sT localhost -p31000-32000  

Starting Nmap 6.40 ( http://nmap.org ) at 2015-08-19 20:59 UTC  
Nmap scan report for localhost (127.0.0.1)  
Host is up (0.00080s latency).  
Not shown: 996 closed ports  
PORT      STATE SERVICE  
31046/tcp open  unknown  
31518/tcp open  unknown  
31691/tcp open  unknown  
31790/tcp open  unknown  
31960/tcp open  unknown  

Nmap done: 1 IP address (1 host up) scanned in 0.08 seconds  
bandit16@melinda:~$ echo test | nc -v localhost 31046  
Connection to localhost 31046 port [tcp/*] succeeded!  
test  
bandit16@melinda:~$ echo test | nc -v localhost 31518  
Connection to localhost 31518 port [tcp/*] succeeded!  
ERROR 
140737354045088:error:1408F10B:SSL routines:SSL3_GET_RECORD:wrong version number:s3_pkt.c:350:  
bandit16@melinda:~$ echo test | nc -v localhost 31691  
Connection to localhost 31691 port [tcp/*] succeeded!  
test  
bandit16@melinda:~$ echo test | nc -v localhost 31790  
Connection to localhost 31790 port [tcp/*] succeeded!  
ERROR 
140737354045088:error:1408F10B:SSL routines:SSL3_GET_RECORD:wrong version number:s3_pkt.c:350:  
bandit16@melinda:~$ echo test | nc -v localhost 31960  
Connection to localhost 31960 port [tcp/*] succeeded!  
test  
bandit16@melinda:~$ echo cluFn7wTiGryunymYOu4RcffSxQluehd | openssl s_client -quiet -connect localhost:31518  
depth=0 CN = li190-250.members.linode.com  
verify error:num=18:self signed certificate  
verify return:1  
depth=0 CN = li190-250.members.linode.com  
verify return:1 
cluFn7wTiGryunymYOu4RcffSxQluehd  
^C  
bandit16@melinda:~$ echo cluFn7wTiGryunymYOu4RcffSxQluehd | openssl s_client -quiet -connect localhost:31790  
depth=0 CN = li190-250.members.linode.com  
verify error:num=18:self signed certificate  
verify return:1  
depth=0 CN = li190-250.members.linode.com 
verify return:1  
Correct!  
-----BEGIN RSA PRIVATE KEY-----  
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY----- 

read:errno=0  
bandit16@melinda:~$ mkdir -p /tmp/key/  
bandit16@melinda:~$ cd /tmp/key/   
bandit16@melinda:/tmp/key$ touch sshkey.private  
bandit16@melinda:/tmp/key$ vim sshkey.private  
bandit16@melinda:/tmp/key$ ssh -i ./sshkey.private bandit17@localhost  
Could not create directory '/home/bandit16/.ssh'.  
The authenticity of host 'localhost (127.0.0.1)' can't be established.  
ECDSA key fingerprint is 05:3a:1c:25:35:0a:ed:2f:cd:87:1c:f6:fe:69:e4:f6.  
Are you sure you want to continue connecting (yes/no)? yes  

#### level 17 to Level 18

###### Procedure
bandit17@melinda:~$ ls  
passwords.new  passwords.old  
bandit17@melinda:~$ diff passwords.new passwords.old  
42c42  
\< kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd  
\---  
\> BS8bqB1kqkinKJjuxL6k072Qq9NRwQpR  

#### level 18 to Level 19
login as : bandit18  
Password : kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd  

