# .cal

### .cal v0.0.4 (20-Dec-2025)

.cal           -- print the current months calendar

.cal yyyy mm   -- print the month calendar for year and month

.cal -2        -- print 2 months across
.cal -3        -- print 3 months across
.cal -4        -- print 4 months across
  ** when printing multiple months ensure you are in a text mode with extra character columns

.cal -v
.cal --version -- print the version of the app

## Requirements
- The znc compiler for ZX Spectrum Next https://taylorza.itch.io/znc-compiler

- From https://github.com/Nuntis-Spayz/sev-znc-libs and the znc compiler itself 
.cal requires the following libraries installed in /zdev/

- io.znc
- datetime.znc
- string.znc
- strcontains.znc
- strtoint.znc

### History
v0.0.4 - 20-Dec-2025 - specify multiple months, -2, -3, -4
v0.0.3 - 19-Dec-2025 - specify yyyy mm
v0.0.2 - 07-Dec-2025 - added -v, --version
v0.0.1 - 06-Dec-2025 - first version

GNU Public Licence
Copyright 2025 Ian "Nuntis"  Jukes
