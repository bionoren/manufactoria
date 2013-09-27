See [http://www.bionoren.com/blog/2013/09/manufactoria-the-language](http://www.bionoren.com/blog/2013/09/manufactoria-the-language)

Valid statements mostly correspond with game controls:

* eb - emit blue

* er - emit red

* eg - emit green

* ey - emit yellow

* ir {} ib {} ie {} - if red, else if blue, else (order not important)

* ig {} iy {} ie {} - if green, else if yellow, else (order not important)

All statements can be labeled with a string in brackets (eg: eb [emit1], ir [if1] {} ib {} ie {})

Other statements are:

* go label - go to the statement indicated by label and execute there

* ret - return (place in yellow goal box)

* end - reject

* assert - condition should never occur (feel free to place random things in front of the output)

C-style comments (// and /**/) and python-style (#) are also supported. Semicolons are optional.
