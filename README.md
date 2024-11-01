# GIT 과 GITHUB
## GIT

- GIT : **분산** 버전 관리 시스템 (중앙 집중 저장소가 없음)
- GITHUB : **원격 GIT 저장소**


### Local Git 

- 저장소 생성
```bash
git init
```


- GIT 설정
```bash
git config user.name "GeonMin Lee"
git config user.email l_lpp@naver.com
# 공용 git 설정을 하려면 -g
# 예) git config -g user.name 이름
#꼭 자기만 쓰는 컴퓨터에만 설정하도록
```

- git 상태 확인
```bash
git status
```

- staging 
```bash
git add .
```

- 저장소에 반영 (commit)
```bash
git commit -m "First Commit"
# -m은 메세지를 의미 
```

- 상태 확인과 로그 확인
```bash
git status # 상태 확인
git log # 로그 확인 
```

### Local Git to GitHub
- GitHub에서 저장소 생성 (원격 저장소 생성)
- 저장소 주소 (원격지 주소 확인)
    - https://github.com/leeguonmin/GITTEST.git


- 원격지 등록
```bash
git remote add origin https://github.com/leeguonmin/GITTEST.git
# git remote add 저장소이름 저장소주소
```

- PUSH
```bash
git push -u origin master # 첫번째 푸시
git push # 기본원격지 현재브랜치를 푸시
```


- 저장소 설정 



- 원격지 변경 사항 확인 
```bash
git fetch
```

- 원격지 변경 사항 pull (내려받기)
```bash
git pull
```





