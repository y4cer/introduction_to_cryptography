# Public key cryptography + concept of secure messaging

В целом, задача не спеша поговорить про то теорию информации, а потом уже 
практикой на питончике позаниматься.

- Paper by Merkle, Diffie and Hellman, RSA paper
- Perfect secrecy and entropy by Claude Shannon, OTPs
- A bit of information theory
    http://workouts.spb.ctf.su:11031/ — Basic Workout, узнавать представления данных в baseXX
    http://workouts.spb.ctf.su:11032/ — Comp Workout, сравнивать два signed int в виде байтов в памяти
    http://workouts.spb.ctf.su:11033/ — Hash Workout, узнавать хеши по длине
    http://workouts.spb.ctf.su:11034/ — Text Ciph Workout, узнавать буквенные шифры
    http://workouts.spb.ctf.su:11035/ — Bin Ciph Workout, узнавать бинарные шифры
    http://workouts.spb.ctf.su:11036/ — Trash Workout, отличать рандомный треш от нерандомного
    http://workouts.spb.ctf.su:11037/ — Format Workout, узнавать форматы файлов
- Formal definition of public key cryptography
- Concept of trapdoor function, concept of underlying mathematical problem (e.g. RSA, DH, SVP ...)
- Classification of cryptographic primitives by type (classical, quantum, post-quantum)
- Example of establishing secure communication (DH) then using AES -> lecture 7
- Example of signing messages with HMAC
    - Example of blockchain as a reference to signing and asymmetric key cryptography in general 
- Data representation in Python. Since we will work much in Python, we want to 
know how to represent some things in Python, i.e. bytes, strings, and others.

# HW
Прогнать через базу38, 52, 64 и через энкодинг сообщение какое-нибудь и сказать раздекодить