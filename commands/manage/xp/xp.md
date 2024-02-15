---
layout: central
---

[!button text="Volver" size="s" variant="contrast" icon="chevron-left"](../manage.md)

# `/manage xp`

### Descripción
¿Quieres modificar la XP de un usuario o grupo de usuarios? Inicia este comando y deja que Catto se encargue de todo.

### Uso
```
/manage xp <afectado> <acción> <valor> <sección>
```

### Argumentos

`afectado` - Usuario o rol afectado por la acción<br>
`acción` - Acción a llevar a cabo sobre el afectado<br>
`valor` - Valor que se le dará a la acción<br>
`sección` - Sección sobre la que se aplicarán los cambios<br>

### Ejemplo
```
/manage xp afectado:gacarbla acción:"Establecer nivel" valor:0 sección:"Texto"
```

### Permisos

El afectado es un usuario<br>
[!button text="Gestión de usuarios" size="xs" variant="warning"]

El afectado es un rol<br>
[!button text="Gestión del servidor" size="xs" variant="warning"]