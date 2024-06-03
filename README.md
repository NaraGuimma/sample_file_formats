# Exemplos de Formatos de Arquivos

Este repositório contém exemplos de diferentes formatos de arquivos, como CSV, JSON e XML. Esses exemplos podem ser úteis para entender como os dados podem ser armazenados e estruturados em diferentes formatos.

## Índice

- [Formato CSV](#formato-csv)
- [Formato JSON](#formato-json)
- [Formato XML](#formato-xml)

## Formato CSV

O formato CSV (Comma-Separated Values) é amplamente utilizado para armazenar dados tabulares em texto simples. Cada linha do arquivo representa um registro e as colunas são separadas por vírgulas.

### Exemplo de Arquivo CSV

```csv
nome,idade,email
João,28,joao@example.com
Maria,34,maria@example.com
Pedro,23,pedro@example.com
```


## Formato JSON

O formato JSON (JavaScript Object Notation) é um formato leve de troca de dados, fácil para humanos lerem e escreverem, e fácil para máquinas interpretarem e gerarem. Ele utiliza uma estrutura de pares chave-valor.

### Exemplo de Arquivo Json

```json
{
    "pessoas": [
        {
            "nome": "João",
            "idade": 28,
            "email": "joao@example.com"
        },
        {
            "nome": "Maria",
            "idade": 34,
            "email": "maria@example.com"
        },
        {
            "nome": "Pedro",
            "idade": 23,
            "email": "pedro@example.com"
        }
    ]
}
```

## Formato XML

O formato XML (eXtensible Markup Language) é um formato de marcação que define um conjunto de regras para a codificação de documentos em um formato que é legível tanto para humanos quanto para máquinas.

### Exemplo de Arquivo XML

```xml
<?xml version="1.0" encoding="UTF-8"?>
<pessoas>
    <pessoa>
        <nome>João</nome>
        <idade>28</idade>
        <email>joao@example.com</email>
    </pessoa>
    <pessoa>
        <nome>Maria</nome>
        <idade>34</idade>
        <email>maria@example.com</email>
    </pessoa>
    <pessoa>
        <nome>Pedro</nome>
        <idade>23</idade>
        <email>pedro@example.com</email>
    </pessoa>
</pessoas>
```
