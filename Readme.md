# Adium rot13 plugin

Adium is an osx instant messenger app. Rot13 is a very simple cypher used to encrypt and decrypt plaintext data. 

###Rot13 

Rot13 (rotation 13) is a very simple cypher. All it does is "rotate" every letter 13 times forwards in the alphabet. Here is a very simple chart 

|Input  letter |a|b|c|d|e|f|g|h|i|j|k|l|m|n|o|p|q|r|s|t|u|v|w|x|y|z|
|--------------|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Output letter |n|o|p|q|r|s|t|u|v|w|q|y|z|a|b|c|d|e|f|g|h|i|j|k|l|m|

13 is the magic number becuase it's exactly 1/2 of the alphabet, meaning that the same algorithm is used for encrypting and decrypting. If you used Rot2, you would need two algorithms, one to encrypt (shift forward two letters) and one to decrypt (shift backwards 2 letters or shift forward 24 letters). With Rot 13, you encrypt by moving forward 13 letters and also decrypt by moving forward 13 letters. 

###To install 

First you need [Adium][Adium] installed. Once that's done, download this and simple double click it. Adium will take care of the rest. 

[Adium] : https://adium.im

###To use

Go ahead and just type %_rot{some text} in any chat and watch your text become "encrypted". 


###Note

Don't use this for any sort of actual encryption. This entire plugin was a 20 minute running joke with my coworker. Please never use this cypher for sensitive data. 
