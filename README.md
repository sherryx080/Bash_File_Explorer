# Bash_File_Explorer

File Explorer make by Bash Shell script

#FileExplorer.sh
-----
제일 기본적인 파일 탐색기. 
실행시 왼쪽에 현 디렉토리에 있는 파일이 출력된다. 이는 디렉토리, 실행파일, 일반파일 순으로 정렬되며 각기 다른 색으로 출력된다.
또한 각 파일은 이름과 권한 용량이 출력되며 키보드 상하좌우를 이용해서 커서를 움직일 수 있고, 엔터키로 디렉토리에 진입할 수 있다.
원래 오른쪽에 현 디렉토리에 있는 모든 파일들을 Tree UI로 구현할려 했지만 시간이 부족해 중단했다.

#CFileMake.sh
-----
FileExplorer.sh 에서 조금 다른 기능이 추가되었다.
기본적인 파일 탐색기능은 동일하나, 오른쪽 UI에 .c, .h 파일만 정렬된다. 
이때 오른쪽 UI에서 "m"버튼을 누르면 make 파일이 만들어진다.
