# Simple bash calculator

### Demo

![calc demo](https://cloud.githubusercontent.com/assets/6382002/13583451/b1e44d30-e4b1-11e5-9efa-804f397c1181.gif)


### Installation

```bash
git clone https://github.com/arzzen/calc.git && cd calc
sudo make install
```

For uninstalling, open up the cloned directory and run

```bash
sudo make uninstall
```

### Usage
```bash
# addition
root@pc:~$ = 5+3                                                
8

# multiplication
root@pc:~$ = '4*2'
8

# subtraction
root@pc:~$ = -4-2
-6

# division
root@pc:~$ = 4/2
2.00000000000000000000

# square root 
root@pc:~$ = "scale=30; sqrt(2)"
1.414213562373095048801688724209

# power
root@pc:~$ = "6^6"
46656

# parentheses
root@pc:~$ = "(6^6)^6"
10314424798490535546171949056

# convert from decimal to hexadecimal 
root@pc:~$ = "obase=16; 255"
FF

# convert from decimal to binary 
root@pc:~$ = "obase=2; 12"
1100

# convert from binary to decimal 
root@pc:~$ = "ibase=2; obase=A;1100"
12

# convert from hexadecimal to decimal 
root@pc:~$ = "ibase=16; obase=A;FF"
255

# arctangent
root@pc:~$ = "a(1)"
.78539816339744830961

# PI value
root@pc:~$ = "scale=10; 4*a(1)"
3.1415926532

# more complex
root@pc:~$ = "scale=2; 3.4+7/8-(5.94*(4*a(1)))"
-14.26
```

