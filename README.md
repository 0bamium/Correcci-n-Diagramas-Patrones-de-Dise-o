## Estudiantes
- David Antonio Frías Zuñiga
- José Raúl Méndez Aqueveque
- Sección: 2
## Desarrollo

### Diagrama de Casos de Uso

#### Corrección del diagrama
![](https://github.com/0bamium/Correcci-n-Diagramas-Patrones-de-Dise-o/blob/1183775ad32aa9d6e27868ac7f141c180433be5d/imagenes/caso%20de%20uso.png)
- Se elimino el caso de uso de ver el historial de otras personas
- se elimino el caso de uso eliminar el historial de reservas
- se cambiaron las flechas de casos de uso conectados a otros casos de uso

#### Justificación de errores

- El estudiante no debe ver el historial de otras personas, ya que esto puede llegar a ser hasta ilegal
- No debe existir eliminar el historial de reservas
- Los casos de uso que conectan con otros se les debe aplicar uniones de <<include>> y <<extend>>

### Diagrama de clases

#### Corrección del diagrama

![](https://github.com/0bamium/Correcci-n-Diagramas-Patrones-de-Dise-o/blob/de6e188b1cb53b15de100d3ad8d8b5060774622b/imagenes/diagramadeclases.jpeg)
- la clase reserva esta fuera del diagrama sin actuar con nada
- el administrador tiene asociado el sistema de reservas
- la asociacion del sistema de reservas hacia el usuario esta implementada del lado contrario

#### Justificación de errores


### Diagrama de Implementación

#### Corrección del diagrama

![](https://github.com/0bamium/Correcci-n-Diagramas-Patrones-de-Dise-o/blob/de6e188b1cb53b15de100d3ad8d8b5060774622b/imagenes/diagrama%20de%20implementacion.jpeg)
- modulo historial debe estar enlazado con el sistema de gestion de reservas, no directamente a la base de datos
- la asociacion del gestor de notificaciones esta implementado del lado contrario
- la API del sistema academico externo tendria que estar dentro del sistema de gestion de reservas y no como un externo

#### Justificación de errores

