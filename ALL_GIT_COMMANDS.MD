# Git commands

1. `git init`: Initializes a new Git repository.

2. `git clone <repository URL>`: Creates a copy of a remote Git repository on your local machine.

3. `git status`: Displays the status of your working directory, showing which files are modified, staged, or untracked.

4. `git add <file>`: Stages changes in a file to be included in the next commit.

5. `git add .` or `git add --all`: Stages all changes in the current directory and its subdirectories for the next commit.

6. `git commit -m "Commit message"`: Commits staged changes with a descriptive commit message.

7. `git log`: Displays the commit history of the current branch.

8. `git diff`: Shows the differences between the working directory and the most recent commit.

9. `git branch`: Lists all branches in the repository and indicates the current branch with an asterisk.

10. `git branch <branchname>`: Creates a new branch with the specified name.

11. `git checkout <branchname>`: Switches to the specified branch.

12. `git merge <branchname>`: Merges changes from the specified branch into the current branch.

13. `git pull`: Fetches changes from a remote repository and merges them into the current branch.

14. `git push`: Pushes local commits to a remote repository.

15. `git remote -v`: Lists all remote repositories connected to your local repository and their URLs.

16. `git remote add <name> <repository URL>`: Adds a remote repository with a custom name.

17. `git remote remove <name>`: Removes a remote repository.

18. `git reset <file>`: Unstages changes in a file.

19. `git reset --hard <commit>`: Resets the branch to a specific commit, discarding all changes after that commit.

20. `git stash`: Temporarily saves changes that are not ready to be committed.

21. `git tag <tagname>`: Creates a new tag at the current commit.

22. `git submodule`: Manages Git submodules within a repository.

23. `git archive --format=<format> -o <outputfile> <commit>`: Creates an archive of a specific commit.

24. `git log --graph --oneline --all`: Displays a concise and graphical commit history of all branches.

25. `git cherry-pick <commit>`: Applies a specific commit from another branch.

26. `git config`: Manages Git configuration settings.

27. `git stash list`: Lists all stashed changes.

28. `git stash pop` and `git stash apply`: Applies the most recent stash and removes it (or leaves it) from the stash list, respectively.

29. `git clean -n` and `git clean -f`: Lists and removes untracked files, respectively.

30. `git log --since="<time>"` and `git log --until="<time>"`: Filters commits by time range (e.g., "3 days ago").

31. `git grep <pattern>`: Searches the working directory for a specified pattern.

32. `git tag -d <tagname>`: Deletes a local tag.

33. `git log --author="<authorname>"`: Filters commits by the author's name or email address.

34. `git checkout -- <file>`: Discards local changes in a file and reverts it to the last committed version.

35. `git rebase -i <commit>`: Launches an interactive rebase, allowing you to edit, squash, or reorder commits.

36. `git commit --amend`: Adds changes to the last commit (used for making quick corrections or additions to the last commit).

37. `git push <remote> --tags`: Pushes tags to a remote repository.

38. `git log --all --grep="<pattern>"`: Searches for a pattern across all branches in the commit history.

39. `git bisect start`: Initiates the binary search for a faulty commit (useful for debugging).

40. `git clean -fd`: Removes untracked files and directories forcefully.

41. `git diff --cached`: Shows the changes staged for the next commit.

42. `git show <commit>`: Displays information about a specific commit, including changes and metadata.

43. `git log --name-status`: Shows commit history with added, modified, and deleted files.

44. `git cherry-pick -n <commit>`: Cherry-picks a commit without committing immediately, allowing you to make additional changes.

45. `git stash clear`: Removes all stashed changes, cleaning up the stash.

46. `git remote rename <oldname> <newname>`: Renames a remote repository reference.

47. `git blame -L <start>,<end> <file>`: Blames a file within a specific line range.

48. `git log --since="<time>"` and `git log --until="<time>"`: Filters commits by time range (e.g., "3 days ago").

49. `git grep <pattern>`: Searches the working directory for a specified pattern.

50. `git tag -d <tagname>`: Deletes a local tag.

51. `git log --oneline`: Displays a simplified one-line log of commit messages.

52. `git reflog`: Shows a log of all Git references (branches, tags, etc.) to track history changes.

53. `git bisect bad <commit>` and `git bisect good <commit>`: Marks a commit as bad or good during the binary search for a faulty commit.

54. `git clean -i`: Interactively remove untracked files.

55. `git fetch --prune`: Fetches changes from a remote repository and prunes deleted branches.

56. `git submodule update --remote`: Updates submodules to the latest commit.

57. `git rebase -i HEAD~n`: Interactively rebase the last n commits.

58. `git commit --fixup <commit>` and `git commit --squash <commit>`: Prepare fixup and squash commits for interactive rebase.

59. `git reset --soft <commit>`: Resets the branch to a specific commit, keeping changes staged.

60. `git diff <commit1>..<commit2>`: Shows the differences between two commits.

61. `git log --grep="<pattern>" --author="<author>"`: Filters commits by both pattern and author.

