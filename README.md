ASAP
=====
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)에서 분기한 [Hekate×ASAP](https://github.com/Asadayot/hekate)을 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa's Switch All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.
- ASAP 에 기본 포함된 [Asanosphère](https://github.com/Asadayot/Asanosphere) & [Hekate×ASAP](https://github.com/Asadayot/hekate) 및 페이로드는 유기적인 관계로 이어져 있으며 기타 올인원과 혼합 사용시 이용하지 못하는 기능이 생기거나 치명적인 충돌이 일어날 수 있습니다, 혼합 사용을 피해주세요.
- 기본 포함 팩을 제외한 홈브류 및 페이로드는 위 내용과 관련이 없으니 자유로이 설치 및 사용하셔도 무방합니다.





새 버전 개선사항
=====
### ⬦ ASAP-0326 주요 개선점
 - Hekate×ASAP
   - 오탈자 수정, 이후 발견시 [Asa's Atelier](https://asadayo.tistory.com) 블로그 톡에 보고 바람
 - ASAP-Updater
   - 2.21.4 → 2.21.5 안정성 업데이트
   - ASAP 업데이트 : `[ INSTINCT 모드칩 ]`, `[ Picofly 모드칩 ]` 추가
   - 추가 구성 다운로드 : `[ Picofly 유저 ] OLED 전용 필수 추가파일` 추가
   - Horizon OS 다운로드 : `[ HOS ] 14.1.2 (Rebootless Update 3)`, `[ HOS ] 15.0.0` 제거 / `[ HOS ] 16.0.1` 추가
 - hb-appstore
   - 2.2 → 2.3.2
   - 더 많은 정보는 [hb-appstore](https://github.com/fortheusers/hb-appstore/releases/tag/v2.3.2) 참고
 - Tesla-Menu
   - 1.0.7 → 1.2.1
   - libtesla 업데이트
 - ovl-Sysmodules
   - 종속성 업데이트, 경고문 수정
 - ldnmitm
   - Atmosphere-libs, libtesla 업데이트
 - Sigpatches
   - ASAP-0326 업데이트

기본 제공 / 변경 로그
=====
<details><summary>자세히 보기</summary>

### ⬦ CFW & 부트로더
- [Asanosphère](https://github.com/Asadayot/Asanosphere)
  - 버전 표기 변경 : `HOS VER│ASAP1.5.1-0326│S/E`
  - exosphere 경로 변경 : `sd:/atmosphere/config`
  - config 폴더의 .ini 파일 한글 부연 설명 추가(주석)
  - 시리얼 변조 코드 변경 : `XAW` → `XAJ`(유럽/일본)
  - 더 많은 정보는 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere/releases) 참고.
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
- [TegraExplorer](https://github.com/Asadayot/TegraExplorer) : 4.0.1-ASAP
  - TegraExplorer 폴더 삭제, Exit/Scripts 수정, 덤프 경로 변경.
  - 스크린샷 : `sd:/backup/screenshots`, HOS 덤프 : `sd:/Firmware`, 기타 : `sd:/backup`
  - ASAP 이외의 CFW에서 일부 기능 이용제한.
- [Lockpick_RCM](https://github.com/Asadayot/Lockpick_RCM) : 1.9.10-ASAP
  - ASAP 설치시 최초 1회 prod.key 및 title.key 생성.
  - 덤프 경로 변경.
  - 스크린샷 : `sd:/backup/screenshots`
  - keys : `sd:/backup/keys`
  - ASAP 이외의 CFW에서 일부 기능 이용제한.
- [hwfly-toolbox](https://github.com/Asadayot/hwfly-toolbox) : 1.1.1 (버전 표기 오류 수정)
  - ASAP 이외의 CFW에서 일부 기능 이용제한.

### ⬦ 시그패치
- ASAP 용 기본 설치, 이후 ASAP-Updater 를 통하여 업데이트 가능.

### ⬦ Warmboot Mariko 캐시
- Mariko 기기용 웜부트 캐시 `wb_0c.bin ~ wb_12.bin`

### ⬦ 홈브류
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater) : 2.21.4-ASAP
  - 오탈자 수정, 내용 변경, 연결 링크 변경, 16.0.0 지원, Tesla 및 홈브류/시스모듈 항목 추가.
- [DB Installer](https://github.com/rashevskyv/dbi) : 519, 바로가기 nsp
- [hb-appstore](https://github.com/fortheusers/hb-appstore) : 2.3.2
- [Hekate-Toolbox/Mariko 전용 설치](https://github.com/Asadayot/Hekate-Toolbox) : 4.0.3, 한글화, 바로가기 nsp
- [JKSV](https://github.com/Asadayot/JKSV) : 2023.02.28, 매끄럽게 재번역 및 언어 고정, 바로가기 nsp
- [Linkalho](https://github.com/Asadayot/linkalho) : 2.0.2, 한글화, 바로가기 nsp
- [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) : 1.5.0, 매끄러운 재번역, 바로가기 nsp
- [Tinfoil](https://github.com/Asadayot/NX-Activity-Log) : 16.0 [v0], 바로가기 nsp
- [vgedit](https://github.com/Asadayot/vgedit) : 2.2, 한글화, 바로가기 nsp
- [Edizon/선택 설치](https://github.com/WerWolv/EdiZon) : 3.1.0, 바로가기 nsp
- [ldnmitm config/선택 설치](https://github.com/Asadayot/ldn_mitm) : 1.1.2
- [sys-clk manager/선택 설치](https://github.com/Asadayot/sys-clk) : 1.0.3-ASAP, 한글화, 바로가기 nsp

### ⬦ 테슬라 & 시스모듈 (선택 설치)
- [Tesla menu](https://github.com/Asadayot/Tesla-Menu) : 1.2.1-ASAP, 한글화
- [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) : 1.3.1-ASAP, 한글화
- [EdiZon-Overlay](https://github.com/proferabg/EdiZon-Overlay) : 1.0.4
- [MissionControl](https://github.com/ndeadly/MissionControl) : 0.9.0
- [ldn_mitm](https://github.com/Asadayot/ldn_mitm) : 1.15.0-ASAP, 한글화
- [QuickNTP](https://github.com/Asadayot/QuickNTP) : 1.2.7-ASAP, 한글화
- [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) : 0.8.1-ASAP
- [sys-clk](https://github.com/Asadayot/sys-clk) : 1.0.3-ASAP, 한글화
- [sys-con](https://github.com/cathery/sys-con) : 0.6.4

</details>

설치 방법
=====
<details><summary>자세히 보기</summary>
  
### ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater)의 `Asano-updater_X.XX.X.zip` [Latest](https://github.com/Asadayot/ASAP-updater/releases/latest)를 내려받습니다.
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.
- 스위치를 커스텀 펌웨어로 기동 후, hbmenu `앨범+R+A` 진입, `ASAP-Updater`를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.

### ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
- [ASAP](https://github.com/Asadayot/ASAP)의 `Install_Supporter.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
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
- 런치 메뉴의 `Asanosphère (퓨즈 체인로드)`로 기동 후, hbmenu `앨범+R+A` 진입하여 ASAP-Updater를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.

### ⬦ 추가 사항 설치
- `ASAP-Updater` 혹은 `Install Supporter` 를 이용한 ASAP 설치 완료 후 기호에 따라 추가 파일을 설치합니다.
  - ASAP-Updater → 추가 구성 다운로드 → '[ Mariko 유저 ] OLED 모델 전용 필수 추가파일' 선택 다운로드.
  - ASAP-Updater → 추가 구성 다운로드 → 'hekate_ipl.ini', 'hwfly firmware.bin' / 'sdloader.enc' 선택 다운로드.
  - ASAP-Updater → Horizon OS 다운로드 → '[ HOS ] XX.X.X', '[ HOS ] XX.X.X (Rebootless Update)' 선택 다운로드. 
  - ASAP-Updater → 버전교체/시그패치/ETC. → 'Signature Patches', 'Tinfoil DB', 'Tesla', 'Sysmodule', 'Homebrew' 선택 다운로드.

</details>

업데이트 순서
=====
### ⬦ 업데이트 순서에 대하여...
- 퓨즈가 연소되는 메이저 업데이트의 경우, 특정기기에서 많은 오류를 동반할 수 있으니 다음을 숙지하세요.
  - HOS 버전과 대응하는 CFW(ASAP)를 `ASAP-Updater` → `ASAP 업데이트`에서 우선적으로 업데이트.
  - 헤카테 `홈` → `재부팅` → `정펌`으로 HOS 기동 후 시스템 업데이트.
  - fss0/Package3, fusee 체인로드를 통한 HOS 기동 후 `ASAP-Updater` → `Horizon OS 업데이트`에서 에뮤낸드 업데이트.
  
  
스크린샷
=====

![01](https://user-images.githubusercontent.com/89662125/227739956-eeda70b8-c6d2-4638-a6be-43c3a1954ce6.jpg)
![02](https://user-images.githubusercontent.com/89662125/227739959-5960370a-c202-4cf5-a414-4442d83eadc5.jpg)
![03](https://user-images.githubusercontent.com/89662125/227739960-443783f8-c637-4c79-879d-e6396167de5f.jpg)
![04](https://user-images.githubusercontent.com/89662125/227739961-fa564b0f-4cd8-40ff-bcd8-dede7e87d137.jpg)
![05](https://user-images.githubusercontent.com/89662125/227739962-6df2c16e-4db5-4cc8-a081-968ad082a7c0.jpg)
![06](https://user-images.githubusercontent.com/89662125/227739963-0d1d239b-c18c-4b72-b5fc-f421324666eb.jpg)
![07](https://user-images.githubusercontent.com/89662125/227739964-9b83850a-658a-44f9-8045-fcb2e919b7f8.jpg)
![08](https://user-images.githubusercontent.com/89662125/227739965-2a012752-e298-41b9-8a35-497c4a36aa26.jpg)
![09](https://user-images.githubusercontent.com/89662125/227739966-dfa20add-ef80-4e96-8545-06a620a10629.jpg)
![10](https://user-images.githubusercontent.com/89662125/227739968-bb11c520-2f90-469b-ae1c-5ca547c216bd.jpg)
![11](https://user-images.githubusercontent.com/89662125/227739969-3442960b-337b-442d-8744-b1cf22d6a955.jpg)
![12](https://user-images.githubusercontent.com/89662125/227739970-395ac6e4-9a2b-4f1f-997e-174b6e23ed7f.jpg)
![13](https://user-images.githubusercontent.com/89662125/227739971-f248a7e6-ce39-41c0-aff7-99b3e6ffde92.jpg)
![14](https://user-images.githubusercontent.com/89662125/227739973-42195964-2b52-4689-87cc-4365946bda1b.jpg)
![15](https://user-images.githubusercontent.com/89662125/227739974-2c6afc29-7a8f-418d-9d4d-85043bc45fdd.jpg)

크레딧
=====
ASAP 을 구성하기 위해 이용한 멋진 팀 및 개발자들과 앱.
  - [Atmosphère-NX](https://github.com/Atmosphere-NX) :  Atmosphère, hbloader, hbmenu
  - [CTCaer](https://github.com/CTCaer) :  Hekate & Nyx
  - [ITotalJustice](https://github.com/ITotalJustice)
  - [suchmememanyskill](https://github.com/suchmememanyskill) :  TegraExplorer
  - [shchmue](https://github.com/shchmue) :  Lockpick RCM
  - [Hwfly-NX](https://github.com/hwfly-nx) :  Hwfly firmware, Hwfly Toolbox
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
  - [ndeadly](https://github.com/ndeadly) :  Mission Control
  - [cathery](https://github.com/cathery) :  sys-con, Hekate-Toolbox
  - [nedex](https://github.com/nedex) :  QuickNTP
  - [masagrator](https://github.com/masagrator) :  Status-Monitor-Overlay
