# app-cafe-de-lima
App Web para la venta de los productos de la empresa `Cafe de Lima`.

## Integrantes
- Bruno Díaz
- Alex Guillen
- Linder Hassinger

## Historias de Usuario
[Link hacia el proyecto](https://github.com/orgs/entertechschool/projects/1)

## Requerimientos del Software
[Link hacia los requerimientos](requirements.md)

## Modelos de Dominio

#### Product
- id (number)
- name (string)
- price (number)
- img (string)

#### Order
- id (number)
- products (object {product: quantity})
- total_price (function)
- status

