---
layout: default
title: Rclone_Seong 개인정보처리방침
---

# 개인정보처리방침

**앱 이름:** Rclone_Seong  
**적용일:** 2026년 11월 19일

[앱 안내로 돌아가기](./)

## 1. 운영 형태

Rclone_Seong은 사용자 본인이 자신의 기기에서 rclone을 실행하여 Google Drive 파일 작업을 수행하는 개인용 OAuth 앱입니다. 별도의 공개 회원가입 서비스나 Drive 파일을 수집하는 웹 서버를 운영하지 않습니다.

## 2. 접근하는 정보와 권한

Google 로그인과 동의를 통해 발급된 OAuth 토큰을 사용하여 Google Drive API에 접근합니다. 현재 사용하는 Drive 권한은 앱 데이터 폴더를 제외한 Drive 파일에 대한 접근을 허용할 수 있으므로, 사용자는 Google 동의 화면의 실제 권한 범위를 확인해야 합니다.

사용자가 지시한 작업에 따라 다음 정보를 처리할 수 있습니다.

- 파일·폴더의 이름, 식별자, 경로, 크기, 수정 시각 등 메타데이터
- 다운로드·업로드·복사·검증에 필요한 파일 내용
- Google API가 발급하는 접근 토큰과 갱신 토큰

허용된 API 권한과 실제로 수행하는 작업의 범위는 다릅니다. 이 앱은 사용자가 요청하거나 설정한 파일 관리·백업 작업을 수행하기 위한 용도로 사용됩니다.

## 3. 이용 목적과 제한

정보는 파일 조회·전송·백업·검증 및 인증 유지에 필요한 용도로 처리합니다. 광고, 판매 또는 범용 인공지능 모델 학습을 목적으로 Google 사용자 데이터를 수집하지 않습니다.

Google API를 통해 받은 정보의 이용 및 다른 앱으로의 전송에는 [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)의 Limited Use 요건을 포함한 해당 정책을 적용합니다. 이 문구는 Google의 검증이나 보안 인증을 받았다는 뜻이 아닙니다.

## 4. 저장·공유·보호

인증정보는 사용자의 기기에 보관합니다. 현재 운영 환경에서는 rclone 설정을 암호화하고 OAuth 원본과 설정 해독 암호를 age 암호문으로 보호하며 개인키를 분리 보관합니다. 같은 사용자 권한으로 기기와 개인키에 접근할 수 있는 프로세스까지 차단하는 방식은 아닙니다.

Drive에 저장한 파일은 사용자의 Google 계정과 Google Drive 설정에 따라 보관됩니다. 사용자가 전송 대상을 별도로 지정하지 않는 한 이 안내 사이트나 공개 GitHub 저장소에 Drive 파일·토큰·OAuth 비밀값을 업로드하지 않습니다.

Google Drive API 요청과 로그인은 Google이 처리합니다. 이 안내 사이트는 GitHub Pages에서 제공되므로 일반적인 웹 접속 정보의 처리는 [GitHub 개인정보처리방침](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)의 적용을 받을 수 있습니다. 이 사이트에는 자체 분석 스크립트, 광고 또는 파일 수집 기능을 넣지 않았습니다.

## 5. 보관 기간과 삭제

로컬 인증정보와 사용자가 만든 백업은 사용자가 유지하기로 한 동안 보관합니다. 사용자는 자신의 기기에서 인증정보와 백업을 삭제하거나 Google Drive에서 파일을 삭제할 수 있습니다.

[Google 계정의 외부 앱 연결 관리](https://myaccount.google.com/connections)에서 이 앱의 권한을 해제하면 이후 접근을 차단할 수 있습니다. 권한을 해제해도 기존에 저장된 파일이 자동 삭제되지는 않습니다. 삭제·권한 변경은 사용자의 명시적인 의사에 따라 진행합니다.

## 6. 문의와 변경 안내

운영자 문의는 [이 저장소의 이슈 페이지](https://github.com/HaYanJongSeong/rclone-seong/issues)를 이용할 수 있습니다. 공개 이슈에는 개인 파일, 비밀번호, OAuth JSON, 토큰을 올리지 마세요.

처리 방식이 달라지면 이 페이지를 수정하고 적용일을 갱신합니다.
