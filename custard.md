rachelskim@MacBook-Air clonetest % git branch
  develop
* feature/button
  main
rachelskim@MacBook-Air clonetest % git switch develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.
rachelskim@MacBook-Air clonetest % git merge feature/button
Updating 76d6535..227e903
Fast-forward
 button.js | 7 +++++++
 1 file changed, 7 insertions(+)
 create mode 100644 button.js
rachelskim@MacBook-Air clonetest % git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/loafcheck/clonetest.git
   76d6535..227e903  develop -> develop
rachelskim@MacBook-Air clonetest % git branch -d feature/button
Deleted branch feature/button (was 227e903).
rachelskim@MacBook-Air clonetest % git push
Everything up-to-date
rachelskim@MacBook-Air clonetest % git push origin --delete feature/button
To https://github.com/loafcheck/clonetest.git
 - [deleted]         feature/button
rachelskim@MacBook-Air clonetest % 
