## Git and GitHub

It was weird to start learning programming with something that is not programming. But after a several tries it seems easy and useful. I also like so much Learn Git Branching. It was somewhat challenging but not so difficult to actully did it.Great tutorial. And now, when I now what Git is, the most difficult task will be to force myself to use it. And I hope it will also help to finally remember all the commands.

(It really was so thrilling to make a first pull request even though it's just adding a couple of lines of greetings.)

---

## Unix Shell

I've never worked with command line before, but it wasn't that difficult. And still, communicating with the PC on this level feels great. I've managed to deal with all quizes on Linux Survival, but returning to them a month later was a challenge. It's really important to use it every day to get used to all commands. 


![LinSurv1](task_unix_shell/LinSurv1.png)

![LinSurv2](task_unix_shell/LinSurv2.png)

![LinSurv3](task_unix_shell/LinSurv3.png)

![LinSurv4](task_unix_shell/LinSurv4.png)


---

## Git Collaboration

Git is a powerful took gut GitHub is a real monster. At first, it's difficult to get used to it. What's even cooler that it seems so elegant. And it it's really a great pleasue when your pull-request was being approved. I want more. And "Git Flight Rules" is an absolute masterpiece.

![git_collaboration](task_git_collaboration/git_collaboration.png)

---

## Python Basics 1

[My HackerRank profile](https://www.hackerrank.com/yura_palayda)


---

## Memory Management 

By far, it is the most difficult topic, primarily because I couldn't gasp what's the point of knowledge about memory usage in high-level programming. But at least it's interesting to better undestand the concept of the whole computer.

### Answers

#### 1

> What's going to happen if program reaches maximum limit of stack?

If the maximum stack size has been reached, it causes a Stack Overflow. 

> What's going to happen if program requests a big (more then 128KB) memory allocation on heap?

Instead of using heap memory an anonymous mapping with the required amount of space will be created.

> What's the difference between Text and Data memory segments?

Data segment is a space for holding static variables. 
Text segment contains executable instructions of the program and is read-only.

#### 2

```
558196c5b000-558196d5f000 r-xp 00000000 08:01 786441                     /bin/bash
558196f5e000-558196f62000 r--p 00103000 08:01 786441                     /bin/bash
558196f62000-558196f6b000 rw-p 00107000 08:01 786441                     /bin/bash
558196f6b000-558196f75000 rw-p 00000000 00:00 0 
558197d89000-558197f00000 rw-p 00000000 00:00 0                          [heap]
7fbfa1c37000-7fbfa1c42000 r-xp 00000000 08:01 1186025                    /lib/x86_64-linux-gnu/libnss_files-2.27.so
7fbfa1c42000-7fbfa1e41000 ---p 0000b000 08:01 1186025                    /lib/x86_64-linux-gnu/libnss_files-2.27.so
7fbfa1e41000-7fbfa1e42000 r--p 0000a000 08:01 1186025                    /lib/x86_64-linux-gnu/libnss_files-2.27.so
7fbfa1e42000-7fbfa1e43000 rw-p 0000b000 08:01 1186025                    /lib/x86_64-linux-gnu/libnss_files-2.27.so
7fbfa1e43000-7fbfa1e49000 rw-p 00000000 00:00 0 
7fbfa1e49000-7fbfa1e60000 r-xp 00000000 08:01 1186019                    /lib/x86_64-linux-gnu/libnsl-2.27.so
7fbfa1e60000-7fbfa205f000 ---p 00017000 08:01 1186019                    /lib/x86_64-linux-gnu/libnsl-2.27.so
7fbfa205f000-7fbfa2060000 r--p 00016000 08:01 1186019                    /lib/x86_64-linux-gnu/libnsl-2.27.so
7fbfa2060000-7fbfa2061000 rw-p 00017000 08:01 1186019                    /lib/x86_64-linux-gnu/libnsl-2.27.so
7fbfa2061000-7fbfa2063000 rw-p 00000000 00:00 0 
7fbfa2063000-7fbfa206e000 r-xp 00000000 08:01 1186036                    /lib/x86_64-linux-gnu/libnss_nis-2.27.so
7fbfa206e000-7fbfa226d000 ---p 0000b000 08:01 1186036                    /lib/x86_64-linux-gnu/libnss_nis-2.27.so
7fbfa226d000-7fbfa226e000 r--p 0000a000 08:01 1186036                    /lib/x86_64-linux-gnu/libnss_nis-2.27.so
7fbfa226e000-7fbfa226f000 rw-p 0000b000 08:01 1186036                    /lib/x86_64-linux-gnu/libnss_nis-2.27.so
7fbfa226f000-7fbfa2277000 r-xp 00000000 08:01 1186021                    /lib/x86_64-linux-gnu/libnss_compat-2.27.so
7fbfa2277000-7fbfa2477000 ---p 00008000 08:01 1186021                    /lib/x86_64-linux-gnu/libnss_compat-2.27.so
7fbfa2477000-7fbfa2478000 r--p 00008000 08:01 1186021                    /lib/x86_64-linux-gnu/libnss_compat-2.27.so
7fbfa2478000-7fbfa2479000 rw-p 00009000 08:01 1186021                    /lib/x86_64-linux-gnu/libnss_compat-2.27.so
7fbfa2479000-7fbfa2fc0000 r--p 00000000 08:01 924470                     /usr/lib/locale/locale-archive
7fbfa2fc0000-7fbfa31a7000 r-xp 00000000 08:01 1185935                    /lib/x86_64-linux-gnu/libc-2.27.so
7fbfa31a7000-7fbfa33a7000 ---p 001e7000 08:01 1185935                    /lib/x86_64-linux-gnu/libc-2.27.so
7fbfa33a7000-7fbfa33ab000 r--p 001e7000 08:01 1185935                    /lib/x86_64-linux-gnu/libc-2.27.so
7fbfa33ab000-7fbfa33ad000 rw-p 001eb000 08:01 1185935                    /lib/x86_64-linux-gnu/libc-2.27.so
7fbfa33ad000-7fbfa33b1000 rw-p 00000000 00:00 0 
7fbfa33b1000-7fbfa33b4000 r-xp 00000000 08:01 1185958                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fbfa33b4000-7fbfa35b3000 ---p 00003000 08:01 1185958                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fbfa35b3000-7fbfa35b4000 r--p 00002000 08:01 1185958                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fbfa35b4000-7fbfa35b5000 rw-p 00003000 08:01 1185958                    /lib/x86_64-linux-gnu/libdl-2.27.so
7fbfa35b5000-7fbfa35da000 r-xp 00000000 08:01 1186093                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fbfa35da000-7fbfa37da000 ---p 00025000 08:01 1186093                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fbfa37da000-7fbfa37de000 r--p 00025000 08:01 1186093                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fbfa37de000-7fbfa37df000 rw-p 00029000 08:01 1186093                    /lib/x86_64-linux-gnu/libtinfo.so.5.9
7fbfa37df000-7fbfa3806000 r-xp 00000000 08:01 1185907                    /lib/x86_64-linux-gnu/ld-2.27.so
7fbfa39ec000-7fbfa39f1000 rw-p 00000000 00:00 0 
7fbfa39ff000-7fbfa3a06000 r--s 00000000 08:01 1053205                    /usr/lib/x86_64-linux-gnu/gconv/gconv-modules.cache
7fbfa3a06000-7fbfa3a07000 r--p 00027000 08:01 1185907                    /lib/x86_64-linux-gnu/ld-2.27.so
7fbfa3a07000-7fbfa3a08000 rw-p 00028000 08:01 1185907                    /lib/x86_64-linux-gnu/ld-2.27.so
7fbfa3a08000-7fbfa3a09000 rw-p 00000000 00:00 0 
7ffdd8ca7000-7ffdd8cc8000 rw-p 00000000 00:00 0                          [stack]
7ffdd8d8c000-7ffdd8d8f000 r--p 00000000 00:00 0                          [vvar]
7ffdd8d8f000-7ffdd8d90000 r-xp 00000000 00:00 0                          [vdso]
ffffffffff600000-ffffffffff601000 r-xp 00000000 00:00 0                  [vsyscall]
```

* Heap - 558197d89000-558197f00000
* Stack - 7ffdd8ca7000-7ffdd8cc8000
* MMS - 7fbfa1c37000-7fbfa1c42000

---

## TCP. UPD. Network

At first, it was as difficult as article about Memory Management. But watching it a couple of times made me understand the topic. Though I still can't write my own requests, it was a good practice to try out some of them. However I fill there is a lot to learn about in this field, and I already want to use it in practice.

![khan](task_networks/khan.png)

![networking](task_networks/networking.png)

## HTTP & HTTPS

### Practice requests

```
* curl -i https://api.github.com/orgs/kottans/repos

* curl -i -u 'jyuart' "https://api.github.com/repos/jyuart/kottans-backend/issues" -d '{"title": "HTTP-Practice", "body": "This issue is created with GitHub API"}'
```

### Answers

> Name at least three possible negative consequences of not using https.

1. Users' info can be stolen (logins, passwords, financial data)
2. Personal data sent to users can be intercepted 
3. Users may deal with changed site
4. There is no neat green lock in the address bar of the browser

> Explain the main idea behind public key cryptography in few sentences

There are two keys: public and private. The first one is used for encrypting messages and available for everyone. The second one is kept by its owner and used for decrypting messages. So, anyone can encrypt their messages, but only the owner of the keys can decrypt and read it.

> Implementaion functionality for the pet clinic application:

* add new pet - **POST** (pets/new; body: {"Name": "pet_name", "Age": age, "Breed": "pets_breed", "Owner's Name": "owner_name", "Medical History": "med_history"}, response = 201 Created)

* search pet by name - **GET** (provide pet's name using query '?name=pets_name', response = 200 OK)

* change name of an existing pet - **PUT** (/pets/pets_name; body: {"Name": "new_pet_name"}, response = 200 OK)

* add new info about pet's health - **PUT** (/pets/pets_name; body: {"Medical History": "new_health_info"}, response = 200 OK)

* assign a pet to a particular doctor in the clinic - **PUT** (/pets/pets_name; body: {"Doctor": "doctor"}, response = 200 OK)

* register an appointment for a pet - **POST** (/appointments/new; body: {"Name": "pet_name", "Doctor": "doctor" [or assigned doctor if any], "Date": date, "Time": time})

I'll use **POST** to add new info to the site (new pet or new appointment). **PUT** will be used to update or add new pet's info to the existing page (including assigned doctor). **GET** is for searching for particular pet.

