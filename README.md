# Awesome code review

This is a checklist to make sure you've been doing your best while reviewing the code. I assume that all boring stuff like following the coding convention you are testing automatically.

#### General 

- [ ] Does PR has one commit per one logical change?
- [ ] Does one PR's commit less than 200 lines of code (LOC)?
- [ ] Does the code work?
    - [ ] Does it being tested?
    - [ ] Could the result be seen effortless (with screenshoots, screencasts, output example)?
- [ ] Does the code make sense?
- [ ] Does the code free from duplication?
- [ ] The code does not contains parts, which could be replaced with current external libraries code.
- [ ] Will this code work in most possible edge cases?
- [ ] Does the code follows Single Responcibility principe?

#### Readability

- [ ] Is it possible to understand, what the code does with only class and function names, without looking to the code itself?

#### With frontend part

- [ ] Has it been tested under different browsers/mobiles?
