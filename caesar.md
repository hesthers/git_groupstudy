#Caesar Cipheir info

##definition:

- one of the simplest and most widely known encryption techniques

- a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet

- the Caesar cipher is easily broken and in modern practice offers essentially no communications security

## Example

- Assuming the position of alphabet is right-shifted of 3,

the general order of the alphabet is A - B - C - D - E - F - ... - W - X - Y - Z.

However, when Caesar cipher is decoded, the order is X - Y - Z - A - B - C - D - E - F - G - ... - T - U - V - W.

- example sentence

1. A DOG IS JUMPING ON THE GROUND WITH ITS TOYS. (해독 메세지)

2. X ALD FP GRJMFKD LK QEB DOLRKA TFQE FQP QLVP. (전달 메세지)

- In reverse, deciphering is done with a left shift of 3.

## 카이사르 암호 사용 시 고려해야 할 사항

1. an attacker knows (or guesses) that some sort of simple substitution cipher has been used, but not specifically that it is a Caesar scheme;
the cipher can be broken using the same techniques as for a general simple substitution cipher.

2. an attacker knows that a Caesar cipher is in use, but does not know the shift value.
Since there are only a limited number of possible shifts (25 in English), they can each be tested in turn in a brute force attack.



