# Commit Message Format

This repositories includes guidelines and best practices to formulate git commit messages.

```
{type}: {subject}

{body}

Issue(s): #{issue-number}
```

**type** and **header** are mandatory.

Example  `FIX: remove unused dependency lodash.camelcase`

Any line of the commit message cannot be longer 72 characters. This allows the message to be easier to read on GitHub as well as in various git tools.

#### Type
Must be one of the following:

* **FEAT**: A new feature.
* **FIX**: A bug fix.
* **DOCS**: Documentation only changes.
* **STYLE**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
* **REFAC**: A code change that neither fixes a bug nor adds a feature.
* **PERF**: A code change that improves performance.
* **TEST**: Adding missing tests.
* **CHORE**: Changes to the build process or auxiliary tools and libraries such as documentation generation.

#### Subject
The subject contains succinct description of the change:

* use the imperative, present tense: `change` not `changed` nor `changes`,
* don't capitalize first letter,
* no dot (.) at the end.
* Use one line with a max of 50 chars

#### Body
Just as in the **subject**, use the imperative, present tense: "change" not "changed" nor "changes".
The body should include the motivation for the change and contrast this with previous behavior.
A blank line above the body is mandatory if the body is presented.

- Bullet points are okay, too.
- Typically a hyphen or asterisk is used for the bullet, followed by a
  single space. Use a hanging indent.

#### Issues
If working on an issue, provide its number preceded by a hashtag #. If provided, a blank line above is mandatory.

---

### Rules for a great git commit message style

* Separate subject from body with a blank line
* Do not end the subject line with a period
* Capitalize the subject line and each paragraph
* Use the imperative mood in the subject line
* Wrap lines at 72 characters
* Use the body to explain what and why you have done something. In most cases, you can leave out details about how a change has been made.

### Information in commit messages
* Describe why a change is being made.
* How does it address the issue?
* What effects does the patch have?
* Do not assume the reviewer understands what the original problem was.
* Do not assume the code is self-evident/self-documenting.
* Read the commit message to see if it hints at improved code structure.
* The first commit line is the most important.
* Describe any limitations of the current code.
* Do not include patch set-specific comments.


---

### References

* [https://gist.github.com/develar/273e2eb938792cf5f86451fbac2bcd51](https://gist.github.com/develar/273e2eb938792cf5f86451fbac2bcd51)
* [https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)
* [https://t3n.de/news/schreibt-richtig-gute-1214910/](https://t3n.de/news/schreibt-richtig-gute-1214910/)

