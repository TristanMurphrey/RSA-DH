This program was created for and at the PKWare hackathon on 04/01/2017.

The program was implemented by Tristan Murphrey, Catelyn Scholl, Adam Dunn, and Evan Macintosh, who took first place in the competition.

This program implements RSA and DH encryption into a user interface. Program shows all calculated intermediary values necessary for both forms of encryption, and how to calculate them. Program fails for large values of n, where the int data type is unable to handle the large values present in the RSA decryption method. The idea behind the program is that it combines the security of (asymmetrical) RSA encryption with (symmetrical) DH encryption, which has new keys generated for each user session. If more time were available, BigInteger would have been implemented, as well as a stronger powermod method in order to handle larger prime values.
