# EJERCICIO DE README CON MARKDOWN

### EJEMPLO DE DIAGRAMAS

Para realizar un **diagrama** emplearemos * *mermaid* *.
La documentación de mermaid se encuentra en el siguiente [enlace](https://mermaid-js.github.io/mermaid/#/).

##### Requisitos:

- [X] Tener una cuenta de GitHub
- [ ] Emplear un editor de textos

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
@damiancastelao :+1: Que te parece? :shipit:

Aquí tienes una bonita imagen[^1].

![Esto es una imagen](https://www.google.com/url?sa=i&url=https%3A%2F%2Fes.pngtree.com%2Ffree-animals-png%2Fcat&psig=AOvVaw2nFq10FFw14J6QiCZo0F_2&ust=1667496830663000&source=images&cd=vfe&ved=0CA0QjRxqFwoTCJDR-fODkPsCFQAAAAAdAAAAABAE)

[^1]: Extraída de la red.
