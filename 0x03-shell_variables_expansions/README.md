This code is working for the task 0x03-shell_variables_expansions
0. <o>--> alias ls="rm *"
1. Hello you --> echo hello $USER
2. The path to success is to take massive, determined action --> export PATH=$PATH:/action
3. If the path be beautiful, let us not ask where it leads --> echo $PATH | tr ":" "\n" | wc -l
4. Global variables --> printenv
5. Local variables --> set | more
6. Local variable --> BEST="School"
7. Global variable --> export BEST="School"
8. Every addition to true knowledge is an addition to human power --> echo $((128 + $TRUEKNOWLEDGE))
9. Divide and rule --> echo $(($(($POWER))/$DIVIDE))
10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath --> echo $(($(($BREATH))**$LOVE))
11. There are 10 types of people in the world -- Those who understand binary, and those who don't --> echo $((2#$BINARY))
12. Combination --> echo {a..z}{a..z} | tr " " "\n" | grep -v oo
13. Floats --> printf "%0.2f\n" $NUM
14. Decimal to Hexadecimal --> #!/bin/bash printf "%x\n" $DECIMAL
15. Everyone is a proponent of strong encryption -->tr 'A-Za-z' 'N-ZA-Mn-za-m'
16. The eggs of the brood need to be an odd number --> paste - - | cut -f1
17. I'm an instant star. Just add water and stir. --> printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 bestchol
