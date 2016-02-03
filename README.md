# otverification

This is a reference implementation of the formal analyses for Finnish prosody accounts given in:

Hulden, M. 2016. "Formal Verification in Optimality Theory"

## Usage

This scripts runs with [foma](http://foma.googlecode.com) or [xfst](http://www.fsmbook.com) (note that for xfst, some functionality in unavailable and lines containing "test identity" must be commented out).

```
foma -l finnish-ot-verification.foma
```
