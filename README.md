#  👓 Welcome to Min Sung's Github 👓

<!--
**msung99/msung99** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmsung99&count_bg=%2379C83D&title_bg=%23555555&icon=stackshare.svg&icon_color=%23E7E7E7&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)


### 🏢 Profile
---

- ##### 인하대학교 컴퓨터공학과 전공 (19.03~ )
- ##### 멋쟁이사자처럼 10기 백엔드 파트


### 💻 Skills  

---

<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Algorithm-00BCB4?style=for-the-badge&logo=Algorithm&logoColor=white">
    <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"> <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=C++&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> 
    
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=msung99&layout=compact&theme=contrast)


### 📌 Future Skills

---

<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Springboot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/Diango-092E20?style=for-the-badge&logo=Diango&logoColor=white"> 


### 📈 Github Stats

---

<img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=msung99">


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=msung99&show_icons=true&theme=radical)


![image](https://user-images.githubusercontent.com/88240193/168724490-cb5c79f0-a8f1-4be4-9c94-abe3575462b7.png)

![image](https://user-images.githubusercontent.com/88240193/168725087-f4d64a42-c6e6-487f-964a-4faadc8e2fc9.png)


![image](https://user-images.githubusercontent.com/88240193/168725795-92243d69-dc03-4c20-8bf7-58a106517b1c.png)

![image](https://user-images.githubusercontent.com/88240193/168726309-24c3c1d0-cf17-45f5-8372-4428d1d6b977.png)



### 💡 1. HTTP 요청과 서버의 응답

-  클라이언트에서 서버로 요청 시 데이터 전달 방식을 알아봅시다.

>1) WEB 이라는 정보의 그물망에서 우리가 원하는 URL 에게 웹브라우저를 통해 HTTP 요청을 보낸다.
(요청의 종류 : GET, POST 요청)

> 2) 서버 컴퓨터는 해당 요청에 대한 알맞은 응답을 해준다.

> 3) 웹 브라우저는 서버 컴퓨터로부터 응답 받아온 HTML 을 코드가 아닌 눈에 보기 좋은 화면으로 보이게 나타내줌.


---


### 📌 2.핵심 용어

#### 1. URL 
     정보의 그물망에서 그 정보의 위치를 나타내는 위치 정보

#### 2. HTTP 
     URL 을 통해 통신하고자 하는 위치를 알게되면, 그 정보와 통신할 수 있게 해주는 것. 


#### 3. HTTP 요청 
      정보 자원의 위치를 URL을 통해 받은 후, 정보 자원에게 내가 수행하고자 하는 작업을 HTTP 통신을 통해 요청을 보내는 것.
(종류 : GET, POST)

> GET : "얻는" 것이 주목적인 요청

> POST : "전달" 하는것이 주목적인 요청으로, 데이터를 담아서 전송하는 것이다.

#### 4. HTML 
      응답으로써의 정보자원. 웹 상의 정보를 보여주고 <a> 태그 href 속성등으로 다른 자원과 연결도 가능.

#### 5. 서버 
     정보를 URL 로써 미리 간직하고 있다가 (경우에 따라선 HTML 도 미리 준비해두고) 간직하고 있던 URL 로 
    HTTP 요청이 들어오게 되면 그에 대한 응답을 해주는 녀석

#### 6. 웹 브라우저 
     기능 2가지 => 1. HTTP 통신 / 2. 응답 받아온 HTML 을 코드가 아닌 보기 좋은 화면으로 보이게 함

---

### 🔍 3.웹 프레임워크 VS 라이브러리

- 웹 프레임워크 : 웹 개발응 하는 명확한 목적을 달성하기 위해 이미 설계까지 만들어진 구조 또는 뼈대
- 라이브러리 : 이것도 쓸만하고 저것도 쓸만한데 필요하면 가져다 쓰라는 것

---

### 📊 4.MVC 패턴 (MTV 패턴)

- 장고를 비롯한 웹 프레임워크는 아래와 같은 3개의 설계 원칙을 따릅니다.

#### 설계 원칙
      M : "M"odel ==  DB 와 상호작용하는 부분
      V : "V"iew == 사용자 인터페이스 (사용자가 직접 눈으로 보고 상호작용 할수 있는 부분) 을 담당하는 부분
      C : "C"ontroller ==  웹 서비스 내부 동작의 논리를 담당하는 부분

(장고는 MVC 패턴을 MTV 패턴이라 부름. MTV = Model + Template + View)

---

### 👩‍💻 5.가상환경

- 독립적인 개발환경을 만들어주기 위한 파이썬 내장 기능


