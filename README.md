# 🛡️ Screen Watermark - 사내 보안용 스크린 워터마크 시스템

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Tech](https://img.shields.io/badge/built%20with-C%23%20%7C%20WPF%20%7C%20API-lightgrey)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

> 🧩 사내 보안 강화를 위해 개발한 WPF 기반의 스크린 워터마크 프로그램입니다.

---

## 📌 프로젝트 개요

이 프로젝트는 **화면 캡처 방지 및 정보 유출 예방**을 목적으로 한 사내 보안 솔루션입니다.  
사용자의 화면에 실시간으로 워터마크(머신 이름, 사용자 이름, 현재 시간)를 표시하여,  
스크린샷 및 화면 공유 시 정보 노출을 방지합니다.

---

## ✨ 주요 기능

- 🖥️ **실시간 워터마크 표시**  
  머신 이름, 사용자 이름, 현재 시간을 모든 모니터 화면에 고정 표시

- 🔄 **멀티 모니터 지원**  
  모니터 추가/해제 이벤트를 감지하여 자동 적용

- 🔒 **예외 처리 시스템 연동**  
  특정 상황에서 워터마크를 임시로 제거할 수 있도록 Web API 연동 기반의 예외 처리 기능 제공

- 📢 **알림 피드백 기능**  
  예외 요청 처리 결과를 사용자에게 알림창으로 표시

---

## 🛠️ 사용 기술

- **C#**, **WPF (.NET)** – UI 및 멀티 모니터 대응 워터마크 오버레이 처리
- **Windows API** – 화면 상단 고정
- **멀티 모니터 대응** - 이벤트 감지
- **단일 인스턴스 보장** – 중복 실행 방지
- **REST API 연동** – 예외 요청 처리를 위한 Web API 통신

---

## 🖼️ 예시 화면

| 설명 | 이미지 |
|------|--------|
| ✅ 워터마크 적용된 바탕화면 | <img src="https://github.com/user-attachments/assets/ea222745-3f46-4e7d-a15c-a42dd6911d44" width="500"/> |
| 🌐 워터마크 적용된 웹 브라우저 | <img src="https://github.com/user-attachments/assets/560ed7f9-ff0d-4cce-861d-2826918a56d1" width="500"/> |
| 📝 예외처리 요청 폼 화면 | <img src="https://github.com/user-attachments/assets/bbb07caf-3c50-4653-a365-cb9600d0813b" width="500"/> |
| 📬 예외처리 완료 알림창 | <img src="https://github.com/user-attachments/assets/a7625bf2-f9b5-436b-919e-025ea0de0a15" width="500"/> |
| ❌ 워터마크 해제된 바탕화면  | <img src="https://github.com/user-attachments/assets/8f206296-e00e-41af-9443-1f9b0609b6cf" width="500"/> |
---

## 🧑‍💻 개발자

- **김태현**  
  Email: koip248@gmail.com

---
