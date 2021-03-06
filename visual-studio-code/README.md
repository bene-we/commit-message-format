# Visual Studio Code Commit Message Format

Visual Studio Code can support a specified commit message format using snippets (see https://pawelgrzybek.com/multi-paragraph-git-commit-messages-cli-and-visual-studio-code/).

Add the following to `git-commit.json` globally or to a local snippet file:

```json
{
	"Commit Message Format": {
		"prefix": "commitformat",
		"body": [
		  "${1|FEAT,FIX,DOCS,STYLE,REFAC,PERF,TEST,CHORE|} ${3:subject}",
		  "",
		  "${4:body (optional)}",
		  "",
		  "Issue(s) #${5:issue-number} (optional)"
		],
		"description": "Commit Message Format"
	  }
}
```
