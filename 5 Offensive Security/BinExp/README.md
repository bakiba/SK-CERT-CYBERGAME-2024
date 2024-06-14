# ReadWrite

> Points: 9

Service: 80.211.209.10:7123 (Ubuntu 22.04)

Binary: https://drive.google.com/file/d/1cyXvN9Nq0pGm7QaVUZo05V0TgnKSAIiu/view?usp=sharing

!!! This challenge is a pure binary exploitation. You are not allowed to use bruteforce, fuzzing or any other techniques which can harm the infrastructure that is serving vulnerable services. Use only final exploits that are tested and working with provided binary (ports may differ with production) !!!

This application is used to read and write data to files. There is a certain limitation what files can be accessed. You goal is to read file called "secret.txt" located in “/”, which should not be possible.