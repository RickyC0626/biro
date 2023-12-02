# biro
A Bisaya-flavored language transpiled to C. Biro means joke in Bisaya.

## Example

```c
// Biro-lang

// Hello, World! example
Mawadwad sa "Hello, World!";

// Variables and data types
Barya gikan 5;
Letra pangalanan "Juan";
Totoo kamatuoran = Dili;

// Control structures
Kon (barya > 10) {
  Ihap sa "Dako ang barya!";
} Kun dili {
  Ihap sa "Gamay lang ang barya.";
}

// Loops
Para i = 0; i < 5; i++ {
  Ihap sa "Kumusta ka, Bisaya?";
}

// Functions
Funksyon kuhaAngKwarta(barya) {
  Balik barya * 2;
}

// Error handling
Subukan {
  KunlaraAngError();
} Ayaw {
  Ihap sa "Na-handle ang error.";
}
```

