## AIFFEL Campus Online Code Peer Review Templete
- 코더 : 서승호
- 리뷰어 : 오선우


## PRT(Peer Review Template)
- [O ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
```
물고기의 이름을 입력하세요: 모리
모리의 속도를 입력하세요 (m/s, 정수로 입력): 3
또 다른 물고기의 이름을 입력하세요: 도리
도리의 속도를 입력하세요 (m/s, 정수로 입력): 5
Using Comprehension:
모리 is swimming at 3 m/s
도리 is swimming at 5 m/s
```
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
```
# 물고기 움직임 출력 함수 (컴프리헨션)
def show_fish_movement_comprehension(fish_list):
    print("Using Comprehension:")
    for fish in fish_list:
        name = fish["이름"]
        speed = fish["속도"]
        print(f"{name} is swimming at {speed} m/s")

# 물고기 움직임 출력 함수 (제너레이터)
def show_fish_movement_generator(fish_list):
    print("Using Generator:")
    for fish in fish_list:
        yield f"{fish['이름']} is swimming at {fish['속도']} m/s"
 ```       
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
```
주어져있는 물고기 리스트 정보로 수행하는 퀘스트였으나 input값으로 대체하여 입력받은 값으로 수행하는 코드를 진행
```   
        
- [X]  **4. 회고를 잘 작성했나요?**
```
회고는 작성되어있지 않은 것 같습니다.     
```
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
```
# 물고기 움직임 출력 함수 (컴프리헨션)
def show_fish_movement_comprehension(fish_list):
    print("Using Comprehension:")
    for fish in fish_list:
        name = fish["이름"]
        speed = fish["속도"]
        print(f"{name} is swimming at {speed} m/s")

컴프리헨션 구문을 사용해서 좀 더 간단히 나타낼 수 있을 것 같습니다. 

def show_fish_movement_comprehension(fish_list):
    print("Using Comprehension:")
    [print(f"{fish['이름']} is swimming at {fish['속도']} m/s") for fish in fish_list]

```    


## 참고 링크 및 코드 개선
```
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

