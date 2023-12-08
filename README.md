# OSS 
### 저장소 구축 과제
**6가지 기본 설정**
- 사용자 설정
- > ```git
  > $ git config --global user.name '사용자이름'
  > $ git config --global user.email '사용자 메일주소'
  > ```

- 맥과 윈도 간의 자동 변환
- > ```git
  > $ git config --global core.autocrlf true
  > ```

- 뉴라인 경고 발생 없애기(옵션)
- >```git
  >$ git config --global core.safecrlf false
  >```
- 기본 편집기 설정
- > ```git
  > $ git config --global core.editor 'code --wait'
  > ```
- 깃 저장 기본 브랜치 이름 설정
- >```git
  >$ git config --global init.defaultBranch main
