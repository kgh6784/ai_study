

갑자기 docker toolbox 실행 시 실행이 되지 않고 hyper-v unavailable 하는 문제가 발생했다. 구글링에서 나온 windows 기능 켜기/끄기에서는 hyper-v가 나는 없었다.. 그래서 포맷하고 다시 했는데 그럴 필요가 없었다.

### bcdedit /set hypervisorlaunchtype off

이 명령어를 cmd에 관리자 권한으로 들어가서 치고 재부팅해주면 해결된다!
