bash history kezelés és a promp színezése
===
`1.`)   Forrás és magyarázat:
>
>HistoryMenteseMindenParancsUtan.txt  
>PromtColorChange.txt
>
`2.`)   Telepítés:  
`2.1.`) Konfig fájlok letöltése:  
```
git clone https://github.com/psalan/linux-basics-bash-config.git Letöltések/linux-basics-bash-config
```
vagy
```
wget -cO Letöltések/linux-basics-bash-config.zip https://github.com/psalan/linux-basics-bash-config/archive/master.zip

unzip Letöltések/linux-basics-bash-config.zip -d Letöltések/

mv Letöltések/linux-basics-bash-config-master/ Letöltések/linux-basics-bash-config
```

`2.2.`) A konfig fájlok másolása:  
`2.2.1`)    user konfig
```
cat Letöltések/linux-basics-bash-config/bashrcForUser >> .bashrc
```
`2.2.2`)    /root konfig  
```
sudo -s  

cat Letöltések/linux-basics-bash-config/bashrcForRoot >> /root/.bashrc
```