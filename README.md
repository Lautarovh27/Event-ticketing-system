# Event Ticketing System — Sistema de Venta de Entradas

Sistema de gestión y venta de entradas desarrollado en **Java puro**, aplicando los pilares de la Programación Orientada a Objetos. Simula la lógica de una plataforma de ticketing con diferentes tipos de eventos, clientes y entradas.

## Tecnologías y conceptos

- **Lenguaje:** Java
- **Paradigma:** Programación Orientada a Objetos (POO)
- **Build:** Eclipse / javac

## Habilidades demostradas

- **Herencia** y jerarquía de clases (distintos tipos de eventos y entradas)
- **Polimorfismo** para manejar comportamientos distintos entre subclases
- **Encapsulamiento** y diseño de clases con responsabilidades claras
- **Estructuras de datos**: listas, colecciones y manejo de objetos
- Modelado de dominio real (eventos, clientes, tickets, precios)
- Validaciones y lógica de negocio en Java puro

## Estructura del modelo

```
Event (abstract)
├── Concert
├── SportsEvent
└── Theater

Ticket
├── GeneralTicket
└── VIPTicket

Client
└── purchase(Event, TicketType)
```


Abrí el proyecto en **Eclipse** o **IntelliJ IDEA** y ejecutá la clase principal.

## Autor

**Ezequiel**
**Lautaro** — Desarrollador Java Junior  
📎 [GitHub](https://github.com/Lautarovh27) · [LinkedIn](https://www.linkedin.com/in/lautaro-van-hoorenbeeck/)
