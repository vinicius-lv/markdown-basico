# Estudando Git e Markdown

![Logo do Git](Git-Logo.png) 
![Logo da Linguagem Markdown](Markdown-Logo.png)

# Lista de marcações em Markdown 

Utilize duas crases `` para destacar um código.
`System.out.print("Hello World!");`

Utilize `---` ou `***` para criar uma linha horizontal.
---

Para destacar um trecho de código, abra três crases ```, escreva o código e feche com três crases.

```
mundialPalmeiras == true ? 'Não tem mundial' : 'Tem mundial'
```

## Titulação

`#`
# Título de nível 1
`##` 
## Título de nível 2
`###`
### Título de nível 3
`####`
#### Título de nível 4

## Ênfase

**Negrito**
`**Palavra**` ou `__Palavra__`

*Itálico*
`*Palavra*` ou `_Palavra_`

~Palavra riscada~
`~Palavra~`

## Lista numerada

Para criar uma lista numerada, coloque um número e um `.` em seguida e escreva o item da lista.

```
1. Item 0
1. Item 1
1. Item 2
```

1. Item 0
1. Item 1
   1. SubItem 0
   1. SubItem 1
1. Item 2
1. Item 3

## Lista demarcada

Para criar uma lista demarcada, utilize um `*` ou `-` na frente de cada item.

```
* Item 0
* Item 1
* Item 2
```

* Item 0
* Item 1
* Item 2
   * SubItem 0
   * SubItem 1
* Item 3

## Lista de Tarefas

Para criar uma lista de tarefas, utilize `-` de um espaço abra `[` de um espaço e feche `]`, de um espaço e escreva a tarefa. Para marcar a tarefa como finalizada coloque um `x` dentro do colchete da tarefa desejada.


- [ ] Tarefa 1
- [x] Tarefa 2
- [ ] Tarefa 3
- [x] Tarefa 4

## Links

Texto âncora, dentro do colchete escreva o texto e dentro do parentese escreva a URL, `[]()`.
[Acesse meu GitHub](https://github.com/vinicius-lv)

Link direto, escreva a URL dentro dos símbolos de menor e maior, `<>`.
<https://github.com/vinicius-lv>

## Tabelas

Para criar uma tabela, escreva os nomes dos títulos das colunas e divida entre barras verticais.
`Coluna 1 | Coluna 2 | Coluna 3`

Separa o título do conteúdo utilizando três hifens para descrever a coluna e separa com uma barra vertical.
`---|---|---`

Por último, escreva o conteúdo de cada coluna, separando por barras verticais.
`Info 1 | Info 2 | Info 3`

### Visualização da tabela no final

Coluna 1 | Coluna 2 | Coluna 3
---|---|---
Info 1 | Info 1 | Info 1
Info 2 | Info 2 | Info 2
Info 3 | Info 3 | Info 3
Info 4 | Info 4 | Info 4



