
구글 서버 콘솔 들어가서
https://codelabs.developers.google.com/codelabs/cloud-natural-language-python3#1
여기에서 1~3 으로 서버 세팅 완료하고

8번으로 Google Natural API 작동 하는거 확인

1. 가상 머신을 중지
2. 클라우드 콘솔에서 GCE VM 인스턴스로 이동
3. 머신을 편집하려면 머신 위에서 "수정"으로 이동
    
![Untitled](https://github.com/veneer-KISIA/docs/assets/88125431/fa870d8e-f240-4143-9749-dabaac66fdda)

    
4. indentity and API access에서 액세스 범위에서 모든 cloud api에 대한 전체 액세스 허용을 눌른다 (기본으로는 기본 엑세스 허용으로 되어있음)
    
![Untitled (1)](https://github.com/veneer-KISIA/docs/assets/88125431/be931679-96c5-4577-a672-14cd08d9556a)

    
5. 머신을 다시 시작하고 API 호출을 다시 실행하세요.

[참고 stackoverflow](https://stackoverflow.com/questions/70099753/access-token-scope-insufficient-403-request-had-insufficient-authentication-scop)
