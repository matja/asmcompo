
### ballzup.asm

#### For #asm compo 5 in 2001

Theme : Make a DOS demo/game/effect, interactive or not, in 1024 bytes or less.

I made an animated vector balls effect, using per-pixel depth testing, so the balls merged together quite nicely.  I generate 628 balls, one for each 0.01 radians, and apply a function to transform them to the screen.  I animate it by adding a linear component and interpolating between the functions over time.  In this I just have a random 'cloud' and a toroidal knot function, I wanted to add more but didn't have space in the end.


### hashasmtro.cpp

#### For #asm compo 6 in 2002

Theme : Write a Win32 intro/game/effect in 4096 bytes or less

I abused the rules a little, and entered a C++ (well, mostly C) program.

compile with MSVC7+ using `cl /O1ityb2 /Gs /G6 /FAs /QIfist hashasmtro.cpp /link /nodefaultlib /entry:main kernel32.lib user32.lib gdi32.lib opengl32.lib glu32.lib /align:4096 /merge:.text=.data /merge:.rdata=.data /subsystem:windows`


### asminity.asm

#### For #asm compo 7 in 2003

Theme : Make a 256 byte intro for 386/486 class PC's

I made an animated IFS fractal which spelt-out 'ASM', which in turn was made from smaller 'ASM's, etc.

