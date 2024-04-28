## 📜 Info

- 첫 번째 네트워킹 때 사용했던 레포지토리에서 이어서 작업합니다.
- `DB 연결 등 환경 설정은 자유롭게 진행합니다.`
- 과제를 완료한 후 Pull Request 를 만든 후 하단의 표에 각자의 Pull Request 주소를 적어주세요.
    
    Pull Request의 제목은 `[이름] 3차 과제 제출` 로 통일합니다!
    
    ex) `[김민욱] 3차 과제 제출`
    
- 정리한 글의 링크의 주소도 하단의 표에 적어주세요.
- 네트워킹 및 과제 불성실하게 참여 시 벌점이 부과될 수 있습니다.
- 구현하지 못하더라도 본인의 역량 내에서 최대한 수행해주시면 감사하겠습니다!

## 📜 Scenario & **Requirement**

### 시나리오

- 김감자의 부모님은 김감자가 만들어준 서버를 사용해 분업에 성공했습니다.
- 이 소문을 들은 `거대 부동산 기업 A`가 김감자에게 컨택해왔습니다.
- A 기업은 매물정보 수십만개가 들어있는 엑셀 파일을 DB에 넣어주길 요구했습니다.
- 많은 양의 데이터를 다뤄본 적 없는 김감자는 걱정하기 시작했습니다,,,,
- 하지만 거절하기엔 엄청난 커미션을 제시했기에 김감자는 일단 인텔리제이를 켰습니다.

### 사용 기술

- **Spring Data JPA**
- **MySQL**

### ⚠️⚠️⚠️⚠️⚠️사전 작업⚠️⚠️⚠️⚠️⚠️

- 1차 과제에서 fork를 하지 않았다면 꼭 fork한 후 진행해주세요!
- 1차 과제에서 본인의 브랜치를 생성하지 않았다면 꼭 생성 후 진행해주세요!

### 요구사항

1. **시간 측정 및 정리 글 작성**
    
    **기존 코드 시간 측정**
    
    - 지난 과제에서 테스트 데이터를 삽입하는 코드를 재활용합니다.
    - 기존 코드를 사용해 아래 엑셀 파일을 DB에 삽입하고 소요 시간을 측정합니다.
        
        [서울시_20만개.xlsx](https://prod-files-secure.s3.us-west-2.amazonaws.com/575cb811-b2db-4171-8046-616e405dd733/b93296ef-14e5-40a4-b4b3-0ab3c1dffda7/%EC%84%9C%EC%9A%B8%EC%8B%9C_20%EB%A7%8C%EA%B0%9C.xlsx)
        
    
     
    
    **성능 개선 및 시간 측정**
    
    - `jpa bulk insert` 와 같은 키워드들로 검색하여 최소 2가지 이상 방법으로 시간을 단축합니다.
    - 각 방법 별로 메소드를 분리하고 시간을 측정합니다.
    - 메소드 단위로 방법을 분류할 수 없다면 편한 방식으로 진행하고 기록해도 좋습니다.
    
    <aside>
    ⚠️ 꼭!!! 시간 측정 전에 테이블을 drop 후 측정해주세요!
    
    </aside>
    
    **정리 글 작성**
    
    - 방법 별 소요 시간을 표로 정리하여 정리 글에 첨부합니다.
    - 각 방법을 구현하며 알게된 지식, 원리 등을 각자 자유형식으로 노션이나 블로그에 기록합니다.
