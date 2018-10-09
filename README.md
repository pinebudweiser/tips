# tips

- RTC(RealTimeClock) Alarm : 바이오스 설정을 통해 지정된 시간에 컴퓨터의 전원을 킬 수 있다. 하지만 윈도우에서 `빠른부팅`이 꺼져있어야 함!
- WshShell : https://www.vbsedit.com/html/6f28899c-d653-4555-8a59-49640b0e32ea.asp, 윈도우 창을 숨길 수 있다.
- 작업 스케쥴러를 통해 배치파일을 항상 관리자 권한으로 실행 할 수 있음! 단, VBS 스크립트는 관리자 권한으로 실행 되지 않는다.
- 작업 스케쥴러를 등록하는 가장 쉬운 방법 : xml 파일을 만든 후, sctasks 명령어 옵션중 xml을 input 하면 됨!<br>Author가 일치하지 않으면 생성이 안되니 그 부분은 지워주면 됩니당 -ㅅ-
- HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies -> Associations -> LowRiskFileTypes -> .exe;.vbs
