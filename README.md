# DATABOARD
> 다양한 API를 이용하여 사용자 맞춤형 콘텐츠를 제작하고 공유하는 서비스

데이터보드 서비스는 웹, 모바일 및 태블릿에서 지원 가능하도록 제작했습니다.
   
- Open API를 쉽게 연계하여 콘텐츠를 저작할 수 있는 저작 도구를 제공합니다.
   
- 다른 사용자가 공개한 콘텐츠를 가져와 새로운 콘텐츠로 수정할 수 있습니다.
   
- 제작한 콘텐츠를 링크, SNS, 이메일등으로 공유할 수 있습니다.
   
   
## 사용 기술

#### 1. Language & Framework
- Dart
- Flutter

#### 2. DB
- MySQL

#### 3. Server
- Naver Cloud Platform

   
## 기능 소개
### 1. 양식 게시판
> 공개된 양식을 확인하고 내 양식으로 가져오거나 내 양식을 공유, 수정할 수 있습니다.
   
![image](https://user-images.githubusercontent.com/37923543/193888040-68ba623d-b165-4670-a42b-04421d1630cc.png)

### 2. 양식 저작 화면
> 새로운 양식을 만들거나 가져온 양식을 수정할 수 있습니다.
   
![image](https://user-images.githubusercontent.com/37923543/193888910-1058a2e2-6c33-4cca-906d-a027f17eb01e.png)

### 3. 데이터소스 연계
> 제작한 양식의 도구에 API데이터를 연결하여 컨텐츠를 동적으로 표시할 수 있습니다.
   
![image](https://user-images.githubusercontent.com/37923543/193889186-8e27a033-56d2-402d-b14f-fc17b056bed7.png)

### 4. 미리보기
> PC, 모바일 양식에 따라 미리보기 화면을 제공합니다.

![image](https://user-images.githubusercontent.com/37923543/193889452-651ff926-eb90-4e6a-90f5-f3837de8ec9a.png)

### 5. 모바일앱
> 모바일앱의 내 양식 메뉴, 양식 게시판, 미리보기, 카카오톡 공유 화면입니다.

<div>
    <img src="https://user-images.githubusercontent.com/37923543/193892969-ba6a41a0-6c93-4f72-9b1b-b307c8902ca7.png" width="300" height="650"/>
    <img src="https://user-images.githubusercontent.com/37923543/193889720-f0197210-4f69-46c4-bc4e-8ba59a1bb836.png" width="300" height="650"/>
    <img src="https://user-images.githubusercontent.com/37923543/193893028-fcd38f07-eeb2-4f08-b669-814ef8f9781a.png" width="300" height="650"/>
    <img src="https://user-images.githubusercontent.com/37923543/193895689-28f083a9-17e2-49eb-9b43-b1d48efedf33.png" width="300" height="650"/>
</div>
   
## 담당 기능

- 다양한 저작 요소 제공 및 저작 기능 구현

- 제작한 대시보드 모양을 저장할 JSON 구조 설계

- 각종 OPEN API 데이터소스 추가 및 도구와 위젯에 연결

- 양식 게시판, 양식 미리보기 & 가져오기

- 모바일 및 태블릿 화면을 고려한 반응형 UI 구성
