heroes = [ ]
heroes.append("아이언맨")
['아이언맨']
heroes.append("닥터 스트레인지")
print(heroes)
['아이언맨', '닥터 스트레인지']


letters = ['A', 'B', 'C', 'D', 'E', 'F']
print(letters[0])
A
print(letters[1])
B
print(letters[2])
C



letters = ['A', 'B', 'C', 'D', 'E', 'F']
print(letters[0:3])
['A', 'B', 'C']


print(letters[:3])
['A', 'B', 'C']
print(letters[3:])
['D', 'E', 'F']
print(letters[:])
['A', 'B', 'C', 'D', 'E', 'F']


heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
heroes[1] = "닥터 스트레인지"
print(heroes)
['아이언맨', '닥터 스트레인지', '헐크', '스칼렛 위치']

heroes.append("스파이더맨")
print(heroes)
['아이언맨', '닥터 스트레인지', '헐크', '스칼렛 위치', '스파이더맨']
heroes.insert(1, "배트맨")
print(heroes)
['아이언맨', '배트맨', '닥터 스트레인지', '헐크', '스칼렛 위치', '스파이더맨']



heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
heroes.remove("스칼렛 위치")
print(heroes)
['아이언맨', '토르', '헐크']


if "슈퍼맨" in heroes:
heroes.remove("슈퍼맨")



heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
del heroes[0]
print(heroes)
['토르', '헐크', '스칼렛 위치']


heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
last_hero = heroes.pop()
print(last_hero)
스칼렛 위치



heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
print(heroes.index())
2


heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
for hero in heroes:
print(hero)
아이언맨
토르
헐크
스칼렛 위치


heroes = [ "아이언맨", "토르", "헐크", "스칼렛 위치" ]
heroes.sort()
print(heroes)
['스칼렛 위치', '아이언맨', '토르', '헐크']
