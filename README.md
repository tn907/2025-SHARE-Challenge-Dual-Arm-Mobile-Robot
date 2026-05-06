# 2025-SHARE-Challenge-Dual-Arm-Mobile-Robot
Award-winning dual-arm mobile robot project: mobility design, STM32 firmware, RTK-GNSS, and system troubleshooting


# 2025 SHARE Challenge - Dual-Arm Mobile Robot Portfolio

## 1. Project Overview
고위험 작업자를 대신해 원격으로 조작 가능한 양팔형 이동로봇을 개발한 프로젝트입니다.

## 2. Award
- 2025 CO-Show SHARE Challenge
- 한국연구재단 이사장상 수상
- 한국공학대학교 대표 출전

## 3. My Role
- 모빌리티 시스템 담당
- 무한궤도 기반 주행부 설계
- STM32F429ZI 기반 펌웨어 개발
- FreeRTOS 기반 태스크 구조 설계
- micro-ROS UART 통신 연동
- GNSS-RTK 기반 위치 측정
- 야외 테스트 중 셧다운 문제 원인 분석 및 개선

## 4. Key Technologies
- STM32F429ZI
- FreeRTOS
- micro-ROS
- UART
- BLDC Motor Control
- PID Control
- GNSS-RTK
- Mechanical Track Tensioner

## 5. Problem Solving
최종 발표 일주일 전 야외 테스트 중 로봇이 반복적으로 셧다운되는 문제가 발생했습니다.
전원, 배선, MCU, 미니PC, 통신 상태를 단계적으로 점검한 결과 LTE 지연으로 인한 응답 지연과 RTOS 태스크 처리 문제가 원인임을 파악했습니다.
초기에는 Watchdog Reset으로 시연 안정성을 확보했고, 이후 Timeout 관리와 최신 데이터 유지 방식으로 구조적 개선을 진행했습니다.

## 6. Result
- 야외 테스트 반복 검증 완료
- 약 10cm 수준의 RTK-GNSS 위치 오차 확인
- 2025 CO-Show SHARE Challenge 수상


<img width="1087" height="611" alt="image" src="https://github.com/user-attachments/assets/26a028f3-4fe2-4a9e-96cf-24cd91eb1ff1" />
<img width="1074" height="604" alt="image" src="https://github.com/user-attachments/assets/d1d6a5ee-f793-4e66-bc13-f16ecce81c02" />




