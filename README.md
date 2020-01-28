# SDL 2

Included is SDL2 libraries collected in one repository.

## Included

 - SDL2
 - SDL2_ttf
 - SDL2_mixer
 - SDL2_image
 - SDL2_ttf

## Installation

Add using subtree:
```
git subtree add --prefix .sdl git@github.com:gameprogrammingii/sdl.git master --squash
```

Additional include directories:
```
..\.sdl\include
```

Linker -> Input -> Additional Dependencies
```
SDL2.lib
SDL2main.lib
SDL2_image.lib
SDL2_mixer.lib
SDL2_ttf.lib
```

Additional library directories (x86)
```
..\.sdl\lib\x86
```

Make sure you have correct main function:
```
int main(int argc, char* args[])
{
  ...
}
```
