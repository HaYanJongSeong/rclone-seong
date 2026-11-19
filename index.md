---
layout: default
title: Rclone_Seong 안내
---

# Rclone_Seong

Rclone_Seong은 사용자가 자신의 Google Drive 파일을 관리하고 개인 설정을 백업하기 위해 사용하는 **개인용 rclone OAuth 앱**입니다. Google이나 rclone 프로젝트가 운영하는 공식 서비스가 아닙니다.

## 사용 목적

- 사용자가 지정한 파일과 폴더 목록 확인
- 사용자 요청에 따른 다운로드, 업로드 및 설정 백업
- 필요한 파일 작업을 사용자의 기기에서 실행

Google Drive 접근은 사용자가 Google 로그인 화면에서 권한을 허용한 뒤에만 가능합니다. 이 앱은 불특정 사용자를 대상으로 가입을 받는 공개 서비스가 아닙니다.

## 데이터 처리

파일 작업은 사용자의 기기에서 실행되는 rclone과 Google Drive API 사이에서 이루어집니다. 이 안내 사이트는 로그인 창이나 파일 업로드 기능을 제공하지 않으며, Google OAuth 토큰이나 Drive 파일을 받지 않습니다.

앱에 허용한 권한은 Google 계정 설정에서 언제든 해제할 수 있습니다. 권한 해제와 이미 Drive에 저장된 파일의 삭제는 별개입니다.

## 안내 및 문의

- [개인정보처리방침](privacy.html)
- [Google 계정의 외부 앱 연결 관리](https://myaccount.google.com/connections)
- [운영자에게 문의하기](https://github.com/HaYanJongSeong/rclone-seong/issues)
- [rclone Google Drive 문서](https://rclone.org/drive/)

문의할 때 비밀번호, OAuth JSON, 토큰 또는 개인 파일을 공개 이슈에 첨부하지 마세요.
