#### cookie


코드를 살펴보면
```python
users = {
    'guest': 'guest',
    'admin': FLAG
}
```

두 가지 정보가 있다.일단 admin으로 접속할 경우 우리가 원하는 FLAG 값을 가져올 수 있다.
일단 게스트로 로그인을 해보면

<img width="554" alt="스크린샷 2023-02-16 오전 4 09 38" src="https://user-images.githubusercontent.com/103236108/219129616-043fbad5-dfec-4d78-911a-c8eda0c21b69.png">


다음과 같은 문구가 나온다.
그 후에 쿠키 값을 admin으로 변경해주면 된다.

<img width="630" alt="스크린샷 2023-02-16 오전 4 10 41" src="https://user-images.githubusercontent.com/103236108/219129703-3a7ee85d-e358-4236-aee1-d5c2ff852205.png">


변경한 후에 정답이 나온다.


<img width="422" alt="스크린샷 2023-02-16 오전 4 16 35" src="https://user-images.githubusercontent.com/103236108/219130096-837d3387-ba13-4bd0-ad64-f17d15fc1056.png">
