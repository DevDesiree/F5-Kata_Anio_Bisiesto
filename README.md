# F5-Kata_Anio_Bisiesto

Kata a realizar : [Fuente](https://www.codurance.com/es/katas/leap-year)

## Descripcion
Este proyecto implementa una función en JavaScript para verificar si un año es bisiesto o no, siguiendo las reglas especificadas.

- Reglas
  - Un año no es bisiesto si no es divisible por 4.
  - Un año es bisiesto si es divisible por 4.
  - Un año es bisiesto si es divisible por 400.
  - Un año no es bisiesto si es divisible por 100 pero no por 400.

 ## Ejemplos de Uso

```javascript
console.log(leapYear(1997)); // Debería imprimir false
console.log(leapYear(1996)); // Debería imprimir true
console.log(leapYear(1600)); // Debería imprimir true
console.log(leapYear(1800)); // Debería imprimir false
```

## Pruebas
Este proyecto utiliza Jest para realizar pruebas. 
Las pruebas están ubicadas en el archivo leapYear.test.js y cubren casos específicos para garantizar el correcto funcionamiento de la función.


## Instalación
1 - Clonar el Repositorio:

```bash
git clone https://github.com/DevDesiree/F5-Kata_Anio_Bisiesto.git
```

2 - Instalar Dependencias:

```bash
npm install
```

3 - Ejecución de Pruebas
Para ejecutar las pruebas, utiliza el siguiente comando:

```bash
npm run test
```

Este comando ejecutará las pruebas utilizando Jest y te mostrará los resultados en la consola.
