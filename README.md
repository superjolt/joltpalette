# joltpalette
A python lib for colors. A big palette of colors, and themes, using ANSI codes.

Example usage:

~~~python
import joltpalette as jp

print(jp.F_RED + "Red text!" + jp.RESET)
print(jp.themes["TOKYO_NIGHT"] + "Cool themed text!" + jp.RESET)
print(jp.B(0, 0, 0) + jp.F(255, 255, 255) + "Black bg, white text!" + jp.RESET)
print(jp.BOLD + "Bold!" + jp.RESET)
~~~