62. `git branch -vv`: Lists branches with tracking information.

63. `git log --graph --all --abbrev-commit --date=relative --format=format:'%h - (%ar) %s [%an]'`: Customized log format with graph, author, and relative date.

64. `git rev-parse HEAD`: Displays the commit hash of the current HEAD.

65. `git pull --rebase`: Fetches and rebases changes from a remote repository.

66. `git reflog expire --expire-unreachable=now --all`: Expire all unreachable references.

67. `git reflog delete --expired --all`: Delete all expired reflogs.

68. `git blame -w <file>`: Blame a file, ignoring whitespace changes.

69. `git log --graph --decorate --oneline`: A concise log with commit graph and decorations.

70. `git log --follow <file>`: Follows file history across renames.

71. `git log --name-only`: Shows commit history with only file names.

72. `git stash branch <branchname> <stash>`: Creates a new branch from a stash.

73. `git log --cherry-pick --right-only <branch>`: Lists commits in the current branch not in the other branch.

74. `git reflog show <refname>`: Shows the reflog for a specific reference.

75. `git clean -e <pattern>`: Excludes files matching a pattern when cleaning untracked files.

76. `git blame -M <file>`: Blame a file and follow renames.

77. `git log --ancestry-path <commit1>..<commit2>`: Lists commits that are ancestors of commit2 but not of commit1.

78. `git log --merges`: Lists only merge commits.

79. `git push --force`: Force-push local commits to a remote repository, overwriting its history.

80. `git stash drop <stash>`: Deletes a specific stash.

81. `git ls-files`: Lists all tracked files in the repository.

82. `git log --follow -p <file>`: Shows commit history and changes for a file, following renames.

83. `git log --pretty=format:"%h %s" --graph`: Custom log format with commit hash and subject, including a graph.

84. `git ls-remote <remote>`: Lists references in a remote repository.

85. `git push --tags`: Pushes only tags to a remote repository.

86. `git stash pop --index`: Pops the most recent stash, also applying changes to the index.

87. `git blame -C -C <file>`: Blame a file, detecting copied or moved lines.

88. `git log --no-merges`: Lists only non-merge commits.

89. `git clean -df`: Removes untracked files and directories forcefully, including ignored ones.

90. `git log --pretty=format:"%h %s [%an]" --graph --all --date=short`: Customized log format with commit hash, subject, author, graph, and short date.

91. `git stash branch <branchname> <stash>`: Creates a new branch from a stash.

92. `git log --pretty=format:"%h - %s (%an <%ae>)" --abbrev-commit`: Customized log format with commit hash, subject, author name, and email.

93. `git remote update --prune`: Updates all remote references and prunes deleted ones.

94. `git blame -L <start>,<end>:<file>`: Blame a specific line range in a file.

95. `git log --pretty=format:"%h %s %ad" --date=relative`: Custom log format with commit hash, subject, and relative date.

96. `git show-branch`: Shows branch names with their most recent commit.

97. `git bundle create <bundlefile> <branchname>`: Creates a bundle file containing the specified branch.

98. `git log --pretty=format:"%h %s %b" --graph`: Custom log format with commit hash, subject, and body, including a graph.

99. `git cat-file -t <object>`: Displays the type of a Git object.

100. `git stash save "<message>"`: Stashes changes with a custom message.

101. `git bisect reset`: Completes the binary search for a faulty commit, resetting the state.

102. `git ls-tree <commit> <path>`: Displays the contents of a tree object at a specific commit and path.

103. `git log --pretty=format:"%h %s" --abbrev-commit --date=iso`: Custom log format with commit hash, subject, and ISO 8601 date.

104. `git stash list --stat`: Lists stashes with a summary of changes.

105. `git show-branch --all`: Shows branch names with their most recent commits in all branches.

106. `git blame -e <file>`: Blame a file, showing author emails.

107. `git log --pretty=format:"%h %s %an %ae" --abbrev-commit`: Custom log format with commit hash, subject, author name, and email.

108. `git stash drop <stash>`: Deletes a specific stash.

109. `git log --pretty=format:"%h %s [%an]" --graph --all --date=short`: Customized log format with commit hash, subject, author, graph, and short date.

110. `git clean -x`: Removes all untracked files and directories, including those listed in `.gitignore`.

111. `git log --pretty=format:"%h %s %b" --graph --all`: Custom log format with commit hash, subject, body, graph, and all branches.

112. `git blame -C -C -C <file>`: Blame a file, detecting copied, moved, or reworded lines.

113. `git log --pretty=format:"%h - %s" --graph --all --date=relative --abbrev-commit`: Customized log format with commit hash, subject, graph, all branches, relative date, and abbreviated commit hash.

114. `git show-branch <branch>`: Shows branch names with their most recent commits in a specific branch.

115. `git clean -X`: Removes only ignored files when cleaning untracked files.

