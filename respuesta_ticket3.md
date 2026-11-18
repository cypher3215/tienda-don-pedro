# Respuesta del Ticket 3

**Pregunta:** ¿en qué commit cambió el precio del pan a $7.000 y qué mensaje tenía?

**Comando usado (solo `git log`):**

```
git log -S 'Pan tajado - $7.000' --oneline -- datos/productos.txt
```

**Resultado:**

```
e3c99e3 fix: sube el precio del pan
```

**Respuesta:** el cambio quedó en el commit `e3c99e3`, con el mensaje `fix: sube el precio del pan`. Ese commit fue el de la rama `pan-proveedor`, que luego se unió a `main`.
