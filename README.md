# ASAP
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)를 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa - Starter All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.




## 기본 제공
### ⬦ CFW & Bootloader
[Asanosphère](https://github.com/Asadayot/Asanosphere) 와 [Hekate](https://github.com/CTCaer/hekate)

### ⬦ 홈브류 메뉴/로더
[nx-hbmenu](https://github.com/Asadayot/nx-hbmenu), [nx-hbloader](https://github.com/Asadayot/nx-hbloader)


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
  - ASAP-Updater → 추가 구성 다운로드 → [ Mariko 유저 ] OLED 모델 전용 필수 추가파일 선택 다운로드.
  - ASAP-Updater → 추가 구성 다운로드 → hekate_ipl.ini, hwfly firmware.bin / sdloader.enc 선택 다운로드.
  - ASAP-Updater → Horizon OS 다운로드 → [ HOS ] XX.X.X, [ HOS ] XX.X.X (Rebootless Update) 선택 다운로드. 
  - ASAP-Updater → 버전교체/시그패치/ETC. → Signature Patches, Tesla, Sysmodule, Homebrew 선택 다운로드.

## Screenshots
<details><summary>Expand to view the screenshots</summary>

![ams_tab](https://user-images.githubusercontent.com/61667930/193625554-ad9a8a5a-72ad-462e-95d9-94979c9750ac.jpg)
![cheats_tab](https://user-images.githubusercontent.com/61667930/193625551-9912210a-c99c-434f-ab5e-b468a698ddcf.jpg)
![individual_cheats](https://user-images.githubusercontent.com/61667930/193625547-18bff50c-1985-4ce5-aadf-2394fa5d29ca.jpg)
![tools_tab](https://user-images.githubusercontent.com/61667930/193625542-4722690a-a86f-48d1-8935-367b16f355f8.jpg)

</details>
