# Información de Compilación

## Entorno de Desarrollo
- **Compilador**: gcc
- **Versión**: 13.3.0
- **Estándar de C**: C17

---

Este proyecto utiliza GCC 13.3.0 con soporte para el estándar C17 (también conocido como C18).

## Verificación del Estándar C

Para verificar el estándar de C soportado, se utilizó el siguiente comando:

```bash
mortal@Mortal:~$ gcc -dM -E - < /dev/null | grep -i c_version
#define __STDC_VERSION__ 201710L