# **UTS SAS**

Nama : Syahrul Suhura

NIM : 1201290027

Kelas: IT02-02

```markdown
Setelah download selesai, buka virtual box dan buat machine baru dan setting seperti ini kemudian next
```



![](C:\Users\syahrul suhura\Pictures\a.png)

```markdown
sesuaikan memori dan next
```

![image-20211123211051657](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123211051657.png)

```markdown
Buat virtual mesin
```

![image-20211123220015074](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220015074.png)

![image-20211123231246038](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123231246038.png)

![image-20211123231627735](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123231627735.png)



![image-20211123220126845](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220126845.png)

```markdown
Masuk ke setting > network dan ubah nat menjadi bridge
```

![image-20211123220151225](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220151225.png)

```markdown
Klik start dan pilih file iso yang sudah di download tadi
```

![image-20211123220219903](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220219903.png)

![image-20211123220224706](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220224706.png)

```markdown
Setting waktu zona Indonesia kemudian next
```

![image-20211123220303996](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220303996.png)

```markdown
kemudian install now
```

![image-20211123220600643](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220600643.png)

```markdown
Pilih windos server 2022 Datacenter Evaluation (desktop experience) dan next
```

![image-20211123220627212](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220627212.png)

```markdown
Centang dan next
```

![image-20211123220857067](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220857067.png)

```markdown
Pilih custome : install Microsoft Server Operating System Only (advanced)
```

![image-20211123220932205](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220932205.png)

```markdown
Kemudian next
```

![image-20211123220951895](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123220951895.png)

```markdown
Tunggu hingga proses selesai
```

![image-20211123221011111](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221011111.png)

```markdown
Setelah proses install selesai maka tampilan akan seperti ini
```

![image-20211123221032384](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221032384.png)

```markdown
Setelah selesai buat password. Setelah selesai buat password pergi  ke input>keyboard >insert ctrl-alt-del untuk membuka layer kunci
```

![image-20211123221056127](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221056127.png)

```markdown
Setelah terbuka baru kita dapat memasaukkan password yang dibuat
```

![image-20211123221136358](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221136358.png)

```markdown
Setelah itu pergi ke device > insert guest additions CD image
Lalu ke file explorer > cd Drive Virtual box > lalu pilih VBox WindiwsAdditions

```

![image-20211123221213223](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221213223.png)

![image-20211123221224858](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221224858.png)

![image-20211123221231842](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221231842.png)

```markdown
install
```

![image-20211123221257076](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221257076.png)

```markdown
Kemudian reboot now
```

```markdown
Setelah reboot lakukan Langkah seperti diatas untuk masuk ke windows server dengan menekan ctrl+alt+del pada input>keyboards
```

![image-20211123221331807](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221331807.png)

### ** INSTALLASI ACTIVE DIRECTORY DOMAIN SERVER**

```markdown
Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”
```

![image-20211123221452911](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221452911.png)

```markdown
Kemudian masuk ke server manager pilih menu manage 
```

![image-20211123221526158](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221526158.png)

```markdown
Kemudian pilih Add Roles and Features dan next
```

![image-20211123221546161](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221546161.png)

```markdown
Pilih Role-Based or feature-based installation kemudian next
```

![image-20211123221606571](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221606571.png)

```markdown
Setelah itu pilih select a server from the server pool
Lalu pilih active directory domain server

```

![image-20211123221628027](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221628027.png)

```markdown
Kemudain klik add features
```

![image-20211123221646741](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221646741.png)

```markdown
Kemudian ke features lalu centang Group Policy Management dan next
```

![image-20211123221705142](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221705142.png)

```markdown
Kemudian install
```

![image-20211123221722375](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221722375.png)

```markdown
Setting ip static di cmd menggunakan command> sconfig
```

![image-20211123221738459](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221738459.png)

![image-20211123221745239](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221745239.png)

![image-20211123221751137](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221751137.png)

![image-20211123221757172](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221757172.png)

![image-20211123221803146](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221803146.png)



#### **INSTALLASI DNS**

```markdown
Kemudian install DNS server sama seperti menginstal domain 
```

![image-20211123221825586](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221825586.png)

#### **INSTALLASI NET FRAMEWORK 3.5**

```markdown
Setelah selesai install NET Framework 3.5
```

![image-20211123221844754](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221844754.png)

![image-20211123221851072](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221851072.png)



#### **PROMOTE SERVER TO A DOMAIN**

```markdown
Kemudian Promote Server to a Domain Controller dengan menekan tanda seru
```

![image-20211123221911768](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221911768.png)

```markdown
Pilih add new forest dan beri nama
```

![image-20211123221946842](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221946842.png)

![image-20211123221953656](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221953656.png)

![image-20211123221959709](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123221959709.png)

![image-20211123222005905](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222005905.png)

![image-20211123222012678](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222012678.png)

![image-20211123222019466](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222019466.png)

```markdown
Kemudian Install
```

![image-20211123222038189](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222038189.png)

```markdown
Kemudian Close setelah install selesai
```

![image-20211123222142772](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222142772.png)

```markdown
Setelah close WS akan restart dan akan berganti nama 
```

![image-20211123222200422](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222200422.png)

```markdown
Lakukan pengecekan konfigurasi pada command prompt untuk mengetahui kesuksesan installasi
```

![image-20211123222226229](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222226229.png)

```markdown
Kemudian cek ip address di network
```

![image-20211123222245220](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222245220.png)

```markdown
Kemudian ubah menjadi ip address yang di atas
```

![image-20211123222302494](C:\Users\syahrul suhura\AppData\Roaming\Typora\typora-user-images\image-20211123222302494.png)