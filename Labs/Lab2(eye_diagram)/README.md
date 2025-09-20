<img width="1456" height="561" alt="image" src="https://github.com/user-attachments/assets/84fef636-e33c-4088-8789-2427769d7949" />

Pseudo Random Bit Sequence for a code of 4 bits : 

The 4 D-flip_flop are 4 bit shift register and the first xor is used to make the pseudo random operation , the secont is for intialization so it won't get stuck at 0000

Output bits at some periodic nodes:

<img width="1650" height="609" alt="image" src="https://github.com/user-attachments/assets/4fe78db4-3b60-4197-be02-d1cc832a4de6" />


Autocorrelation occurs every 15 UI, which means that during each 15 UI interval the bit sequence is random but contains the same number of zeros and ones. Therefore, it is correlated at every 2^number of bits×UI period:

<img width="1917" height="661" alt="image" src="https://github.com/user-attachments/assets/1a6fc049-6376-4555-931f-158bb094ad06" />
