# git_test
깃허브 연습용

자주 쓰는 명령어

git init 									현재 위치에서 git 시작 .git 파일이 없으면 자동으로 생성됨 
										(.git에는 git으로 생성한 버전 정보와 원격 저장소 주소 등이 들어가 있음)
git config --global user.email ""					""안에 자신의 이메일 입력 (이메일 정보 저장)
git config --global user.name ""					""안에 자신의 이름입력 (이름 정보 저장)
git add 파일      								지정한 파일을 커밋
git commit -m "내용입력"						"" 안의 내용을 커밋의 설명으로 추가
git log									커밋기록  확인. 커밋한 사람의 이름과 이메일을 확인 가능
git checkout 커밋코드앞7자리 혹은 전체				로그에 적인 커밋 코드 앞7자리나 전체를 적어 해당 버전으로 롤백
git checkout -								최신 커밋으로 되돌리기
git remote add origin 원격저장주소				원격저장장소 설정
git push origin master							원격저장소에 올리기
git clone 원격저장소주소						원격저장소주소원격저장소의 파일 워킹트리에 다운받기
git pull origin master							원격 저장소의 수정파일을 로컬 파일에 반영하기

git status									git저장소 상태를 나타내는 명령
git status -s								git staus 보다 간단한 정보를 보여줌 변겨오딘 파일 많을때 좋음

-----------------------------------------------------------------------------------------------------------------------------------------------------------

옵션 설정 

git config									git 옵션들 표시


-----------------------------------------------------------------------------------------------------------------------------------------------------------

Git에서 쓰는 기본적인 유닉스 계열 명령어

pwd										현재 위치
ls 										현재 디렉토리 파일 
ls -a										현재 디렉토리의 모든 파일(숨김 처리된 파일도 표시)
mkdir										디렉토리 생성
cd 										홈 디렉토리로 이동
cd 하위디렉토리명							지정한 하위 디렉토리로 이동
cd ../										상위 디렉토리로 이동





