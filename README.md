# SAMSUNG Galaxy Note 3 Neo, 4용 루팅 스크립트

## system.img에서 *.apk 추출
1. simg2img system.img system.img.ext4
1. ext2expore로 system.img 열기

## 루팅 순서
1. SamFirm을 통한 순정롬 다운로드 및 Odin으로 플래싱
1. USB 디버깅 활성화 후 종료
1. CF_Auto-Root 플래싱
1. SuperSU, Xposed 등 *.zip 플래싱 파일 복사
1. PhilzTouch 리커버리 플래싱
1. 리커버리 부팅 후 Xposed wanam 플래싱
1. 리커버리 부팅 후 PUA Killer 플래싱
1. 재부팅

## 알려진 문제
CraXicS_PUA_Killer_1.3.06.zip 플래싱 후 배틀그라운드, 영상통화 안 됨.

## 추가 제거 검토
1. PageBuddyNotiSvcK
1. SmartClipProvider
1. SmartClipServiceHLMR
