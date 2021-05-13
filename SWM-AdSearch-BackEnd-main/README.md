# Ad-Search BackEnd

`SpringBoot`, `mariadb`, `Spring data JPA` 를 사용하여 개발하였습니다.  
- Java Persistence API `JPA`  - Object 와 RDB 간의 연결    
- RestTemplateBuilder UriBuilder - openAPI 와 SpringBoot 간의 연결    

`박경호` OpenAPI를 이용해 Json형태의 데이터 파싱  
`박승현` DB 스키마에 맞게 OpenAPI데이터 가공  
`신봉근` aws ec2, rds를 이용하여 인프라 구축, domain 설계 및 구현   
`이창하` Controller작성 및 구현  

저희팀의 프론트 엔드가 궁금하신가요? 👉🏻 [SWM-AdSearch-FrontEnd](https://github.com/swm-pgui/SWM-AdSearch-Intergrated/edit/main/SWM-AdSearch-FrontEnd-main)

## How to build

1. AppKey 설정  
opEnAPI 사용간에 ServiceKey 유출을 방지하기 위한 `.gitignore` 파일을 main/resources/ 에 생성해두었습니다.   
`main/resources/appKey` 에 생성하고, 사용가능한 ServiceKey를 붙여넣어야 정상적인 실행이 가능합니다.  

2. Dependencies sync  
maven빌드 툴을 이용한 Springboot Dependency build

3. application Run  
PguiApplication.java 를 main class 로 application RUN
    
## api 명세 
|url|method|설명|
|------|---|---|
|/list/start/size|GET|허위광고 적발 업체들의 리스트를 출력한다. start페이지에서 size개수 만큼의 개체를 반환한다. |
|/search|GET|검색어(query)를 입력하면 업체명, 제품명에서 비슷하거나 일치하는 값의 개체를 반환한다.<br>variable) query : 검색값. |
