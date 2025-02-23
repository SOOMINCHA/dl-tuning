# 딥러닝 기반 튜닝 노하우 웹 연계 시스템

## 프로젝트 개요
이 프로젝트는 **Binary Crossentropy 손실 함수를 적용한 딥러닝 모델**을 사용하여 **튜닝 최적화**를 수행하는 시스템입니다.  
딥러닝 모델을 활용하여 엔지니어의 경험적 노하우를 지속적으로 유지하고 개선하며,  
**Restful API를 통해 웹 서비스와 연동**하여 실제 환경에서도 활용할 수 있도록 개발되었습니다.

## 개발 환경 및 기술

### 운영 체제
- Windows 10
- Ubuntu 22.04.4

### 개발 언어
- Python 3.10.11
- Java 1.8

### 개발 도구
- MariaDB 10.6
- JDK 1.8.0_151
- eGovFrameDev 3.9.0
- Apache Tomcat 8.5.87

### 적용 기술
- **딥러닝 모델:** TensorFlow + Keras  
- **데이터 전처리:**  
  - `LabelEncoder`를 사용한 범주형 데이터 인코딩  
  - `MinMaxScaler`를 이용한 데이터 정규화  
- **모델 학습:** Binary Crossentropy 손실 함수를 적용한 **H5 형식** 모델 저장  
- **예측 및 응용:** 학습된 모델을 활용하여 **새로운 데이터 예측**  

## 시스템 구성 및 기능

### 주요 기능
1. **데이터 전처리**  
   - 범주형 데이터 인코딩 (`LabelEncoder`)
   - 데이터 정규화 (`MinMaxScaler`)

2. **딥러닝 모델 학습 및 저장**
   - TensorFlow + Keras 기반 모델 학습
   - Binary Crossentropy 손실 함수 적용
   - 학습된 모델을 `.h5` 형식으로 저장

3. **모델 배포 및 웹 연동**
   - Restful API를 통한 예측 서비스 제공
   - Apache Tomcat을 이용한 웹 서버 구축

## 기대 효과

**최적화된 튜닝 값 도출**  
  - 다양한 재료에 대해 **최적의 구동 튜닝 값을 자동으로 결정**  
  - 제품의 성능과 효율성을 극대화  

**지속 가능한 운영**  
  - 인공지능을 통해 **지속적으로 최적의 튜닝 값을 개선**  
  - 엔지니어의 노하우를 자동화하여 **지속적인 유지 가능**  

---

