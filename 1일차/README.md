## VSCode 개발 환경 설정

1. Extension 설치 리스트
 - Extension Pack for Java
 - Git Extension Pack

2. JDK 설치

3. 프로젝트 settings.json 파일 설정
 - Ctrl + Shift + P → Open Workspace Settings (JSON) 검색 후 Enter
 - 자동으로 프로젝트 폴더 내 .vscode/settings.json 생성 및 열린후 아래 코드 입력
{
   "emmet.excludeLanguages": ["java"]
}

4. Git 환경 설정 하기
 - cd 프로젝트경로
 - git init
 - git config --global user.name "이근호"
 - git config --global user.email "your@email.com"
