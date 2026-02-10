# 머신러닝 스터디
혼자 공부하는 머신러닝 + 딥러닝을 함께 공부하는 스터디입니다.

## Study Flow
1. 매주 정해진 분량 학습
2. 개인별 코드/노트 정리
3. Pull Request 제출
4. 주간 미팅에서 질의응답

## Guide
### 1. 레포 클론(최초 1회)
#### 명령 프롬포트에 아래 코드 붙여넣기
```
git clone https://github.com/pandasneeze/MachineLearning.git
```
<img width="151" height="42" alt="image" src="https://github.com/user-attachments/assets/c9368ada-3b92-4992-ba49-fe834c593d30" /><br>
- 명령 프롬포트에 나타난 경로에 파일 자동 생성됨<br>
#### vs code에서 해당 폴더 경로 찾아서 열기
<img width="342" height="220" alt="image" src="https://github.com/user-attachments/assets/3aad52a9-e4f0-4fc3-97ea-a4e044dc1c36" /><br>
`ctrl`+ `~`로 터미널 열기

### 2. 자기 이름 브랜치 만들기(최초 1회)
```
git branch 자기 이름
git push -u origin 자기 이름
```
⚠️ master로 직접 push 금지

### 3. 자신의 브랜치, 폴더에서만 작업
- `git branch`: 현재 브랜치 확인 가능
- `git switch -c 브랜치 이름`으로 브랜치 이동 가능
- 파일 구조 예
```
03 회귀 알고리즘/
 └─ 이름/
    ├─ 내용 정리.md
    └─ linear_regression.ipynb
```
⚠️ 작업을 하기 전 깃허브에서 pull을 해야 충돌이 생기지 않음
```
git pull origin 브랜치이름
```
### 4. 파일 push하기
```
git add .
git commit -m "커밋 메시지"
git push origin 브랜치이름
```
⚠️ master가 아닌 본인 이름 브랜치로 push

### 5. PR 올리기(미팅 전까지)
**PR 내용**
- 무엇을 배웠는지 간단하게 요약
- 이해 안 된 점
- 토론하고 싶은 점
