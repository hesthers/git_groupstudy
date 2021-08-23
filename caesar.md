#Caesar Cipher

#definition:

- 카이사르가 이전에 사용했던 암호 해독법

- a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet

- 가장 단순하고 널리 알려진 해독 기법

## Example

- 알파벳 순서를 3씩 이동한다고 가정할 때,

일반적인 알파벳 순서는 A - B - C - D - E - F - ... - W - X - Y - Z이다.

그러나, Caesar cipher 방식으로 암호화하게 되면 일반적인 알파벳 순서가 3씩 뒤로 이동해X - Y - Z - A - B - C - D - E - F - G - ... - T - U - V - W가 된다.

- 예시문장

1. A DOG IS JUMPING ON THE GROUND WITH ITS TOYS. (해독 메세지)

2. X ALD FP GRJMFKD LK QEB DOLRKA TFQE FQP QLVP. (전달 메세지)

- 다시 원래의 전달  메세지로 돌아가고 싶은 경우 (암호화) 해독하기 위해 이동했던 숫자만큼 다시 알파벳 순서로 돌아오면 된다. (예. A -> X -> A)

## 카이사르 암호 사용 시 고려해야 할 사항

1. 상대방이 단순한 대체 암호의 종류가 사용되었다고 알고있거나 추측할 수 있는 경우

2. 상대방이 메세지에 카이사르 암호 코드가 사용되었음을 알고는 있으나해 알파벳을 얼마만큼 이동해서 메세지를 작성했는지 알 수 없는 경우

이 두 가지는 주의해야한다.

첫 번째 경우, 상대방이 단순 치환암호 등의 방식으로 사용되었다고 추측하는 경우 규칙성(문자의 활용 빈도수)을 통해 쉽게 암호를 해독할 수 있기 때문이다.

두 번째 경우, 영어 알파벳의 경우 최대25번까지 알파벳을 이동시켜서 암호를 해독할 수 있기 때문이다.

