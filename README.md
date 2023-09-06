<div align="center">


# classic-breakout

*Developed in July 2023*

<br>

"A classic breakout game clone."    
Use `Q` to move the paddle left, `D` to move it right and `space` to restart

<br>

This game is developed in C++ using Object-Oriented Programming principles.  It leverages the [raylib](https://www.raylib.com/) library for graphical rendering

<br>

![Gameplay](https://github.com/EzTaah/cpp-breakout/blob/main/assets/gameplay.gif)

<br>
<br>

</div>

---

# Building and Development

## Informations
- Your best score is saved to your local storage. You can find it in the following directory:  
```C:\Users\USERNAME\AppData\Local```

## Prerequisites
- Ensure you have a compiler installed on your computer.
- There's no need to install Raylib separately. It is already precompiled and stored in the 'lib' folder.

## Compilation instructions

1. Open a PowerShell/cmd terminal and navigate to the project's directory.

2. Navigate to the build directory : 
```
cd build 
```

3. Compile the project : (assuming that you use the minGW compiler)   
``` 
mingw32-make 
```

4. Run the game :   
```
.\debug.exe
```
