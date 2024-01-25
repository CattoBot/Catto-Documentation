---
layout: central
---

[!button text="Volver" size="s" variant="contrast" icon="chevron-left"](../moderation.md)
# `/mod notes add`
### Description
Añade una nota de moderación a un usuario. Sea lo que sea que haya hecho, no se te olvidará, y podrás adjuntar archivos de hasta 25MB o establecer que sólo un rol en específico tenga acceso a ella.

### Uso
```
/mod notes add <usuario> <texto> [adjunto1] ... [adjunto5] [restricción]
```

### Argumentos
`usuario` - Usuario al que se le adjuntará la nota.<br>
`texto` - Nota a adjuntar.<br>
`adjunto1-6` - Archivos a añadir en la nota (No pueden superar los 25MB en conjunto).<br>
`restricción` - Rol que podrá ver la nota (En caso de no especificarse, todos los moderadores podrán).

### Ejemplo
```
/mod notes add usuario:gacarbla texto:Reproducción de audios saturados
```

### Permisos
[!button text="Gestión de mensajes" size="xs" variant="warning"]