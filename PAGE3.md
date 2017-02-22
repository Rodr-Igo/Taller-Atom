# Convertir Atom en IDE

## Para C/C++

# gpp-compiler

Esta paqueteria te permite compilar y ejecutar codigo en C/C++ en el editor de texto.

Para compilar, presiona <kbd>F5</kbd> o haz click derecgo `Compile and Run`.

## Dependencias

Este paquete se basa en el compilador de C / C++ (gcc).

### Linux

La coleccion compilador GNU  deberia venir con la distribución.
Ejecuta `which gcc g++`

Si el comando no muestra

```
/usr/bin/gcc
/usr/bin/g++
```

Necesitaras intalarlo

Para RHEL-based distros, ejecutar `sudo dnf install gcc gcc-c++`.

Para Debian-based distros, ejecutar `sudo apt install gcc g++`.

Para Arch-based distros, ejecutar `sudo pacman -S gcc`.

### Windows

Tendras que instalar [MinGW](http://www.mingw.org/) y [agregarlo a tu PATH](http://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/).

### Mac

Tendras que instalar [XCode](https://developer.apple.com/xcode/).