116. `git log --pretty=format:"%h %s [%an]" --graph --all --date=relative`: Custom log format with commit hash, subject, author, graph, all branches, and relative date.

117. `git pull --rebase=preserve`: Fetches and rebases changes from a remote repository while preserving merge commits.

118. `git stash branch <branchname>`: Creates a new branch from the most recent stash.

119. `git log --pretty=format:"%h %s %ar" --graph --all --abbrev-commit --date=short`: Custom log format with commit hash, subject, author, relative date, graph, all branches, abbreviated commit hash, and short date.

120. `git log --pretty=format:"%h %s [%an]" --graph --all --date=iso`: Custom log format with commit hash, subject, author, graph, all branches, and ISO 8601 date.

121. `git stash drop --all`: Deletes all stashes.

122. `git log --pretty=format:"%h %s %b [%an]" --graph --all --date=rfc`: Custom log format with commit hash, subject, body, author, graph, all branches, and RFC 2822 date.

123. `git clean -xd`: Removes only ignored directories when cleaning untracked files.

124. `git reflog expire --expire=now --all`: Expires all reflogs immediately.

125. `git reflog delete --expire=now --all`: Deletes all expired reflogs immediately.

126. `git log --pretty=format:"%h %s [%an]" --graph --all --date=rfc-local`: Custom log format with commit hash, subject, author, graph, all branches, and local RFC 2822 date.

127. `git log --pretty=format:"%h %s %ar" --graph --all --abbrev-commit --date=relative`: Custom log format with commit hash, subject, author, relative date, graph, all branches, abbreviated commit hash, and relative date.

128. `git stash branch <branchname> <stash>`: Creates a new branch from a specific stash.

129. `git stash pop --index --quiet`: Pops the most recent stash, applying changes to the index quietly.

130. `git log --pretty=format:"%h %s %an <%ae>" --graph --all --date=rfc-2822`: Custom log format with commit hash, subject, author, author email, graph, all branches, and RFC 2822 date.

131. `git log --pretty=format:"%h %s" --graph --all --date=relative`: Custom log format with commit hash, subject, graph, all branches, and relative date.

132. `git clean -Xn`: Shows a preview of files to be removed when cleaning untracked files.

133. `git blame -L :<regex>:<file>`: Blame a file, limiting output to lines matching a regex pattern.

134. `git log --pretty=format:"%h %s [%an]" --graph --all --date=local`: Custom log format with commit hash, subject, author, graph, all branches, and local date

.

135. `git checkout --recurse-submodules`: Checks out submodules along with the main repository.

136. `git log --pretty=format:"%h %s %ar" --graph --all --abbrev-commit --date=local`: Custom log format with commit hash, subject, author, relative date, graph, all branches, abbreviated commit hash, and local date.

137. `git blame -L <start>,<end>:<regex>:<file>`: Blame a specific line range in a file, limiting output to lines matching a regex pattern.

138. `git stash drop --all --quiet`: Deletes all stashes quietly.

139. `git log --pretty=format:"%h %s %b" --graph --all --date=short`: Custom log format with commit hash, subject, body, graph, all branches, and short date.

140. `git log --pretty=format:"%h %s [%an]" --graph --all --date=local-iso`: Custom log format with commit hash, subject, author, graph, all branches, and local ISO 8601 date.

141. `git log --pretty=format:"%h %s %an <%ae>" --graph --all --date=rfc-local`: Custom log format with commit hash, subject, author, author email, graph, all branches, and local RFC 2822 date.

142. `git checkout --recurse-submodules=<option>`: Checks out submodules with various options, such as `on-demand`, `no`, or `yes`.

143. `git cherry-pick --abort`: Aborts an ongoing cherry-pick operation.

144. `git log --pretty=format:"%h %s %ar" --graph --all --abbrev-commit --date=local-iso`: Custom log format with commit hash, subject, author, relative date, graph, all branches, abbreviated commit hash, and local ISO 8601 date.

145. `git log --pretty=format:"%h %s [%an]" --graph --all --date=relative-iso`: Custom log format with commit hash, subject, author, graph, all branches, and relative ISO 8601 date.

146. `git log --pretty=format:"%h %s %b" --graph --all --date=local-iso-strict`: Custom log format with commit hash, subject, body, graph, all branches, and strict local ISO 8601 date.

147. `git stash drop <stash> --quiet`: Deletes a specific stash quietly.

148. `git log --pretty=format:"%h %s %ar" --graph --all --abbrev-commit --date=local-iso-strict`: Custom log format with commit hash, subject, author, relative date, graph, all branches, abbreviated commit hash, and strict local ISO 8601 date.

149. `git log --pretty=format:"%h %s [%an]" --graph --all --date=relative-iso-strict`: Custom log format with commit hash, subject, author, graph, all branches, and strict relative ISO 8601 date.

150. `git stash clear --quiet`: Removes all stashes quietly.

These additional Git commands offer further capabilities for managing your Git repositories and version control workflow. Feel free to explore and experiment with these commands as you continue to learn Git and GitHub.
