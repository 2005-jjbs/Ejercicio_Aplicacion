# Casos de Uso

## Diagrama de Casos de Uso

```plantuml
@startuml
left to right direction
skin rose

actor "Estudiante / Usuario" as Usuario
actor Visitante

rectangle "Marketplace Javeriana" {

    Visitante --> (Confirmar contraseña y enviar formulario)

    Usuario --> (Completar registro complementario)
    Usuario --> (Visualizar catálogo de productos)
    Usuario --> (Registrar nuevo producto)

}
@enduml
```

## Listado de Casos de Uso

| #    | Nombre                                                                                                    |
| ---- | --------------------------------------------------------------------------------------------------------- |
| CU01 | [Confirmar contraseña y enviar formulario](casos-de-uso/CU01-Confirmar-contraseña-y-enviar-formulario.md) |
| CU02 | [Completar registro complementario](casos-de-uso/CU02-Completar-registro-complementario.md)               |
| CU03 | [Visualizar catálogo de productos](casos-de-uso/CU03-Visualizar-catalogo-productos.md)                    |
| CU04 | [Registrar nuevo producto](casos-de-uso/CU04-Registrar-nuevo-producto.md)                                 |
