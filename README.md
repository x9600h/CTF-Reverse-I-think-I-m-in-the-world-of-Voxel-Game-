# CTF-Reverse task writeup
CTF Reverse task writeup (I think I'm in the world of Voxel Game)
### Let's try to open the executable file
>You can find it in this repository

As you can see, the Godot engine is used here

![изображение](https://github.com/user-attachments/assets/59696a30-e9c2-44b9-bf0e-40a55b398e0e)

Let's use the utility to access GDScripts [(Link)](https://github.com/bruvzg/gdsdecomp)

### Let's start going through the files

![изображение](https://github.com/user-attachments/assets/a68f14e8-e83c-4e02-ae98-6586eb1a86fd)

**I found something interesting. A GD file with an array of bytes inside. Let's check what is it**

![изображение](https://github.com/user-attachments/assets/8cbb6eed-950f-45a5-ae9f-550cbf7ac310)

Let's write a python script thats decode this to ascii. And as we can see: 

![изображение](https://github.com/user-attachments/assets/25d8153d-76de-481f-9575-d9dd5f5e5cea)

**This is our flag: CODEBY{fl@g_1n_thE_g0dOt_G@me}**







