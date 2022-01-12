# Code Review

sast kann nur pattern matching machen aber versteht das design des codes nicht
wissentransfer


- team code-review
  - get a peer from the guild
- guild code-review
-
- [OWASP Code Review Guide](https://owasp.org/www-project-code-review-guide/)
- [How to do a code review](https://google.github.io/eng-practices/review/reviewer/)

The following areas of code tend to have a high-risk of containing security vulnerabilities:
  - Crypto implementations / usage
  - Parser, unparser
  - System configuration
  - Authentication, authorization
  - Session management
  - Request throttling
  - :unicorn: (self-developed code, only used in that one software)
