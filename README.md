#Docker action "Hola Mundo"

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.
Esta action imprime "Hola Mundo" o "Hola" + el nombre de la persona al log.

## Inputs

### 'who-to greet'

**Requerido** El nombre de la persona a quein saludar. Por defecto "Mundo".

## Outputs

### 'time'

La fecha en la que te salude.

## Example usage

'''
uses: daniel-castrejon/MyFirstAction@v1
with:
    who-to-greet: 'pelades'
'''