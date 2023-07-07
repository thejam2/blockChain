# blockChain

## 특징
### 1. 자율 분산 시스템
- 많은 노드가 같은 데이터를 마치 배턴을 전달하는 것처럼 복사하며, 모든 노드의 동작도 같습니다.
- 일부 노드가 고장 나는 정도로는 전체 시스템의 동작에 지장을 주지 않습니다.

### 2. 리더가 없는 구조
- 정해진 역할이 없습니다. 모든 노드의 역할과 동작이 같습니다.따라서 어떤 노드가 고장 났을 때 시스템이 중단된다는 약점이 없습니다.

### 3. 지갑 주소
- 블록체인은 공개 키 암호의 '공개 키'와 '비밀 키' 쌍으로 지갑 주소에 대응합니다.
- 지갑 주소는 얼마든지 마음대로 만들 수 있습니다.

### 4. 트랜잭션
- 블록체인은 지갑 주소의 현재 잔액을 모릅니다. 과거 거래의 모든 내용을 기록할 뿐입니다.
- 현재 잔액이 얼마인지 알고 싶다면 사용자가 지갑 주소 안 트랜잭션 내용의 증가와 감소를 모두 합해야 합니다.

## 종류
### 퍼블릭 체인
- 네트워크에 참여한 노드 개수 파악 불가능
- 참여자 수 제한 X
- 악의적 사용자 있을지 모르지만 과반수가 넘는 선의적 사용자 있다면 문제 없음. 따라서 보상 있음.

### 프라이빗 체인
- 네트워크에 참여한 노드 개수 파악 가능
- 참여자 수 제한 O
- 노드수 적어서 속도 빠름.
- 일반적으로 다수결 합의 알고리즘 선택하므로 보상 필요 없음.

## 장단점
- 관리자가 없어도 정상 동작 (데이터 변조와 변경이 불가능 하기 때문)
- 서비스 제공자의 신뢰도가 낮아도 안심하고 이용 가능
- 누구에게나 데이터 공개, 삭제 불가

## 비트코인
- 20년9월 기준 64만블록, 10분마다 블록 1개 연결
- 첫번째 블록 = 제네시스 블록
- 초기 발행량 약 2100만 BTC

### 비트코인 처음 사용 시 필요한 사항
1. 실제화폐
2. 지갑
3. 거래소 계좌

#### 지갑 종류
- 거래소 지갑 (서비스 제공자가 관리)
- 웹 지갑 (서비스 제공자가 관리)
- 모바일 지갑 (사용자가 관리)
- 종이 지갑 (사용자가 관리)

## 한국 주요 거래소
- 고팍스
- 빗썸
- 업비트
- 코인원

## 지갑 공개키, 비밀키
- 공개키 -> 계좌번호
- 비밀키 -> 계좌 비밀번호

## 블록체인의 알고리즘
블록체인에서는 타원 곡선 디지털 서명 알고리즘이라는 공개 키 암호를 많이 사용

## 해시 함수
임의의 값을 넣었을 때 어떤 값을 반환 할지 예상 불가, SHA2-256 알고리즘, 출력값은 항상 64자리의 16진수
