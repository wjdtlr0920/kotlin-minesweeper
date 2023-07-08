# kotlin-minesweeper

## Step 1. 지뢰 찾기(그리기)

- 높이와 너비, 지뢰 개수를 입력받을 수 있다.
- 지뢰는 눈에 잘 띄는 것으로 표기한다.
- 지뢰는 가급적 랜덤에 가깝게 배치한다.

## Step 2. 지뢰 찾기(지뢰 개수)

- 각 사각형에 표시될 숫자는 자신을 제외한 주변 8개 사각형에 포함된 지뢰의 개수다.

## Step 3. 지뢰 찾기(게임 실행)

- 지뢰가 없는 인접한 칸이 모두 열리게 된다.

## Step 4. 지뢰 찾기(리팩터링)

- 불필요한 delegation 로직을 줄일 수 있게 List<List<BoardPoint>> 구조를 Map<Position, BoardPoint> 구조로 리팩토링