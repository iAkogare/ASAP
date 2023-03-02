# ASAP
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)를 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa - Starter All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.




## 기본 제공
### ⬦ CFW & 부트로더
- [Asanosphère](https://github.com/Asadayot/Asanosphere) & [Hekate](https://github.com/CTCaer/hekate)
  - 버전 표기 변경 : `HOS VER│ASAP1.5.0-0302│S/E`
  - exosphere 경로 변경 : `sd:/atmosphere/config`
  - 시리얼 변조 코드 변경 : `XAW` → `XAJ`(유럽/일본)
- Boot.dat & Boot.ini
  - SX OS / 모드칩 전용 필수 로더 및 

### ⬦ 홈브류 메뉴/로더
- [nx-hbmenu](https://github.com/Asadayot/nx-hbmenu) & [nx-hbloader](https://github.com/Asadayot/nx-hbloader)
  - 한글화.
  - 고정 위치 변경 : `sd:/atmospheer/hb` 

### ⬦ 페이로드
- [fusse.bin](https://github.com/Asadayot/Asanosphere)
- [TegraExplorer](https://github.com/Asadayot/TegraExplorer) : 4.5.0-ASAP
  - TegraExplorer 폴더 삭제, Exit/Scripts 수정, 덤프 경로 변경.
  - 스크린샷 : `sd:/bootloader/screenshots`, HOS 덤프 : `sd:/Firmware`, 기타 : `sd:/backup`
- [Lockpick_RCM](https://github.com/Asadayot/Lockpick_RCM) : 1.9.11
  - 덤프 경로 변경.
  - 스크린샷 : `sd:/bootloader/screenshots`, keys : `sd:/backup/keys`
- [hwfly-toolbox](https://github.com/Asadayot/hwfly-toolbox) : 1.1.1, 버전 표기 오류 수정.

### ⬦ 시그패치
- ASAP 용 기본 설치, 이후 ASAP-Updater 를 통하여 업데이트 가능

### ⬦ 홈브류
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater) : 2.21.4-ASAP
  - 오탈자 수정, 내용 변경, 연결 링크 변경, 16.0.0 지원, Tesla 및 홈브류/시스모듈 항목 추가.
- [DB Installer](https://github.com/rashevskyv/dbi) : 506, 바로가기 nsp
- [hb-appstore](https://github.com/fortheusers/hb-appstore) : 2.2
- [Hekate-Toolbox/Mariko 전용 설치](https://github.com/Asadayot/Hekate-Toolbox) : 4.0.3, 한글화, 바로가기 nsp
- [JKSV](https://github.com/Asadayot/JKSV) : 2023.02.28, 한글화, 바로가기 nsp
- [Linkalho](https://github.com/Asadayot/linkalho) : 2.0.2, 한글화, 바로가기 nsp
- [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) : 1.5.0, 한글화, 바로가기 nsp
- [Tinfoil](https://github.com/Asadayot/NX-Activity-Log) : 16.0 [v0], 바로가기 nsp
- [vgedit](https://github.com/Asadayot/vgedit) : 2.2, 한글화, 바로가기 nsp
- [Edizon/선택 설치](https://github.com/WerWolv/EdiZon) : 3.1.0, 바로가기 nsp
- [ldnmitm config/선택 설치](https://github.com/Asadayot/ldn_mitm) : 1.1.2
- [sys-clk manager/선택 설치](https://github.com/Asadayot/sys-clk) : 1.0.3-ASAP, 한글화, 바로가기 nsp

### ⬦ 테슬라 & 시스모듈 (선택 설치)
- [Tesla menu](https://github.com/Asadayot/Tesla-Menu) : 1.0.7-ASAP, 한글화
- [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) : 1.3.1-ASAP, 한글화
- [EdiZon-Overlay](https://github.com/proferabg/EdiZon-Overlay) : 1.0.4
- [MissionControl](https://github.com/ndeadly/MissionControl) : 0.9.0
- [ldn_mitm](https://github.com/Asadayot/ldn_mitm) : 1.15.0-ASAP, 한글화
- [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) : 0.8.0-ASAP
- [sys-clk](https://github.com/Asadayot/sys-clk) : 1.0.3-ASAP, 한글화
- [sys-con](https://github.com/cathery/sys-con) : 0.6.4


## 설치 방법
### ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
- [ASAP-Updater](https://github.com/Asadayot/ASAP-updater)의 `Asano-updater_X.XX.X.zip` [Latest](https://github.com/Asadayot/ASAP-updater/releases/latest)를 내려받습니다.
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.
- 스위치를 커스텀 펌웨어로 기동 후, `hbmenu` 진입, `ASAP-Updater`를 실행합니다.
- `ASAP 업데이트` 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, `뒤로` 선택하여 재기동 하며 자동 설치를 진행합니다.

### ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
- [ASAP](https://github.com/Asadayot/ASAP)의 `Install Supporter.zip` [Latest](https://github.com/Asadayot/ASAP/releases/latest)를 내려받습니다.
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
  - 혹은 디렉토리를 `sd:/` 최상위 경로로 모두 붙여넣습니다.
- 닌텐도 온라인 가입자 설정을 진행합니다. (선택사항)
  - Hekate 로 기동 하여 Launch 메뉴로 진입, `HOS (Warmboot Error Fix)` 로 부팅합니다.
  - 설정→데이터 관리→저장 데이터 맡기기→온라인 가입자 선택→설정→저장 데이터 자동 백업/다운로드 OFF 순으로 설정합니다.
  - 설정→본체→소프트웨어 자동 업데이트 OFF→에러 정보 송신 OFF 순으로 설정합니다.
- `파티션 기반` 에뮤낸드를 생성합니다. (선택사항)
  - 부팅화면이 표기되면 `- 볼륨 버튼` 선택하여 Hekate로 진입합니다. 
  - Tools→Partition SD Card→OK→emuMMC(RAW)-12GiB→Next Step→Start→전원버튼→OK 순으로 선택하여 파티션을 분할합니다.
  - Hekate 홈메뉴로 돌아가 emuMMC→Create emuMMC→SD Partition→Part X 순으로 선택하여 자동 생성합니다.
- `파일 기반` 에뮤낸드를 생성합니다. (선택사항)
  - 부팅화면이 표기되면 `- 볼륨 버튼` 선택하여 Hekate로 진입합니다. 
  - Tools→Partition SD Card→OK→Next Step→Start→전원버튼→OK 순으로 선택하여 FAT32로 포맷합니다.
  - Hekate 홈메뉴로 돌아가 emuMMC→Create emuMMC→SD Partition→SD File 순으로 선택하여 자동 포맷합니다.
- Launch 메뉴의 `Atmosphere (fusee.bin)`로 기동 후, hbmenu `앨범+R+A` 진입하여 ASAP-Updater를 실행합니다.
- 'ASAP 업데이트' 항목에서 해당 사항을 선택하여 다운로드합니다.
- 다운로드 후, '뒤로' 선택하여 재기동 하며 자동 설치를 진행합니다.

### ⬦ 추가 사항 설치
- `ASAP-Updater` 혹은 `Install Supporter` 를 이용한 ASAP 설치 완료 후 기호에 따라 추가 파일을 설치합니다.
  - ASAP-Updater → 추가 구성 다운로드 → '[ Mariko 유저 ] OLED 모델 전용 필수 추가파일' 선택 다운로드.
  - ASAP-Updater → 추가 구성 다운로드 → 'hekate_ipl.ini', 'hwfly firmware.bin' / 'sdloader.enc' 선택 다운로드.
  - ASAP-Updater → Horizon OS 다운로드 → '[ HOS ] XX.X.X', '[ HOS ] XX.X.X (Rebootless Update)' 선택 다운로드. 
  - ASAP-Updater → 버전교체/시그패치/ETC. → 'Signature Patches', 'Tinfoil DB', 'Tesla', 'Sysmodule', 'Homebrew' 선택 다운로드.

## 스크린샷
<details><summary>미리보기</summary>

![1](https://user-images.githubusercontent.com/89662125/222483463-2504129c-09e8-464d-80eb-b51397d1556b.jpg)
![2](https://user-images.githubusercontent.com/89662125/222483471-7005b38c-e9cf-4148-87bb-dc6059e9bf7b.jpg)
![3](https://user-images.githubusercontent.com/89662125/222483481-45e95eb4-c723-405d-a1d7-30368fcc6f54.jpg)
![4](https://user-images.githubusercontent.com/89662125/222483526-38d4ac45-37f4-4db8-8516-2f5ecb7ef655.jpg)
![5](https://user-images.githubusercontent.com/89662125/222483540-e9bdb9a5-6b2a-469d-9919-efc86a5239cd.jpg)
![6](https://user-images.githubusercontent.com/89662125/222483557-b8f6dfbf-ce01-4566-8b1a-b7ac19c644e4.jpg)
![7](https://user-images.githubusercontent.com/89662125/222483568-07d7e32c-560c-4a0f-bebb-7da1c99387d1.jpg)
![8](https://user-images.githubusercontent.com/89662125/222483583-1d41ebd1-3cc5-4136-a731-077e93c6bd37.jpg)
![9](https://user-images.githubusercontent.com/89662125/222483594-0c738b3c-8c00-4356-8641-715f05a498a9.jpg)
![10](https://user-images.githubusercontent.com/89662125/222483708-68230b7b-97b5-4329-b25d-b587ae8d327c.jpg)
![11](https://user-images.githubusercontent.com/89662125/222483718-91a2ffa1-8022-4007-b911-b76f03f97fb4.jpg)
![12](https://user-images.githubusercontent.com/89662125/222483729-e9399261-b2eb-4af4-880e-217980faa047.jpg)
![13](https://user-images.githubusercontent.com/89662125/222483738-b10c9844-351b-4abd-8a73-a533881f5a4f.jpg)
![14](https://user-images.githubusercontent.com/89662125/222483759-ae856d50-81b0-4e39-9743-51e7af41f6fd.jpg)
![15](https://user-images.githubusercontent.com/89662125/222483793-c8a87a5c-508b-42cb-8294-bdc94a5ac356.jpg)
![16](https://user-images.githubusercontent.com/89662125/222483816-f3ad4b3a-be0f-41e0-8001-ccbd4e2e16a3.jpg)

</details>
