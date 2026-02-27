# DOSW2_ParcialT1_Juan David Gomez Cuellar

## Pruebas de acceso a figma 

![Diagrama en Figma](src/docs/images/figma.png)


## Pruebas de acceso a draw.io
![Diagrama en draw.io](src/docs/images/draw.io.png)

## Punto 1: Realice el diagrama de contexto con las generalidades de su sistema.
![Diagrama punto 1](src/docs/images/Punto1.png) 

## Punto 2: Identifique 2 patrones de diseño que puedan aplicarse al caso de estudio, especificando por cada uno:

# a. Nombre del Patrón
- Decorator 
- Bridge
# b. Tipo de patrón (creacional, estructural o de comportamiento).
- Ambos son estructurales
# c. Justificación de la decisión.
- Se tomo la decision de tomar decorator ya que a la hora que el usuario tiene la posibilidad de personalizar su pedido, decorator permite añadir funcionalidades encapsulando todo de manera mas simple, sin depender de tantas clases, cumpliendo los principios SOLID de Open/closed.

- Se tomo la decision de usar Bridge ya que permite dividir las clases que estan relacionadas en jerarquias separads. util ya que el usuario estara desarrollando de manera independiente una de otra, usando abstracciones para cumplir Liskov de los principios SOLID
