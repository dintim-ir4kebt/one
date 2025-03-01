한 코드베이스로 PC와 모바일 앱을 동시에 빌드하기

빌드를 돌리면 첫 화면이 이렇게 뜹니다.

![poster](./img2.png)


SQL 쪽에서 빌드 오류가 나면 참조를 지우고 다시 빌드하면 대개 해결됩니다.

![poster](./img1.png)


라이브러리 참조에서 오류가 날 때는 버전 표기를 손봐야 합니다.

`hybrid-native-package` 의 버전은 보통 `3.5.*-*` 같은 와일드카드로 두는데, 특정 패치로 고정해 두면 참조가 어긋나는 경우가 적습니다. 아래는 특정 버전으로 잠근 예시입니다.

```
"hybrid-native-package" Version="3.5.17"
```

![poster](./img3.png)

![poster](./img4.png)



라이선스: MIT.