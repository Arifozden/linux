# linux

s374976@data2500:~/arif/minmappe$ if [ "a"! = "b" ]; then echo TRUE; fi
s374976@data2500:~/arif/minmappe$ if [ "a" != "b" ]; then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$ if [ "a" ! = "b" ]; then echo TRUE; fi
-bash: [: too many arguments
s374976@data2500:~/arif/minmappe$ if [ 2 -eq 2 ]; then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$ if [ 2 -gt 2 ]; then echo TRUE; fi
s374976@data2500:~/arif/minmappe$ if [ 2 -gt 1 ]; then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$ if [ 2 -lt 1 ]; then echo TRUE; fi
s374976@data2500:~/arif/minmappe$ if [ 2 -lt 5 ]; then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$ if (( 7 > 4 )); then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$ if (( 7 == 7 )); then echo TRUE; fi
TRUE
s374976@data2500:~/arif/minmappe$






