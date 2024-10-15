for freelance work? do reach, [email](mailto:bikrant.acc.edu@icloud.com) :)







<div align="center">
<br><br>
<pre>
    💼 CTF • HTB • Full stack Developer
    💻 Creative Coding • Machine Learning
    📖 Software architecture • Competative Programming
    🎮 Music • Games • Anime • Code • Art
     Muffin  • anddddd SAMOSEEEEEEEEE 
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



# <a href="https://github.com/vikrant-vikram/prengen">  *1. Prengen* </a>

<div align="center">

    
<pre>

With the advent of digitalization and burgeoning demand to disburse the top-notch services to the whooping 
    numberof users which is flourishing day-by-day – arises the desideratum to propound an efficacious and 
    duly method whichcan assess the massive amount of data or information being generated by users explicitly 
    or implicitly while theybrowse, click, comment, search, etc and as an outcome facilitates one to extrapolate 
    the next course of action a usermight take. As an increasing number of users access information on the web, 
    there lies a great opportunity to studyfrom the server logs to learn about the users’ probable actions in 
    the future. Beneficiaries of such state-of-the-arttechnology – to exemplify such as Amazon, Flipkart have 
    garnered a lot of gain by practising the latest trend to useRecommendation systems, that try to capture the 
    behaviour of the customers while they browse and suggest theofferings accordingly. The proposed recommendation 
    systems work on navigation data of the users that are stored inweb servers of the websites and search engines; 
    accordingly, it can be used for intra- website and inter-web siterecommendations. Inclusively, the inundation 
    of the users can be best served by deploying appropriate methodsdiscussed, that can herald the upcoming action 
    of the user and provide edge especially to the emerging e-commerceand digital marketing platforms to display the 
    right data at the right time .

<a href="https://www.researchgate.net/publication/352508231_Prengen_A_Prediction_System_for_Web_Requests"> Read More</a>

</pre>

</div>




# <a href="https://github.com/vikrant-vikram/DES?tab=readme-ov-file">  *2. Data Encryption Standard* </a>

<a href="https://en.wikipedia.org/wiki/DES_supplementary_material">DES supplementary material</a>


<div align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/DES-main-network.png/500px-DES-main-network.png" height="500" />

<pre>

DES (Data Encryption Standard) is a symmetric-key block cipher algorithm developed in the 1970s by IBM and later adopted by the U.S. government as an official standard. Here are key details about DES:
Block Size and Key Length: DES operates on 64-bit blocks of data and uses a 56-bit key (technically 64 bits, but 8 bits are used for parity checking and discarded).
Feistel Network: DES uses a 16-round Feistel network structure, where the data block is split into two 32-bit halves that are processed alternately.
S-boxes: DES employs eight substitution boxes (S-boxes) that perform the core of the cryptographic transformation, introducing non-linearity to the cipher.
Key Schedule: The algorithm generates 16 48-bit subkeys from the original 56-bit key, one for each round of the Feistel network.
Initial and Final Permutations: DES applies initial and final permutations to the data block, which don't contribute to the cryptographic strength but were included for ease of implementation in hardware.
Security: While considered secure when first introduced, DES is now vulnerable to brute-force attacks due to its short key length. It has been largely replaced by more secure algorithms like AES.







Example for Avalanche Property (as you can see there is a difference in only one bit of the plaintext)
Plaintext: 0000000000000000       Key: 22234512987ABB23    Ciphertext: 4789FD476E82A5F1

Plaintext: 0000000000000001       Key: 22234512987ABB23    Ciphertext: 0A4ED5C15A63FEA3


Then in this case you should observe the changes in the following number of bits in each round as described below:
Rounds:                 1    2    3     4    5    6    7    8    9    10    11    12    13    14    15    16
Bit differences:     1   6   20   29  30  33  32  29  32  39    33    28     30    31    30    29
</pre>
</div>

    


# <a href="https://github.com/vikrant-vikram/Cryptography/blob/main/Assignment/trivium_cipher.py">  *3. Trivium Cipher* </a>

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





# <a href="https://github.com/vikrant-vikram/mrGrapher">  *4. mrGrapher* </a>

<div align="center">

    
<pre>

In this day-to-day modernizing era where data security is becoming a major concern, data security refers to 
    securing information in potentially hostile environments. Several methods or ways have been proposed in 
    the area of concern, i.e., securing data and assuring its safe and sound transmission from the sender to 
    the receiver. The specialized method focused here is encryption and decryption. Decryption is the process 
    of de-transforming encrypted information so that it gets intelligible. Encryption translates actual data 
    into another form, or code so that only people with access to a secret key (formally called a decryption key)
    or password can decrypt it. Encryption is the process of transforming information, so it is unintelligible
    to anyone but the intended recipient. This method emphasizes the substitution of characters with RGB color 
    format later in the form image pixel, because of which it becomes unable for the hacker to find out where 
    the data is hidden, thus, before cracking the data they need to first find where the data is. It becomes 
    useful in various fields such as organizational level, national level to maintain the integrity of data 
    and can be used at a personal level too to avail the security benefits using the created platform.

<a href="https://www.researchgate.net/publication/346344540_Encryption_and_Decryption_Unraveling_the_Intricacies_of_Data_Reliability_Attributed_by_Incorporating_the_Usage_of_Color_Code_and_Pixels"> Read More</a>

</pre>

</div>




# <a href="https://github.com/vikrant-vikram/">  *..and Many More.* </a>











