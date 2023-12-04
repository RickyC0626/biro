# biro
A Bisaya-flavored language transpiled to C. Biro means joke in Bisaya.

## Example

```c
// Biro-lang

// Hello, World! example
Mawadwad_sa "Hello, World!";

// Variables (strings and numbers for now)
var gikan = 5;
var pangalanan = "Juan";

// Control structures
Kon (barya > 10) {
  Ihap_sa "Dako ang barya!";
} Kun_dili {
  Ihap_sa "Gamay lang ang barya.";
}

// Loops
Para (var i = 0; i < 5; i = i + 1) {
  Ihap_sa "Kumusta ka, Bisaya?";
}

// Functions
Funksyon kuhaAngKwarta(barya) {
  Balik barya * 2;
}

// Classes and inheritance
Klase Mananap {
  sulti() {}

  lupad() {
    Ihap_sa "Dili ko makalupad";
  }
}

Klase Iro < Mananap {
  sulti() {
    Ihap_sa "woof";
  }
}
```

## Keywords w/ Equivalent Tokens

- `Bakak` - `false`
- `Balik` - `return`
- `Funksyon` - `function`
- `Ihap_sa` - `print`
- `Kini` - `this`
- `Klase` - `class`
- `Kon` - `if`
- `Kun_dili` - `else`
- `Mawadwad_sa` - `print`
- `O` - `or`
- `Para` - `for`
- `Samtang` - `while`
- `Tinuod` - `true`
- `Ug` - `and`
- `Wala` - `nil`

