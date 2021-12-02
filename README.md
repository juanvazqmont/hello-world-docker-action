# Docker action "Hola Mundo"

Esta acción imprime "Hello world" o "Hello" + el nombre de una persona que se quiere saludar al log.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a saludar, por defecto `"mundo"`

## Outputs

### `time`

```
uses: juanvazqmont/hello-world-docker-action@v1
with:
  who-to-greet: 'Messi'
```

