# **UTS SAS**

Nama : Syahrul Suhura

NIM : 1201290027

Kelas: IT02-02

```markdown
Setelah download selesai, buka virtual box dan buat machine baru dan setting seperti ini kemudian next
```



![image](https://user-images.githubusercontent.com/93044506/143052792-2b4f556c-05dd-43b7-aca9-106f853da189.png)


```markdown
sesuaikan memori dan next
```

![image](https://user-images.githubusercontent.com/93044506/143053713-505d354b-66c1-43dc-93fe-f93100409408.png)

```markdown
Buat virtual mesin
```

![image](https://user-images.githubusercontent.com/93044506/143053795-90a68ffa-6bc1-41cc-9730-0d0e58de66a9.png)

![image](https://user-images.githubusercontent.com/93044506/143054048-fe533d76-049f-4052-9d60-fdeb29ae5215.png)


![image](https://user-images.githubusercontent.com/93044506/143054250-d7a053b6-b2ab-4a71-975a-11437c013385.png)



![image](https://user-images.githubusercontent.com/93044506/143054650-fd3c51a0-206e-4866-8b7e-4c53c5e3614c.png)

```markdown
Masuk ke setting > network dan ubah nat menjadi bridge
```

![image](https://user-images.githubusercontent.com/93044506/143054876-5922f7fe-1c39-4957-a0cb-4e6531563309.png)


```markdown
Klik start dan pilih file iso yang sudah di download tadi
```

![image](https://user-images.githubusercontent.com/93044506/143055020-076a74ef-1cd0-4101-a741-124ab70ff9fb.png)

![image](https://user-images.githubusercontent.com/93044506/143055121-8206ac96-d1e8-4865-bc47-8e3645959fa6.png)

```markdown
Setting waktu zona Indonesia kemudian next
```

![image](https://user-images.githubusercontent.com/93044506/143055178-4cb8dac7-650c-46d7-a70f-26cb90f1eb8d.png)

```markdown
kemudian install now
```

![image](https://user-images.githubusercontent.com/93044506/143055273-63c8d45b-841d-4a91-b5e4-9b3e1f3e98a6.png)

```markdown
Pilih windos server 2022 Datacenter Evaluation (desktop experience) dan next
```

![image](https://user-images.githubusercontent.com/93044506/143055499-f99b0ab9-2f9b-49f9-85c5-ec0d6dc8beb0.png)

```markdown
Centang dan next
```

![image](https://user-images.githubusercontent.com/93044506/143055595-173f7279-831e-4e22-b648-60d10135d27f.png)

```markdown
Pilih custome : install Microsoft Server Operating System Only (advanced)
```

![image](https://user-images.githubusercontent.com/93044506/143055682-01fa476a-c65f-4bc2-844b-56ae611b9779.png)

```markdown
Kemudian next
```

![image](https://user-images.githubusercontent.com/93044506/143055751-ecdd62c6-f2bd-4a0b-87f2-13524af2211e.png)

```markdown
Tunggu hingga proses selesai
```

![image](https://user-images.githubusercontent.com/93044506/143055821-e0f464dd-513d-4272-ae13-3d7dbbc8b3b2.png)

```markdown
Setelah proses install selesai maka tampilan akan seperti ini
```

![image](https://user-images.githubusercontent.com/93044506/143055872-293c599f-cc52-4f69-9398-679cfc363c8e.png)

```markdown
Setelah selesai buat password. Setelah selesai buat password pergi  ke input>keyboard >insert ctrl-alt-del untuk membuka layer kunci
```

![image](https://user-images.githubusercontent.com/93044506/143058516-6a6a17e4-04b7-47b8-805e-1887601f4a89.png)

```markdown
Setelah terbuka baru kita dapat memasaukkan password yang dibuat
```

![image](https://user-images.githubusercontent.com/93044506/143058696-01a7caa9-e4d2-4488-91f2-093b3fac2755.png)

```markdown
Setelah itu pergi ke device > insert guest additions CD image
Lalu ke file explorer > cd Drive Virtual box > lalu pilih VBox WindiwsAdditions

```

![image](https://user-images.githubusercontent.com/93044506/143058840-581cfbb7-f589-4c04-bbde-e253f0951e36.png)

![image](https://user-images.githubusercontent.com/93044506/143058902-76fa6184-5bfb-4283-a950-9f0d3d1b2399.png)

![image](https://user-images.githubusercontent.com/93044506/143058959-57fc26ad-23f9-406f-8ec6-bba9d4be5e95.png)

```markdown
install
```

![image](https://user-images.githubusercontent.com/93044506/143059068-d8b34469-e0f5-402c-8a1f-61c5eede1211.png)

```markdown
Kemudian reboot now
```

```markdown
Setelah reboot lakukan Langkah seperti diatas untuk masuk ke windows server dengan menekan ctrl+alt+del pada input>keyboards
```

![image](https://user-images.githubusercontent.com/93044506/143059358-0c869d0b-6257-4e2e-8bb5-d183b7d45a6c.png)

### ** INSTALLASI ACTIVE DIRECTORY DOMAIN SERVER**

```markdown
Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”
```

![image](https://user-images.githubusercontent.com/93044506/143059461-27fbb6fe-a773-4b40-8136-cd281e80ba8f.png)

```markdown
Kemudian masuk ke server manager pilih menu manage 
```

![image](https://user-images.githubusercontent.com/93044506/143059523-1f3e50df-2976-4e3d-8790-4eb182f7e93f.png)

```markdown
Kemudian pilih Add Roles and Features dan next
```

![image](https://user-images.githubusercontent.com/93044506/143059578-6dfe76da-a637-43cc-8c1c-bd8dcb62cc77.png)

```markdown
Pilih Role-Based or feature-based installation kemudian next
```

![image](https://user-images.githubusercontent.com/93044506/143059675-9bd05beb-29e1-43d4-8e0e-f596b295eec0.png)

```markdown
Setelah itu pilih select a server from the server pool
Lalu pilih active directory domain server

```

![image](https://user-images.githubusercontent.com/93044506/143059758-d353e507-9588-46c4-ab7f-9583ac89e917.png)
```markdown
Kemudain klik add features
```

![image](https://user-images.githubusercontent.com/93044506/143061716-22dcf30f-f7e3-4077-9a5c-094dc81dbc25.png)

```markdown
Kemudian ke features lalu centang Group Policy Management dan next
```

![image](https://user-images.githubusercontent.com/93044506/143061818-9cd57c94-9c26-4879-b9d7-4f48dc1ed722.png)
```markdown
Kemudian install
```

![image](https://user-images.githubusercontent.com/93044506/143062033-48f55a56-5683-496a-828c-0e48d1f71fc8.png)

```markdown
Setting ip static di cmd menggunakan command> sconfig
```

![image](https://user-images.githubusercontent.com/93044506/143062121-6c661b27-d1e0-47bf-84ba-2286e2a5808c.png)

![image](https://user-images.githubusercontent.com/93044506/143062191-9574d740-468e-4fe9-80d8-31d83a1e2bb7.png)

![image](https://user-images.githubusercontent.com/93044506/143062258-876663e1-e604-47f4-8176-1ac1179878d0.png)

![image](https://user-images.githubusercontent.com/93044506/143062317-f459c69b-b8b6-4f11-99cc-48d077497bfd.png)

![image](https://user-images.githubusercontent.com/93044506/143062350-13c88e4a-417e-4aa7-a4e7-7d4e3f1b21ec.png)


#### **INSTALLASI DNS**

```markdown
Kemudian install DNS server sama seperti menginstal domain 
```

![image](https://user-images.githubusercontent.com/93044506/143062424-4881d36a-904f-4888-b0a9-811aaecfa241.png)

#### **INSTALLASI NET FRAMEWORK 3.5**

```markdown
Setelah selesai install NET Framework 3.5
```

![image](https://user-images.githubusercontent.com/93044506/143062534-2fb31a21-4d13-496e-a233-e42793e8b288.png)

![image](https://user-images.githubusercontent.com/93044506/143062785-3b29e92d-5050-4c32-9edc-e22daebb3eb9.png)



#### **PROMOTE SERVER TO A DOMAIN**

```markdown
Kemudian Promote Server to a Domain Controller dengan menekan tanda seru
```

![image](https://user-images.githubusercontent.com/93044506/143062854-2826b680-20a3-42df-9be8-e54810cb192b.png)

```markdown
Pilih add new forest dan beri nama
```

![image](https://user-images.githubusercontent.com/93044506/143063016-99949d95-e6e4-4c0d-b923-20094fd232e9.png)

![image](https://user-images.githubusercontent.com/93044506/143063113-b4d72bd8-fbf8-4920-a27e-a0279b100b1f.png)

![image](https://user-images.githubusercontent.com/93044506/143063155-ca178616-783e-4580-a21c-5ea99bec1d58.png)

![image](https://user-images.githubusercontent.com/93044506/143063216-4a936df2-7d5c-4528-b722-bd0e3e1795f0.png)

![image](https://user-images.githubusercontent.com/93044506/143063279-d24a662b-9208-4493-90cc-34f90232d09b.png)

![image](https://user-images.githubusercontent.com/93044506/143063326-372e609f-8229-4e02-a713-c6d819c4bf26.png)

```markdown
Kemudian Install
```

![image](https://user-images.githubusercontent.com/93044506/143063382-f687ead4-4a28-4ccd-b308-e42f93b27d06.png)

```markdown
Kemudian Close setelah install selesai
```

![image](https://user-images.githubusercontent.com/93044506/143063425-2d93623e-8f29-401c-a836-dffc52f428d6.png)

```markdown
Setelah close WS akan restart dan akan berganti nama 
```

![image](https://user-images.githubusercontent.com/93044506/143063487-9c3aaf91-2f75-427e-8446-a7abc2809022.png)

```markdown
Lakukan pengecekan konfigurasi pada command prompt untuk mengetahui kesuksesan installasi
```

![image](https://user-images.githubusercontent.com/93044506/143063745-f64fbb44-5d6b-4a8f-939c-1525d3fd2eb6.png)

```markdown
Kemudian cek ip address di network
```

![image](https://user-images.githubusercontent.com/93044506/143063854-47fb5c94-8ee6-42c2-b951-a2c15f19cb68.png)

```markdown
Kemudian ubah menjadi ip address yang di atas
```

![image](https://user-images.githubusercontent.com/93044506/143063913-73ebb33e-14a6-4a50-832c-15a5bec3844a.png)
