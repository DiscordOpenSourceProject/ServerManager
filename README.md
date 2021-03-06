# ServerManager 
### 오픈소스 디스코드 관리 봇
이 프로젝트는 디스코드 서버에서 관리를 효율적으로 하기 위해 도와줄 수 있는 봇입니다.  
오픈소스 프로젝트이며 누구나 자유롭게 이용이 가능하되, 배포 및 수정하여 배포할 때에는 **출처를 표기**해주세요.  
출처 표기법 : **해당 소스코드는 디스코드 오픈소스 프로젝트 팀에서 제공 한 오픈소스를 기반으로 제작되었습니다.**  

**본 프로젝트는 Discord.js V14 버전을 이용하여 제작되었습니다**  
**릴리즈 이외의 소스코드는 정상적으로 작동하지 않을 수 있습니다**  

## 사용법
### config.json 파일 수정
봇을 사용하기 전 봇의 토큰값과 클라이언트 아이디 및 부가 설정을 위해 config.json 파일을 수정해주어야 합니다.  
config.json 파일은 **최상위 폴더에 속하며** 파일을 열면 아래와 같은 구성으로 되어있으며 아래의 설명에 따라 수정해주세요.  
```json
{
      "Token":"토큰 값을 입력하세요.",
      "TestMode":"테스트 모드를 켤 지 설정하세요. (true Or false, 테스트 모드 활성화 : 빗금 명령어를 테스트 길드에만 등록",
      "TestGuild":"테스트 모드 활성화에서 빗금 명령어를 등록 할 서버 아이디를 입력하세요.",
      "ClientId":"봇의 클라이언트 아이디를 입력하세요."
}
```
위와 같이 수정하고 봇을 실행시키면 아래와 같이 출력이 되며 정상적으로 시작됩니다.  
```console
정보 : 빗금 명령어 등록에 필요한 명령어를 가져오는 중입니다.
정보 : 빗금 명령어 등록을 완료하였습니다.
정보 : 봇에 로그인하였습니다.
```





