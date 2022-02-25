---
status-success: ':white_check_mark:'
status-fail: ':x:'
activity1-success:
activity1-fail: Not sure how you got to this point without accepting the assignment. There is probably a bug in the marking code. Please submit an issue to https://github.com/markpatterson27/GitHub-Classroom-Introductory-Assignment/issues.
activity2-success: Yay. You made a commit.
activity2-fail: |
  A commit authored by you has not been found.
  <details>
    <summary>How to make a git commit</summary>
    
    **Clone** - [Clone](https://github.com/git-guides/git-clone) the repository to your local machine.

    \`\`\`
    git clone https://github.com/${GITHUB_REPOSITORY}.git
    \`\`\`

    **Edit** - Edit and save the files.

    \`\`\`
    cd ${REPO_NAME}
    code editme.md
    \`\`\`

    **Add** - [Add](https://github.com/git-guides/git-add) the changes to staging.
    
    \`\`\`
    git add editme.md
    \`\`\`

    **Commit** - [Commit](https://github.com/git-guides/git-commit) the changes to the git repo.

    \`\`\`
    git commit -m \"asked a question in editme.md\"
    \`\`\`

    **Push** - [Push](https://github.com/git-guides/git-push) the new commits back to the remote repository.

    \`\`\`
    git push origin main
    \`\`\`
  </details>
activity3-success: Interesting comment.
activity3-fail: Leave a comment below.
quiz-success: Five out of five. All questions answered correctly. Well done.
---

## Auto-Feedback

### ${status-activity1} Activity 1 - Accept assignment

${fb-activity1}

### ${status-activity2} Activity 2 - Make commit

${fb-activity2}

### ${status-activity3} Activity 3 - Comment on Feedback PR

${fb-activity3}

### ${status-quiz} Quiz

${fb-quiz}

Autograding Score: ${points}
