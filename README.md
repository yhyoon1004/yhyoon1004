#  👨‍💼 YunHwan's
 - :accessibility: ability > `FullStack` , `CICD` , `K8S` , `Infra`
 - 📄 blog > https://dev-yunhwan.tistory.com
 - 🚗 The site I developed > https://renteasy.co.kr             

# Recently Thoughts (느낀점)
- 무엇보다 하면서 조금은 즐거워야된다
- 기술이 중요한게 아니라 도메인/업무가 중요하다
- 초기 설계는 중요하지만 전체 플로우를 모르면 일단 기능이 되게 만들어 놓고 리팩토링을 반복, 어쩔 수 없는 과정
- 네트워크, 인프라, os 개념이 연차가 쌓일수록 더더욱 중요하다
- 규모에 맞게 생각하고 설계하고 개발해야된다
- 고품질 소프트웨어
    -  `고품질 소프트웨어` = `잘 설계된 도메인 디자인` + `읽기 쉬운 코드`
    -  `잘 설계된 도메인 디자인` = `사용자의 업무과정` + `응집도가 낮은 설계`
    -  `읽기 쉬운 코드` = `도메인 기준 코드 분리` + `통일된 네이밍 규칙`
-  효과
    - 추가요구사항 처리 및 확장에 용이 -> 추가 요구사항 개발 기간 단축
    - 유지보수 용이
    - 리팩토링 및 프로젝트 개편에 용이

-   네이밍 규칙
    - 객체/클래스 = 도메인, 데이터 영역 별 네이밍 `Product`, `Admin`, `ProductDAO`, `ProductDTO`
    - 메서드 = 기능동사 + 조건  `Product.addItem()`, `ProductDAO.getProductById(id)`
