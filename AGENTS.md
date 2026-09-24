<!-- Sustituye {{NOMBRE_REPO}} por el nombre oficial del repositorio. -->
# {{NOMBRE_REPO}}

<!-- Sustituye {{PROPOSITO_UNA_LINEA}} por una frase que resuma el propósito del repositorio. -->
Propósito: {{PROPOSITO_UNA_LINEA}}

## Reglas aplicables

Las reglas transversales del repositorio están en [`docs/standards/`](docs/standards/). Consúltalas antes de realizar cambios.

No repitas esas reglas aquí; este archivo solo contiene el contexto específico del repositorio.

## Estructura

El repositorio es un proyecto autocontenido:

- `theme/`: theme de bloques del proyecto.
- `plugin/`: plugin del proyecto.
- `docs/`: documentación del proyecto y el submódulo `docs/standards/`.

No dependas de paquetes compartidos de otros repositorios; theme, plugin y contenido
viven aquí.

Convenciones de commit: los scopes habituales son el nombre del proyecto, `theme` y
`plugin` (por ejemplo `feat(theme): ...`).

## Validación

<!-- Sustituye {{COMANDO_TEST}} por el comando completo para ejecutar las pruebas del repositorio. -->
```sh
{{COMANDO_TEST}}
```

Ejecuta la validación antes de entregar cualquier cambio.
