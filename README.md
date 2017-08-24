# Platzom
Platzom es un idioma inventado para el [Curso de fundamentos de javascript](https://platzi.com/clases/fundamentos-javascript), el mejor lugar de educacion online

## Descripcion del idioma

- Si la palabra termina con "ar", Se les quitan esas dos letras.
- Si la palabra inicia con Z, se le pone "pe" al final. 
- Si la palabra traducida tiene más de 10 letras, se debe partir en dos por la mitad y unir con un guion medio
- Si la palabra original es un polindromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayusculas y minusculas 

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Créditos
- [Sacha Lifszyc](https://twitter.com/@slifszyc)

## Licencia

[MIT](https://opensource.org/licenses/MIT)