# Kantodo-Lexorank

```php
$lexorank = new Lexorank();

// default rank
$rank = $lexorank->generate();

// rank before $rank
$rankBefore = $lexorank->generate(NULL, $rank);

// rank after $rank
$rankAfter = $lexorank->generate($rank);

```
