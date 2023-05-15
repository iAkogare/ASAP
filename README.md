ASAP
=====
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)에서 분기한 [Hekate×ASAP](https://github.com/Asadayot/hekate)을 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa's Switch All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.
- ASAP 에 기본 포함된 [Asanosphère](https://github.com/Asadayot/Asanosphere) & [Hekate×ASAP](https://github.com/Asadayot/hekate) 및 페이로드는 유기적인 관계로 이어져 있으며 기타 올인원과 혼합 사용시 이용하지 못하는 기능이 생기거나 치명적인 충돌이 일어날 수 있습니다, 혼합 사용을 피해주세요.
- 기본 포함 팩을 제외한 홈브류 및 페이로드는 위 내용과 관련이 없으니 자유로이 설치 및 사용하셔도 무방합니다.





새 버전 개선사항
=====
### ⬦ ASAP-0515 주요 개선점

| 대상  | 버전         | 커밋             | 변경사항                                      | 기 | 
| ----- | ---------- | -------------- | ----------------------------------------- | ------ | 
| [ASAP](https://github.com/Asadayot/ASAP) | 0515 | a60862c | [지그/로더] sx로더 지원 (boot.dat/boot.ini) 기본 추가, 사진 설명서 추가 |  | 
| [Asanosphère](https://github.com/Asadayot/Asanosphere) | 1.5.4 | 3cb54e2 | [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere/releases) 참고 | 시험판 | 
| [Hekate×ASAP](https://github.com/Asadayot/hekate) | 6.0.4 & 1.5.3 | 937ab53 | 오탈자 수정 |  | 
| Sigpatches | 0515 |  | 3cb54e2 & 937ab53 기반 시그패치 최신화 |  | 
| [ASAP-Updater](https://github.com/Asadayot/ASAP) | 2.21.7 | 012b89e | SXOS 동글 페이로드 링크 추가, [012b89e](https://github.com/HamletDuFromage/aio-switch-updater) 커밋, 변경로그 웹 확인 변경(시험판-기능불가) |  |
| [RetroArch](https://www.retroarch.com/) | 1.15.0 |  | 요청에 따른 선택설치 홈브류 추가 |  | 
| [Edizon](https://github.com/WerWolv/EdiZon) | 3.1.0 | dc14c3a | 요청에 따른 선택설치 원본 홈브류 추가 |  | 
| [emuiibo](https://github.com/Asadayot/emuiibo) | 1.0.0 | 97326a0 | 선택설치 시스모듈 추가 |  | 
| [ldn_mitm](https://github.com/Asadayot/ldn_mitm) | 1.15.0 | b98d2c6 | Atmosphere-libs 업데이트 |  | 
| [Tesla menu](https://github.com/Asadayot/Tesla-Menu) | 1.2.2 | 97b9677 | libtesla 업데이트 |  | 
| [MissionControl](https://github.com/Asadayot/MissionControl) | 0.9.2 | fe31665 | Atmosphere-libs, libnx 업데이트 |  | 
| [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) | 0.9.0 | 4bf7b23 | 글자 깨짐 수정 |  | 
| [Quick-NTP](https://github.com/Asadayot/QuickNTP) | 1.2.8 | 11b9897 | libtesla 업데이트 |  | 

기본 제공 / 변경 로그
=====
<details><summary>자세히 보기</summary>

### ⬦ CFW & 부트로더
- [Asanosphère](https://github.com/Asadayot/Asanosphere)
  - 버전 표기 변경 : `HOS VER│ASAP1.5.4-0515│S/E`
  - exosphere 경로 변경 : `sd:/atmosphere/config`
  - config 폴더의 .ini 파일 한글 부연 설명 추가(주석)
  - 시리얼 변조 코드 변경 : `XAW` → `XAJ`(유럽/일본)
- [Hekate×ASAP](https://github.com/Asadayot/hekate)
  - 한글화
  - 덤프 경로 변경.
  - 스크린샷 : `sd:/backup/screenshots`, 기타 : `sd:/backup`
  - ASAP 이외의 CFW에서 이용제한(충돌 및 일부 서비스 이용 불가). 
- Boot.dat & Boot.ini
  - SX OS / 모드칩 전용 필수 로더 및 설정

### ⬦ 홈브류 메뉴/로더
- [nx-hbmenu](https://github.com/Asadayot/nx-hbmenu) & [nx-hbloader](https://github.com/Asadayot/nx-hbloader)
  - 한글화.
  - 고정 위치 변경 : `sd:/atmosphere/hb` 

### ⬦ 페이로드
- [fusee.bin](https://github.com/Asadayot/Asanosphere)
- [TegraExplorer](https://github.com/Asadayot/TegraExplorer) : 4.0.1
  - TegraExplorer 폴더 삭제, Exit/Scripts 수정.
  - 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`
  - HOS 덤프 경로 변경: `sd:/Firmware`
  - 기타 덤프 경로 변경: `sd:/backup`
  - ASAP 이외의 CFW에서 일부 기능 이용제한.
- [Lockpick_RCM](https://github.com/Asadayot/Lockpick_RCM) : 1.9.10
  - ASAP 설치 및 업데이트시 최초 1회 prod.key 및 title.key 교체/생성.
  - 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`
  - keys 덤프 경로 변경: `sd:/backup/keys`
  - ASAP 이외의 CFW에서 일부 기능 이용제한.
- [ASAP-Cleaner](https://github.com/Asadayot/CommonProblemResolver) : 1.0.1
  - OLED 기기 화면 지원.
- [Hwfly-Toolbox](https://github.com/Asadayot/hwfly-toolbox) : 1.1.1
  - 버전 표기 오류 수정
  - ASAP 이외의 CFW에서 일부 기능 이용제한.
- [PiCoFly-Toolbox](https://github.com/Ansem-SoD/Picofly) : 0.1(unlock 전용), 0.2
  - Install Supporter에 언락 툴박스 기본 페이로드로 설치.

### ⬦ 시그패치
- ASAP 용 기본 설치, 이후 ASAP-Updater 를 통하여 업데이트 가능.

### ⬦ Warmboot Mariko 캐시
- Mariko 기기용 웜부트 캐시 `wb_0c.bin ~ wb_12.bin`
  - 캐시 기본 제공으로 HOS 16.0.3 까지 정펌 및 HOS(Warmboot Error Fix)의 필수 기동 필요없음.

### ⬦ 홈브류 (기본 설치)
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater) : 2.21.7-ASAP
  - 바로가기 NSP 설치 파일 제공.
- [Daybreak](https://github.com/Asadayot/Asanosphere) : 1.0.0
- [Reboot2payload](https://github.com/Asadayot/Asanosphere) : 1.0.0
- [Haze](https://github.com/Asadayot/Asanosphere) : 1.0.0
- [DB Installer](https://github.com/rashevskyv/dbi) : 563
  - 바로가기 NSP 설치 파일 제공.
- [Hekate-Toolbox/Mariko 전용 설치](https://github.com/Asadayot/Hekate-Toolbox) : 4.0.3
  - 한글화.
  - 바로가기 NSP 설치 파일 제공.
- [Tinfoil](https://github.com/Asadayot/NX-Activity-Log) : 16.0 [v2]
  - 바로가기 NSP 설치 파일 제공.

### ⬦ 테슬라 & 홈브류 & 시스모듈 (선택 설치-재부팅 필요)
- [Tesla menu](https://github.com/Asadayot/Tesla-Menu) : 1.2.2
  - 한글화.
- [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) : 1.3.1
  - 한글화.
- [DB Installer](https://github.com/rashevskyv/dbi) : 551
  - 바로가기 NSP 설치 파일 제공.
- [HB-appstore](https://github.com/fortheusers/hb-appstore) : 2.3.2
  - 한글화.
- [JKSV](https://github.com/Asadayot/JKSV) : 2023.04.17
  - 매끄럽게 재번역 및 언어 고정. 
  - 바로가기 NSP 설치 파일 제공.
- [Linkalho](https://github.com/Asadayot/linkalho) : 2.0.2
  - 한글화.
  - 바로가기 NSP 설치 파일 제공.
- [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) : 1.5.0
  - 매끄럽게 재번역 및 언어 고정. 
  - 바로가기 NSP 설치 파일 제공.
- [vgedit](https://github.com/Asadayot/vgedit) : 2.2
  - 한글화.
  - 바로가기 NSP 설치 파일 제공.
- [ldnmitm config](https://github.com/Asadayot/ldn_mitm) : 1.1.2
- [sys-clk manager](https://github.com/Asadayot/sys-clk) : 1.0.3
  - 한글화.
  - 바로가기 NSP 설치 파일 제공.
- [Edizon-SE](https://github.com/tomvita/EdiZon-SE/releases) : 3.8.36
  - 바로가기 NSP 설치 파일 제공. 
- [EdiZon-Overlay](https://github.com/proferabg/EdiZon-Overlay) : 1.0.5
- [MissionControl](https://github.com/ndeadly/MissionControl) : 0.9.2
- [ldn_mitm](https://github.com/Asadayot/ldn_mitm) : 1.15.0
  - 한글화.
- [QuickNTP](https://github.com/Asadayot/QuickNTP) : 1.2.8
  - 한글화.
  - 한국 시간대 기본 템플릿에 추가.
- [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) : 0.9.0
- [sys-clk](https://github.com/Asadayot/sys-clk) : 1.0.3
  - 한글화.
- [sys-con](https://github.com/cathery/sys-con) : 0.6.4

</details>

설치 방법
=====
<details><summary>자세히 보기</summary>
  
### ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater)의 `ASAP-updater.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.
- 스위치를 커스텀 펌웨어로 기동 후, hbmenu `앨범+R+A` 진입, `ASAP-Updater`를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.
- `자동 설치가 진행되며 폴더를 지정하지 않은 홈브류, 다른 올인원 팩의 구성요소를 모두 제거합니다.`

### ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
- [ASAP](https://github.com/Asadayot/ASAP)의 `Install_Supporter.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
  - `자동 설치가 진행되며 폴더를 지정하지 않은 홈브류, 다른 올인원 팩의 구성요소를 모두 제거합니다.`
  - 혹은 디렉토리를 `sd:/` 최상위 경로로 모두 붙여넣습니다.
- 닌텐도 온라인 가입자 설정을 진행합니다. (선택사항)
  - 부팅화면이 표기되면 `- 볼륨 버튼` 선택하여 Hekate×ASAP으로 기동 하여 런치 메뉴로 진입, `HOS (웜부트 오류 수정)` 로 부팅합니다.
  - 설정→데이터 관리→저장 데이터 맡기기→온라인 가입자 선택→설정→저장 데이터 자동 백업/다운로드 OFF 순으로 설정합니다.
  - 설정→본체→소프트웨어 자동 업데이트 OFF→에러 정보 송신 OFF 순으로 설정합니다.
- `파티션 기반` 에뮤낸드를 생성합니다. (선택사항)
  - 부팅화면이 표기되면 `- 볼륨 버튼` 선택하여 Hekate×ASAP으로 진입합니다. 
  - 도구→SD 카드 파티션 분할→확인→에뮤낸드(RAW)-12 권장→포맷 및 분할 계속→시작→전원버튼→확인 순으로 선택하여 파티션을 분할합니다.
  - 홈메뉴로 돌아가 에뮤낸드→에뮤낸드 생성→파티션 기반→파티션 X 순으로 선택하여 자동 생성합니다.
- `파일 기반` 에뮤낸드를 생성합니다. (선택사항)
  - 부팅화면이 표기되면 `- 볼륨 버튼` 선택하여 Hekate×ASAP으로 진입합니다. 
  - 도구→SD 카드 파티션→확인→포맷 및 분할 계속→시작→전원버튼→확인 순으로 선택하여 FAT32로 포맷합니다.
  - 홈메뉴로 돌아가 에뮤낸드→에뮤낸드 생성→파일 기반 순으로 선택하여 자동 생성합니다.
- 런치 메뉴의 `Asanosphère (시스/에뮤낸드)`로 기동 후, hbmenu `앨범+R+A` 진입하여 ASAP-Updater를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.

### ⬦ 이용 중 알 수 없는 충돌이 발생할 시
  - Hekate×ASAP→기타런처or페이로드→`ASAP-Cleaner` 선택하여 ASAP을 `Install Supporter` 상태로 되돌립니다.
  - 이 작업은 개인파일, backup 폴더, 홈브류를 제외한 거의 모든 파일을 삭제 및 초기화합니다.

### ⬦ 추가 사항 설치
- `ASAP-Updater` 혹은 `Install Supporter` 를 이용한 ASAP 설치 완료 후 기호에 따라 추가 파일을 설치합니다.
  - ASAP-Updater → 추가 구성 다운로드 → '[ OLED 유저 ] OLED 모델 전용 필수 추가파일' 선택 다운로드.
  - ASAP-Updater → 추가 구성 다운로드 → '[ Hwfly ]', '[ PiCoFly ]' 필요 파일 선택 다운로드.
  - ASAP-Updater → Horizon OS 다운로드 → '[ HOS ] XX.X.X', '[ HOS ] XX.X.X (Rebootless Update)' 선택 다운로드. 
  - ASAP-Updater → 버전교체/추가설치 → 'Signature Patches', 'Tinfoil DB', 'Tesla', 'Sysmodule', 'Homebrew' 선택 다운로드.

</details>

업데이트 순서
=====
### ⬦ 업데이트 순서에 대하여...
- 퓨즈가 연소되는 메이저 업데이트의 경우, 특정기기에서 많은 오류를 동반할 수 있으니 다음을 숙지하세요.
  - HOS 버전과 대응하는 CFW(ASAP)를 `ASAP-Updater` → `ASAP 업데이트`에서 우선적으로 업데이트.
  - 헤카테 `홈` → `재부팅` → `정펌`으로 HOS 기동 후 시스템 업데이트.
  - Asanosphère (시스/에뮤낸드), (에뮤낸드) 를 통한 HOS 기동 후 `ASAP-Updater` → `Horizon OS 업데이트`에서 에뮤낸드 업데이트.
  
  
스크린샷
=====

![01](https://user-images.githubusercontent.com/89662125/232354082-3dcc1999-0125-4dd0-9473-ac5fa91c780a.jpg)
![02](https://user-images.githubusercontent.com/89662125/232354085-933490ea-8ad4-4dff-bd6d-afdbb2426568.jpg)
![03](https://user-images.githubusercontent.com/89662125/232354086-06a23868-90e1-4a23-b263-b28b782472cc.jpg)
![04](https://user-images.githubusercontent.com/89662125/232354089-f841d021-25fd-4607-91cd-a4617432f661.jpg)
![05](https://user-images.githubusercontent.com/89662125/232354092-730990bd-a8d2-4c2c-9473-be3c4ece7b14.jpg)
![06](https://user-images.githubusercontent.com/89662125/234256902-c192053b-f9b0-41fd-b1b6-480af8e834e8.jpg)
![07](https://user-images.githubusercontent.com/89662125/232692003-ea66f56d-8f79-47c4-8e15-804279859d3b.jpg)
![08](https://user-images.githubusercontent.com/89662125/232692005-445aaa72-ee6e-439a-a5e6-01a061205f3d.jpg)
![09](https://user-images.githubusercontent.com/89662125/232691995-5ef6a162-57f5-450c-bd4c-f4fd354c79b1.jpg)
![10](https://user-images.githubusercontent.com/89662125/232691998-fdca1f98-a16a-4f62-a430-005167bfac14.jpg)
![11](https://user-images.githubusercontent.com/89662125/232354100-c77dc9fe-b2bc-4111-953c-6c56d77028ee.jpg)
![12](https://user-images.githubusercontent.com/89662125/232354103-164c9f7e-0371-4c73-a29b-fcb9292567fe.jpg)
![13](https://user-images.githubusercontent.com/89662125/232354104-53f01bd4-27b1-433c-b1fa-71c3ab3b050e.jpg)
![14](https://user-images.githubusercontent.com/89662125/232354105-615e8384-8269-4692-94f1-80305f1f87c5.jpg)
![15](https://user-images.githubusercontent.com/89662125/232354107-5bcb4e52-49d1-46e8-910e-15f4944aff04.jpg)

크레딧
=====
ASAP 을 구성하기 위해 이용한 멋진 팀 및 개발자들과 앱.
  - [Atmosphère-NX](https://github.com/Atmosphere-NX) :  Atmosphère, hbloader, hbmenu
  - [CTCaer](https://github.com/CTCaer) :  Hekate & Nyx
  - [ITotalJustice](https://github.com/ITotalJustice)
  - [suchmememanyskill](https://github.com/suchmememanyskill) :  TegraExplorer
  - [Team-Neptune](https://github.com/Team-Neptune) :  CPR
  - [shchmue](https://github.com/shchmue) :  Lockpick RCM
  - [Hwfly-NX](https://github.com/hwfly-nx) :  Hwfly firmware, Hwfly Toolbox
  - [Ansem-SoD](https://github.com/Ansem-SoD) :  PiCoFly firmware, PiCoFly Toolbox
  - [HamletDuFromage](https://github.com/HamletDuFromage) :  Aio-switch-updater
  - [rashevskyv, duckbill](https://github.com/rashevskyv) :  DBI
  - [fortheusers](https://github.com/fortheusers) :  hb-appstore
  - [WerWolv](https://github.com/WerWolv) :  Tesla menu, ovl-sysmodules, Edizon, Hekate-Toolbox
  - [J-D-K](https://github.com/J-D-K) :  JKSV
  - [rdmrocha](https://github.com/rdmrocha) :  Linkalho
  - [tallbl0nde](https://github.com/tallbl0nde), [zdm65477730](https://github.com/zdm65477730) :  NX-Activity-Log
  - [blawar](https://github.com/blawar) :  tinfoil
  - [vgmoose](https://github.com/vgmoose) :  vgedit
  - [spacemeowx2](https://github.com/spacemeowx2) :  ldn-mitm
  - [retronx-team](https://github.com/retronx-team) :  sys-clk manager
  - [proferabg](https://github.com/proferabg) :  Edizon-Overlay
  - [tomvita](https://github.com/tomvita) :  Edizon-SE
  - [ndeadly](https://github.com/ndeadly) :  Mission Control
  - [cathery](https://github.com/cathery) :  sys-con, Hekate-Toolbox
  - [nedex](https://github.com/nedex) :  QuickNTP
  - [masagrator](https://github.com/masagrator) :  Status-Monitor-Overlay
