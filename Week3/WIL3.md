## What-I-Learned

commit --ammend 
-마지막 commit의 내용에 변경이 있을 때 사용
-완전히 새로운 commit으로 대체
-commit id가 바뀜
-vim으로 진입하여 commit 메시지를 수정하게 됨

reset
-commit을 제거하는 데 사용
-돌아갈 commit의 id를 사용
$ git reset ‘--option’ “<commit id>”

reset --soft
-커밋만 취소
-변경 사항이 Staging Area로 돌아감

reset --mixed
-커밋을 취소
-변경 사항을 working directory로 돌아감

reset --hard    
-커밋을 취소
-변경 사항을 모두 제거하고 이전 커밋으로 돌아감

revert
-commit을 제거하지 않고 되돌림
-되돌리기 위한 새로운 commit이 생성

revert --no-edit
-편집기 진입 없이 바로 revert 가능

revert --no-commit
직접 commit 하지 않고, revert 내용을 Staging Area에 올림
