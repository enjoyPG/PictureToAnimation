# PictureToAnimation
 

## 유의점
### 1. python은 3.6버전 설치를 추천 (3.8까지만 지원됨)

### 2. test.ipynb의 경우 텐서 1.15버전설치
pip install tensorflow==1.15

### 3. 특정 텐서 설치를 위해 가상환경 구성하는 것을 추천
1) pip install virtualenv
2) 프로젝트 폴더로 이동 후 python -m virtualenv venv
3) 윈도우경우 powershell에 들어가서 Set-ExecutionPolicy Unrestricted 입력
4) .\venv\script\activate
5) 팔레트(ctrl+shift+p) 인터프리터에서 venv 인터프리터 선택해주기
