# sshclient
SSH Bash Client para uso em redes q não podem baixar moba, putty etc, com recurso de passar senha

Alternativa: ssh-pass para uso em stages Pipeline com SAS Solutions 

## usage

ssh_sas -h

```
$ ssh_sas -p password ssh user@srv_host

```

## Path bin
```
cp -v ssh_sas /usr/bin/ ; ssh_sas -h
```

Exemplos de uso
```
 ssh_sas -p passw0rd ssh user@servername_or_ip df -h /sasdata  #Logar em server e rodar comando df
```





<h4 style="color: blue;">Referência</h4>
 - sshpass : https://sourceforge.net/projects/sshpass/
