# QueryScripter editing rules
This document will outline the rules you have to follow when getting in on the fun of editing QS.

## If you're not sure, ask (please do this before pushing anything new to the codebase. Thanks)
We would much rather you ask someone "Is this OK to put in?" or "What do you think about this?" than to just assume and go ahead with the push. If anyone has anything they feel anyone can edit without permission, please put it in the "FREE" folder.

## Beta/pre-release releases must be pushed to their respective branch (the branch is actually called 'beta', by the way)
If you have any code that is worthy of beta or pre-release status, please push it to the respective 'beta' branch. This applies to all free code as well.

## '#', '/' and '?' are all prohibited as query markers
It may seem weird being each one is a valid character in both html 4.01 and 5, but each character does have a reason why it is not allowed as a query marker:
- '#' isn't allowed because it is used in HTML to notate an id (#idExample),
- '/' isn't allowed because it is used in URLs to notate a path branch (example.com<b>/</b>path<b>/</b>to<b>/</b>file.html),
- and '?' isn't allowed because it is used already in PHP to notate a query marker (example.com/path/to/file.html?isRightFile=true)

If anyone has any adjustments they want to make, feel free. This is one of the only files that's "free" that's placed outside of the FREE folder.

Thank you for adhering to there rules.
