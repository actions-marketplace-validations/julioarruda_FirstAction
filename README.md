# Hello world docker action

Essa action imprime "Hello World" ou "Hello" + o nome da pessoa a quem comprimentar no log

## Inputs

### `who-to-greet`

**Required** o nome da pessoa a quem compirmentar. Default `"World"`.

## Outputs

### `time`

momento da Execução.

## Example usage

uses: julioarruda/FirstAction@v1
with:
  who-to-greet: 'Julio Arruda'