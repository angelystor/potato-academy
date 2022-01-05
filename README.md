# potato-academy
Some vulnerability research slides that I made to help our team get familiar with various bug classes.
This is by no means complete, but could be a good primer for people who are interested in bug hunting non web stuff.

Some of it is taken from the book, the Art of Software Security Assessment, which is a great book (although dated) to read.
The most time consuming portions was looking for, and understanding the relevant case studies (that are not present in the book) to illustrate the different bug classes. Phew!

Topics covered
- Brief overview on audit strategies
- Various bug classes such as
  - Off by 1
  - Arithmetic conversions
  - Type conversions 
  - Type confusions
- Hooking
  - Hooking dynamically linked functions is useful to hijack the behaviour of external functions, such as:
    - Forcing a fixed seed for a random() call
    - Faking hardware such as NVRAM
    - The possibilities are endless!
