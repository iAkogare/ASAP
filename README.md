ASAP
=====
![Image of ASAP](https://user-images.githubusercontent.com/89662125/222437596-ec56021f-bbf4-4326-916b-8abaa23049cd.png)


- NX-Atmosphère 팀의 [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere)에서 분기한 [Asanosphère](https://github.com/Asadayot/Asanosphere)와 CTCaer 팀의 [Hekate](https://github.com/CTCaer/hekate)에서 분기한 [Hekate×ASAP](https://github.com/Asadayot/hekate)을 베이스로 한 초보자용 올인원 패키지입니다.

- ASAP 은 Asa's Switch All-in-one Package 의 약자로 As Soon As Possible (최대한 빠르게) 의 이중적 의미를 갖습니다.
- ASAP 에 기본 포함된 [Asanosphère](https://github.com/Asadayot/Asanosphere) & [Hekate×ASAP](https://github.com/Asadayot/hekate) 및 페이로드는 유기적인 관계로 이어져 있으며 기타 올인원과 혼합 사용시 이용하지 못하는 기능이 생기거나 치명적인 충돌이 일어날 수 있습니다, 혼합 사용을 피해주세요.
- 기본 포함 팩을 제외한 홈브류 및 페이로드는 위 내용과 관련이 없으니 자유로이 설치 및 사용하셔도 무방합니다.

<br><br>

· 새 버전(0610) 변경/개선 사항
=====

### ⬦ ASAP 추가 사항 
  - [Lineage OS](https://download.switchroot.org/) 설치파일/방법 추가: `Install_Supporter+android.zip`<br><br>
### ⬦ CFW/BOOTLOADER 업데이트
  - [Hekate×ASAP](https://github.com/Asadayot/hekate) ([0215d16](https://github.com/CTCaer/hekate) 커밋) - 6.0.5 & 1.5.4 업데이트, 오역 수정.
  - [Asanosphère](https://github.com/Asadayot/Asanosphere) ([8b88351](https://github.com/Atmosphere-NX/Atmosphere) 커밋) - 업데이트된 libnx를 통한 리빌드.<br><br>
### ⬦ 홈브류 업데이트
  - [ASAP-Updater](https://github.com/Asadayot/ASAP-updater) ([2519534](https://github.com/HamletDuFromage/aio-switch-updater) 커밋) - 2.22.0_2 업데이트.<br><br>
### ⬦ 시스모듈/오버레이 업데이트 
  - [Switch-OC-Suite](https://github.com/Asadayot/Switch-OC-Suite) ([266f014](https://github.com/hanai3Bi/Switch-OC-Suite) 커밋) - 1.5.3-v1.5.1 업데이트.
  - [FPSLocker](https://github.com/Asadayot/FPSLocker) ([42af8c5](https://github.com/masagrator/FPSLocker) 커밋) - 1.2.4 업데이트.
  - [NX-FPS](https://github.com/Asadayot/NX-FPS) ([b82e5cd](https://github.com/masagrator/NX-FPS) 커밋) - 1.5.4 업데이트.<br><br>
### ⬦ ASAP-Updater 추가 사항
  - 안드로이드 설치 파일 추가: [[ Lineage OS ]](https://download.switchroot.org/)
  - 올인원 교체 파일 업데이트: [ Hekate & Atmosphère ], [ ASAP ], [ HATS ]
  - ASAP 0610용 시그패치 추가.
  - 안드로이드용 hekate_ipl.ini 파일 추가.<br><br>
### ⬦ 홈브류 메뉴(애플릿/풀 메모리 모드) 진입 방법 변경
 - 0604 버전부터 홈브류 메뉴 진입 방법이 변경되었습니다.
 - 기존 설치 해놓은 `hbmenu_[01E2044444AB9000][v0].nsp` 바로가기는 기존대로 이용 가능합니다.
 - `앨범 + A버튼` 입력시 앨범 진입.
 - `앨범 + A버튼 홀드(길게 입력)`시 홈브류 메뉴(애플릿 모드) 진입.
 - `타이틀 + A버튼 홀드(길게 입력)`시 홈브류 메뉴(풀 메모리 모드 진입).

<br><br><br>

· 설치/업데이트 방법
=====

## ⬦ 설명문

<details><summary>자세히 보기</summary>
  
![구분](https://github.com/Asadayot/img/assets/89662125/282ecad3-a9a5-49c5-a798-5208055afc7b)
<br>
- 위 이미지를 참고하여 ASAP-Updater에서 해당하는 사항을 다운로드하면 자동 설치를 진행합니다.  
- 자동 설치시 `emuMMC`, `Nintendo`, `contents` 및 폴더를 지정한 홈브류는 제거하지 않습니다.
- 또한 `prod.keys`, `title.keys`, `location.conf`, `JKSV SAVES`, `DBI SAVES` 등은 `backup` 폴더로 백업됩니다.
- 안드로이드, 리눅스 등의 기타 파티션이 존재할 경우 자동설치가 진행되지 않을 수 있습니다.
   - 이 경우 hekate_ipl.ini의 autoboot, autoboot_list 항목을 ASAP 업데이트로 맞춰주어야합니다. 
<br><br><br>
  
### ⬦ 기존 커스텀 펌웨어 이용 유저의 경우
  
- 설치 전 홈브류 폴더 지정. 'sd:/switch/daybreak.nro' → 'sd:/switch/daybreak/daybreak.nro'<br><br>
- [ASAP-updater.zip](https://github.com/Asadayot/ASAP/releases/latest) Latest를 내려받습니다.<br><br>
- 압축 해제 후 디렉토리를 `sd:/` 최상위 경로로 붙여넣습니다.<br><br>
- 스위치를 커스텀 펌웨어로 기동 후, hbmenu `앨범+A 홀드` 진입, `ASAP-Updater`를 실행합니다.<br><br>
- `ASAP 업데이트`, `올인원 교체/추가설치` 항목에서 설치하고픈 올인원을 선택하여 다운로드합니다.
  - `ASAP 업데이트` 항목은 Asanosphère 와 Hekate 및 기본 홈브류의 설치/업데이트 메뉴이며 기종에 따른 불필요한 파일을 제거합니다.
  - `올인원 교체/추가설치` 항목의 `[ ASAP ]` 은 전기종 지원 마스터팩(개발자킷)으로 더 많은 시스모듈/오버레이, 홈브류 등이 포함됩니다.<br><br> 
- 다운로드 후, `A` 버튼 입력하여 재기동 하며 자동 설치를 진행합니다.<br><br>
- hbmenu `앨범+A 홀드` → `DBI` - `Browse SD Card` → `nsp` → `hbmenu_[01E2044444AB9000][v0].nsp` 및 바로가기 설치.<br><br> 
- 안드로이드를 설치합니다. (선택사항)
  
  <details><summary>자세히 보기</summary> 
  
  - `ASAP-Updater`→`올인원 교체/추가설치`→`[ Lineage OS ]` 선택 설치 후 헤카테로 재부팅.<br><br> 
  - `도구`→`eMMC 백업`→`에뮤낸드 RAW 파티션으로 전환 ON`→`emuMMC BOOT0 & BOOT1`→`닫기`→`emuMMC RAW GPP`→`닫기`→`닫기` 선택.<br><br> 
  - 스위치 PC와 연결 후 `USB 도구`→`backup, emuMMC, Nintendo 폴더 PC 백업 후 장치 꺼내기로 연결 해제`→`닫기`→`홈` 선택.<br><br> 
  - `Nyx 설정`→`조이콘 BT 덤프`→`확인`→`닫기` 순으로 선택 후 홈메뉴로 돌아갑니다.<br><br> 
  - `도구`→`SD 카드 파티션 분할`→`확인`→`에뮤낸드(RAW)-설정크기(파일기반 선택X)` + `안드로이드(USER)-8 ~ nn`<br>→`포맷 및 분할 계속`→`시작`→`전원버튼`→`안드로이드 플래시`→`계속`→`계속` 순으로 선택합니다.<br><br> 
  - `Factory reset`→`Format data/factory reset`→`Format data`→`Yes`<br>→`Format system partition`-`Yes`→`←` 순으로 선택합니다.<br><br> 
  - `Apply update`→`Choose from SWITCH SD`→`LineageOS_18.1_Android11.zip`→`Yes`<br>→`Choose from SWITCH SD`→`joycon-xbox.zip`→`Yes`→`←` 순으로 선택합니다.<br><br> 
  - `Reboot system now`→`런처`→`Lineage OS (안드로이드)` 부팅하여 안드로이드 초기 설정.<br><br> 
  - `도구`→`eMMC 복원`→`에뮤낸드 RAW 파티션으로 전환 ON`→`emuMMC BOOT0 & BOOT1`→`전원버튼`→`닫기`<br> →`emuMMC RAW GPP`→`전원버튼`→`닫기`→`닫기` 선택.<br><br> 
  - `홈`→`에뮤낸드`→`에뮤낸드 이주`→`RAW 수정 or 에뮤낸드`→`계속`→`확인` 선택.
  
  </details>  
<br><br><br>

### ⬦ 새 Micro SD Card 를 이용하여 설치하는 경우
  
- [Install_Supporter.zip](https://github.com/Asadayot/ASAP/releases/latest) Latest를 내려받습니다.<br><br>
- 압축 해제 후 `install.bat` 배치 파일을 실행합니다.<br><br>
  - Windows의 PC 보호 팝업창이 생성되면 추가정보 → 실행 선택 후, CMD 창의 안내에 따라 진행하세요.
  - 또는 디렉토리를 `sd:/` 최상위 경로로 모두 붙여넣습니다.<br><br>
- 닌텐도 온라인 가입자 설정을 진행합니다. (선택사항)
  - Hekate×ASAP으로 기동 하여 런치 메뉴로 진입, `HOS (웜부트 오류 수정)` 로 부팅합니다.
  - 설정→데이터 관리→저장 데이터 맡기기→온라인 가입자 선택→설정→저장 데이터 자동 백업/다운로드 OFF 순으로 설정합니다.
  - 설정→본체→소프트웨어 자동 업데이트 OFF→에러 정보 송신 OFF 순으로 설정합니다.<br><br>
- `파티션 기반` 에뮤낸드를 생성합니다. (선택사항)
  - Hekate×ASAP으로 진입합니다. 
  - 도구→SD 카드 파티션 분할→확인→에뮤낸드(RAW)-12 권장→포맷 및 분할 계속→시작→전원버튼→확인 순으로 선택하여 파티션을 분할합니다.
  - 홈메뉴로 돌아가 에뮤낸드→에뮤낸드 생성→파티션 기반→파티션 X 순으로 선택하여 자동 생성합니다.<br><br>
- `파일 기반` 에뮤낸드를 생성합니다. (선택사항) 
  - Hekate×ASAP으로 진입합니다. 
  - 도구→SD 카드 파티션→확인→포맷 및 분할 계속→시작→전원버튼→확인 순으로 선택하여 FAT32로 포맷합니다.
  - 홈메뉴로 돌아가 에뮤낸드→에뮤낸드 생성→파일 기반 순으로 선택하여 자동 생성합니다.<br><br>
- 다운로드 후, `A` 버튼 입력하여 재기동 하며 자동 설치를 진행합니다.<br><br>
- hbmenu `앨범+A 홀드` → `DBI` - `Browse SD Card` → `nsp` → `hbmenu_[01E2044444AB9000][v0].nsp` 및 바로가기 설치.<br><br>     
- `에뮤낸드` 및 `안드로이드`를 생성합니다. ([Install_Supporter+android.zip](https://github.com/Asadayot/ASAP/releases) 한정)
  
  <details><summary>자세히 보기</summary> 
    
  - [Install_Supporter+android.zip](https://github.com/Asadayot/ASAP/releases/latest) Latest를 내려받습니다.<br><br>
  - 압축 해제 후 `install.bat` 배치 파일을 실행합니다.<br><br>  
  - 런치 메뉴의 `Asanosphère (시스/에뮤낸드)`로 기동 후, hbmenu `앨범+A 홀드` 진입하여 ASAP-Updater를 실행합니다.<br><br>
  - `ASAP 업데이트`, `올인원 교체/추가설치` 항목에서 설치하고픈 올인원을 선택하여 다운로드합니다.<br><br>
  - 다운로드 후, `A` 버튼 입력하여 재기동 하며 자동 설치를 진행합니다.<br><br>
  - `Nyx 설정`→`조이콘 BT 덤프`→`확인`→`닫기` 순으로 선택 후 홈메뉴로 돌아갑니다.<br><br>
  - `도구`→`SD 카드 파티션 분할`→`확인`→`에뮤낸드(RAW)-12 권장(선택사항)` + `안드로이드(USER)-8 ~ nn`<br>→`포맷 및 분할 계속`→`시작`→`전원버튼`→`안드로이드 플래시`→`계속`→`계속` 순으로 선택합니다.<br><br>
  - `Factory reset`→`Format data/factory reset`→`Format data`→`Yes`<br>→`Format system partition`-`Yes`→`←` 순으로 선택합니다.<br><br>
  - `Apply update`→`Choose from SWITCH SD`→`LineageOS_18.1_Android11.zip`→`Yes`<br>→`Choose from SWITCH SD`→`joycon-xbox.zip`→`Yes`→`←` 순으로 선택합니다.<br><br>
  - `Reboot system now`→`런처`→`Lineage OS (안드로이드)` 부팅하여 안드로이드 초기 설정을 진행합니다.<br><br>
  - 헤카테로 재부팅하여 `에뮤낸드`→`에뮤낸드 생성`→`파일 기반 or 파티션 기반`→`파티션 X` 순으로 선택하여 자동 생성합니다.<br><br>
  - 런치 메뉴의 `Asanosphère (에뮤낸드)`로 기동 후, hbmenu `앨범+A 홀드` 진입하여 ASAP-Updater를 실행합니다.<br><br>
  - `추가 구성 다운로드`→`[ Lineage OS ]`를 선택 설치합니다.<br><br>
  - hbmenu `앨범+A 홀드` → `DBI` - `Browse SD Card` → `nsp` → `hbmenu_[01E2044444AB9000][v0].nsp` 및 바로가기 설치.  
    
  </details>
  <br>   
</details>
<br>  

## ⬦ 사진설명

<details><summary>자세히 보기</summary>

### - 설치 파일 다운로드

<details><summary>자세히 보기</summary>
  
![1](https://github.com/Asadayot/img/assets/89662125/57b8cd71-576c-44ad-a5ef-3edada848eb9)
![2](https://github.com/Asadayot/img/assets/89662125/4f4b4a5c-aefc-4c0d-af4c-b4b04380779a)
![3](https://github.com/Asadayot/img/assets/89662125/b0c48a49-c7eb-49bf-a029-e956df6316d4)

</details>

### - [선택사항] 저장 데이터 맡기기 해제

<details><summary>자세히 보기</summary>

![4](https://github.com/Asadayot/img/assets/89662125/4c3eb94e-4d41-411e-8639-9f42479a59a2)
![5](https://github.com/Asadayot/img/assets/89662125/0ca20400-8cd6-48ec-98fa-f8d0658bee16)
![6](https://github.com/Asadayot/img/assets/89662125/02c09056-3200-402f-8787-b1d71d98a9aa)
![7](https://github.com/Asadayot/img/assets/89662125/62a9dbbc-fefd-4658-bf88-902df16e919e)
![8](https://github.com/Asadayot/img/assets/89662125/f3c6349b-6d25-4974-8905-fc38667d70bf)
![9](https://github.com/Asadayot/img/assets/89662125/a32d5728-ef8f-4499-a4d4-ec7a24704366)
![10](https://github.com/Asadayot/img/assets/89662125/ed4dfd34-a2e5-4712-8381-8f3d66551b00)

</details>

### - [선택사항] 파티션 분할

<details><summary>자세히 보기</summary>

![11](https://github.com/Asadayot/img/assets/89662125/827350db-7f11-4538-8916-e7e9231eff14)
![12](https://github.com/Asadayot/img/assets/89662125/3489be89-6cdc-4b72-817a-a8834bb2b14d)
![13](https://github.com/Asadayot/img/assets/89662125/22e97403-8423-43ac-bfbd-c2ae9905831e)
![14](https://github.com/Asadayot/img/assets/89662125/23c8426b-d48c-450f-b3f6-5002b88f5b11)
![15](https://github.com/Asadayot/img/assets/89662125/2bb15377-c46b-4817-8921-ef0e21900e5e)
![16](https://github.com/Asadayot/img/assets/89662125/d397e1db-532f-4c62-b368-99a9db42ee7e)
![17](https://github.com/Asadayot/img/assets/89662125/d29fe66a-4ee6-428c-98fa-5e8c1ebb19e5)

</details>

### - [선택사항] 에뮤낸드 생성

<details><summary>자세히 보기</summary>

![18](https://github.com/Asadayot/img/assets/89662125/41f5c4b6-60df-4273-ae0d-ce0b9b7596f3)
![19](https://github.com/Asadayot/img/assets/89662125/8f8b7d7e-5799-4ac9-8011-a45da8070436)
![20](https://github.com/Asadayot/img/assets/89662125/1f817d41-b606-4548-930a-490c14531cd5)
![21](https://github.com/Asadayot/img/assets/89662125/c93c90ec-c806-4911-875c-5aa887addbfa)
![22](https://github.com/Asadayot/img/assets/89662125/08719236-979b-4dfd-9693-6d7a93121b17)

</details>

### - [선택사항] 정크파일 제거, 홈브류 바로가기

<details><summary>자세히 보기</summary>

![23](https://github.com/Asadayot/img/assets/89662125/6ad51e4d-557e-49d4-9a10-00651426d584)
![24](https://github.com/Asadayot/img/assets/89662125/d9190e89-38b3-4c31-b299-9119ef41feed)
![25](https://github.com/Asadayot/img/assets/89662125/bc1aee3d-e225-43d6-b656-76a5a9af5830)
![26](https://github.com/Asadayot/img/assets/89662125/e4460479-a622-48df-989c-78f9a5579cec)
![27](https://github.com/Asadayot/img/assets/89662125/9c79e66a-0431-4f95-a131-9a5acbd2756e)
![28](https://github.com/Asadayot/img/assets/89662125/10bfafd6-f82d-44bb-8d46-a7592a1b195f)
![29](https://github.com/Asadayot/img/assets/89662125/061cf04c-a2ba-4e92-bc9f-f8838a60fc72)
![30](https://github.com/Asadayot/img/assets/89662125/724c1afc-b43b-49a5-8837-efee5ab48328)
![31](https://github.com/Asadayot/img/assets/89662125/bc9aa4e1-36e5-4dcf-bc6a-dadfac47adac)
![32](https://github.com/Asadayot/img/assets/89662125/6672f9c8-140b-44d9-8601-f865878d5e03)
![33](https://github.com/Asadayot/img/assets/89662125/e2ab7d83-067a-4e10-ae86-56016e4f9995)
![34](https://github.com/Asadayot/img/assets/89662125/ba27e477-4c36-4f0e-b82c-2b2c8d1806e0)
![35](https://github.com/Asadayot/img/assets/89662125/4bd403a3-e8c3-474e-937d-8c30fd22cb44)
![36](https://github.com/Asadayot/img/assets/89662125/4bfa6ae4-a986-4b62-84b2-f87c532e0305)
![37](https://github.com/Asadayot/img/assets/89662125/11951b5c-732e-45b4-8a10-343e27ca7d27)
![38](https://github.com/Asadayot/img/assets/89662125/22ff381b-9b59-4367-a550-feae856e007d)
![39](https://github.com/Asadayot/img/assets/89662125/9fd8df97-eafb-47ea-b1a3-8a193f3e8155)
![40](https://github.com/Asadayot/img/assets/89662125/1c19751e-00d9-42c6-a80c-ea10d1fd5e74)
![41](https://github.com/Asadayot/img/assets/89662125/3e1a17c0-adea-4996-816a-902388ae93c4)
![42](https://github.com/Asadayot/img/assets/89662125/dc22a618-8db1-40f2-81f8-964252079679)
![43](https://github.com/Asadayot/img/assets/89662125/d4f63c98-5329-4823-b9eb-c8da76e8a205)

</details>

### - 설치 마무리/버전 업데이트

<details><summary>자세히 보기</summary>

![44](https://github.com/Asadayot/img/assets/89662125/6544f8bc-d77b-4023-8bfd-62e784c2092a)
![45](https://github.com/Asadayot/img/assets/89662125/b2a1eb37-a8d9-47b8-8cfb-2552baad2bc4)
![46](https://github.com/Asadayot/img/assets/89662125/bd87bf2e-2c7c-4712-92da-89442704d023)
![47](https://github.com/Asadayot/img/assets/89662125/52c10f63-de1f-44ac-85f6-e1c0cb220b2e)
![48](https://github.com/Asadayot/img/assets/89662125/f36dae48-77f0-4def-b347-587d6eba8283)
![49](https://github.com/Asadayot/img/assets/89662125/50816a95-a384-4e30-b390-caad4023427b)
![50](https://github.com/Asadayot/img/assets/89662125/b132545e-36a1-4cc1-a576-237ffb09a69e)
![51](https://github.com/Asadayot/img/assets/89662125/569b0632-3f01-4412-b9d7-bf6e452a2ae6)
![52](https://github.com/Asadayot/img/assets/89662125/08946f34-a79d-424b-92a7-573c3f4cfd9f)
![53](https://github.com/Asadayot/img/assets/89662125/01f262d4-01fe-4cea-8ce8-704d91091105)

</details>

### ⬦ ASAP 간단 설명

<details><summary>자세히 보기</summary>
  
![54](https://github.com/Asadayot/img/assets/89662125/d95d2c9f-85f2-4de9-93a4-d1daa6d5ede6)
![55](https://github.com/Asadayot/img/assets/89662125/283e6e67-85c3-428b-8212-80b3583d5ef6)
![56](https://github.com/Asadayot/img/assets/89662125/460fcf4c-0269-4948-af85-a6b7bdfd5ed0)
![57](https://github.com/Asadayot/img/assets/89662125/2a6776e9-ac47-422a-8d56-e2a7a1ee92de)
![58](https://github.com/Asadayot/img/assets/89662125/68364fb8-b57d-4567-bc18-d777b7288e37)

</details></details>
<br>

## ⬦ ASAP-Updater 설명서

<details><summary>자세히 보기</summary>
   
![1](https://github.com/Asadayot/img/assets/89662125/6a8295a7-7651-4971-a481-a79e7c2d60b6)
![2](https://github.com/Asadayot/img/assets/89662125/befd8c53-a397-4f65-ba9e-13652c14dd2c)
![3](https://github.com/Asadayot/img/assets/89662125/6fbce7e7-20ef-4201-ac6e-a6477c95aa04)
![4](https://github.com/Asadayot/img/assets/89662125/f85feeaa-3059-47ce-b4e9-79b2a99fdc2b)
![5](https://github.com/Asadayot/img/assets/89662125/c4f5bbf0-92f5-4d45-9b07-c73ebe357519)
![6](https://github.com/Asadayot/img/assets/89662125/39b7ee13-6d66-48c3-9b57-9c61b66ff604)
![7-1](https://github.com/Asadayot/img/assets/89662125/aacca1f4-0b03-4867-8b85-fef26a75ad80)
![7](https://github.com/Asadayot/img/assets/89662125/6f343fd2-0738-4bf7-89ce-cbfd82944b52)
![7-2](https://github.com/Asadayot/img/assets/89662125/014a2c68-9d41-4a21-b6d5-ebb0bb1f75a2)
![7-3](https://github.com/Asadayot/img/assets/89662125/fa7f100e-4f2f-4560-b5a5-53c346841d05)
![7-4](https://github.com/Asadayot/img/assets/89662125/bc9b2d7f-dd0d-4aa2-addf-5ab7916ea39f)
![7-5](https://github.com/Asadayot/img/assets/89662125/53b21940-0603-4be7-bc2d-aaf0ad73950e)
![8](https://github.com/Asadayot/img/assets/89662125/795590ea-edd0-4674-83df-cd4f2ad82525)

<br>
  
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
<br> 

## ⬦ 추가 사항 설치 / 올인원 이주

<details><summary>자세히 보기</summary>
  
- ASAP 설치 완료 후 ASAP-Updater를 통해 개인 기호에 따라 추가 파일을 설치합니다.
  - `추가 구성 다운로드` → 해당 사항 다운로드.
  - `올인원 교체/추가설치` → 시그패치, 홈브류, 시스모듈/오버레이 선택 설치.
- ASAP-Updater를 통해 기타 올인원 팩으로 쉽고 간편하게 이주할 수 있습니다.
  - `올인원 교체/추가설치` → 순정 ATMO & Hekate, ASAP 마스터팩, KEFIR, HATS, Deepsea 선택 자동 설치 및 이주.

</details>
<br><br>

· 업데이트 방법
=====
  
## ⬦ 업데이트 순서에 대하여...

<details><summary>자세히 보기</summary>
  
- 퓨즈가 연소되는 메이저 업데이트의 경우, 특정기기에서 많은 오류를 동반할 수 있으니 다음을 숙지하세요.
1. HOS 버전과 대응하는 CFW(ASAP)를 `ASAP-Updater` → `ASAP 업데이트` 혹은 `올인원 교체/추가설치`에서 우선적으로 업데이트.
2. 헤카테 `홈` → `재부팅` → `정펌` → `설정-본체-본체 업데이트`
 - Hwfly 모드칩의 경우 정펌에서 직접 업데이트할 경우 딥 슬립되어 정펌으로만 부팅 혹은 블랙스크린을 동반할 수 있습니다.
   - 방법 1. 헤카테 `런처` → `HOS (웜부트 오류 수정)` → `설정-본체-본체 업데이트`
   - 방법 2. 헤카테 `런처` → `Asanosphère (시스낸드)` → `ASAP-Updater` → `Horizon OS 업데이트` → `Daybreak`
3. Asanosphère (시스/에뮤낸드) 횩은 (에뮤낸드) 를 통한 에뮤낸드 커펌 기동 후 `ASAP-Updater` → `Horizon OS 업데이트` → `Daybreak`

</details>
<br>

## ⬦ SX · Spacecraft → Hwfly 펌웨어 이전

<details><summary>자세히 보기</summary>

- Hwfly 모드칩은 CORE, LITE, OLED 모두 제조 팩토리/스토어에 따라 SX, Spacecraft, Hwfly 중 펌웨어가 무작위 설치되어 판매됩니다.
- SX 펌웨어의 경우 SD카드 및 커펌 파일 없이 아무 동작도 할 수 없습니다.
- 이에 펌웨어 이전 방법을 소개합니다. https://asadayo.tistory.com/293 참고<br><br>

- 방법 1. 
  1. [Hwfly Firmware](https://github.com/hwfly-nx/firmware/releases) - release_072.zip 다운로드/압축해제 - PC 와 모드칩 USB 케이블 연결
  2. flash.bat 파일 실행
- 방법 2.
  1. [Hwfly Firmware](https://github.com/hwfly-nx/firmware/releases) - release_072.zip 다운로드/압축해제 - PC 와 모드칩 USB 케이블 연결
  2. release_072 폴더 주소창에 CMD 입력 후 엔터 - bootloaderupdater bootloader 엔터 - firmwareupdater firmware 엔터
  
</details>
<br>
  
## ⬦ Hwfly · PiCoFly 모드칩 펌웨어 업데이트

<details><summary>자세히 보기</summary>
  
### PiCoFly의 경우 2.6 이상 펌웨어에서만 가능하며, 2.5번 이하 펌웨어는 USB 연결을 통한 직접 플래시가 필요합니다.
   
![1](https://github.com/Asadayot/img/assets/89662125/6b04c305-c4ee-40c4-9792-3918d05f50c9)
![2](https://github.com/Asadayot/img/assets/89662125/e9619f33-3088-4254-9616-74de5c7b01b3)
![3](https://github.com/Asadayot/img/assets/89662125/2f2d4781-44b0-4b79-8a94-0abb7fef1cf2)

</details>
<br><br>
  
  
· 오류 관련
=====

<details><summary>자세히 보기</summary>
  
## ⬦ 홈브류 메뉴 ( 애플릿 모드 = 앨범 ) 에 갇히는 경우 - SaltyNX 오류
 - 홈브류 메뉴 ( 풀 메모리 모드 ) 실행 상태에서 홈브류 메뉴 ( 애플릿 모드 ) 를 중첩 기동 시 메모리 부족/충돌 오류로 앨범에 갇히게 됩니다.
 - SaltyNX 와 emuiibo 가 실행되고 있는 상태에서 홈브류 메뉴 ( 애플릿 모드 ) 를 기동 시 메모리 부족/충돌 오류로 앨범에 갇히게 됩니다.<br><br>
 - 이를 해결하기 위한 방법 4가지 (선택). 
   - 해결 방법 1. 테슬라 메뉴 진입 후 시스모듈 메뉴에서 SaltyNX 실행 중지합니다.
   - 해결 방법 2. 테슬라 메뉴 진입 후 시스모듈 메뉴에서 emuiibo의 실행을 중지, 자동 실행을 OFF로 설정 후 재부팅 합니다.
   - 해결 방법 3. SaltyNX와 관련된 모든 파일 (`SaltyNX module`, `SaltySD`, `FPSLocker`, `ReverseNX-RT`, `Status-Monitor`)을 제거합니다.
   - 해결 방법 4. emuiibo 와 관련된 모든 파일 (`emuiibo`, `emuiibo module`, `emuiibo overlay`)을 제거합니다.
<br><br><br>

## ⬦ 이용 중 알 수 없는 충돌이 발생할 시
  - ASAP은 홈브류, 시스모듈/오버레이를 제거하지 않고 커펌 파일만 교체하는 업데이트를 진행합니다.<br>시스모듈/오버레이 혹은 테마가 존재할 경우 업데이트 이후 기동 시 에러가 발생 수 있습니다.<br>이 때에는 시스모듈/오버레이, 테마 제거 혹은 헤카테 `도구` → `아카이브 비트 수정` 을 진행하여야 정상적으로 부팅할 수 있습니다.<br><br>
  - Hekate×ASAP→기타런처or페이로드→`ASAP-Cleaner` 선택하여 ASAP을 `Install Supporter` 상태로 되돌립니다.<br>이 작업은 Nintendo, emummc 폴더, 개인파일, backup 폴더, 홈브류를 제외한 거의 모든 파일을 삭제 및 초기화합니다.
<br><br><br>

## ⬦ 모드칩 관련 LED 자가 진단표

### Hwfly 펌웨어
- Hwfly 모드칩과 관계없이 Hwfly 펌웨어에서만 적용되는 LED 진단표 입니다.
- SX 혹은 Spacecraft 펌웨어인 경우 LED 색상이 다르게 표기되므로 Hwfly 펌웨어로 이주를 추천합니다.

<details><summary>자세히 보기</summary>
  
![LED진단표](https://github.com/Asadayot/img/assets/89662125/02f47cf4-7eeb-4e40-877e-4bdc973d5a63)

</details>       
<br>  
  
### PiCoFly 펌웨어

<details><summary>자세히 보기</summary>
  
![4](https://github.com/Asadayot/img/assets/89662125/cd571be2-756e-4f43-acb9-18514db2e9aa)     

</details></details>       
<br><br>

· ASAP 기본 구성
=====

<details><summary>자세히 보기</summary>
  
| 폴더/파일 | 해설 | 최신 버전 | 설치 대상 |
| -------- | -------- | -------- | -------- |
| atmosphere                                 |  |  | `ALL` |
| \|__ [package3](https://github.com/Asadayot/Asanosphere) | 아트모스피어 | 1.5.4 | `ALL` |
| \|__ [reboot_hekate.bin](https://github.com/Asadayot/hekate) | (한글화) 헤카테 페이로드 | 6.0.5 | `지그/로더` `Master` |
| \|__ [reboot_payload.bin](https://github.com/Asadayot/Asanosphere) | 아트모스피어 페이로드 | 1.5.4 | `ALL` |
| \|__ [stratosphere.romfs](https://github.com/Asadayot/Asanosphere) | 스트라토스피어 romfs | 1.5.4 | `ALL` |
| /config/                                   |  |  | `ALL` |
| \|__ [exosphere.ini](https://github.com/Asadayot/ASAP) | (한글 주석) PRODINIFO(CAL0) 시리얼 넘버 변조 설정 |  | `ALL` |
| \|__ [override_config.ini](https://github.com/Asadayot/ASAP) | 홈브류 메뉴 오버라이드 설정 |  | `ALL` |
| \|__ [stratosphere.ini](https://github.com/Asadayot/ASAP) | (한글 주석) 카트리지 읽기/인식 설정 |  | `ALL` |
| \|__ [sys-patche_config.ini](https://github.com/Asadayot/sys-patch) | (한글 주석) 시스템 패치(시그패치 대용) 설정 |  | `ALL` |
| \|__ [system_settings.ini](https://github.com/Asadayot/ASAP) | (한글 주석) 아트모스피어/오버클럭 설정 |  | `ALL` |
| /contents/                                 |  |  | `ALL` |
| \|__ /[00FF0000636C6BFF](https://github.com/Asadayot/Switch-OC-Suite) | sys-clk(Switch-OC-Suite) 모듈 | 1.5.3-v1.5.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ /[054e4f4558454000](https://github.com/tomvita/Noexes) | Noexes 모듈 | 1.4.157 | `Master` |
| \|__ /[0000000000534C56](https://github.com/Asadayot/SaltyNX) | SaltyNX 모듈 | 0.6.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ /[010000000000bd00](https://github.com/Asadayot/MissionControl) | MissionControl 모듈 | 0.9.2 | `Master` |
| \|__ /[420000000007E51A](https://github.com/Asadayot/Tesla-Menu)| Tesla 모듈 | 1.2.3 | `Install Supporter` `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ /[010000000000000D](https://github.com/tomvita/SE-tools) | SE-Tools 모듈 | 1.5 | `Master` |  
| \|__ /[0100000000000352](https://github.com/Asadayot/emuiibo) | emuiibo 모듈 | 1.0.0 | `Master` |
| \|__ /[0100000000001013](https://github.com/Asadayot/EdiZon-Overlay) | EdiZon 치트 매니저 모듈 | 1.0.5 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ /[420000000000000B](https://github.com/Asadayot/sys-patch) | sys-patch 모듈 | 1.4.2 | `Install Supporter` `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ /[690000000000000D](https://github.com/Asadayot/sys-con) | sys-con 모듈 | 0.6.4 | `Master` |
| \|__ /[4200000000000010](https://github.com/Asadayot/ldn_mitm) | ldn_mitm 모듈 | 1.15.0 | `Master` |
| /exfs_patches/                             |  |  | `ALL` |
| \|__ /[ASAP](https://github.com/Asadayot/ASAP) | 부팅 로고 패치 | 0610 | `ALL` |
| \|__ /[bluetooth_patches](https://github.com/Asadayot/MissionControl) | MissionControl 블루투스 패치 | 0.9.2 | `Master` |
| \|__ /[btm_patches](https://github.com/Asadayot/MissionControl) | MissionControl btm 패치 | 0.9.2 | `Master` |
| /fatal_errors                              |  |  | `ALL` |
| /flags                                     |  |  | `ALL` |
| /hb/                                       |  |  | `ALL` |
| \|__ [hbl.nsp](https://github.com/Asadayot/nx-hbloader) | 홈브류 메뉴 로더 | 2.4.3 | `ALL` |
| \|__ [hbmenu.nro](https://github.com/Asadayot/nx-hbmenu) | (한글화) 홈브류 메뉴 | 3.5.1 | `ALL` |
| /hbl_html/accessible-urls/                 |  |  | `ALL` |
| \|__ accessible-urls.txt                   | 엑세스 가능 URL 설정 |  | `ALL` |
| /hosts/                                    |  |  | `ALL` |
| \|__ emummc.txt                            | emuMMC DNS 설정 |  | `ALL` |
| /kip_patches                               |  |  | `ALL` |
| /kips/                                     |  |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [loader.kip](https://github.com/Asadayot/Switch-OC-Suite) | Switch-OC-suite Kip 패치 | 1.5.3-v1.5.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| <br><br>                                   |  |  |  |
| backup                                     |  |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` | 
| /keys/                                     |  |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ prod.keys                             | PRODINFO 키모음 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ title.keys                            | 설치 타이틀 키모음 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` | 
| \|__ /automatic_backups/                   |  |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ XXX00000000000_BISKEYS.bin            | BISKEYS 모음 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| \|__ XXX00000000000_PRODINFO_00000000.bin  | PRODINFO 모음 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| /SaveData/                                 | JKSV 세이브 데이터 백업 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ /JKSV                                 | JKSV 세이브 데이터 백업 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |    
| \|__ /saves                                | DBI 세이브 데이터 백업 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| /screenchots                               | 헤카테, 페이로드 스크린샷 폴더 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /scripts                                   |  |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /Tinfoil                                   | 틴포일 location.conf 백업 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| <br><br>                                   |  |  |  |
| bootloader                                 |  |  | `ALL` |
| \|__ hekate_ipl.ini                        | 헤카테 런처 INI 설정 |  | `ALL` |
| \|__ patches.ini                           | 로더 패치 INI 설정 | 0610 | `ALL` |
| \|__ [update.bin](https://github.com/Asadayot/hekate) | (한글화) 헤카테 페이로드 | 6.0.5 | `ALL` |
| /ini/                                      |  |  | `ALL` |
| \|__ payloads.ini                          | 페이로드 런처 INI 설정 |  | `기종별 구성 상이` |
| /payloads/                                 |  |  | `ALL` |
| \|__ [ASAP-Cleaner.bin](https://github.com/Asadayot/CommonProblemResolver) | ASAP 초기화 페이로드 | 1.0.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [fusee.bin](https://github.com/Asadayot/Asanosphere) | 아트모스피어 페이로드 | 1.5.4 | `ALL` |
| \|__ [hwfly_toolbox.bin](https://github.com/Asadayot/hwfly-toolbox) | Hwfly Toolbox 페이로드 | 1.1.1 | `Hwfly` |
| \|__ Lockpick_RCM.bin                      | Lockpick RCM 페이로드 | 1.9.10 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [PiCoFly_HOS_Unlock.bin](https://gbatemp.net/threads/picofly-a-hwfly-switch-modchip.622701/) | PiCoFly HOS Unlock Toolbox 페이로드 | 0.1 | `Install Supporter` `Master` |
| \|__ [PiCoFly_toolbox.bin](https://gbatemp.net/threads/picofly-a-hwfly-switch-modchip.622701/) | PiCoFly Toolbox 페이로드 | 0.2 | `PiCoFly` |
| \|__ [TegraExplorer.bin](https://github.com/Asadayot/TegraExplorer) | TegraExplorer 페이로드 | 4.0.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /res/                                      |  |  | `ALL` |
| \|__ backgraound.bmp                       | 헤카테 바탕화면 이미지 |  | `ALL` |  
| \|__ /bootscreen                           | 런처 부팅 이미지 | 0610 | `기종별 구성 상이` |
| \|__ /icon                                 | 런처 아이콘 이미지 | 0610 | `기종별 구성 상이` |
| /sys/                                      |  |  | `ALL` |
| \|__ [emummc.kipm](https://github.com/Asadayot/emuMMC) | emuMMC KIP1 모듈 | 16.0.3 | `ALL` |
| \|__ [libsys_lp0.bso](https://github.com/Asadayot/hekate) | LP0 모듈 | 1.5.4 | `ALL` |
| \|__ [libsys_minerva.bso](https://github.com/Asadayot/hekate)  | 미네르바 트레이닝 셀 | 1.5.3 | `ALL` |
| \|__ [nyx.bin](https://github.com/Asadayot/hekate) | 헤카테 GUI | 1.5.4 | `ALL` |
| \|__ [res.pak](https://github.com/Asadayot/hekate) | 닉스 리소스 | 1.5.4 | `ALL` |
| \|__ [thk.bin](https://github.com/Asadayot/hekate) | 아트모스피어 TSEC 키젠 | 1.5.4 | `ALL` |
| \|__ /[l4t](https://github.com/CTCaer/hekate) | LINUX for Tegra | 1.5.4 | `ALL` |  
| <br><br>                                   |  |  |  |
| config                                     |  |  | `ALL` |
| /[Asano-assist](https://github.com/Asadayot/hekate) | ASAP assist 설정 | 0610 | `ALL` |
| /[MissionControl](https://github.com/Asadayot/MissionControl) | MissionControl 설정 |  | `Master` |
| /[sys-clk-oc](https://github.com/Asadayot/sys-patch) | Switch-OC-Suite 설정 |  | `Master` |
| /[sys-con](https://github.com/Asadayot/sys-con) | sys-con 설정 |  | `Master` |
| <br><br>                                   |  |  |  |
| emuiibo                                    |  |  | `Master` |
| /amiibo                                    | 아미보 폴더 |  | `Master` |
| /miis                                      | 미 폴더 |  | `Master` |  
| <br><br>                                   |  |  |  |
| modchip_firmware                           |  |  | `Master` |
| /[Hwfly-OS](https://github.com/hwfly-nx/firmware)| Hwfly 최신 펌웨어, SDloader | 0.7.2 | `Master` |
| /[PiCoFly-OS](https://gbatemp.net/threads/picofly-a-hwfly-switch-modchip.622701/) | PiCoFly 최신 펌웨어, SDloader | 2.74 | `Master` |
| /[INSTINCT-OS](https://drive.google.com/drive/folders/16A9lhFMS_zuNKO6AZEB2QH8XLo7skx86) | INSTINCT 최신 펌웨어 | 1.0 | `Master` |
| <br><br>                                   |  |  |  |
| nsp                                        |  |  | `ALL` |
| \|__ [ASAP-Updater_[01B88DD22E0D0000].nsp](https://github.com/Asadayot/ASAP) | ASAP-Updater 바로가기 설치 파일 |  | `ALL` |
| \|__ [DBI_[01ED1F4DEEA68000].nsp](https://github.com/Asadayot/ASAP) | DBI 바로가기 설치 파일 |  | `ALL` |
| \|__ [EdiZon_[016855715D498000].nsp](https://github.com/Asadayot/ASAP) | Edizon 바로가기 설치 파일 |  | `Master` |
| \|__ [hbmenu_[01E2044444AB9000][v0].nsp](https://github.com/Asadayot/ASAP) | hbmenu 바로가기 설치 파일 |  | `ALL` |
| \|__ [Hekate-Toolbox_[010BD5E33025D000].nsp](https://github.com/Asadayot/ASAP) | Hekate-Toolbox 바로가기 설치 파일 |  | `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [JKSV_[01A3CFBEAE110000].nsp](https://github.com/Asadayot/ASAP) | JKSV 바로가기 설치 파일 |  | `ALL` |
| \|__ [Linkalho_[010D1B400E63F000].nsp](https://github.com/Asadayot/ASAP) | Linkalho 바로가기 설치 파일 |  | `ALL` |
| \|__ [Tinfoil_[050000BADDAD0000].nsp](https://github.com/Asadayot/ASAP) | Tinfoil 바로가기 설치 파일 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [vgedit_[01E993F41FB31000].nsp](https://github.com/Asadayot/ASAP) | vgedit 바로가기 설치 파일 |  | `ALL` |
| <br><br>                                   |  |  |  |
| SaltySD                                    |  | 0.6.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ exceptions.txt                        | 예외 설정 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| \|__ [saltysd_core.elf](https://github.com/Asadayot/ReverseNX-RT) | slatysd_core 플러그인 | 0.6.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| /flags                                     | SaltyNX 로그 플래그 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /patches                                   | SaltyNX 패치 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` | 
| /plugins/                                  | SaltyNX 플러그인 |  | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [NX-FPS.elf](https://github.com/Asadayot/NX-FPS) | FPSLocker, Status-Monitor FPS 플러그인 | 1.5.4 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| \|__ [ReverseNX-RT.elf](https://github.com/Asadayot/ReverseNX-RT) | FPSLocker, ReverseNX-RT 플러그인 | 1.1.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |   
| <br><br>                                   |  |  |  |
| switch                                     |  |  | `ALL` |
| /.overlays/                                |  |  | `ALL` |  
| \|__ [ovlmenu.ovl](https://github.com/Asadayot/Tesla-Menu) | (한글화) 테슬라 메뉴 오버레이 | 1.2.3 | `ALL` | 
| \|__ [01.ovlSysmodules.ovl](https://github.com/Asadayot/ovl-sysmodules) | (한글화) 시스모듈 오버레이 | 1.3.1 | `ALL` |
| \|__ [02.ovlEdiZon.ovl](https://github.com/Asadayot/EdiZon-Overlay) | (한글화) 치트 매니저 오버레이 | 1.0.5 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [03.emuiibo.ovl](https://github.com/Asadayot/emuiibo) | (한글화) 가상 아미보 관리 오버레이 | 1.0.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [04.FPSLocker.ovl](https://github.com/Asadayot/FPSLocker) | (한글화) FPS 관리 오버레이 | 1.2.4 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [05.ldnmitm_config.ovl](https://github.com/Asadayot/ldn_mitm) | (한글화) LAN 플레이 설정 오버레이 | 1.15.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [06.QuickNTP.ovl](https://github.com/Asadayot/QuickNTP) | (한글화) 네트워크 시간 동기화 오버레이 | 1.2.8 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [07.ReverseNX-RT-ovl.ovl](https://github.com/Asadayot/ReverseNX-RT) | (한글화) ReverseNX-RT 오버레이 | 1.1.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [08.status-monitor-overlay.ovl](https://github.com/Asadayot/Status-Monitor-Overlay) | (한글화) 상태 모니터 오버레이 | 0.9.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [09.sys-clk-overlay.ovl](https://github.com/Asadayot/Switch-OC-Suite) | (한글화) Switch-OC-suite 오버레이 | 1.5.3-v1.5.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| \|__ [10.sys-patch-overlay.ovl](https://github.com/Asadayot/sys-patch) | (한글화) 시스템 패치 오버레이 | 1.4.2 | `ALL` |    
| /[appstore](https://github.com/Asadayot/hb-appstore) | (한글화) 시스모듈/오버레이, 홈브류 스토어 홈브류 | 2.3.2 | `Master` |  
| /[Asano-updater](https://github.com/Asadayot/ASAP-updater) | (한글화) 종합 CFW 관리 홈브류 | 2.22.0_2 | `ALL` |
| /[breeze](https://github.com/tomvita/Breeze-Beta) | 치트 관리 홈브류 | Beta 38 | `Master` |
| /[Daybreak](https://github.com/Asadayot/Asanosphere) | HOS 업데이트 홈브류 | 1.0.0 | `ALL` |  
| /[DBI](https://github.com/rashevskyv/dbi) | 유/무선 종합 파일 관리 홈브류 | 576 | `ALL` |
| /[EdiZon](https://github.com/Asadayot/EdiZon-SE) | (한글화) EdiZon-SE 램 치트 매니저 | 3.8.37 | `Master` |
| /[Haze](https://github.com/Asadayot/Asanosphere) | 유선 PTP/MTP 파일 관리 홈브류 | 1.0.0 | `ALL` |  
| /[Hekate-Toolbox](https://github.com/Asadayot/Hekate-Toolbox) | (한글화) 페이로드 리부트/오버라이드 관리 홈브류 |  | `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /[JKSV](https://github.com/Asadayot/JKSV) | (한글화) 세이브 데이터 관리 홈브류 | 2023.05.23 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /[ldnmitm_config](https://github.com/Asadayot/ldn_mitm) | LAN 플레이 관련 홈브류 | 1.1.1 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /[Linkalho](https://github.com/Asadayot/linkalho) | (한글화) 닌텐도 어카운트 관리 홈브류 | 2.0.2 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /[NX-Activity-Log](https://github.com/Asadayot/NX-Activity-Log) | (한글화) 활동 기록 관리 홈브류 | 1.5.0 | `지그/로더` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| /[NxThemesinstaller](https://github.com/exelix11/SwitchThemeInjector) | 테마 관리 홈브류 | 2.7 | `Master` |
| /[Reboot2payload](https://github.com/Asadayot/Asanosphere) | 페이로드 리부트 홈브류 | 1.0.1 | `Install Supporter` `지그/로더` `Master` |
| /[Tinfoil](https://tinfoil.io/) | 온/오프라인 파일관리 홈브류 | 16.0[v2] | `ALL` |
| /[vgedit](https://github.com/Asadayot/vgedit) | (한글화) 텍스트 편집 홈브류 | 2.2 | `Master` |
| <br><br>                                   |  |  |  |
| warmboot_mariko                            |  |  | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_0c.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 9.1.0 ~ 9.2.0 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` | 
| \|__ [wb_0d.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 10.0.0 ~ 10.2.0 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_0e.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 11.0.0 ~ 12.0.1 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_0f.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 12.0.2 ~ 13.1.0 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_10.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 13.2.1 ~ 14.1.2 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_11.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 15.0.0 ~ 15.0.1 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |
| \|__ [wb_12.bin](https://github.com/Asadayot/ASAP) | 마리코 웜부트 캐시 | 16.0.0 ~ 16.0.3 | `Install Supporter` `SX` `Hwfly` `PiCoFly` `Spacecraft/INSTINCT` `Master` |  
| <br><br>                                     |  |  |  |
| [boot.dat](https://github.com/Asadayot/ASAP) | SX data 파일 | 1.1 | `Install Supporter` `지그/로더` `SX` `Master` |
| [boot.ini](https://github.com/Asadayot/ASAP) | SX INI 설정 파일 | 1.1 | `Install Supporter` `지그/로더` `SX` `Master` |
| [payload.bin](https://github.com/Asadayot/hekate) | (한글화) 헤카테 페이로드 | 6.0.5 | `ALL` |
| [unlock.bin](https://gbatemp.net/threads/picofly-a-hwfly-switch-modchip.622701/) | PiCoFly HOS unlock 펌웨어 | ~2.5_unlock | `Install Supporter` |
  
</details>       
<br><br>
  
· 크레딧
=====
### ASAP 을 구성하기 위해 이용한 멋진 팀 및 개발자들과 앱.
 
| 개발팀/개발자 | 주요 | 페이로드 | 시스모듈 | 오버레이 | 홈브류 | 
| -------- | -------- | -------- | -------- | -------- | -------- |
| [CTCaer](https://github.com/CTCaer) | Hekate & Nyx | payload<br>update |  |  |  |
| [Atmosphère-NX](https://github.com/Atmosphere-NX) | Atmosphère | package3<br>fusee<br>reboot_payload |  |  | Daybreak<br>Haze<br>Reboot_to_payload |
| [switchbrew](https://github.com/switchbrew) |  | hbloader |  |  | hbmenu |
| [ITotalJustice](https://github.com/ITotalJustice) |  |  | sys-patch | sys-patch |  | 
| [shchmue](https://github.com/shchmue) |  | Lockpick RCM |  |  |  |
| [suchmememanyskill](https://github.com/suchmememanyskill) |  | TegraExplorer |  |  |  |
| [Team-Neptune](https://github.com/Team-Neptune) | DeepSea | CPR |  |  |  |
| [Ansem-SoD](https://github.com/Ansem-SoD) | PiCoFly | SDloader<br>PiCoFly Toolbox |  |  |  |
| [blawar](https://github.com/blawar) |  |  |  |  | tinfoil |
| [cathery](https://github.com/cathery) |  |  | sys-con |  |  |  
| [exelix11](https://github.com/exelix11) |  |  |  |  | NxThemesinstaller |
| [fortheusers](https://github.com/fortheusers) |  |  |  |  | hb-appstore |
| [HamletDuFromage](https://github.com/HamletDuFromage) |  |  |  |  | Aio-switch-updater |
| [hanai3Bi](https://github.com/hanai3Bi) |  |  | sys-clk-OC | Switch-OC-Suite |  | 
| [Hwfly-NX](https://github.com/hwfly-nx) | Hwfly | SDloader<br>Hwfly Toolbox |  |  |  | 
| [J-D-K](https://github.com/J-D-K) |  |  |  |  | JKSV |   
| [libretro](https://www.libretro.com) |  |  |  |  | RetroArch |  
| [masagrator](https://github.com/masagrator) |  |  | SaltyNX | FPSLocker<br>ReverseNX-RT<br>Status-Monitor |  |   
| [mgba-emu](https://github.com/mgba-emu) |  |  |  |  | mGBA |
| [nedex](https://github.com/nedex) |  |  |  | QuickNTP |  | 
| [ndeadly](https://github.com/ndeadly) |  |  | MissionControl |  |  | 
| [proferabg](https://github.com/proferabg) |  |  | Edizon | Edizon-Overlay |  | 
| [rashevskyv](https://github.com/rashevskyv) | KEFIR |  |  |  | DBI |   
| [rdmrocha](https://github.com/rdmrocha) |  |  |  |  | Linkalho | 
| [retronx-team](https://github.com/retronx-team) |  |  | sys-clk | sys-clk | sys-clk manager |
| [spacemeowx2](https://github.com/spacemeowx2) |  |  | ldnmitm | ldn-mitm | ldn_mitm config |   
| [sthetix](https://github.com/sthetix) | HATS |  |  |  |  |  
| [tallbl0nde](https://github.com/tallbl0nde) |  |  |  |  | NX-Activity-Log |   
| [tomvita](https://github.com/tomvita) |  |  | Noexes |  | breeze<br>Edizon-SE |  
| [thestr4ng3r](https://git.sr.ht/~thestr4ng3r/chiaki) |  |  |  |  | Chiaki |  
| [vgmoose](https://github.com/vgmoose) |  |  |  |  | vgedit |  
| [WerWolv](https://github.com/WerWolv) |  |  | Edizon<br>Tesla menu | ovlmenu<br>ovl-sysmodules | Edizon<br>Hekate-Toolbox | 
| [XorTroll](https://github.com/XorTroll) |  |  |  | emuiibo |  | 

