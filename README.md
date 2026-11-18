![Markdown](https://img.shields.io/badge/Markdown-guia-black) ![Git](https://img.shields.io/badge/Git-ramas%20y%20conflictos-orange)

# Tienda Don Pedro

Sistema sencillo para organizar la información de la tienda de barrio de Don Pedro: productos, clientes, fiado, descuentos y domicilios.

## Qué vende Don Pedro

| Producto | Precio |
|---|---|
| Leche 1L | $4.500 |
| Pan tajado | $7.000 |
| Huevos x12 | $14.000 |
| Café 500g | $16.000 |
| Panela | $3.500 |
| Arroz 1kg | $4.800 |

## Cómo está organizada la carpeta

```
tienda-don-pedro/
├── datos/
│   ├── clientes.txt
│   ├── descuentos.txt
│   ├── domicilios.txt
│   ├── fiado.txt
│   └── productos.txt
├── respuesta_ticket3.md
└── README.md
```

## Domicilios

- Centro: $2.000
- La Esperanza: $3.500
- El Carmen: $5.000

El detalle está en `datos/domicilios.txt`.

## Cambios que hice

- Agregué el arroz y actualicé el precio de la leche.
- Registré un cliente con dirección y un pedido; después borré el pedido con `git rm`.
- Guardé el fiado y los descuentos en ramas propias, unidas a `main` y borradas al terminar.
- Generé y resolví dos conflictos de precio: en el pan ganó `pan-proveedor` y en el café ganó `cafe-promocion`.
- Agregué el cobro de domicilios por barrio.
- Reescribí este README con títulos, listas y una tabla.

> [!NOTE]
> El precio del pan pasó a $7.000 en el commit `e3c99e3`. La explicación está en [respuesta_ticket3.md](respuesta_ticket3.md).
