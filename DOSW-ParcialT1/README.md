# DOSW2_ParcialT1_Juan David Gomez Cuellar

## Pruebas de acceso a figma 

![Diagrama en Figma](src/docs/images/figma.png)


## Pruebas de acceso a draw.io
![Diagrama en draw.io](src/docs/images/draw.io.png)

## Punto 1: Realice el diagrama de contexto con las generalidades de su sistema.
![Diagrama punto 1](src/docs/images/Punto1.png) 

## Punto 2: Identifique 2 patrones de diseño que puedan aplicarse al caso de estudio, especificando por cada uno:
---
# a. Nombre del Patrón
- Decorator 
- Bridge
# b. Tipo de patrón (creacional, estructural o de comportamiento).
---
- Ambos son estructurales
# c. Justificación de la decisión.
- Se tomo la decision de tomar decorator ya que a la hora que el usuario tiene la posibilidad de personalizar su pedido, decorator permite añadir funcionalidades encapsulando todo de manera mas simple, sin depender de tantas clases, cumpliendo los principios SOLID de Open/closed.

- Se tomo la decision de usar Bridge ya que permite dividir las clases que estan relacionadas en jerarquias separads. util ya que el usuario estara desarrollando de manera independiente una de otra, usando abstracciones para cumplir Liskov de los principios SOLID

---
## Identifique 5 requerimientos del sistema y clasifíquelos

### Funcionales
- La pagina debe permitir personalizar el pedido
- La pagina debe permitir retroceder en caso de equivocarse
- La pagina le debe dar al usuario el precio total de los productos solicitados

### No funcionales
- La aplicación web use colores institucionales Dorado, Azul y Rosado
- El sistema debe responder en máximo 1 segundos para el 85% de transacciones y debe soportar 500 pagos concurrentes

## Seleccione los 2 requerimientos funcionales más importantes del sistema y desarrolle un diagrama de casos de uso con surespectiva historia de usuario
![Diagrama en caso de uso](src/docs/images/Funcionalidad1.png)

#  Historia de Usuario

| Campo        | Descripción |
|-------------|------------|
| ID          | HU1|
| Título      | Permitir personalizar el pedido |
| Descripción | Redacción en formato: Como Usuario/Cliente quiero que la pagina me permita personalizar mi pedido para poder personalizar mi pedido a mi gusto |
| Prioridad   | Alta |
| Estimación  | 3 |

---
![Diagrama en caso de uso](src/docs/images/Funcionalidad2.png)

#  Historia de Usuario

| Campo        | Descripción |
|-------------|------------|
| ID          | HU2|
| Título      | Permitir ver el totatl del pedido|
| Descripción | Redacción en formato: Como Usuario/Cliente quiero que la pagina me permita ver el total mi pedido para poder ver me manera cuantitativa lo que debo pagar de  mi pedido  |
| Prioridad   | Alta |
| Estimación  | 3 |
