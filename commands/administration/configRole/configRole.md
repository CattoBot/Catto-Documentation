---
layout: central
---
[!button text="Volver" size="s" variant="contrast" icon="chevron-left"](../administration.md)
# `/admin config role`
### Descripción
Modifica la configuración de roles en el servidor.

Al usar este comando podría mostrarse un formulario modal para especificar uno o más valores. En caso de rellenarlo de forma incorrecta el comando será cancelado y será necesario volver a usarlo para intentar nuevamente modificar esta configuración.

### Uso
```
/admin config role <rol> <opción>
```

### Argumentos
`rol` - Rol del servidor.<br>
`opción` - Configuración que será aplicada al rol.

### Ejemplo
```
/admin config role rol:@principiante opción:Asignar al lograr un nivel
```

### Permisos
[!button text="Administrador" size="xs" variant="danger"]