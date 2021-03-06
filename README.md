# Awesome code review [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a checklist to make sure you've been doing your best while reviewing the code. I assume that all boring stuff like following the coding convention you are testing automatically.

#### General 

- [ ] Does the code work (and you have proofs)?
    - [ ] Does new functionality has (unit or acceptance or both) tests?
    - [ ] Could the result be seen effortless (with screenshoots, screencasts, output example)?
- [ ] Does PR has one commit per one logical change?
- [ ] Does one PR's commit less than 200 lines of code (LOC)?
- [ ] Does the code make sense?
- [ ] Does the code free from duplication?
- [ ] The code does not contains parts, which could be replaced with current external libraries code.
- [ ] Will this code work in most possible edge cases?
- [ ] Does the code follows Single Responcibility principe?
- [ ] It's not scaring for me to maintain this code in a future.
- [ ] Does the code works in differerent environments after your change?

#### Readability

- [ ] Is it possible to understand, what the code does with only class and function names, without looking to the code itself?

#### With frontend part

- [ ] Has it been tested under different browsers/mobiles?
