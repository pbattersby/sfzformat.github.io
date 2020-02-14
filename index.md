---
title: Home
layout: home
---

Here testing an issue when using `anchor-headings` in 2 layouts,
where one inherits the other.

The behaviour can be seen by looking in one of [opcode pages] that uses the
`sfz/opcode.html` layout which inherits `default.html`, e.g. in [sample]:
a double anchor is displayed.
The problem can also be seen in the related page source from the browser
by searching "Some text".

I don't know if "the issue" can be "fixed" in the code or just by avoiding
doing this, since by logic it's wrong, the script should be called once from the
inheriting one only.

[sample]: /opcodes/sample
[opcode pages]: /misc/all_opcodes
