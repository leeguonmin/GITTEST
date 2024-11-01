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

