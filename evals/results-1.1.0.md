# Text Humanizer 1.1.0: targeted regression check

Historical report. See [current results and status](results-1.1.2.md).

Date: 2026-10-23.

The skill was renamed from `humanizer` to `text-humanizer`. Its delivery rule
now explicitly excludes routine fact-checking disclaimers and process notes
from an ordinary rewrite or new draft. Tests 1 and 7 check that requirement.

One targeted rerun of request 1 used Codex CLI 0.164.0, `gpt-6-astra`, reasoning
`xhigh`, and a fresh session. The complete updated skill and both language notes
were supplied in the input, followed by the original request. The grading
criteria were not supplied. This is a content test, not a native loading test.

Result: passed. Preliminary attribution to sales, possibility, the 8% upper
bound, and the unchanged advertising budget remain. No disclaimer or process
note follows the sentence. The actual output is recorded below.

Metadata, UTF-8, relative links, the renamed archive directory, extraction,
and archive/source byte equality were also checked.

The full corpus, native skill loading after the rename, Claude, Hermes, and
long-form article/script generation were not rerun for this release. The
[1.0.0 report](results-2026-10-23.md) remains historical evidence for that version.

## Actual output

```text
По предварительной оценке отдела продаж, новая форма может принести до 8% больше заявок при том же рекламном бюджете.
```
