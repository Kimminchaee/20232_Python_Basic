#양의 정수를 입력받아 그 수의 팩토리얼을 계산하는 문제

```py
num = int(input("양의 정수를 입력하세요: "))
factorial = 1
for i in range(1, num + 1):
    factorial *= i
print(f"{num}의 팩토리얼은 {factorial}입니다.")
```
