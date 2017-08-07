# Platzom

Platzom es un idioma inventado para el Curso de fundamentos de JavaScript.

## Descripción del idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres.
- Si la palabra inicia con Z, se le añade la "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guion en el medio.
- Si la palabra original es un palindromo ninguna regla anterior cuenta y se  devuelve la misma palabra intercalando mayúsculas y minúsculas.

## Instalación
 ```
 npm install platzom
 ```

 ## Uso
 ```
import platzom from 'platzom'

platzom('Programar') // program
platzom('Zorro') // Zorrope
platzom('Zarpar') // Zarppe
platzom('abecedario') // abece-dario
platzom('sometemos') // SoMeTeMoS
 ```

 ## Créditos
 - [Evelyn Farfán](https://github.com/efarfan2393)

 ## Licencia
 - [MIT] (https://opensource.org/licenses/MIT)
