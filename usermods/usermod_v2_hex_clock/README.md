### Other modifications
To `wled.h` add `WLED_GLOBAL int8_t currentLedmap _INIT(-1);`

And to `wled.cpp` add `currentLedmap = loadLedmap;` (line 240)
