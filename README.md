# github-practice
Github의 Issue, Project 기능 설명 및 실습을 위한 레파지토리입니다.

## 1. Project 추가하기
- Projects 탭에서 두번째 Projects 항목을 선택합니다.
- New project 버튼을 눌러 새로운 프로젝트를 추가 할 수 있습니다.
- 프로젝트의 이름과 설명을 작성하고, Template은 Automated Kanban 항목을 선택합니다.
- 

## 2. Issue 추가하기
- 이슈 탭에서 New issue 버튼을 눌러 이슈를 추가 할 수 있습니다.
- 제목과 내용을 작성하고, 오른쪽 탭에서 Projects를 눌러 이전에 추가한 프로젝트를 선택 할 수 있습니다.
- 또한 담당자(Assignees), 태그(Labels) 등의 항목을 지정 할 수 있습니다. 
- 작성이 완료되면 Submit new issue 버튼을 눌러 이슈를 생성합니다.
- 연결된 프로젝트에서 Issue가 등록된 것을 확인 할 수 있습니다.

## 3. Commit으로 Issue 해결하기
- Issue에 해당하는 내용을 해결하는 코드를 작성했다고 가정합니다.
- commit 메세지에 close keyword와 Issue 번호를 함께 작성합니다.
  ex) `fix download bug #1`
    -> 여기서 fix가 close keyword, #1이 Issue 번호입니다.
- push 되면 Issues 탭에서 close 된 #1 이슈를 확인합니다.
- #1 Issue에 연결된 프로젝트에서도 Done으로 이동한 #1을 확인 할 수 있습니다.

## 4. PR로 Issue 해결하기
- PR은 PullRequest의 약자입니다. PR은 Branch를 통해서만 이루어진다고 가정합니다.
- Branch를 생성하고, 코드를 작성하여 해당 Branch에 푸시합니다.
- PR을 작성합니다. Issue와 마찬가지로 오른쪽 탭에서 프로젝트를 연결 할 수 있습니다.
- 내용에 해결 할 Issue의 번호와 키워드를 함께 작성하는 것으로 이 PR이 push 되었을 때, Issue가 함께 close 되도록 할 수 있습니다.
- PR 작성이 완료되면, 연결된 프로젝트에서는 In progress에 PR이 생성됩니다.
- PR 작성이 push 되면, 연결된 Issue와 PR이 함께 done으로 이동합니다.
