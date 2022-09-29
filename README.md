# Markdown básico
![Logo da Linguagem Markdown](Markdown-Logo.png)

Repositório para ajudar com o básico de markdown.

Clique no link do sumário para ir a sessão que deseja aprender.

## Sumário
1. [Titulação](#titulacao)
1. [Ênfase](#enfase)
1. [Lista ordenada](#lista-ordenada)
1. [Lista desordenada](#lista-desordenada)
1. [Lista de tarefas](#lista-tarefas)

---
---

<a id="titulacao"></a>
# Titulação
Para criar um título, utilize `#` e escreva o título, como no exemplo abaixo.

`# Título de nível`
# Título de nível 1

`## Título de nível 2` 
## Título de nível 2

`### Título de nível 3`
### Título de nível 3

`#### Título de nível 4`
#### Título de nível 4

---
---

<a id="enfase"></a>
# Ênfase
Para dar algum tipo de ênfase à uma palavra, utilize os caracteres específicos no início e no final de cada palavra.

**Negrito**
`**Palavra**` ou `__Palavra__`

*Itálico*
`*Palavra*` ou `_Palavra_`

~Tachado~
`~Palavra~`

---
---

<a id="lista-ordenada"></a>
# Lista ordenada
Para criar uma lista ordenada, coloque o número do item e seguido de um ponto e escreva o item da lista. Exemplo:

```
1. Item 1
2. Item 2
```

1. Item 0
2. Item 1
3. Item 2


Lista com sublista, apenas de um tab abaixo do item que terá uma sublista e crie uma lista normalmente.

```
1. Item 1
2. Item 2
   1. SubItem 1
```

1. Item 0
1. Item 1
   1. SubItem 0
   1. SubItem 1
1. Item 2
1. Item 3

----
----

<a id="lista-desordenada"></a>
# Lista desordenada
Para criar uma lista desordenada, utilize um `*` ou `-` na frente de cada item, Exemplo:

```
* Item 300
* Item 301
```

* Item 0
* Item 1
* Item 2

Lista com sublista, apenas de um tab abaixo do item que terá uma sublista e crie uma lista normalmente.

```
- Item 1
- Item 2
   - SubItem 1
```

* Item 0
* Item 1
* Item 2
   * SubItem 0
   * SubItem 1
* Item 3

---
---

<a id="lista-tarefas"></a>
# Lista de Tarefas
Para criar uma lista de tarefas, utilize `-` de um espaço abra `[` de um espaço e feche `]`, de um espaço e escreva a tarefa. Para marcar a tarefa como finalizada coloque um `x` dentro do colchete da tarefa desejada. Exemplo:

```
- [ ] Tarefa 400
- [x] Tarefa 401
```

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

## Imagens
Para adicionar utilize o seguinte padrão `![]()`, dentro do colchete escreva a descrição da imagem e dentro do parentese escreva a URL da imagem.

`![Descrição da imagem](https://imagems.com/doguinho.png)`

## Emojis
Para colocar um emoji no seu texto, coloque abra `:` escreva o nome do emoji e feche com `:`.
Repositório com a lista dos emojis: <https://github.com/ikatyang/emoji-cheat-sheet>.

```
:smile:
:vulcan_salute:
:alien:
```
:smile:
:vulcan_salute:
:alien:

## Citação (Quote)
Para criar uma citação, basta adicionar um sinal de maior `>` na frente da frase.

```
> Olá, mundo!
```

> Olá, mundo!

Utilize duas crases `` para destacar um código.
`System.out.print("Hello World!");`

Utilize `---` ou `***` para criar uma linha horizontal.
---

Para destacar um trecho de código, abra três crases ```, escreva o código e feche com três crases. Você ainda pode deixar mais específico o trecho do código, especificando a linguagem que está sendo utilizada após as três primeiras crases.

```javascript
mundialPalmeiras == true ? 'Não tem mundial' : 'Tem mundial'
```
