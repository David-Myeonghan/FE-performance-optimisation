## METRICS
### First Contentful Paint (FCP)
페이지 로드 시 브라우저가 DOM 컨텐츠의 첫 번째 부분을 렌더링하는 데 걸리는 시간에 관한 지표 - 10% 가중치

### Speed Index (SI)
페이지 로드 중 콘텐츠가 시각적으로 표시되는 속도에 관한 지표 <= 순차적으로 뜨는지, 아니면 한꺼번에 뜨는지 - 10% 가중치

### Largest ContentfulPaint (LCP)
페이지 로드 중화면 내에 있는 가장 큰 이미지나 텍스트 요소가 렌더링되기까지 걸리는 시간을 나타내는 지표 - 25% 가중치

### Time to Interactive (TTI)
사용자가 페이지와 상호작용(클릭 또는 키보드 누름 같은 사용자 입력)이 가능한 시점까지 걸리는 시간, 화면이 뜨더라도 이 시점까지는 인풋이 동작하지 않는다. - 10% 가중치

### Total Blocking Time (TBT)
페이지가 클릭, 키보드 입력 등의 사용자 입력에 응답하지 않도록 차단된 시간을 총합한 지표. FCP와 TTI사이 시간 + 메인 스레드를 독점하여 다른 동작을 방해하는 작업에 걸린 시간 총합 - 30%의 가중치

### Culmulative Layout Shift (CLS)
페이지 로드 중 예기치 못하게 발생하는 레이아웃(화면상 요소의 위치나 크기가 순간적으로 변하는 것) 이동 측정한 지표 - 15%의 가중치

## OPPORTUNITIES & DIAGNOSTICS
- 문제점과 해결 방안, 해결시 이점 표시

맨 밑 `Emulated Desktop`, `Custorm throttling` 주의깊게 볼 것.
- CPU 성능 제한, 네트워크 속도 제한




===========================================================================
## Lecture-1

'프론트엔드 개발자를 위한, 실전 웹 성능 최적화(feat. React) - Part. 1' 1번째 강의 소스입니다.

### 실행

1. download sources

```
$ git clone https://github.com/performance-lecture/lecture-1.git
```

2. install dependencies

```
$ npm install
or
$ yarn
```

3. start development server

```
$ npm run start
or
$ yarn start
```

4. start json-server

```
$ npm run server
or
$ yarn server
```
*3번의 dev server 와 다른 콘솔에서 띄워줍니다.

5. build + serve

```
$ npm run serve
or
$ yarn serve
```

### 질문

궁금하신 부분은 강의 내 질문 & 답변 게시판을 이용해주시길 바랍니다.
