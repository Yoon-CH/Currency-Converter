# **📱 실시간 환율 계산기**

## 프로젝트 소개

> 주어진 API를 활용하여 두 종류의 환율 계산기가 각각 작동하도록 구현하는 프로젝트

### member

<table>
  <tr>
        </td>
      <td align="center">
      <a href="https://github.com/LEEHYUNHO2001"
        ><img
          src="https://avatars.githubusercontent.com/LEEHYUNHO2001"
          width="100px;"
          alt=""
        /><br /><sub><b>이현호</b></sub></a>
    <br />
    </td>
    <td align="center">
      <a href="https://github.com/hoonjoo-park"
        ><img
          src="https://avatars.githubusercontent.com/hoonjoo-park"
          width="100px;"
          alt=""
        /><br /><sub><b>박훈주</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/Yoon-CH"
        ><img
          src="https://avatars.githubusercontent.com/Yoon-CH"
          width="100px;"
          alt=""
        /><br /><sub><b>윤창현</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/devjoylee"
        ><img
          src="https://avatars.githubusercontent.com/devjoylee"
          width="100px;"
          alt=""
        /><br /><sub><b>이주영</b></sub></a
      ><br />
  </tr>
</table>

| 팀 구성        | 담당                              |
| -------------- | --------------------------------- |
| 이현호, 윤창현 | 선택박스 계산기 (SelectConverter) |
| 박훈주, 이주영 | 탭 계산기 (TabConverter)          |

<br/>

## 배포 주소

[http://beefplz.s3-website.ap-northeast-2.amazonaws.com/](http://beefplz.s3-website.ap-northeast-2.amazonaws.com/)

<br/>

## 사용 기술 및 스택

- Stack
  - React Hooks
  - styled-components
  - fetch
  - Deploy : Netilfy
  - Other : Git / GitHub
  - Build Tool (Create React App)
  - Code Quality Tool (Prettier)

<br/>

## 과제 구현 목록

### **Select Box Converter (이현호, 윤창현)**

![select-converter](https://user-images.githubusercontent.com/68415905/151094234-e3891e6d-b48f-4a18-be26-a3436b0dd67c.gif)

- [x] 레이아웃 및 UI ( SelectConverter )
- [x] API 데이터 받아 사용
- [x] 리스트 위아래 선택 박스
- [x] current에 따른 수취국가 환율 표시
- [x] 결과값에 따른 환전값 반환

<br />

## CRA 구조

```markdown
src
│
├─components
│ │  
│ └─SelectConverter  
│ │ SelectConverter.jsx
│ └─TabConverter
│ TabConverter.jsx
│
├─constants
│ index.js
│
├─pages
│ MainPage.jsx
│
├─styles
│ GlobalStyles.js
│
├─utils
│ dateConverter.js
│
```

<br/>

## 커밋 컨벤션

깃모지를 사용하여 직관성을 높이고, 기능이나 UI 설계에 따른 메세지를 커밋 메세지에 담는것을 컨벤션으로 결정했습니다. 깃모지로 인해 상대방이 어떤 작업을 수행했는지 한 눈에 확인할 수 있고, 메세지를 보며 조금 더 상세한 상황을 파악할 수 있습니다.

| 깃모지 | 사용 예시               |
| ------ | ----------------------- |
| 🎉     | init                    |
| 🚚     | 디렉토리 또는 파일 이동 |
| ✨     | 기능 구현               |
| 💄     | CSS 스타일링            |
| ♻️     | 리팩토링                |
| 📝     | Readme 수정             |
| ➕     | 모듈 추가               |
| 🐛     | 버그 해결               |
| 🚑️    | 치명적인 오류 해결      |

<br/>

## 과제 후기

### 윤창현 ✨

명확한 업무분담과 빠르고 정확한 협업과 소통으로 프로젝트를 완성 하였고, 한걸음 더 발전할 수 있었던 좋은 시간이었습니다.
또한, API연동 이후 데이터를 가져와서 사용하는 부분과 국가에 따른 환율변동 로직을 구현하는데 다양한 시도를 할 수 있었고
그 과정에서 리팩토링을 통해 간결한 코드를 구현해보며 리팩토링의 중요성을 느낄 수 있었습니다.

[회고록 보러가기](https://velog.io/@changh950/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%9A%8C%EA%B3%A0-%ED%99%98%EC%9C%A8-%EA%B3%84%EC%82%B0%EA%B8%B0)
