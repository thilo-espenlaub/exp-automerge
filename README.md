# exp-automerge

Changes to the README.md so that I can create a PR

Trigger build... automerge feature is enabled but actions do not contain `gh pr merge --auto --merge`. what happens? Not much: the PR is stays open after build passed


Another experiment... automerge feature is disabled and actions contain `gh pr merge --merge` what happens? The PR build fails with "To have the pull request merged after all the requirements have been met, add the `--auto` flag." 
