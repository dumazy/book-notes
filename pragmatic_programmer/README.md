# The Pragmatic Programmer (2019)

20th anniversary edition.

- Authors: David Thomas, Andrew Hunt
- ISBN: 978-0-13-595705-9
- link: https://pragprog.com/book/tpp20/the-pragmatic-programmer-20th-anniversary-edition

## Notes

I'll keep my notes in different chapters and their topics.
I won't keep notes about all the topics, just things that I remembered to write about.

### Topics

#### DRY - The evils of duplication

DRY is about duplication of knowledge, of intent, **not** coincidentally have the same lines of code.

I remember reading a good article about this difference:
[Stop trying to be so DRY, instead Write Everything Twice (WET)](https://dev.to/wuz/stop-trying-to-be-so-dry-instead-write-everything-twice-wet-5g33)

It's important to think about the intent before you write a reusable piece of code, because you might get yourself stuck into a certain pattern.

#### Tracer bullets vs Prototypes

Tracer bullets are a sort of coding 'attempts' at making a product work as expected.
They should easily be altered, but are part of the actual project's code.

Prototypes should not be part of the code and should never be moved to it.
It's important to be very clear about this.
Although a prototype might look as a nearly completed product, it is very dangerous to use it as production code.
Always make sure the clients (or managers) are aware that this is throw-away code.

