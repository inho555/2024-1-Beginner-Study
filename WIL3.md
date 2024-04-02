# git log
 commit 기록을 최신 순으로 확인
 옵션을 사용하면 각 커밋을 한 줄에 요약
# HEAD
 HEAD는 현재 작업 중인 위치를 가리킨다.	
 현재 작업중인 브랜치의 가장 최근 commit
 다음 commit의 base가 되는 commit
 새로운 commit이 생기면 HEAD도 변경
# commit --amend
 마지막 commit의 내용에 변$이 있을 때 사용한다.
 완전히 새로운 commit으로 대체한다.
 vim으로 진입하여 commit 메시지를 수정하게 된다. 
다른 사람이 작업 기반으로 삼고 있는 commit은 amend하면 안됨!
## reset --soft
 커밋만 취소
 변경 사항이 Staging Area로 돌아감
## reset --mixed
 커밋을 취소
 변경 사항이 working directory로 돌아감
## reset --hard
 커밋을 취소
 변경 사항을 모두 제거하고 이전 커밋으로 돌아감