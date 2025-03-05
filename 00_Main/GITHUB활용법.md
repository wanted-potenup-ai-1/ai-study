# AI-STUDY Repository 사용법

## 1. 레포지토리 로컬 컴퓨터에 받기

```
git clone "깃허브주소"
```

## 2. 내 이름의 브랜치 만들기

```
git branch -b "브랜치이름"
```

## 3. 작업

```
git add .       # 전체 스테이징 영역으로 이동
git commit
git push origin "브랜치이름"
```

## 4. GITHUB 웹에서 내 브랜치 들어가기 


## 5. PULL REQUEST

내 브랜치에 작업 내용이 있으면 이를 main 브랜치에 적용할 필요가 있다. 이를 위해서는 PULL REQUEST로 main에 Merge 해달라고 요청을 해야 한다. 

## 6. MAIN에서 최신 기록 가져오기

main 브랜치에서 PULL REQUEST 내용에 대해 Merge 작업을 진행하면, 로컬에서는 자신이 만든 브랜치에 Main의 작업을 가져와야 한다. 

```
git pull origin main
```

## 7. 반복

3번부터의 과정을 반복한다. 