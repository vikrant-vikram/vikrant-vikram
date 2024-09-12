for freelance work? do reach, [email](mailto:bikrant.acc.edu@icloud.com) :)







<div align="center">
<br><br>
<pre>
    💼 CTF • HTB • Full stack Developer
    💻 System programming languages • Machine Learning
    📖 Software architecture • Competative Programming
    🎮 Music • Games • Anime • Code • Art
    🐾 Muffin 🐰 • anddddd SAMOSEEEEEEEEE 
</pre>
<br><br>
<img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM212MTVjYm10Z3o2MWlmdnZ0aTNrZHVqamkwNW9hMGVldm9jM29jMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5GS13A3jXN9xSQF6HL/giphy.gif" height="100" />
<br><br><br>
  
</div>




```txt
Python       5 hrs 34 mins   █████████████████████░░░░   80.10 %
Bash         28 mins         █▓░░░░░░░░░░░░░░░░░░░░░░░   07.08 %
C            14 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   03.76 %
Cryptography 10 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.61 %
JavaScript   6 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.66 %
```

<!--END_SECTION:waka-->

if you like what i do, maybe consider buying me a coffee/tea 🥺👉👈


🚧 **my todoist stats:**
<!-- TODO-IST:START -->
🏆  8,004 Karma Points           
🌸  Completed 0 tasks today           
✅  Created  673 problems so far    
⏳  Remaining things I will write down later
<!-- TODO-IST:END -->




<!--<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=vikrant-vikram&show_icons=true&theme=gotham" alt="vikrant-vikram" />-->




# <a href="https://github.com/vikrant-vikram/Cryptography/blob/main/Assignment/trivium_cipher.py">  *1. Trivium Cipher* </a>

<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Trivium_%28cipher%29.png/600px-Trivium_%28cipher%29.png" height="500" />

<pre>

Our cryptography methods are often block based which require memory storage and have a considerable gate footprint for their implementation.
For devices with limited storage space and processing requirements, the requirements of many block-based symmetric encryption methods cannot be feasibly implement.

We thus get light-weight cryptography method, and which have a lower processing requirement, and memory and gate footprint. With this, for symmetric key encryption,
we often replace block cipher with stream ciphers. For this we generate an almost infinitely long key stream based on a key value and an IV (initialisation vector).
The incoming bit stream is then EX-ORed with the key stream, and this is sent with the IV. On the other side, the key stream is recreated, and EX-OR with the cipher stream.
This created the original data.
Trivium is a Light Weight Stream Cipher and was created Christophe De Cannière and Bart Preneel, and has a low footprint for hardware.
It uses an 80-bit key, and generates up to 2⁶⁴ bits of output, with an 80-bit IV.
The Trivium cryptography method has 288 bit states and uses three registers (A, B and C), of 93, 84 and 111 bits. The method for each state is:

The key and IV are loaded up initially as:

(1,2,., 93) <- (K3,..., K80,0, ..., 0)
(94, 95,.,177) <- (IV1,..., IV80, 0,..., 0)
(178, 179, .., 288) <- (0,..., 0,1,1,1)
We initially run through four 288 bit shifts before we take an output (this is defined as the warm up phase). The following gives an example of the cipher:
 for 𝑖=1to𝑁
   do
    𝑡1 ← 𝑠66 + 𝑠93
    𝑡2 ← 𝑠162 + 𝑠177
    𝑡3 ← 𝑠243 + 𝑠288
    𝑧𝑖 ← 𝑡1 + 𝑡2 + 𝑡3
    𝑡1 ←𝑡1 +𝑠91 ⋅𝑠92 +𝑠171
     𝑡2 ←𝑡2 +𝑠175 ⋅𝑠176 +𝑠264
    𝑡3 ←𝑡3 +𝑠286 ⋅𝑠287 + 𝑠69
    (𝑠1,𝑠2,...,𝑠93) ← (𝑡3,𝑠1,...,𝑠92)
    (𝑠94,𝑠95,...,𝑠177) ← (𝑡1,𝑠94,...,𝑠176)
    (𝑠178,𝑠179,...,𝑠288) ← (𝑡2,𝑠178,...,𝑠287)

Trivium has low requirements in hardware.
</pre>
</div>






