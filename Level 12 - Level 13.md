---
created: 14-08-2024
---
![[Pasted image 20240814154328.png]]


![[Pasted image 20240814154605.png]]

FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn


```
ls -lhart

mkdir /tmp/anubis

cp data.txt /tmp/anubis

cd /tmp/anubis

ls -lhart

cat data.txt | xxd -r > data2.bin

file data2.bin

mv data2.bin data2.gz

gunzip data2.gz

ls -lhart

bunzip2 data2

ls -lhart

strings data2.out

mv data2.out data4.gz

gunzip data4.gz

strings data4

file data4

 tar -xvf data4

 tar -xvf data5.bin

tar -xvf data6.bin

file data8.bin

mv data8.bin data8.gz

gunzip data8.gz

cat data8

```
