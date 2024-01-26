import random
import statistics

# 랜덤한 숫자의 리스트 생성
data = [random.randint(0, 100) for _ in range(10)]
print(f"Generated Data: {data}")

# 기본 통계 계산
mean = statistics.mean(data)
median = statistics.median(data)
mode = statistics.mode(data)

print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Mode: {mode}")

test11
