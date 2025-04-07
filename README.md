# 🧇와플(wafer flow) - 웨이퍼 공정 수율 분석 및 분류 시스템

## 📌프로젝트 설명
- 이 프로젝트는 반도체 제조 공정에서 생성된 웨이퍼 검사 데이터를 기반으로, 머신러닝을 통해 수율을 분석하고 불량 여부를 분류하는 시스템입니다. 
- Kaggle의 [WM811K Wafer Map Dataset]을 활용하여 불량 패턴을 학습하고, 직관적인 사용자 인터페이스(UI)를 제공하는 것을 목표로 합니다.
- PyQt를 이용해 GUI를 구현하며, 최종적으로는 불량 판별 및 결함 패턴 시각화를 통해 수율 관리에 도움을 줄 수 있는 시스템을 개발하려고 합니다.
- 웹사이트에서 사용자가 로그인하고 결과를 db에 저장해서 누구나 볼 수 있게끔 하는 게 이번 프로젝트의 최종 목표입니다.

## 🚀개발 동기
- 반도체 산업에서 웨이퍼 검사 공정은 수율과 직결되는 핵심 단계이지만, 수작업 위주로 진행되기 때문에, 정확한 분석 및 시각화에 어려움이 있습니다.
- 본 프로젝트는 머신러닝을 적용하여 웨이퍼 불량을 자동 분류하고, 수율 분석 결과를 직관적으로 확인할 수 있도록 하여 실제 공정 관리의 효율성을 높이고자 기획하게 되었습니다.

## 🎯 개발 목적
- 반도체 산업에서 발생하는 웨이퍼 불량 데이터를 활용하여 수율을 자동으로 분석하고, 불량 여부를 신속히 판별할 수 있는 시스템을 개발하는 것이 주 목적입니다.
- 기존의 수작업 또는 시각적 검사를 통해 이뤄지던 공정 평가 과정에 머신러닝을 도입하여 정확도 및 효율성을 향상시키고자 하였습니다.
- 궁극적으로는 반도체 생산 공정의 불량률 감소 및 품질 개선에 기여하는 데이터 기반 공정 분석 시스템 완성하는 것을 목표로 합니다.

## 🛠️ 구현할 기능
- 머신러닝 모델 구축: CNN 기반 분류기를 활용하여 웨이퍼의 불량 여부를 자동 판별
- 수율 판별 기능: 입력된 Pass/Fail 기준과 픽셀 수를 바탕으로 제품의 수율 평가 자동화
- 사용자 입력 필드: 제품명, 검사일, 예상 수율 등의 사용자 입력 기능 제공
- GUI 개발: PyQt5를 활용한 데스크탑 기반 인터페이스 구현, 사용자 친화적인 레이아웃 구성
- 분석 결과 요약: 불량 유형 비율, 전체 수율 %, 판별 결과 저장 기능 등 요약 기능 제공

## 🧩기술 스택
- 언어: Python
- GUI 프레임워크: PyQt5
- 시각화: Matplotlib, NumPy
- 머신러닝: scikit-learn, TensorFlow (선택적), pandas
- 데이터셋: WM811K Wafer Map Dataset(자료 출처 : https://www.kaggle.com/code/ashishpatel26/wm-811k-wafermap)

## 👤역할 분담
- 팀장 역할 (aroundbeast@naver.com)
1) 전체 일정 관리 및 역할 조정
2) 프로젝트 진행 상황 점검
3) 보고서, github 정리 및 작성
4) 논문 분석 후 총괄 정리

- 이건해 팀원 역할 (yoandyo2000@gmail.com)
1)  머신러닝 모델 개발 및 학습
2) 벤치마킹 서비스 검색 후 보고서 작성

- 이승우 팀원 역할 (brian524560@gmail.com)
1) 분류 분석 트레이닝, 성능 최적화
2) 논문 분석

- 박우빈 팀원 역할 (oi3oi3oi@naver.com)
1) 데이터셋 전처리 및 개발 + PyQt 인터페이스 구현
2) 논문 분석

## 📆 진행 과정
- 1주차: 캡스톤디자인 오리엔테이션 및 아이디어 브레인스토밍
- 2~3주차: 반도체 공정 이론 학습 및 웨이퍼 검사 프로세스 조사
- 4~5주차: 프로젝트 계획서 작성



## 🔖 Release
