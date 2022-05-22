# 오늘의 학습 ✏️

1. readLine 함수를 이용하여 받은 값을 무한 출력하는 코드를 작성한다.
```swift
while true {
    print("입력해주세요 : ",terminator: "")
    let input: String = readLine()!
    if input == "x" {
        print("종료합니다")
        break;
    }
    print("입력값은 \(input)입니다")
}
```

```swift
var input2: String = ""
while input2 != "x" {
    print("입력해주세요 : ",terminator: "")
    input2 = readLine()!
    print("입력값은 \(input2)입니다")
}
print("종료합니다")
```

두가지 방법으로 작성해 보았다.
첫번째 코드에서는 while문에 조건을 주지 않고 반복문 내부에서 반복 종료 조건을 작성하였고, 두번째 코드에서는 반복문 자체에 조건을 주어 조건이 충족하면 탈출하도록 작성하였다.
