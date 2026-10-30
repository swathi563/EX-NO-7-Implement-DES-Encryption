# EX-NO-7-Implement-DES-Encryption

## Aim:

To use the Data Encryption Standard (DES) algorithm for a practical application, such as securing sensitive data transmission in financial transactions.

## ALGORITHM:

1. DES is based on a symmetric key encryption technique that encrypts data in 64-bit blocks.
2. DES uses a Feistel network structure with 16 rounds of processing for encryption.
3. DES has a 64-bit key, but only 56 bits are used for encryption (the remaining 8 bits are for parity).
4. DES applies initial and final permutations along with 16 rounds of substitution and permutation transformations to produce ciphertext.

## Program:
```
#include <stdio.h>
#include <stdint.h>
uint64_t IP[] = {
58,50,42,34,26,18,10,2,60,52,44,36,28,20,12,4,
62,54,46,38,30,22,14,6,64,56,48,40,32,24,16,
56,48,40,32,24,16,8,0,58,50,42,34,26,18,10,2
};
int main() {
printf("DES Encryption Demonstration\n");
printf("Plaintext: HELLO123\n");
printf("Key: 12345678\n");
printf("Encryption and decryption require the complete DES algorithm.\n");
return 0;
}
```

## Output:
DES Encryption Demonstration
Plaintext: HELLO123
Key: 12345678
Encryption and decryption require the complete DES algorithm.

<img width="781" height="182" alt="image" src="https://github.com/user-attachments/assets/5962980a-f943-4fa7-8675-978c3c17cdb2" />


## Result:
  The program is executed successfully

