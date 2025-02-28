# Basic ciphers for Codebusters
### By Sam Rohrbach

## Aristocrat
Information from [the Aristocrat Wikipedia page](https://en.wikipedia.org/wiki/Aristocrat_Cipher). 

- K1 cipher: 
    - This type uses a keyed plaintext alphabet for encryption. The plaintext alphabet is rearranged according to a keyword, and each letter is substituted according to this rearranged alphabet. 
    - Example: This cipher encodes `CIPHER` into plaintext, with normally-shifted ciphertext. 
        | Plaintext | `A B C I P H E R D F G J K L M N O Q S T U V W X Y Z` |
        | --------- | ----------------------------------------------------- | 
        | Ciphertext | `V W X Y Z A B C D E F G H I J K L M N O P Q R S T U` |

- K2 Cipher: 
    - In this type, the ciphertext is generated using a keyed ciphertext alphabet. The ciphertext alphabet is rearranged according to a keyword, which then replaces the plaintext letters.
    - Example: This cipher has normal plaintext, but encodes `CIPHER` into ciphertext. 
        | Plaintext | `A B C D E F G H I J K L M N O P Q R S T U V W X Y Z` |
        | --------- | ----------------------------------------------------- | 
        | Ciphertext | `V W X Y Z C I P H E R A B D F G J K L M N O Q S T U` |

- K3 Cipher: 
    - This variation uses both a keyed plaintext and a keyed ciphertext alphabet, but the same keyword is used for both.
    - Example: This cipher encodes `CIPHER` in both plaintext and ciphertext. 
        | Plaintext | `A B C I P H E R D F G J K L M N O Q S T U V W X Y Z` |
        | --------- | ----------------------------------------------------- | 
        | Ciphertext | `V W X Y Z C I P H E R A B D F G J K L M N O Q S T U` |

- K4 Cipher: 
    - Similar to the K3 Cipher, but different keywords are used for the plaintext and ciphertext alphabets. 
    - Example: This cipher encodes `CIPHER` in plaintext, but `ARCHBTW` in ciphertext. 
        | Plaintext | `A B C I P H E R D F G J K L M N O Q S T U V W X Y Z` |
        | --------- | ----------------------------------------------------- | 
        | Ciphertext | `U V X Y Z A R C H B T W D E F G I J K L M N O P Q S` |


## Patristocrat
Information from [Cryptocrack](https://sites.google.com/site/cryptocrackprogram/user-guide/cipher-types/substitution/aristocratpatristocrat). 
Patristocrat is like Aristocrat, but word divisions are not retained. 
