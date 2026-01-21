# nostos-utils

A collection of utility functions for the Nostos programming language.

## Modules

### math.nos
Mathematical utilities:
- `clamp`, `abs`, `sign`
- `isEven`, `isOdd`
- `gcd`, `lcm`
- `fib`, `factorial`, `pow`
- `sum`, `product`, `average`
- `minimum`, `maximum`

### strings.nos
String manipulation utilities:
- `repeat`, `padLeft`, `padRight`
- `startsWith`, `endsWith`, `contains`
- `countChar`, `isBlank`
- `reverseStr`, `toUpper`, `toLower`

## Usage

```nostos
use github.pegesund/nostos-utils/math.*

main() = {
  x = math.clamp(15, 0, 10)  # Returns 10
  y = math.gcd(48, 18)       # Returns 6
  z = math.fib(10)           # Returns 55
  x + y + z
}
```

## License

MIT
