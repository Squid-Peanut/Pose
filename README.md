---

## 1. calculate_angle(point1, point2, point3)
설명: 이 함수는 2D 공간에서 세 점 사이의 각도를 계산. 

### 매개변수:

point1, point2, point3: 각도를 계산할 세 점을 나타냅니다. 각 점은 x와 y 좌표를 포함하는 튜플 또는 리스트여야 합니다.
반환값:

세 점 사이의 각도를 도(degree) 단위로 반환합니다. 여기서 point2가 각도의 정점입니다.



## 2. is_outlier(current_point, previous_point, threshold=50)
설명: 이 함수는 현재 키포인트의 위치가 이전 위치와 비교하여 이상치(outlier)인지 확인. 오차나 예상치 못한 움직임으로 인한 노이즈를 필터링.

### 매개변수:

current_point: 현재 키포인트의 위치를 나타내는 배열 또는 리스트 (x, y 좌표 포함).
previous_point: 이전에 감지된 같은 키포인트의 위치.
threshold: 현재와 이전 위치 간의 최대 허용 거리를 정의. 기본값은 50 px
### 반환값:

현재 키포인트가 이상치인 경우 True, 그렇지 않으면 False를 반환.

---

### CSV 파일로 정리되어있음 (83부터 슛포즈 시작) 
