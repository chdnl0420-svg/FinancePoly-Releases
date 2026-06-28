# FinancePoly Releases

FinancePoly Windows 트레이 포트폴리오 앱의 배포 전용 저장소입니다.

## 다운로드

최신 설치 파일은 아래 릴리즈에서 받을 수 있습니다.

[최신 릴리즈 다운로드](https://github.com/chdnl0420-svg/FinancePoly-Releases/releases/latest)

이 저장소에는 배포용 설치 파일만 올립니다.
소스 코드와 개발 이력은 포함하지 않습니다.
배포 정책상 사용자가 받을 수 있는 릴리즈는 항상 최신 설치 파일 1개만 유지합니다.

## 설치와 업데이트

설치 파일 이름은 `FinancePoly-Setup-버전.exe` 형식입니다.
앱 안의 업데이트 기능은 5분마다 이 저장소의 최신 릴리즈를 확인합니다.
새 버전이 있으면 사용자에게 알리고, 다운로드, 설치, 재시작을 한 번에 진행할 수 있습니다.

수동으로 다시 설치할 때는 실행 중인 FinancePoly를 먼저 종료한 뒤 설치 파일을 실행하는 것을 권장합니다.

## 사용자 데이터 보존

재설치하거나 업데이트해도 사용자가 추가한 데이터는 유지됩니다.
설치 프로그램은 앱 실행 파일과 바로가기만 교체합니다.

앱 설치 위치:

```text
%LOCALAPPDATA%\Programs\FinancePoly
```

사용자 데이터 위치:

```text
%LOCALAPPDATA%\FinancePoly\financepoly.db
%APPDATA%\FinancePoly\settings.json
```

거래 기록, 관심종목, 신호 조건, AI 신호 기록, 앱 설정은 위 사용자 데이터 위치에 저장됩니다.
앱을 완전히 초기화하려는 경우가 아니라면 이 폴더와 파일을 삭제하지 마세요.

## 주의

FinancePoly는 포트폴리오 기록과 분석 보조용 앱입니다.
실제 주식 매수, 매도 주문은 실행하지 않습니다.