# Bash TDD

A repo to test writing testable bash programs using [progrium](https://github.com/progrium)s best practices

## Best practices used

See [bashstyle](https://github.com/progrium/bashstyle)

## Run tests

Use [basht](https://github.com/progrium/basht)

```
$ basht app1
=== RUN T_getUsage
--- PASS T_getUsage (0s)
=== RUN T_getVersion
--- PASS T_getVersion (0s)
=== RUN T_helloBash
--- PASS T_helloBash (0s)
=== RUN T_helloWorld
--- PASS T_helloWorld (0s)

Ran 4 tests.

PASS
$ basht fizzbuzz
=== RUN T_doBuzz
--- PASS T_doBuzz (0s)
=== RUN T_doFizz
--- PASS T_doFizz (0s)
=== RUN T_doFizzBuzz
--- PASS T_doFizzBuzz (0s)
=== RUN T_doLoop
--- PASS T_doLoop (0s)
=== RUN T_doNotFizzbuzz
--- PASS T_doNotFizzbuzz (0s)
=== RUN T_getVersion
--- PASS T_getVersion (0s)
=== RUN T_invalidNumber
--- PASS T_invalidNumber (0s)
=== RUN T_notVersion
--- PASS T_notVersion (0s)
=== RUN T_validNumber
--- PASS T_validNumber (0s)

Ran 9 tests.

PASS
```
