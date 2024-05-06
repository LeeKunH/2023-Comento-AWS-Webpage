# 학교 프로그램 - 코멘토(IT직무 기초체험)
> ### 소개
- Amazon AWS 클라우드 서비스를 사용하여 워드프레스 기반의 개인 블로그를 구축하고 배포하는 과정/과제사진 기록

----

> ### 웹 페이지 기획
- ### 1.단계 - 웹 페이지 기획 목적 작성
- **작성내용** =>
	- 간단한 자기소개 웹 페이지 제작
	- 개인 작업 정리 목적의 웹 페이지 제작
- ### 2. 단계 - 트래픽 목표수치 작성
- **어떤 내용을 작성?**
	- 웹사이트를 방문할 예상 사용자 수와 그에 따른 데이터 트래픽을 예측하고 계획 작성
	- 이 목표 설정은 호스팅 선택, 서버 구성, 비용 예산 등에 중요한 영향을 미침
	- EX)
		- 웹사이트 방문자 수 예측: 웹사이트를 방문할 것으로 예상되는 일일, 주간, 월간 사용자 수 작성
		- 페이지 뷰 수: 예상되는 페이지 뷰 수를 계산하여 서버 부하를 예상하고 적절한 리소스 할당 계획 작성
		- 데이터 전송량: 예상 트래픽에 기반하여 필요한 데이터 전송량을 추정하며, 이는 호스팅 비용 산정에 중요한 변수
- **작성내용** =>
	- 개인 포트폴리오 목적으로 웹사이트를 운영 > 따라서 친구, 가족, 면접관 등 아주 제한된 수의 방문자 예상됨.
	- 웹페이지 방문자 수 예측 : 월 30~40 접속 가정
- ### 3. 단계 - 컨텐츠 종류 내용 작성
- **어떤 내용을 작성?**
	- 웹 페이지에 포함될 주요 내용과 정보의 유형을 명확히 정리
    - 각 종류의 컨텐츠-정보(텍스트, 이미지, 인터랙티브 요소 등)가 어떤 목적으로 사용될 것인지, 그리고 어떻게 구성 및 제공될 것인지 계획
- **작성내용** =>
	- 1. 텍스트 컨텐츠
		- 자기소개  : 
			- 웹 페이지에 나를 소개하는 짧은 내용 작성
			- 좌우명 작성
		- 공부 정리 노트 :
			- 공부했던 내용들에 대한 요약 내용 제공
			- 공부한 내용에 대한 요약 제공
	- 2. 이미지 컨텐츠
		- 프로필 사진 : 
			- 웹 페이지 첫 화면에 내 사진 출력
		- 학습 관련 이미지 : 
			- 공부했던 주제에 대한 이미지 출력
	- 3. 인터랙티브 요소
		- 내비게이션 추가
			- 방문자가 웹 페이지 특정 내용을 클릭하면 연관된 새로운 페이지로 이동할 수 있도록 링크 구현
- ### 4. 단계 - 기술 선정 작성
- **어떤 내용을 작성?**
	- 웹 페이지 구축에 사용될 기술 스택과 도구를 선택하고 그 이유를 설명
	- 사용할 프론트엔드 및 백엔드 기술, 데이터베이스 관리 시스템, 서버 환경 등을 포함
- **작성내용** =>
	- 프론트엔드 기술 : 
	    - 무료 웹 템플릿을 활용하여 기본적인 구조와 디자인을 구현
	    - 복잡한 코딩 없이 콘텐츠를 삽입하고 내용 수정으로 개인 웹사이트를 완성 진행
		- 디자인 : Aerial | HTML5 UP 사용 > `실습 이미지` 확인
	- 호스팅 :
	    - AWS (Amazon Web Services) EC2 
		    - OS : 리눅스
			    - 서버 프로그램 : 아파치
		    - AWS 클라우드 서비스를 사용하여 웹사이트를 호스팅
- ### 5. 단계 - 비용 산정 작성
- **어떤 내용을 작성?**
	- 웹 페이지를 운영하고 유지하는 데 필요한 전반적인 비용을 고려해 작성
	- 단순히 서비스를 시작할 때만의 비용이 아니라, 장기적으로 발생할 수 있는 다양한 비용 요소들을 포함
	- EX) 호스팅 비용, 도메인 등록 및 유지 비용, 웹사이트의 정기적인 유지 및 업데이트 비용 등이 포함
		- => 지금은 연습단계로서 매우 간단히 작성
- **작성내용** =>
	- 서비스 호스팅 비용
		- AWS 클라우드 서비스 프리티어로 초기 1년간 무로로 호스팅 진행
		- 프리티어 종료 후 새로운 계정으로 변경 진행
	- 웹 페이지 도메인 비용 :
		- https://domain.gabia.com/ 에서 가장 저렴한 이벤트성 도메인 구매 진행
		- 1년간 초기 등록비용 500원. 이후 연간 갱신 비용 동일하게 진행
- ### 6. 단계 - 그림으로 표현
- 참고사이트-이미지
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/aff6af23-e9ed-4a1a-be6a-198994cc6a1f" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/20ff4b1f-6070-4734-abfb-e2e449722ee1" alt="이미지 설명" width="500" height="auto">
</p>

- 그림 표현-이미지
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/9ff7ad54-474c-49ab-bdd3-80ddf9c19885" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/f0baee0c-ad95-4a59-8410-f6d34e347ebb" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/3714ed2c-b83a-4427-8dd5-7fd056d17d19" alt="이미지 설명" width="500" height="auto">
</p>

***

> ### 실습 이미지

- 무료 웹 템플릿 활용 자기소개 첫 웹 페이지 구현
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/51ab3b01-865d-421f-890a-87c6bfed5784" alt="이미지 설명" width="500" height="auto">
</p>

- AWS 계정가입
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/c5fa166b-0def-4188-8ae3-88010518f5fd" alt="이미지 설명" width="500" height="auto">
</p>

- EC2 인스턴스 생성
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/4e2cc874-b147-43e5-afed-46c5928e5321" alt="이미지 설명" width="500" height="auto">
</p>

- CloudWatch > 모니터링
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/727cbc00-c6ea-4990-9cfb-87de9aedcdd2" alt="이미지 설명" width="500" height="auto">
</p>

- 웹 서버 테스트 페이지
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/d47316a3-bcbe-4ba5-a227-7c33f43cdf5a" alt="이미지 설명" width="500" height="auto">
</p>

- 리눅스(터미널)에서 PHP가 제대로 동작하는지 동작 테스트 진행(/var/www/html 위치에 phpinfo 테스트 페이지를 생성 후 삭제)
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/0ba16d92-79a3-47a4-a61b-5cfe645f7625" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/e8ac13f4-4d9c-4c15-a23b-4186ab92ae53" alt="이미지 설명" width="500" height="auto">
</p>


- WordPress 접속
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/3f4895ed-d428-481f-9ad0-e22dcba06d63" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/eec095a9-a904-4809-8390-178e63cffd3c" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/e2172fb8-3869-4e23-840f-14c6480a48ac" alt="이미지 설명" width="500" height="auto">
</p>
<p align="center">
  <img src="https://github.com/LeeKunH/2023-Comento-AWS-Webpage/assets/139840981/8874459b-de08-4bcf-9955-5c11e988c1a9" alt="이미지 설명" width="500" height="auto">
</p>



