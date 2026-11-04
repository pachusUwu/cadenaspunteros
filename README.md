# Cadenas y Punteros – Actividad 4: Control de Acceso RAM (LPR 2026)

Sistema básico de control de acceso por edad en C++ que lee y evalúa el dato **a través de un puntero**, mostrando la dirección física hexadecimal de la variable en la memoria RAM.

**E.E.S.T. N.° 1 "Eduardo Ader" – Vicente López** · Laboratorio de Programación 5° 3° · Prof. Mansilla Muñoz York E.

## Integrantes

- Ian Quiroga – código y pruebas
- Santino Laudati – informe APA v7 y cuestionario
- Dante Iglesias – esquema de RAM, capturas y repositorio

## Uso de punteros en la RAM

```cpp
int edad = 0;
int* p = &edad;   // & -> direccion de edad
cin >> *p;        // * -> escribe en el casillero de edad
cout << p;        // imprime la direccion (ej. 0xcb907ffa14)
cout << *p;       // imprime el valor (ej. 18)
```

## Compilar y ejecutar

```powershell
g++ src/main.cpp -o src/cadenaspunteros.exe
.\src\cadenaspunteros.exe
```

## Documentación

- [Informe APA v7](docs/InformeProyectoCADENASPUNTEROS.pdf)
- [Manual del programador](docs/manuales/manual_programador_v1.0.0.md)
- Evidencias: `capturas/ejecucion_punteros.png`, `capturas/esquema_ram.png`
