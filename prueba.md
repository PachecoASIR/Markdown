#EJERCICIO DE README CON MARKDOWN#

###EJEMPLO DE DIAGRAMAS###

Para realizar un **diagrama** emplearemos * *mermaid* *.
La documentación de mermaid se encuentra en el siguiente [enlace](https://mermaid-js.github.io/mermaid/#/).

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
```
Ahora bien, tenemos más formas de crear diagramas como puede ser la siguiente
```

```mermaid
sequenceDiagram
    participant Pacheco
    participant Pepe
    Pacheco->>Pepe: Hola Pepe, como estás?
    loop Pensando
        Pepe->>Pepe: Lucha con sus pensamientos
    end
    Note right of Pepe: Pensamientos racionales <br/>Prevalecen!
    Pepe-->>Pacheco: Bien!
    Pepe->>Pacheco: Y tu que tal?
    Pacheco-->>Pepe: Mejor ni hablemos!
```
[Contribution guidelines for this project](docs/README.md)