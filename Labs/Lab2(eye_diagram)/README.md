<img width="1615" height="536" alt="image" src="https://github.com/user-attachments/assets/40208e49-83cf-43b4-8cbc-c125ef11eea8" /><img width="1456" height="561" alt="image" src="https://github.com/user-attachments/assets/84fef636-e33c-4088-8789-2427769d7949" />

Pseudo Random Bit Sequence for a code of 4 bits : 

The 4 D-flip_flop are 4 bit shift register and the first xor is used to make the pseudo random operation , the secont is for intialization so it won't get stuck at 0000

Output bits at some periodic nodes:

<img width="1650" height="609" alt="image" src="https://github.com/user-attachments/assets/4fe78db4-3b60-4197-be02-d1cc832a4de6" />


Autocorrelation occurs every 15 UI, which means that during each 15 UI interval the bit sequence is random but contains the same number of zeros and ones and the same sequence as the one after,EX:111110000 first 15UI then the second 15UI is 111110000. Therefore, it is correlated at every 2^number of bits×UI period:

<img width="1917" height="661" alt="image" src="https://github.com/user-attachments/assets/1a6fc049-6376-4555-931f-158bb094ad06" />

Equation used:

<img width="551" height="51" alt="image" src="https://github.com/user-attachments/assets/ef6059ef-4d01-49be-b48c-498b6ac4db19" />

sequence repetation :

<img width="1660" height="673" alt="image" src="https://github.com/user-attachments/assets/433dd8d8-4fe3-431e-abb9-9a7283f422d1" />

PART-2:
testing 6-inch of FR4:

<img width="1615" height="536" alt="image" src="https://github.com/user-attachments/assets/c755aa7d-c485-4951-a68c-be893f0297d8" />

1-inch of FR4:


Eye diagram of unterminated in TX side :

<img width="1349" height="568" alt="image" src="https://github.com/user-attachments/assets/54b4feaf-68f4-4e43-aabc-901bfcea5a14" />m
<img width="788" height="683" alt="image" src="https://github.com/user-attachments/assets/cd7efc73-93a5-42a6-b9ba-e93cd4d0387f" />


in blue that's losses due to reflection losses which causes verticale eye collapse 

in orange that's frequency dependent losses

in white that's cross talk losses ==> near and far end

we see in the follwing graph the diffrential output with time jitter than the input

<img width="1600" height="685" alt="image" src="https://github.com/user-attachments/assets/5c0d865e-6b9f-4ff5-a777-2b80e33df8e9" />


WITH INPUT TERMINATION :

we expect less swing as the 50 ohm cause voltage drop so it won't be as large swing as the one unterminated but expect less reflection.

<img width="1905" height="613" alt="image" src="https://github.com/user-attachments/assets/4d9cb7e3-a04e-402d-864f-03d65271082c" />

Eye diagram :

<img width="1596" height="688" alt="image" src="https://github.com/user-attachments/assets/041726d7-fda0-4e3c-ad51-87b00a3990f2" />

verticall collapse is less wider eye open less reflection:

