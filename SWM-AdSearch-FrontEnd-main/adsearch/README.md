# AdSearch FrontEnd
*_"식품 허위·과대광고 업체 및 제품검색 서비스"_*

### 🚩 **기획배경**

- YouTube, SNS등 광고 채널이 늘어나면서 식품 허위·과대광고 증가
- 무분별한 과대광고에 많은 피해자 발생 → 개선되지 않고 현재에도 지속중
- 소비자가 식품 허위·과대광고를 판별하는 능력이 필요하다고 생각함

### 🚩 **기획목표**

- 식품 허위·과대광고정보 서비스를  제공함으로서 소비자의 피해 줄이기
- 식품 허위·과대광고를 한 업체 혹은 제품을 검색할 수 있는 서비스 개발
- 더치트와 유사한 서비스 제공

### 🚩 **발전 가능성**

- 사용자 제보 등 데이터 수집도구로서의 기능 개발
- 데이터 분석을 통해 부가적인 기능 개발

### 사용 오픈소스 API

[공공데이터 포털 | 식품의약품안전처_식품 허위·과대광고정보](https://www.data.go.kr/data/15058599/openapi.do)

## 👯 FrontEnd

`React` 프레임워크를 기반으로 `Ant Design`, `G2Plot`, `axios` 등의 라이브러리를 사용하였습니다.
- UI Design `Ant Design` - 여러 컴포넌트를 활용한 디자인
- `G2Plot` - Data에 맞는 차트 렌더링
- HTTP 비동기 통신 라이브러리 `axios` - REST API와의 통신

`송영범` 홈페이지 UI/UX 설계 및 구현  
`김경환` 홈페이지 UI/UX 설계 및 구현  

저희팀의 백 엔드가 궁금하신가요? 👉🏻 [SWM-AdSearch-BackEnd](https://github.com/swm-pgui/SWM-AdSearch-Intergrated/tree/main/SWM-AdSearch-BackEnd-main)

## How to build

1. `nodejs` 와 `npm` 의 설치가 선행되어야 합니다.  
관련 설치페이지 -> [Download | Node.js](https://nodejs.org/en/download/)  
2. change directory to `adsearch/` then execute command    
   > $ npm install    
$ npm start  
3. 브라우저에서 [http://localhost:3000/](http://localhost:3000/) 에 접속해서 확인하실 수 있습니다.
