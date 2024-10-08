# Repository 소개
## 1. 공개 Repository 목록
  - emsbigdata
  - EMS Open API
    
## 2. 비공개 Repository 목록
  - EMS NEDIS Agent
  - EMS PSM Algorithm

## 3. 공통 요구사양
  - OS : Ubuntu 22.04
  - DBMS : PostGreSQL 16.2
  - DB Admin Tool : pgAdmin 4
  - DB User Tool : DBeaver Community 24.2.0
  - Programming Language : Python 3.11

    
[![Ubuntu](https://github.com/user-attachments/assets/c25473d8-efb9-4fe1-afab-2b231a0d0727)](https://releases.ubuntu.com/jammy/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![postresql](https://github.com/user-attachments/assets/82800751-3f13-4db9-ad53-d6aa8543f0a0)](https://www.postgresql.org/download/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![pgadmin-removebg](https://github.com/user-attachments/assets/2bf57a44-de2d-4672-8607-4b652dd5526f)](https://www.pgadmin.org/download/)
<br>
<br>
[![python](https://github.com/user-attachments/assets/b9ba1abd-55bf-4163-98cc-6f9a79af49da)](https://www.python.org/downloads/release/python-3110/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![dbeaver](https://github.com/user-attachments/assets/7e6e8568-7ad0-4264-98ad-84553c58fa41)](https://dbeaver.io/2024/09/01/dbeaver-24-2/)


## 4. Repository 관련 문의처
  - Repository : emsbigdata
  - 문의방법 : Discusion의 Q&A를 사용하여 문의
  - 바로가기
[![Q&A](https://img.shields.io/badge/Ask%20Questions-Q%26A-blue)](https://github.com/emsbigdata/emsbigdata/discussions/categories/q-a)

---

# 스마트 응급의료 빅데이터 플랫폼 소개

## 1. 스마트 응급의료 빅데이터 플랫폼 개요
  - 스마트 응급의료 빅데이터 플랫폼은 응급환자 재이송률 및 이송시간 단축을 통한 골든타임 확보가 목적입니다.
  - 스마트 응급의료 빅데이터 플랫폼 사업단의 대상은 연구자, 의료진, 국민입니다.
  - (연구자) 실시간 정보 공유
    - 환자 상태, 응급처치 상황, 이송 경로 등 중요한 정보를 관련 의료진 및 기관과 즉시 공유합니다.
    - 개방형 강화, 즉 응급의료 빅데이터의 공유, 상호 호환성 강화, 아이디어·지식·자원을 공유하는 개방형 혁신 강화가 목표입니다.
  - (의료진) 환자 이송 병원 신속 결정
    - 환자 이송 과정에서 신속하고 정확한 결정을 지원합니다.
    - 데이터 활용 생태계 체계 확립, 즉 센터 간의 유기적이고 체계화 된 네트워크 조성을 통해 응급의료 빅데이터 활용을 증대시킵니다.
  - (국민) 골든타임 확보
    - 골든타임 내 적절한 응급처치와 이송읕 통해 골든타입을 확보합니다.
    - 국민을 대상으로 보다 나은 서비스를 제공합니다.

![image](https://github.com/user-attachments/assets/4a869d8b-dd1b-439e-81da-8cf845aed0ae)

---

## 2. 플랫폼 구성도
  - 데이터 시각화를 통해 누구나 쉽게 응급의료 데이터를 분석하고 활용할 수 있습니다.
  - 실시간 자원 연계를 통해 환자 이송 병원 결정과 응급처치 정보 공유 등 응급의료 조정과 대응의 효율성이 증대됩니다.
  - 자동차사고 심층조사 분석를 통해 사고 예방과 신속하고 최적화된 응급의료 대응 방안을 개선하는 데 기여합니다.
    
![image](https://github.com/user-attachments/assets/d2683837-e82f-47f6-87ca-59ac7a7ff783)

---

## 3. 빅데이터 분석 포털 기능
  - 메타 데이터 조회
    - 메타 데이터 조회를 통한 데이터 속성을 파악합니다.
    - 특정 연구 목적에 맞는 데이터를 선택적으로 조회하여 필요한 데이터를 빠르게 구성함으로써 분석을 더욱 신속하고 정확하게 진행할 수 있게하는 기능입니다.
  - 충청북도와 전국 데이터 비교
    - 충청북도 소재 참여병원에서 수집된 응급의료 데이터를 전국 응급의료 데이터와 비교분석할 수 있는 기능입니다.
    - 지역별 응급의료 서비스의 차이를 파악하고, 충청북도 응급의료 체계를 개선하는 데 필요한 구체적인 인사이트 도출이 가능합니다.      
  - 데이터 접근 및 분석
    - 일반 사용자에게 공개된 통계성 데이터를 기반으로 분석 및 시각화 서비스를 이용하는 기능입니다.
    - IRB를 갖춘 권한자에 한해 NEDIS 자료 및 자동차사고 심층조사 분석 데이터를 활용합니다.
  - 구급-병원 데이터 연계
    - 구급 단계와 병원 단계의 데이터를 통합적으로 분석하기 위해 확률적 매칭 방법(Propensity Score Matching, PSM)을 사용한 구급-병원 데이터 연계 기능입니다.

![image](https://github.com/user-attachments/assets/3a9ad84a-6d71-4e09-a7d6-1713226a9728)

---

## 4. 응용서비스
  - 국가응급진료정보망(NEDIS)
    - 국가응급의료정보망(National Emergency Department Information System, NEDIS)은 응급이송 환자의 치료 정보를 실시간으로 제공하는 시스템입니다.
    - EMS는 도내 참여병원의 NEDIS 데이터를 실시간으로 연계하여 응급의료체계 각 단계에서 필요한 병원의 자원 정보와 응급 환자 진료 정보를 관계자들에게 제공합니다.
    - 또한, 맞춤형 연구자료-NEDIS를 기반으로 분석된 자료를 제공하여 응급의료 정책 수립과 연구 분석에 활용할 수 있도록 지원합니다.

![image](https://github.com/user-attachments/assets/d1a87d2b-7626-4943-98b6-3012caa96a6d)
      
  - 자동차사고 심층조사 분석 서비스
    - 본 서비스는 실사고 조사 기반의 자동차사고 심층조사 분석자료(Korean In-Depth Accident Study, KIDAS) 데이터베이스 구축을 기반으로 교통사고 환자의 손상기전 연구를 통하여 자동차 사고에 의한 인체손상기전을 분석하여 사고예방과 치료기술 및 시스템 개발이 주요 목적입니다.
    - 자동차사고 응급환자의 중증도를 신속하게 분류하는 진단 지원 시스템입니다.
    - 실시간 데이터를 활용해 정확한 중증도 평가를 제공하며, 의료진이 신속한 의사결정 지원합니다.
    - 연세대학교 원주의과대학 자동차의과학연구소(Automotive Medical Science Research Institute) 및 충북대학교병원 응급의학과와 함께 응급의학, 손상, 응급의료체계, 자동차의학 등에 대하여 연구합니다.

![image](https://github.com/user-attachments/assets/3744f18b-1b6d-49c1-ad94-f0188118b791)

  - 응급의료 상황 정보
    - 스마트 응급의료 빅데이터 플랫폼에서 제공하는 응급환자이송 상황판은 구급이송 상황에서 환자정보와 병원의 응급자원정보를 연계하여 충청북도 응급의료조정을 위한 중추적 역할을 담당합니다.
    - 응급환자이송 상황판은 충북 응급의료지원단에 설치되어 이송 환자의 분류정보를 병원과 공유하고, 환자 전원을 위한 응급의료 조정 지원합니다.

![image](https://github.com/user-attachments/assets/37c50118-08c2-49f8-86b9-0c9adbbd087e)

  - 참여병원 상황정보
    - 응급실 도착 전 환자 정보를 공유해 응급환자 대응을 효율화하고, 골든타임을 확보하는 것을 목표입니다.
    - 도착 예정 구급차 정보, 환자의 기본 정보, 중증도 및 손상 현황 등 응급환자 이송 현황을 실시간으로 제공합니다.
    - 응급실 혼잡도, 평균 체류 시간, 응급환자 및 질병 비율, 119 구급차 이용 비율 정보도 함께 제공해 응급실 상황을 종합적으로 파악합니다.
    - 병원 대시보드 서비스는 실시간 구급(소방) 데이터와 참여 병원의 NEDIS 연계 데이터를 바탕으로 구현하였습니다.

---

# PSM(Propensity Score Matching, PSM) Algorithm

## 1. 개요
  - SFM-NEDIS Gmatch 알고리즘은 구급활동일지 데이터와 NEDIS 두 개의 다른 소스에서 환자 기록을 병원 코드, 성별, 내원 날짜 및 연령과 같은 다양한 속성을 기준으로 매칭하는 도구입니다.
  - 매칭 과정에서는 연령과 내원 시간의 유클리드 거리를 계산하여 가장 가까이 위치한 일치되는 항목 매칭합니다.
  - 결과는 구급활동일지 데이터의 환자ID와 NEDIS 데이터의 환자 ID를 매칭하여 저장합니다.

![image](https://github.com/user-attachments/assets/682d95ca-5c0c-4e0e-886a-fd50328b904d)

---

# EMS NEDIS Agent

## 1. 개요
  - 의료데이터 연계를 위해 NEDIS Agent PC 데이터를 서버 적재합니다.
  - 스마트응급의료 빅데이터 플랫폼을 통해 참여병원 간 데이터 연계합니다.

![image](https://github.com/user-attachments/assets/2e347f68-82af-4702-bb5a-3dd1bd80ebf9)

  - NEDIS Agent PC 활용 데이터를 연계·적재 및 충북 맞춤형 응급의료 데이터 서비스를 제공합니다.

![image](https://github.com/user-attachments/assets/e97cfeda-3e0b-45d9-8fb3-3cb5324d6ac7)

## 2. 수집 데이터
  - 환자 메인(EMIHPTMI)
    - 참여병원의 환자 메인 데이터는 병원에서 진료를 받은 환자에 대한 핵심 정보를 포함하는 데이터셋입니다.
    - 병원의 진료 및 치료 과정에서 수집된 다양한 환자 정보를 포괄하며, 환자 내원정보, 환자 초기 평가 정보, 중등도 분류일자, 환자 추가 정보, 환자 응급진료 내용과 결과, 환자정보 등이 포함됩니다.
  - 퇴원진단내역(EMIHDGDC)
    - 퇴원진단 내역은 응급의료기관코드, 내원일자, 내원시간, 진단코드, 진단 구분 등으로 구성합니다.
    - 한국표준질병/사인분류의 진단코드를 채용하여 사용하고 있으며, KCD-7 완전코드를 사용합니다.
  - 퇴실진단내역(EMIHDGOT)
    - 퇴원진단 내역은 주진단, 부진단, 의중으로 구분되어있으며, 응급의료기관코드, 내원일자, 내원시간, 진단코드, 진단 구분 등으로 이루어집니다.
    - 한국표준질병/사인분류의 진단코드를 채용하여 사용하고 있으며, KCD-7 완전코드를 사용합니다.
  - 응급실 검사,처치, 수술내역(EMIHTRPT)	
    - 응급실 내에서 발생한 모든 검사, 처치 및 수술정보가 입력되는 데이터로, 응급환자 검사, 처치 및 수술 내역은 해당하는 EDI표준수가 코드를 사용합니다.
    - 내원일자, 내원시간, 검사/처치/수술 코드, 검사/처치/수술시작일자, 검사/처치/수술시작시간 등으로 구성합니다.
  - 전문의 진료내역(EMIHSDMD)
    - 전문의 진료내역 데이터는 전문의 진료가 있었을 경우 해당되는 진료과목 및 진료내역에 해당하는 데이터입니다.
    - 전문의 진료과목, 전문의 의사 면호번호, 응급실 내 전문의 진료일자, 응급실 내 전문의 진료시간 등의 데이터로 구성합니다.
  - 입원시 검사,처치, 수술내역(EMIHOPPT)
    - 응급실 경유 입원환자의 입원기간 중 발생한 검사, 처치 및 수술정보 데이터로 입원 중 발생한 검사, 처치 및 수술처방 코드에 해당하는 EDI 표준수가코드를 사용하는 데이터입니다.
  - 외상환자 진료내역(EMIHTRMS)
    - 외상환자 진료내역은 외상을 입은 환자에 대한 진료를 기록한 데이터셋입니다.
    - 외상의 원인, 부상 정도, 응급처치 및 치료 과정, 결과 등을 포함합니다.
  - 외상환자 진료내역(3.0 추가) (EMIHTRMS_ADD)
    - 외상환자 진료내역은 외상을 입은 환자에 대한 진료를 기록한 데이터셋, 3.0 버전이 추가되었습니다.
    - 보호장구 착용여부 및 종류, 내원시 GCS 평가 관련 사항, 기저질환 여부 및 종류 등을 포함합니다.

## 3. 데이터 연계   
      
  - 참여병원 NEDIS 데이터 연계
    - 충청북도 스마트챌린지사업 참여병원을 대상으로 NEDIS 데이터 연계를 위한 협의를 거쳐 EMS와의 연계 작업을 진행합니다.
    - 참여병원의 NDEIS 데이터 제공 구조와 데이터 현황을 파악한 후, EMS NEDIS Agent 연계 시스템을 개발 및 적용하여 데이터 연계를 구현합니다.
    - 안정적인 NEDIS 데이터 연계를 위해 EMS NEDIS Agent PC에서 구동 상태, 버전 정보, 전송 유형, 로그 정보 등을 지속적으로 모니터링합니다.

![image](https://github.com/user-attachments/assets/77b4a5c8-fb9b-4a86-b673-be5af2659d75)



<!---
emsbigdata/emsbigdata is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
