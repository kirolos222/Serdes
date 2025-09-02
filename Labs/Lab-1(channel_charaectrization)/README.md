
this a method to charaectrize a channel but to get the needed S21 from diffrential equation we need to derive it , it was derived from this link https://www.signalintegrityjournal.com/articles/1832-a-guide-for-singleended-to-mixedmode-s-parameter-
conversions

<img width="1034" height="601" alt="image" src="https://github.com/user-attachments/assets/136a43be-914c-400e-b76a-32e10d1f7b68" />

channel S21 ==> to show the effect of losses like skin losses and dieletric losses :

remember that skin losses is direct proportional to sqrt(freq) and dieletric losses is direct proportional to freq 

<img width="987" height="630" alt="image" src="https://github.com/user-attachments/assets/a04c7aa9-5b28-4084-8eb2-61e576ef1fa3" />


why is the phase shift is a ramp signal for S21 ?? 

<img width="1541" height="759" alt="image" src="https://github.com/user-attachments/assets/f5550218-3d8c-454a-8174-d8595d508ed0" />

<img width="993" height="648" alt="image" src="https://github.com/user-attachments/assets/46630cf6-1b5f-4e0b-a580-8ef98db1db64" />

what will happen if we enter a diffrenetial pulse signal throght the channel :

well we expect many things i guess ==> :
1) first the output will of be delayed which is to be expected as the physical length of the channel determine time delay
2) the output will be atteunated due to losses like skin losse , dielectric losses , connector losses ,etc...
3) the output will not be as sharp as input signal (not squarre wave but a more smoth signal like a sinsoidal) because of ISI that accts as a LPF and filter higher harmonics that make the squarre wave.

<img width="993" height="684" alt="image" src="https://github.com/user-attachments/assets/01d6b7b7-7cff-4873-8b0f-dda259dddff7" />
