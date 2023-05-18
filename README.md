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


| 대상  | 버전         | 커밋             | 변경사항                                      | 비고 | 
| ----- | ---------- | -------------- | ----------------------------------------- | ------ | 
| [ASAP](https://github.com/Asadayot/ASAP) | 0515 | a60862c | [지그/로더] SXOS-boot.dat, boot.ini 파일 추가 |  | 
| [Asanosphère](https://github.com/Asadayot/Asanosphere) | 1.5.4 | 3cb54e2 | [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere/releases) 참고 |  | 
| [Hekate×ASAP](https://github.com/Asadayot/hekate) | 6.0.4 & 1.5.3 | 937ab53 | 오탈자 수정 |  | 
| Sigpatches | 0515 |  | 3cb54e2 & 937ab53 기반 시그패치 최신화 |  | 
| [ASAP-Updater](https://github.com/Asadayot/ASAP/releases) | 2.22.0_fix3 | [012b89e](https://github.com/HamletDuFromage/aio-switch-updater) | 기타 올인원 팩 자동설치 링크 추가<br>- 커스텀 링크 추가<br>- 버전확인 웹 기반 변경 | 23.05.18 |
| [RetroArch](https://www.retroarch.com/) | 1.15.0 |  | 요청에 따른 선택설치 홈브류 추가 |  | 
| [Edizon](https://github.com/WerWolv/EdiZon) | 3.1.0 | dc14c3a | 요청에 따른 선택설치 원본 홈브류 추가 |  | 
| [emuiibo](https://github.com/Asadayot/emuiibo) | 1.0.0 | 97326a0 | 요청에 따른 선택설치 시스모듈 추가 |  | 
| [ldn_mitm](https://github.com/Asadayot/ldn_mitm) | 1.15.0 | b98d2c6 | Atmosphere-libs 업데이트 |  | 
| [Tesla menu](https://github.com/Asadayot/Tesla-Menu) | 1.2.2 | 97b9677 | libtesla 업데이트 |  | 
| [MissionControl](https://github.com/Asadayot/MissionControl) | 0.9.2 | fe31665 | Atmosphere-libs, libnx 업데이트 |  | 
| [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) | 0.9.0 | 4bf7b23 | 글자 깨짐 수정 |  | 
| [Quick-NTP](https://github.com/Asadayot/QuickNTP) | 1.2.8 | 11b9897 | libtesla 업데이트 |  | 

기본 제공 / 변경 로그
=====
<details><summary>자세히 보기</summary>

### ⬦ CFW & 부트로더

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [Asanosphère](https://github.com/Asadayot/Asanosphere) | HOS｜ASAP1.5.4-0515｜S/E | - 커스텀 펌웨어<br>- exosphere 경로 변경 : `sd:/atmosphere/config`<br>- config 폴더의 .ini 파일 한글 부연 설명 추가(주석)<br>- 시리얼 변조 코드 변경 : `XAW` → `XAJ`(유럽/일본) |
| [Hekate×ASAP](https://github.com/Asadayot/hekate) | 6.0.4 & 1.5.3 × 0515 | - ASAP 전용 올인원 부트로더<br>- 한글화<br>- 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`<br>- 기타 덤프 경로 변경 : `sd:/backup` |
| Boot.dat<br>Boot.ini | 1.1 | - SXOS / 모드칩 SX펌웨어 전용 필수 로더 및 설정 |

### ⬦ 홈브류 메뉴/로더

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [nx-hbmenu](https://github.com/Asadayot/nx-hbmenu) | 3.5.1 | - 홈브류 메뉴<br>- 한글화<br>- 고정 경로 변경: `sd:/atmosphere/hb` |
| [nx-hbloader](https://github.com/Asadayot/nx-hbloader) | 2.4.3 | - 홈브류 로더<br>- 한글화<br>- 고정 경로 변경: `sd:/atmosphere/hb` |

### ⬦ 페이로드
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- |
| [fusee.bin](https://github.com/Asadayot/Asanosphere) | 1.5.4 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) 페이로드 |
| [TegraExplorer](https://github.com/Asadayot/TegraExplorer) | 4.0.1 | - 파일, 페이로드 관리 및 덤프<br>- TegraExplorer 폴더 삭제, Exit/Scripts 수정<br>- 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`<br>- HOS 덤프 경로 변경: `sd:/Firmware`<br>- 기타 덤프 경로 변경: `sd:/backup` |
| [Lockpick_RCM](https://github.com/Asadayot/Lockpick_RCM) | 1.9.10 | - Key 파일 추출 페이로드<br>- ASAP 설치 및 업데이트시 최초 1회 prod.key 및 title.key 교체/생성<br>- 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`<br>- keys 덤프 경로 변경: `sd:/backup/keys` |
| [ASAP-Cleaner](https://github.com/Asadayot/CommonProblemResolver) | 1.0.1 | - ASAP 파일 클리너 페이로드<br>- OLED 기기 화면 지원 |
| [Hwfly-Toolbox](https://github.com/Asadayot/hwfly-toolbox) | 1.1.1 | - Hwfly 모드칩 전용 툴박스 페이로드<br>- 버전 표기 오류 수정 |
| [PiCoFly-Toolbox](https://github.com/Ansem-SoD/Picofly) | 0.1 | - PiCoFly 언락 전용 툴박스 페이로드<br>- unlock.bin과 함께 제공<br>- Install Supporter에 언락 툴박스 기본 페이로드로 설치 |
| [PiCoFly-Toolbox](https://github.com/Ansem-SoD/Picofly) | 0.2 | - PiCoFly 2.6 이상 버전 전용 툴박스 페이로드 |

### ⬦ 시그패치
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- |  
| Signature Patches | 0515 | - ASAP 전용 [3cb54e2](https://github.com/Asadayot/Asanosphere) & [937ab53](https://github.com/Asadayot/hekate) 기반 시그패치 |  

### ⬦ Warmboot Mariko 캐시

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- |  
| wb_0c.bin<br>wb_0d.bin<br>wb_0e.bin<br>wb_0f.bin<br>wb_10.bin<br>wb_11.bin<br>wb_12.bin | 9.1.0 ~ 9.2.0 지원<br>10.0.0 ~ 10.2.0 지원<br>11.0.0 ~ 12.0.1 지원<br>12.0.2 ~ 13.1.0 지원<br>13.2.1 ~ 14.1.2 지원<br>15.0.0 ~ 15.0.1 지원<br>16.0.0 ~ 16.0.3 지원 | - HOS 16.0.3 까지 정펌 및 HOS(Warmboot Error Fix)의 필수 기동 필요없음 |

### ⬦ 홈브류 (기본 설치)
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [ASAP-Updater](https://github.com/Asadayot/ASAP/releases) | 2.22.0_fix3 | - ASAP, HOS, Homebrew, Sysmodule, etc. 업데이터<br>- 바로가기 NSP 설치 파일 제공 |
| [Daybreak](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) HOS 업데이터 홈브류  | 
| [Reboot2payload](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) 구형 전용 페이로드 재부팅 홈브류 | 
| [Haze](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) PTP/MTP USB 전송 홈브류 | 
| [DB Installer](https://github.com/rashevskyv/dbi) | 563 | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 | 
| [Hekate-Toolbox](https://github.com/Asadayot/Hekate-Toolbox) | 4.0.3 | - 타이틀 오버라이드, 페이로드 재부팅 설정 홈브류<br>- 모드칩 기기 전용 페이로드 재부팅 홈브류<br>- 한글화 | 
| [Tinfoil](https://github.com/Asadayot/NX-Activity-Log) | 16.0 [v2] | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 | 

### ⬦ 테슬라 & 홈브류 & 시스모듈 (선택 설치-재부팅 필요)
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [Tesla menu](https://github.com/Asadayot/Tesla-Menu) | 1.2.2 | - 테슬라 오버레이 메뉴<br>- 한글화 |  
| [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) | 1.3.1 | - 테슬라 시스모듈 오버레이<br>- 한글화 |
| [DB Installer](https://github.com/rashevskyv/dbi) | 563 | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [HB-appstore](https://github.com/fortheusers/hb-appstore) | 2.3.2 | - 홈브류, 시스모듈 앱 스토어<br>- 한글화 |
| [JKSV](https://github.com/Asadayot/JKSV) | 2023.04.17 | - 세이브 데이터 관리 홈브류<br>- 매끄럽게 재번역 및 언어 고정<br>- 바로가기 NSP 설치 파일 제공 |
| [Linkalho](https://github.com/Asadayot/linkalho) | 2.0.2 | - 닌텐도 어카운트 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) | 1.5.0 | - 활동 기록 관리 홈브류<br>- 매끄럽게 재번역 및 언어 고정<br>- 바로가기 NSP 설치 파일 제공 |
| [vgedit](https://github.com/Asadayot/vgedit) | 2.2 | - 텍스트 파일 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [ldnmitm config](https://github.com/Asadayot/ldn_mitm) | 1.1.3 | - LAN 플레이 관리 홈브류 |
| [ldn_mitm](https://github.com/Asadayot/ldn_mitm) | 1.15.0 | - LAN 플레이 관리 시스모듈<br>- 한글화 |  
| [sys-clk manager](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [RetroArch](https://www.retroarch.com/) | 1.15.0 | - 콘솔 에뮬레이터 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [emuiibo](https://github.com/Asadayot/emuiibo) | 1.0.0 | - 가상 아미보 관리 시스모듈 |
| [Edizon](https://github.com/WerWolv/EdiZon) | 3.1.0 | - 치트 관리 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [Edizon-SE](https://github.com/tomvita/EdiZon-SE/releases) | 3.8.36 | - 치트 관리 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [EdiZon-Overlay](https://github.com/proferabg/EdiZon-Overlay) | 1.0.5 | - 치트 관리 시스모듈 |
| [MissionControl](https://github.com/ndeadly/MissionControl) | 0.9.2 | 타사 컨트롤러 무선 지원 시스모듈 |
| [QuickNTP](https://github.com/Asadayot/QuickNTP) | 1.2.8 | - 네트워크 시간 설정 시스모듈<br>- 한글화<br>- 한국 시간대 기본 템플릿에 추가 |
| [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) | 0.9.0 | - 상태 모니터 확인 시스모듈 |
| [sys-clk](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 시스모듈<br>- 한글화 |
| [sys-con](https://github.com/cathery/sys-con) | 0.6.4 | - 타사 컨트롤러 유선 지원 시스모듈 |

</details>

설치 방법
=====
![구분](https://github.com/Asadayot/img/assets/89662125/282ecad3-a9a5-49c5-a798-5208055afc7b)

<details><summary>자세히 보기</summary>
  
### ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
- [ASAP-Updater](https://github.com/Asadayot/ASAP)의 `ASAP-updater.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.
- 스위치를 커스텀 펌웨어로 기동 후, hbmenu `앨범+R+A` 진입, `ASAP-Updater`를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.
- `자동 설치가 진행되며 Nintendo, emummc 폴더를 제외하고 폴더를 지정하지 않은 홈브류, 다른 올인원 팩의 구성요소를 모두 제거합니다.`

### ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
- [ASAP](https://github.com/Asadayot/ASAP)의 `Install_Supporter.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
  - `자동 설치가 진행되며 Nintendo, emummc 폴더를 제외하고 폴더를 지정하지 않은 홈브류, 다른 올인원 팩의 구성요소를 모두 제거합니다.`
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
  - 이 작업은 Nintendo, emummc 폴더, 개인파일, backup 폴더, 홈브류를 제외한 거의 모든 파일을 삭제 및 초기화합니다.

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
<details><summary>자세히 보기</summary>

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

</details>  

안내사항
=====
<details><summary>자세히 보기</summary>
  
### ⬦ 소스코드 관련
업로드 전 소스 소실로 인한 복구 및 공개 불가하며
소유하고 있는 선에서만 업로드 진행되었습니다.<br>각 시스모듈, 홈브류는 다음 업데이트부터 재작업하여 공개할 수 있습니다.
  
</details>

크레딧
=====
ASAP 을 구성하기 위해 이용한 멋진 팀 및 개발자들과 앱.
<details><summary>자세히 보기</summary>
  
  - [Atmosphère-NX](https://github.com/Atmosphere-NX) :  Atmosphère, hbloader, hbmenu
  - [CTCaer](https://github.com/CTCaer) :  Hekate & Nyx
  - [ITotalJustice](https://github.com/ITotalJustice)
  - [suchmememanyskill](https://github.com/suchmememanyskill) :  TegraExplorer
  - [Team-Neptune](https://github.com/Team-Neptune) :  CPR
  - [shchmue](https://github.com/shchmue) :  Lockpick RCM
  - [Hwfly-NX](https://github.com/hwfly-nx) :  Hwfly firmware, Hwfly Toolbox
  - [Ansem-SoD](https://github.com/Ansem-SoD) :  PiCoFly firmware, PiCoFly Toolbox
  - [HamletDuFromage](https://github.com/HamletDuFromage) :  Aio-switch-updater
  - [rashevskyv, duckbill](https://github.com/rashevskyv) :  DBI, KEFIR
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
  - [XorTroll](https://github.com/XorTroll) : emuiibo
  - [libretro](https://www.libretro.com/) : RetroArch
  - [ndeadly](https://github.com/ndeadly) :  Mission Control
  - [cathery](https://github.com/cathery) :  sys-con, Hekate-Toolbox
  - [nedex](https://github.com/nedex) :  QuickNTP
  - [masagrator](https://github.com/masagrator) :  Status-Monitor-Overlay
  - [Team-Neptune](https://github.com/Team-Neptune) :  DeepSea
  - [sthetix](https://github.com/sthetix) :  HATS
  
</details>
