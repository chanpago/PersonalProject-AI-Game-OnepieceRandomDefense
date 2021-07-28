# PersonalProject-AI-Game-OnepieceRandomDefense
## 인공지능을 이용한 워크래프트 유즈맵 "원피스랜덤디팬스" 자동 클리어 프로그램
![image](https://user-images.githubusercontent.com/69561410/127288286-99fe75ad-5ad9-48bb-898a-1ab659668884.png)
![image](https://user-images.githubusercontent.com/69561410/127288324-0f62430b-d882-4217-a2f4-15cfb7b78db4.png)
![image](https://user-images.githubusercontent.com/69561410/127288356-fdc13bb3-6268-4f45-8832-f55ab90ce35e.png)
![image](https://user-images.githubusercontent.com/69561410/127288387-f911f1f2-95a9-4332-a301-291d95e581cb.png)
![image](https://user-images.githubusercontent.com/69561410/127288401-c8570797-6026-4cb7-a787-2d9860ae141c.png)
![image](https://user-images.githubusercontent.com/69561410/127288416-c8e1a709-4a67-4125-8e18-f1c0e9d3a74f.png)
---
# 1. 목적
> "원피스랜덤디팬스"라는 게임은 클리어 횟수에따라 조합을 해서 갈 수 있는 상위유닛의 폭이 다름(클리어 횟수가 낮을 경우 갈 수 있는 상위유닛 제한!)

> 또한 클리어 횟수에따라 칭호가 다른데 이 프로그램을 이용하여 별다른 노력없이 클리어 횟수를 쌓고 싶었음

![image](https://user-images.githubusercontent.com/69561410/127290102-e08bcb57-7f4e-41e9-ae83-23aba8382be6.png)

# 2. 원랜디란?

>말 그래도 랜덤으로 나오는 유닛을 조합하여 더 쌘 상위유닛을 만들어서 돌아가는 라인을 막으면 클리어인 게임

>난이도는 쉬움, 보통, 어려움, 지옥, 신, 악몽이 있으며 난이도가 올라갈수록 나오는 몹들의 체력, 마법방어력, 물리방어력이 올라감

![image](https://user-images.githubusercontent.com/69561410/127293981-315e2d9c-fda5-4071-82ab-1347fdb5cd3b.png)

>처음에 난이도를 설정가능

![image](https://user-images.githubusercontent.com/69561410/127294284-f06d2b6b-edd6-4c77-b903-8e3e48557efe.png)

>라운드가 시작할 때 마다 위습을 통하여 어느곳에 선택을 할지 결정할 수 있음 1라운드당 2개의 위습을 받음

![image](https://user-images.githubusercontent.com/69561410/127294556-bc16d43c-1257-400e-a315-07ee4e186653.png)

>내 유닛이 있는 장소 11시방향의 포탈에서 디펜스를 할 유닛들이 나옴 (1라운드당 40마리)

![image](https://user-images.githubusercontent.com/69561410/127294874-e50b9b1e-60fa-48c0-9135-c3010af9f6ed.png)

>만약 위습을 유닛랜덤에 넣었다면 "흔함"등급의 유닛들이 지정한 칸으로 들어감

![image](https://user-images.githubusercontent.com/69561410/127295165-8e90569a-80cf-4999-b69f-31653101c607.png)

>맵의 우측 하단을 보면 유닛의 조합법이 표기되어 있음. 이 조합법을 보고 상위 유닛을 만들어서 나오는 몬스터들을 막으면됨. 위습을 '유닛 랜덤'에 넣었다면 제공되는 유닛은 "흔함"등급이며 최하위 등급임

>등급은 흔함 < 안흔함 < 특별함 < 희귀함 < 전설적인 = 히든조합 = 변화된 < 제한됨 = 초월함 = 영원함 = 불멸의 등급으로 나누어짐

>10라운드 마다 라인에서 보스가 나옴

>라운드별로 깨주어야하는 스토리가 있음

# 3.어떻게 자동화 할 것인가?
