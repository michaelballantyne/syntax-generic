# Syntax Generics

```racket
(require syntax-generic)
```

```racket
(define-generic-syntax generic-name
  #:fallback fallback-procedure)
```
Defines a syntax generic procedure.

```racket
(define-syntax/generics name
  expand-procedure
  [generic-name generic-procedure] ...)
```
Defines a syntactic form with a macro transformer and syntax generic implementations.

```racket
(syntax-generic-prop generic-name)
```
Evaluates to the structure type property associated with a syntax generic.
