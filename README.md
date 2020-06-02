# Week1

## [문제로 이동](./PROBLEM.md)

## 내 컴퓨터에 문제 다운로드 받기

### 1. 터미널을 켜서 원하는 폴더 위치로 이동

- 폴더 목록을 확인하는 명령어

```sh
ls
```

![image](https://user-images.githubusercontent.com/30258523/83059687-42d44400-a095-11ea-9c92-708654816b31.png)

- 폴더를 이동하는 명령어

```sh
# 현재 폴더에 있는 다른 폴더로 이동
cd 원하는 폴더 이름

# 이전 폴더로 이동
cd ..
```

![image](https://user-images.githubusercontent.com/30258523/83060205-11a84380-a096-11ea-8f8f-80be38c1aab6.png)

### 2. 프로젝트의 저장소를 내 컴퓨터로 clone

- clone은 다른 사람의 저장소를 내 컴퓨터로 복사해오는 것을 의미합니다.

```sh
git clone https://github.com/madesignoper/week1.git
```

### 3. 작업 branch 생성

- branch는 다른 사람과 작업 공간이 겹치는 것을 방지하는데 도움을 주는 기능입니다.

```sh
cd week1 # clone해서 만들어진 폴더로 이동
git checkout -b 자기 영어 이름(내 브랜치 이름이 됨) # ex) git checkout -b jisu
```

## 내가 푼 문제 업로드

### 1. 터미널을 실행하고 clone을 해서 만들어졌던 폴더로 이동합니다.

### 2. 다음과 같이 입력해서 원격에 내가 푼 문제를 올리도록 합니다.

```sh
git add .
git commit -m "[본인이름] X주차 문제 풀이 완료"
git push origin 본인 브랜치 이름(본인 영어 이름)
# ex) git push origin jisu
```
