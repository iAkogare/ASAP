ASAP
=====
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)에서 분기한 [Hekate×ASAP](https://github.com/Asadayot/hekate)을 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa's Switch All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.
- ASAP 에 기본 포함된 [Asanosphère](https://github.com/Asadayot/Asanosphere) & [Hekate×ASAP](https://github.com/Asadayot/hekate) 및 페이로드는 유기적인 관계로 이어져 있으며 기타 올인원과 혼합 사용시 이용하지 못하는 기능이 생기거나 치명적인 충돌이 일어날 수 있습니다, 혼합 사용을 피해주세요.
- 기본 포함 팩을 제외한 홈브류 및 페이로드는 위 내용과 관련이 없으니 자유로이 설치 및 사용하셔도 무방합니다.

<br><br>

새 버전 개선사항
=====
## ⬦ ASAP-0531 주요 개선점

### 버그보고로 인한 0531 배포 일시 중지 
출장중이라 수정 늦을 수 있으니 0523_fix 사용해주세요.

<br><details><summary>스크린샷 미리보기</summary>

![0](https://github.com/Asadayot/img/assets/89662125/20586913-195d-4d47-a960-181cc7958168)
![1](https://github.com/Asadayot/img/assets/89662125/01d04a2a-d4bd-48cb-bd50-77080571001c)
![2](https://github.com/Asadayot/img/assets/89662125/8a8a3302-488b-48a2-b11a-61f2c4d8aef2)
![3](https://github.com/Asadayot/img/assets/89662125/f47a7271-391a-4254-ae71-d3906efdc88f)
![4](https://github.com/Asadayot/img/assets/89662125/58dfca6b-37a1-4bc0-b766-488cae932511)
![5](https://github.com/Asadayot/img/assets/89662125/acad7fa7-6aae-4e34-b323-e8af107982fa)
![6](https://github.com/Asadayot/img/assets/89662125/6f815220-a546-462b-8557-b475330c4466)
![7](https://github.com/Asadayot/img/assets/89662125/4ce945c5-ec52-4a23-9263-922a004b7454)
![8](https://github.com/Asadayot/img/assets/89662125/b9c70313-5fdf-4918-96ec-0870731012ff)
![9](https://github.com/Asadayot/img/assets/89662125/0d6333f9-f4f7-43b2-9ac4-c8a92a291ad3)
![10](https://github.com/Asadayot/img/assets/89662125/30028c97-33e9-4e6f-9d3a-ab5712118510)
![11](https://github.com/Asadayot/img/assets/89662125/34b60aaa-efa9-46a1-a560-bb124b311c47)
![12](https://github.com/Asadayot/img/assets/89662125/6da98ff7-a6aa-4284-a323-96a745c3f9b5)

</details>
<br><br>   
- ASAP-Updater : 올인원 교체/추가설치 메뉴의 홈브류, 시스모듈/오버레이 일부 제외 모두 순정파일로 교체.<br><br>
- ASAP 시그패치 : 0531 버전으로 교체.<br><br>
- ASAP 기본 홈브류, 시스모듈, 오버레이 대폭 추가 및 최신 libnx, libtesla 로 리빌드.<br><br>
  - ASAP-Updater, Breeze, Daybreak, DBI, EdiZon-SE, Haze, HB-appstore, Hekate-Toolbox, ldnmitm config,<br>Linkalho, NX-Activity-Log, Tinfoil, Reboot2payload, vgedit+<br><br>
  - Tesla-menu, ovlloader, ovlsysmodules, FPSLocker, NX-FPS, ReverseNX-RT, emuiibo, ldn mitm, EdiZon, QuickNTP, Status-Monitor, sys-clk-OC<br><br>
- 홈브류 메뉴 시간표기 오류 수정.<br><br>
- 에디존-SE 한글화.<br><br>
- 시스모듈/오버레이 전부 한글화 - ASAP에서만 한글 적용 / 기타 올인원에서 한글 깨짐. 
  
<br><br>

ASAP-Updater 설명서
=====
<details><summary>자세히 보기</summary>
   
![1](https://github.com/Asadayot/img/assets/89662125/6a8295a7-7651-4971-a481-a79e7c2d60b6)
![2](https://github.com/Asadayot/img/assets/89662125/befd8c53-a397-4f65-ba9e-13652c14dd2c)
![3](https://github.com/Asadayot/img/assets/89662125/6fbce7e7-20ef-4201-ac6e-a6477c95aa04)
![4](https://github.com/Asadayot/img/assets/89662125/705aba24-154e-458d-96f3-f931a3df4769)
![5](https://github.com/Asadayot/img/assets/89662125/c4f5bbf0-92f5-4d45-9b07-c73ebe357519)
![6](https://github.com/Asadayot/img/assets/89662125/39b7ee13-6d66-48c3-9b57-9c61b66ff604)
![7-1](https://github.com/Asadayot/img/assets/89662125/aacca1f4-0b03-4867-8b85-fef26a75ad80)
![7](https://github.com/Asadayot/img/assets/89662125/6f343fd2-0738-4bf7-89ce-cbfd82944b52)
![7-2](https://github.com/Asadayot/img/assets/89662125/014a2c68-9d41-4a21-b6d5-ebb0bb1f75a2)
![7-3](https://github.com/Asadayot/img/assets/89662125/fa7f100e-4f2f-4560-b5a5-53c346841d05)
![7-4](https://github.com/Asadayot/img/assets/89662125/bc9b2d7f-dd0d-4aa2-addf-5ab7916ea39f)
![7-5](https://github.com/Asadayot/img/assets/89662125/53b21940-0603-4be7-bc2d-aaf0ad73950e)
![8](https://github.com/Asadayot/img/assets/89662125/795590ea-edd0-4674-83df-cd4f2ad82525)
   
</details>
<br><br> 

설치 방법
=====
<details><summary>자세히 보기</summary>
  
![구분](https://github.com/Asadayot/img/assets/89662125/282ecad3-a9a5-49c5-a798-5208055afc7b)
<br>
- 위 이미지를 참고하여 ASAP-Updater에서 해당하는 사항을 다운로드하면 자동 설치를 진행합니다.  
- 자동 설치시 `emuMMC`, `Nintendo`, `contents` 및 폴더를 지정한 홈브류는 제거하지 않습니다.
- 또한 `prod.keys`, `title.keys`, `location.conf`, `JKSV SAVES`, `DBI SAVES` 등은 `backup` 폴더로 백업됩니다.
- 안드로이드, 리눅스 등의 기타 파티션이 존재할 경우 자동설치가 진행되지 않을 수 있습니다.
   - 이 경우 hekate_ipl.ini의 autoboot, autoboot_list 항목을 ASAP 업데이트로 맞춰주어야합니다. 
<br><br><br>
  
## ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
- 설치 전 홈브류 폴더 지정. `'sd:/switch/daybreak.nro' → 'sd:/switch/daybreak/daybreak.nro'` 
- [ASAP-updater.zip](https://github.com/Asadayot/ASAP/releases/latest) Latest를 내려받습니다.
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.
- 스위치를 커스텀 펌웨어로 기동 후, hbmenu `앨범+R+A` 진입, `ASAP-Updater`를 실행합니다.
- `ASAP 업데이트` `올인원 교체/추가설치` 항목에서 설치하고픈 올인원을 선택하여 다운로드합니다.
  - `ASAP 업데이트` 항목은 Asanosphère 와 Hekate 및 기본 홈브류의 설치/업데이트 메뉴이며 기종에 따른 불필요한 파일을 제거합니다.
  - `올인원 교체/추가설치` 항목의 `[ ASAP ]` 은 전기종 지원 마스터 패키징으로 테슬라, 시스모듈, 홈브류 등이 포함됩니다.
  - 처음 설치하거나 다른 올인원 팩에서 이주하는 경우 후자 설치를 권장합니다.   
- 다운로드 후, `A` 버튼 입력하여 재기동 하며 자동 설치를 진행합니다.
- hbmenu `앨범+R+A` → `DBI` - `Browse SD Card` → `nsp` → `hbmenu_[01E2044444AB9000][v0].nsp` 및 바로가기 설치.  
<br><br><br>

## ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
- [Install_Supporter.zip](https://github.com/Asadayot/ASAP/releases/latest) Latest를 내려받습니다.
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
  - 또는 디렉토리를 `sd:/` 최상위 경로로 모두 붙여넣습니다.
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
- `ASAP 업데이트` `올인원 교체/추가설치` 항목에서 설치하고픈 올인원을 선택하여 다운로드합니다.
  - `ASAP 업데이트` 항목은 Asanosphère 와 Hekate 및 기본 홈브류의 설치/업데이트 메뉴이며 기종에 따른 불필요한 파일을 제거합니다.
  - `올인원 교체/추가설치` 항목의 `[ ASAP ]` 은 전기종 지원 마스터 패키징으로 테슬라, 시스모듈, 홈브류 등이 포함됩니다.
  - 처음 설치하거나 다른 올인원 팩에서 이주하는 경우 후자 설치를 권장합니다. 
- 다운로드 후, `A` 버튼 입력하여 재기동 하며 자동 설치를 진행합니다.
- hbmenu `앨범+R+A` → `DBI` - `Browse SD Card` → `nsp` → `hbmenu_[01E2044444AB9000][v0].nsp` 및 바로가기 설치.     
<br><br><br>
  
## ⬦ 이용 중 알 수 없는 충돌이 발생할 시
  - ASAP은 홈브류와 시스모듈을 제거하지 않고 커펌 파일만 교체하는 업데이트를 진행합니다.<br>시스모듈 혹은 테마가 존재할 경우 업데이트 이후 기동 시 에러가 발생 수 있습니다.<br>이 때에는 시스모듈, 테마 제거 혹은 헤카테 `도구` → `아카이브 비트 수정` 을 진행하여야 정상적으로 부팅할 수 있습니다.<br>
  - Hekate×ASAP→기타런처or페이로드→`ASAP-Cleaner` 선택하여 ASAP을 `Install Supporter` 상태로 되돌립니다.<br>이 작업은 Nintendo, emummc 폴더, 개인파일, backup 폴더, 홈브류를 제외한 거의 모든 파일을 삭제 및 초기화합니다.
<br><br><br>
  
## ⬦ 추가 사항 설치 / 올인원 이주
- ASAP 설치 완료 후 ASAP-Updater를 통해 개인 기호에 따라 추가 파일을 설치합니다.
  - `추가 구성 다운로드` → 해당 사항 다운로드.
  - `올인원 교체/추가설치` → 시그패치, 홈브류, 시스모듈 선택 설치.
- ASAP-Updater를 통해 기타 올인원 팩으로 쉽고 간편하게 이주할 수 있습니다.
  - `올인원 교체/추가설치` → 순정 ATMO & Hekate, ASAP 풀패키징, KEFIR, HATS, Deepsea 선택 자동 설치 및 이주.
<br><br><br> 
   
## ⬦ ASAP-Updater 커스텀 링크 추가 
   `올인원 교체/추가설치` → `커스텀 링크` 선택 혹은 `sd:/config/Asano-updater/ASAP_packs.json` 에서 링크 연결
```
 {
    "home": {
        "[ 이름 ] 설명": "https://link_to_zip"
    },    
    "sys": {
        "[ 이름 ] 설명": "https://link_to_zip"
    }
}  
```   
   
</details>
<br><br>

업데이트 방법
=====
<details><summary>자세히 보기</summary>
  
## ⬦ 업데이트 순서에 대하여...
- 퓨즈가 연소되는 메이저 업데이트의 경우, 특정기기에서 많은 오류를 동반할 수 있으니 다음을 숙지하세요.
1. HOS 버전과 대응하는 CFW(ASAP)를 `ASAP-Updater` → `ASAP 업데이트`에서 우선적으로 업데이트.
2. 헤카테 `홈` → `재부팅` → `정펌` → `설정-본체-본체 업데이트`
 - Hwfly 모드칩의 경우 정펌에서 직접 업데이트할 경우 딥 슬립되어 정펌으로만 부팅 혹은 블랙스크린을 동반할 수 있습니다.
   - 방법 1. 헤카테 `런처` → `HOS (웜부트 오류 수정)` → `설정-본체-본체 업데이트`
   - 방법 2. 헤카테 `런처` → `Asanosphère (시스낸드)` → `ASAP-Updater` → `Horizon OS 업데이트` → `Daybreak`
3. Asanosphère (시스/에뮤낸드), (에뮤낸드) 를 통한 에뮤낸드 커펌 기동 후 `ASAP-Updater` → `Horizon OS 업데이트` → `Daybreak`
<br><br><br>

## ⬦ Hwfly 모드칩 펌웨어 업데이트
  - `추가 구성 다운로드` → `[ Hwfly ] 펌웨어` 다운로드<br><br>헤카테 진입 → 추가런처 or 페이로드 → Hwfly 툴박스 or Hwfly_Toolbox.bin 선택 → sdloader/Update 선택 → 전원종료<br>→ + 볼륨버튼 누르며 전원버튼 입력 → 모드칩 초록색 LED 점멸 확인 → 페이로드 → 추가런처 or 페이로드<br>→ Hwfly 툴박스 or Hwfly_Toolbox.bin 선택 → Firmware/Update 선택 → 재부팅 후 버전 확인.
<br><br><br> 
  
## ⬦ PiCoFly 모드칩 펌웨어 업데이트
  ※이 방법은 2.6 이상 펌웨어에서만 가능하며 2.5번대 펌웨어는 USB 연결을 통한 직접 플래시가 필요합니다.※<br>
  - `추가 구성 다운로드` → `[ PiCoFly ] 펌웨어` 다운로드<br><br>헤카테 진입 → 추가런처 or 페이로드 → PiCoFly 툴박스 or PiCoFly_Toolbox.bin 선택 → sdloader/Update 선택 → Firmware/Update 선택 → 재부팅 후 버전 확인.
  - LED 인디케이터 및 2.7 이상 펌웨어 안정화 회로도 제공<br>
     <details><summary>자세히 보기</summary>
   
     ![제목 없음-6](https://github.com/Asadayot/img/assets/89662125/63ca1b02-ac95-453f-b9a9-e00848e5d8b2)
   
     </details>
  
</details>   
<br><br>

기본 제공 / 변경 로그
=====
<details><summary>자세히 보기</summary>
<br>
### ⬦ CFW & 부트로더

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [Asanosphère](https://github.com/Asadayot/Asanosphere) | HOS｜ASAP1.5.4-0531｜S/E | - 커스텀 펌웨어<br>- exosphere 경로 변경 : `sd:/atmosphere/config`<br>- config 폴더의 .ini 파일 한글 부연 설명 추가(주석)<br>- 시리얼 변조 코드 변경 : `XAW` → `XAJ`(유럽/일본) |
| [Hekate×ASAP](https://github.com/Asadayot/hekate) | 6.0.4 & 1.5.3 × 0531 | - ASAP 전용 올인원 부트로더<br>- 한글화<br>- 스크린샷 덤프 경로 변경: `sd:/backup/screenshots`<br>- 기타 덤프 경로 변경 : `sd:/backup` |
| Boot.dat<br>Boot.ini | 1.1 | - SXOS / 모드칩 SX펌웨어 전용 필수 로더 및 설정 |
<br>
### ⬦ 홈브류 메뉴/로더

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [nx-hbmenu](https://github.com/Asadayot/nx-hbmenu) | 3.5.1 | - 홈브류 메뉴<br>- 한글화<br>- 고정 경로 변경: `sd:/atmosphere/hb` |
| [nx-hbloader](https://github.com/Asadayot/nx-hbloader) | 2.4.3 | - 홈브류 로더<br>- 한글화<br>- 고정 경로 변경: `sd:/atmosphere/hb` |
<br>
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
<br>
### ⬦ 시그패치
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- |  
| Signature Patches | 0531 | - ASAP 전용 [63ea152](https://github.com/Asadayot/Asanosphere) & [937ab53](https://github.com/Asadayot/hekate) 기반 시그패치 |  
<br>
### ⬦ Warmboot Mariko 캐시

| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- |  
| wb_0c.bin<br>wb_0d.bin<br>wb_0e.bin<br>wb_0f.bin<br>wb_10.bin<br>wb_11.bin<br>wb_12.bin | 9.1.0 ~ 9.2.0 지원<br>10.0.0 ~ 10.2.0 지원<br>11.0.0 ~ 12.0.1 지원<br>12.0.2 ~ 13.1.0 지원<br>13.2.1 ~ 14.1.2 지원<br>15.0.0 ~ 15.0.1 지원<br>16.0.0 ~ 16.0.3 지원 | - HOS 16.0.3 까지 정펌 및 HOS(Warmboot Error Fix)의 필수 기동 필요없음 |
<br>
### ⬦ 홈브류 (기본 설치)
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [ASAP-Updater](https://github.com/Asadayot/ASAP/releases) | 2.22.0_fix5 | - ASAP, HOS, Homebrew, Sysmodule, etc. 업데이터<br>- 바로가기 NSP 설치 파일 제공 |
| [Daybreak](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) HOS 업데이터 홈브류  | 
| [Reboot2payload](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) 구형 전용 페이로드 재부팅 홈브류 | 
| [Haze](https://github.com/Asadayot/Asanosphere) | 1.0.0 | - [Asanosphère](https://github.com/Asadayot/Asanosphere) PTP/MTP USB 전송 홈브류 | 
| [DB Installer](https://github.com/rashevskyv/dbi) | 576 | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 | 
| [Hekate-Toolbox](https://github.com/Asadayot/Hekate-Toolbox) | 4.0.3 | - 타이틀 오버라이드, 페이로드 재부팅 설정 홈브류<br>- 모드칩 기기 전용 페이로드 재부팅 홈브류<br>- 한글화 | 
| [Tinfoil](https://github.com/Asadayot/NX-Activity-Log) | 16.0 [v2] | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 | 
| [Tesla menu](https://github.com/Asadayot/Tesla-Menu) | 1.2.3 | - 테슬라 오버레이 메뉴<br>- 한글화 | 
| [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) | 1.3.1 | - 테슬라 시스모듈 오버레이<br>- 한글화 |
| [HB-appstore](https://github.com/Asadayot/hb-appstore) | 2.3.2 | - 홈브류, 시스모듈, 오버레이 앱 스토어<br>- 한글화 |
| [JKSV](https://github.com/Asadayot/JKSV) | 2023.05.23 | - 세이브 데이터 관리 홈브류<br>- 매끄럽게 재번역 및 언어 고정<br>- 바로가기 NSP 설치 파일 제공 |
| [Linkalho](https://github.com/Asadayot/linkalho) | 2.0.2 | - 닌텐도 어카운트 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) | 1.5.0 | - 활동 기록 관리 홈브류<br>- 매끄럽게 재번역 및 언어 고정<br>- 바로가기 NSP 설치 파일 제공 |
| [vgedit](https://github.com/Asadayot/vgedit) | 2.2 | - 텍스트 파일 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [ldnmitm config](https://github.com/Asadayot/ldn_mitm) | 1.1.3 | - LAN 플레이 관리 홈브류 |
| [ldn_mitm](https://github.com/Asadayot/ldn_mitm) | 1.15.0 | - LAN 플레이 관리 오버레이<br>- 한글화 | 
| [emuiibo](https://github.com/Asadayot/emuiibo) | 1.0.0 | - 가상 아미보 관리 오버레이<br>- 한글화 |
| [Edizon-SE](https://github.com/Asadayot/EdiZon-SE/releases) | 3.8.37 | - 치트 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [EdiZon-Overlay](https://github.com/Asadayot/EdiZon-Overlay) | 1.0.5 | - 치트 관리 오버레이<br>- 한글화 |
| [MissionControl](https://github.com/Asadayot/MissionControl) | 0.9.2 | 타사 컨트롤러 무선 지원 시스모듈 |
| [QuickNTP](https://github.com/Asadayot/QuickNTP) | 1.2.8 | - 네트워크 시간 설정 오버레이<br>- 한글화<br>- 한국 시간대 기본 템플릿에 추가 |
| [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) | 1.1.1 | 리얼타임 모드 변환 오버레이<br>- 한글화 |
| [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) | 0.9.1 | - 상태 모니터 확인 오버레이<br>- 한글화 |
| [Switch-OC-Suite](https://github.com/Asadayot/Switch-OC-Suite) | 2023.05.31 | 오버클럭 관리 오버레이<br>- 한글화 |
| [sys-con](https://github.com/cathery/sys-con) | 0.6.4 | - 타사 컨트롤러 유선 지원 시스모듈 |
| [SaltyNX](https://github.com/Asadayot/SaltyNX) | 0.6.0 | 파일/코드 관리<br>- 한글화 |  
| [FPSLocker](https://github.com/Asadayot/FPSLocker) | 1.2.3 | FPS 관리 오버레이<br>- 한글화 |

### ⬦ 테슬라 & 홈브류 & 시스모듈 (선택 설치-재부팅 필요)
  
| 대상 | 버전 | 설명 or 변경사항 |
| ----- | ----- |  ----------------------------------------- | 
| [Tesla menu](https://github.com/Asadayot/Tesla-Menu) | 1.2.3 | - 테슬라 오버레이 메뉴 |  
| [ovl-sysmodules](https://github.com/Asadayot/ovl-sysmodules) | 1.3.1 | - 테슬라 시스모듈 오버레이 |
| [DB Installer](https://github.com/rashevskyv/dbi) | 576 | - 파일 전송, 설치 및 추가기능 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [HB-appstore](https://github.com/fortheusers/hb-appstore) | 2.3.2 | - 홈브류, 시스모듈, 오버레이 앱 스토어 |
| [JKSV](https://github.com/Asadayot/JKSV) | 23.02.2023 | - 세이브 데이터 관리 홈브류 |
| [Linkalho](https://github.com/Asadayot/linkalho) | 2.0.1 | - 닌텐도 어카운트 관리 홈브류 |
| [NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) | 1.4.0 | - 활동 기록 관리 홈브류 |
| [vgedit](https://github.com/Asadayot/vgedit) | 2.1 | - 텍스트 파일 관리 홈브류 |
| [ldnmitm config](https://github.com/Asadayot/ldn_mitm) | 1.1.3 | - LAN 플레이 관리 홈브류 |
| [ldn_mitm](https://github.com/Asadayot/ldn_mitm) | 1.15.0 | - LAN 플레이 관리 오버레이 |  
| [sys-clk manager](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 홈브류 |
| [sys-clk manager](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 홈브류<br>- 한글화<br>- 바로가기 NSP 설치 파일 제공 |
| [RetroArch](https://www.retroarch.com/) | 1.15.0 | - 콘솔 에뮬레이터 홈브류<br>- 바로가기 NSP 설치 파일 제공 |
| [emuiibo](https://github.com/Asadayot/emuiibo) | 1.0.0 | - 가상 아미보 관리 오버레이 |
| [Edizon](https://github.com/WerWolv/EdiZon) | 3.1.0 | - 치트 관리 홈브류 |
| [Edizon-SE](https://github.com/tomvita/EdiZon-SE/releases) | 3.8.37 | - 치트 관리 홈브류 |
| [EdiZon-Overlay](https://github.com/proferabg/EdiZon-Overlay) | 1.0.5 | - 치트 관리 오버레이 |
| [MissionControl](https://github.com/ndeadly/MissionControl) | 0.9.2 | 타사 컨트롤러 무선 지원 시스모듈 |
| [QuickNTP](https://github.com/Asadayot/QuickNTP) | 1.2.8 | - 네트워크 시간 설정 오버레이 |
| [Status-Monitor-Overlay](https://github.com/Asadayot/Status-Monitor-Overlay) | 0.9.1 | - 상태 모니터 확인 오버레이 |
| [sys-clk](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 오버레이<br>- 한글화 |
| [sys-clk](https://github.com/Asadayot/sys-clk) | 1.0.3 | - 오버클럭 관리 오버레이 |
| [Switch-OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite) | 1.5.3-v1.4 | 오버클럭 관리 오버레이 |
| [sys-con](https://github.com/cathery/sys-con) | 0.6.4 | - 타사 컨트롤러 유선 지원 시스모듈 | 
| [mGBA](https://github.com/mgba-emu/mgba) | 0.10.2 | GBA 콘솔 에뮬레이터 홈브류 |
| [NxThemesinstaller](https://github.com/exelix11/SwitchThemeInjector) | 2.7 | 스위치 테마 관리 홈브류 |   
| [SaltyNX](https://github.com/masagrator/SaltyNX) | 0.6.0 | 파일/코드 관리 |  
| [FPSLocker](https://github.com/masagrator/FPSLocker) | 1.2.3 | FPS 관리 오버레이 |  
   
</details>
<br><br>

ASAP 구성
=====
<details><summary>자세히 보기</summary>
<br>
  
### ⬦ ASAP은 마스터 폴더를 시드로 두고 선택한 기종에 따라 폴더 및 파일을 삭제하는 방식으로 설치됩니다.
  
| Folder/File                                | Description                            | 설치 대상     |
| ------------------------------------------ | -------------------------------------- | -------- |
| atmosphere                                 | Main folder                            | `ALL` |
| \|__ package3                              | Atmosphere                             | `ALL` |
| \|__ reboot_hekate.bin                     | Hekate payload                         | `지그/로더` `Master` |
| \|__ reboot_payload.bin                    | Atmosphere payload                     | `ALL` |
| \|__ stratosphere.romfs                    | stratosphere romfs                     | `ALL` |
| atmosphere/config/                         |                                        | `ALL` |
| \|__ exosphere.ini                         | PRODINIFO forgery config               | `ALL` |
| \|__ override_config.ini                   | hbmenu override config                 | `ALL` |
| \|__ stratosphere.ini                      | Cartridge Read config                  | `ALL` |
| \|__ system_settings.ini                   | Atmosphere System config               | `ALL` |
| atmosphere/contents/                       |                                        | `ALL` |
| \|__ 00FF0000636C6BFF/                     | sys-clk                                | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 054e4f4558454000/                     | PointerSearcher                        | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 0000000000534C56/                     | SaltyNX                                | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 010000000000bd00/                     | MissionControl                         | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 420000000007E51A/                     | Tesla                                  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 0100000000000352/                     | emuiibo                                | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 0100000000001013/                     | EdiZon Cheat Manager                   | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 010000000000000D/                     | SE-Tools                               | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 690000000000000D/                     | sys-con                                | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ 4200000000000010/                     | ldn_mitm                               | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| atmosphere/exfs_patches/                   |                                        | `ALL` |
| \|__ ASAP                                  | BootLogo patches                       | `ALL` |
| \|__ bluetooth_patches/                    | MissionControl patches                 | `Master` |
| \|__ btm_patches/                          | MissionControl patches                 | `Master` |
| \|__ es_patches/                           | Signature Patches                      | `ALL` |
| \|__ nfim_ctest/                           | Signature Patches                      | `ALL` |
| atmosphere/fatal_errors                    | Fatal error report                     | `ALL` |
| atmosphere/flags                           | Flags                                  | `ALL` |
| atmosphere/hb/                             |                                        | `ALL` |
| \|__ hbl.nsp                               | hbmenu loader                          | `ALL` |
| \|__ hbmenu.nro                            | hbmenu                                 | `ALL` |
| atmosphere/hbl_html/accessible-urls        |                                        | `ALL` |
| \|__ accessible-urls.txt                   | accessible URLs config                 | `ALL` |
| atmosphere/hosts/                          |                                        | `ALL` |
| \|__ emummc.txt                            | emuMMC dns config                      | `ALL` |
| atmosphere/kip_patches/                    |                                        | `ALL` |
| \|__ default_nogc/                         | nogc patches                           | `ALL` |
| \|__ fs_patches/                           | Signature Patches                      | `ALL` |
| \|__ loader_patches/                       | Signature Patches                      | `ALL` |
| atmosphere/kips                            |                                        | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ loader.kip                            | OverClock patches                      | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
|                                            |                                        |  |
| backup/                                    | Main folder / Backup created on update | `ALL` |
| \|__ keys/                                 | prod/title.keys, PRODINFO backup       | `ALL` |
| \|__ SaveData/                             | DBI, JKSV Saves backup                 | `ALL` |
| \|__ Tinfoil/                              | Tinfoil location.conf backup           | `ALL` |
|                                            |                                        |  |
| bootloader                                 | Main folder                            | `ALL` |
| \|__ hekate_ipl.ini                        | Hekate Launcher config INI             | `ALL` |
| \|__ patches.ini                           | Loader patches INI                     | `ALL` |
| \|__ update.bin                            | Hekate payload                         | `ALL` |
| bootloader/ini/                            |                                        | `ALL` |
| \|__ payloads.ini                          | Payloads Launcher INI                  | `기종별 구성 상이` |
| bootloader/payloads/                       |                                        | `ALL` |
| \|__ ASAP-Cleaner.bin                      | ASAP Reset payload                     | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ fusee.bin                             | Atmosphere payload                     | `ALL` |
| \|__ hwfly_toolbox.bin                     | Hwfly Toolbox payload                  | `Hwfly` |
| \|__ Lockpick_RCM.bin                      | Lockpick RCM payload                   | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ PiCoFly_HOS_Unlock.bin                | PiCoFly HOS Unlock Toolbox payload     | `Install Supporter` `Master` |
| \|__ PiCoFly_toolbox.bin                   | PiCoFly Toolbox payload                | `PiCoFly` |
| \|__ TegraExplorer.bin                     | TegraExplorer payload                  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| bootloader/res/                            |                                        | `ALL` |
| \|__ bootscreen/                           | Launcher Booting Image                 | `기종별 구성 상이` |
| \|__ icon/                                 | Launcher icon                          | `기종별 구성 상이` |
| \|__ backgraound.bmp                       | Hekate Background Image                | `ALL` |
| bootloader/sys/                            |                                        | `ALL` |
| \|__ l4t/                                  | LINUX for Tegra                        | `ALL` |
| \|__ emummc.kipm                           | emuMMC KIP1 module                     | `ALL` |
| \|__ libsys_lp0.bso                        | LP0 module                             | `ALL` |
| \|__ libsys_minerva.bso                    | Minerva Traning Cell                   | `ALL` |
| \|__ nyx.bin                               | Hekate GUI                             | `ALL` |
| \|__ res.pak                               | Nyx resource                           | `ALL` |
| \|__ thk.bin                               | Atmosphere TSEC Keygen                 | `ALL` |
|                                            |                                        |  |
| config/                                    | Main folder                            | `ALL` |
| \|__ Asano-assist/                         | ASAP assist config                     | `ALL` |
| \|__ MissionControl/                       | MissionControl config                  | `Master` |
| \|__ sys-clk-oc/                           | Switch-OC-Suite config                 | `Master` |
| \|__ sys-con/                              | sys-con config                         | `Master` |
|                                            |                                        |  |
| emuiibo/                                   | Main folder / emuiibo config           | `Master` |
|                                            |                                        |  |
| modchip_firmware/                          | Main folder                            | `Master` |
| \|__ Hwfly-OS/                             | Latest Hwfly Firmware, SDloader        | `Master` |
| \|__ PiCoFly-OS/                           | Latest PiCoFly Firmware,SDloader       | `Master` |
| \|__ INSTINCT-OS/                          | Latest INSTINCT Firmware               | `Master` |
|                                            |                                        |  |
| nsp/                                       | Main folder                            | `ALL` |
| \|__ ASAP-Updater_[01B88DD22E0D0000].nsp   | ASAP-Updater shortcut                  | `ALL` |
| \|__ DBI_[01ED1F4DEEA68000].nsp            | DBI shortcut                           | `ALL` |
| \|__ EdiZon_[016855715D498000].nsp         | Edizon shortcut                        | `ALL` |
| \|__ hbmenu_[01E2044444AB9000][v0].nsp     | hbmenu shortcut                        | `ALL` |
| \|__ Hekate-Toolbox_[010BD5E33025D000].nsp | Hekate-Toolbox shortcut                | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ JKSV_[01A3CFBEAE110000].nsp           | JKSV shortcut                          | `ALL` |
| \|__ Linkalho_[010D1B400E63F000].nsp       | Linkalho shortcut                      | `ALL` |
| \|__ Tinfoil_[050000BADDAD0000].nsp        | Tinfoil shortcut                       | `ALL` |
| \|__ vgedit_[01E993F41FB31000].nsp         | vgedit shortcut                        | `ALL` |
|                                            |                                        |  |
| SaltySD/                                   | Main folder / SaltyNX config           | `Master` |
|                                            |                                        |  |
| switch/                                    | Main folder                            | `ALL` |
| \|__ .overlays/                            | Sysmodule Overlays                     | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ appstore/                             | Homebrew, Sysmodule, Overlay store     | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ Asano-updater/                        | Asano-updater                          | `ALL` |
| \|__ breeze/                               | Cheats Manager                         | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ DBI/                                  | DBI                                    | `ALL` |
| \|__ EdiZon-SE/                            | Cheats Editor                          | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ Reboot2payload/                       | Reboot_to_payload                      | `Install Supporter` `지그/로더` `Master` |
| \|__ Hekate-Toolbox/                       | Hekate-Toolbox                         | `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ JKSV/                                 | JKSV                                   | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ ldnmitm_config/                       | ldn_mitm                               | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ Linkalho/                             | Linkalho                               | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ NX-Activity-Log/                      | NX-Activity-Log                        | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ NxThemesinstaller/                    | NxThemesinstaller                      | `Master` |
| \|__ Reboot2payload/                       | Reboot2payload                         | `지그/로더` `Master` |
| \|__ Tinfoil/                              | Tinfoil                                | `ALL` |
| \|__ vgedit/                               | vgedit                                 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
|                                            |                                        |  |
| warmboot_mariko/                           | Main folder / Mariko Warmboot cache    | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
|                                            |                                        |  |
| boot.dat                                   | SX data file                           | `Install Supporter` `지그/로더` `SX` `Master` |
| boot.ini                                   | SX INI config file                     | `Install Supporter` `지그/로더` `SX` `Master` |
| payload.bin                                | Hekate payload                         | `ALL` |
| unlock.bin                                 | PiCoFly HOS unlock file                | `Install Supporter` `Master` |
  
</details>
<br><br>

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
<br><br>

크레딧
=====
ASAP 을 구성하기 위해 이용한 멋진 팀 및 개발자들과 앱.
  
  - [Atmosphère-NX](https://github.com/Atmosphere-NX) :  Atmosphère, hbloader, hbmenu
  - [CTCaer](https://github.com/CTCaer) :  Hekate & Nyx
  - [ITotalJustice](https://github.com/ITotalJustice)
  - [suchmememanyskill](https://github.com/suchmememanyskill) :  TegraExplorer
  - [Team-Neptune](https://github.com/Team-Neptune) :  CPR, DeepSea
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
  - [masagrator](https://github.com/masagrator) :  Status-Monitor-Overlay, SaltyNX, FPSLocker, ReverseNX-RT
  - [sthetix](https://github.com/sthetix) :  HATS
  - [hanai3Bi](https://github.com/hanai3Bi) : Switch-OC-Suite
  - [mgba-emu](https://github.com/mgba-emu) : mGBA
  - [exelix11](https://github.com/exelix11) : NxThemesinstaller

