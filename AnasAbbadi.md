## CST 8254 Practical Mid Term

**Your Name:**

```
Abbadi Anas
```




**1.**

```
 scp "C:\Users\Anas\OneDrive\Bureau\EExam\AnasAbbadi.txt" pi@192.168.2.26:/home/pi

```


**2. What command do you use to see a directory listing that includes the permissions of the files?**

```
ls -l

```

**3.**

```
ls -l > pr1.txt

```

**4.**

```
-rw-r--r-- 1 pi pi 516 Jun 18 16:08 pr1.txt
owner : read and write 
group : read only 
other users : read only
```

**5.**
```
pwd
```
**6.**

```
chmod 710 pr1.txt

```

**7.**

```
mkdir

```

**8.**

```
drwxr-xr-x 2 pi pi 4096 Jun 18 16:15 midtermExam-301
owner : read , write and execute
group : read and execute
other users : read and execute

```

**9.**

```
netstat -at

```

**10.**

```
netstat -at > pr2.txt

```

**11.**

```
sftp pi@192.168.2.26

```

**12.**

```
put midtermPi.txt

```

**13.** 

```
It saves the current folder in a file called mt.txt and adds a list of files and folders one level deep to pr.txt

```

**14.**

```
 sudo useradd AnasAbbadi

```
 **15.**

```
sudo mkdir /home/AnasAbbadi
sudo chown AnasAbbadi:AnasAbbadi /home/AnasAbbadi
```

**16.**

```
sudo apt-get update
sudo apt-get install filezilla
```



**2. What command do you use to see a directory listing that includes the permissions of the files?**

```
ls -l

```
