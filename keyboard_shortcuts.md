# 단축키 

`파일 > 기본 설정 > 바로가기 키` 에서 현재 활성화된 키보드 단축키 확인이 가능합니다.

## 기본 편집

| 키 | 명령 | 명령ID |
|----|------|--------|
|ctrl+X | 행 삭제 (빈 선택) | editor.action.clipboardCutAction
|ctrl+C | 행 복사 (빈 선택) | editor.action.clipboardCopyAction
|ctrl+shift+k |행 삭제| editor.action.deleteLines   
|ctrl+Enter | 아래에 행 삽입 |editor.action.insertLineAfter 		
|ctrl+shift+Enter | 위에 행 삽입 |editor.action.insertLineBefore 		
|alt+Down | 행을 아래로 이동 |editor.action.moveLinesDownAction		
|alt+Up |행을 위로 이동 |editor.action.moveLinesUpAction
|shift+alt+Down|위에 행 복사 추가 |editor.action.copyLinesDownAction  			
|shift+alt+Up|	아래에 행 복사 추가|editor.action.copyLinesUpAction
|ctrl+d|	다음 선택 찾기|	editor.action.addSelectionToNextFindMatch
|ctrl+k ctrl+d|	마지막 선택 항목을 다음 찾기 항목으로 이동|	editor.action.moveSelectionToNextFindMatch
|ctrl+u|	마지막 커서 작업 실행 취소|	cursorUndo
|shift+alt+i|	선택한 각 줄 끝의 커서 삽입|	editor.action.insertCursorAtEndOfEachLineSelected
|ctrl+shift+l|	현재 선택 항목을 모두 선택|	editor.action.selectHighlights
|ctrl+f2|	현재 단어의 모든 항목 선택	|editor.action.changeAll
|ctrl+i|	현재 행 선택	expandLineSelection
|ctrl+alt+Down|	커서를 아래에 추가|	editor.action.insertCursorBelow
|ctrl+alt+Up|	커서를 위에 추가|	editor.action.insertCursorAbove
|ctrl+shift+\ |	일치하는 대괄호로 건너 뛰기|	editor.action.jumpToBracket
|ctrl +]	|라인 들여쓰기|	editor.action.indentLines
|ctrl+[	|라인 내어쓰기|	editor.action.outdentLines
|Home	|행의 시작으로 이동|	cursorHome
|End	|행의 끝으로 이동|	cursorEnd
|ctrl+End |파일 끝으로 이동|	cursorBottom
|ctrl+Home |파일 시작으로 이동|	cursorTop
|ctrl+Down	|스크롤 다운|	scrollLineDown
|ctrl+Up	|스크롤 업|	scrollLineUp
|alt+PageDown	|아래로 페이지 스크롤|	scrollPageDown
|alt+PageUp	|페이지 위로 스크롤|	scrollPageUp
|ctrl+shift+[	|영역 접기|	editor.fold
|ctrl+shift+]	|영역 펼치기|	editor.unfold
|ctrl+k ctrl+[	|현재 영역 접기|	editor.foldRecursively
|ctrl+k ctrl+]	|현재 영역 펼치기|	editor.unfoldRecursively
|ctrl+k ctrl+0	|모든 영역 접기|	editor.foldAll
|ctrl+k ctrl+j	|모든 영역 펼치기|	editor.unfoldAll
|ctrl+k ctrl+c	|행 주석 추가|	editor.action.addCommentLine
|ctrl+k ctrl+u	|행 주석 제거|	editor.action.removeCommentLine
|ctrl+/	|주석 토글|	editor.action.commentLine
|shift+alt+a	|커서위치에 주석 토글|	editor.action.blockComment
|ctrl+f	|찾기|	actions.find
|ctrl+h	|바꾸기| editor.action.startFindReplaceAction
|f3	|다음 찾기|	editor.action.nextMatchFindAction
|shift+f3	|이전 찾기|	editor.action.previousMatchFindAction
|alt+Enter	|모든 일치 항목을 선택|	editor.action.selectAllMatches
|alt+c	|대소 문자 찾기를 토글|	toggleFindCaseSensitive
|alt+r	|정규식 찾기 전환|	toggleFindRegex
|alt+w	|전체 단어 찾기 토글|	toggleFindWholeWord
|ctrl+m	|포커스 설정을 위해 Tab 키 사용 토글|	editor.action.toggleTabFocusMode
|할당되지 않음	|렌더링 공백을 토글합니다.|	toggleRenderWhitespace
|alt+z	|단어 감싸기 토글|	editor.action.toggleWordWrap




# 마크다운 미리보기

단축키: `ctrl+shfit+v`  
또한 옆에서 미리보기를 하면서 수정까지 실시간으로 반영되게 할 수도 있습니다.

![markdown](./img\20190317205420.png)

참고 URL   
> https://demun.github.io/vscode-tutorial/shortcuts/