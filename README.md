# linux

if [ "a"! = "b" ]; then echo TRUE; fi
if [ "a" != "b" ]; then echo TRUE; fi
TRUE
if [ "a" ! = "b" ]; then echo TRUE; fi
-bash: [: too many arguments
if [ 2 -eq 2 ]; then echo TRUE; fi
TRUE
if [ 2 -gt 2 ]; then echo TRUE; fi
if [ 2 -gt 1 ]; then echo TRUE; fi
TRUE
if [ 2 -lt 1 ]; then echo TRUE; fi
if [ 2 -lt 5 ]; then echo TRUE; fi
TRUE
if (( 7 > 4 )); then echo TRUE; fi
TRUE
if (( 7 == 7 )); then echo TRUE; fi
TRUE







