# Markdown básico
![Logo da Linguagem Markdown](Markdown-Logo.png)

Repositório para ajudar com o básico de markdown.

Clique em algum link do sumário para ir a sessão que deseja se inteirar.

## Sumário
1. [Titulação](#titulacao)
1. [Ênfase](#enfase)
1. [Lista ordenada](#lista-ordenada)
1. [Lista desordenada](#lista-desordenada)
1. [Lista de tarefas](#lista-tarefas)
1. [Links](#links)
1. [Tabelas](#tabelas)
1. [Imagens](#imagens) 
1. [Emojis](#emojis)
1. [Citação (Blockquote)](#quote)
1. [Destacar um trecho de código](#codigo)
1. [Linha horizontal](#linha)

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

---
---

<a id="links"></a>
# Links
Texto âncora, dentro do colchete escreva o texto e dentro do parentese escreva a URL, exemplo: 

`[Acesse meu GitHub](https://github.com/vinicius-lv)`
[Acesse meu GitHub](https://github.com/vinicius-lv)

Link direto, escreva a URL dentro dos símbolos de menor e maior, exemplo:

`<https://github.com/vinicius-lv>`.
<https://github.com/vinicius-lv>

---
---

<a id="tabelas"></a>
# Tabelas
Para criar uma tabela, escreva os nomes dos títulos das colunas e divida entre barras verticais.

`Coluna 1 | Coluna 2 | Coluna 3`.

Separa o título do conteúdo utilizando três hifens para descrever a coluna e separa com uma barra vertical.

`---|---|---`.

Por último, escreva o conteúdo de cada coluna, separando por barras verticais.

`Info 1 | Info 2 | Info 3`.

### Visualização da tabela no final
Coluna 1 | Coluna 2 | Coluna 3
---|---|---
Info 1 | Info 1 | Info 1
Info 2 | Info 2 | Info 2
Info 3 | Info 3 | Info 3
Info 4 | Info 4 | Info 4

---
---

<a id="imagens"></a>
# Imagens
Para adicionar uma imagem utilize o seguinte padrão `![]()`, dentro do colchete escreva a descrição da imagem e dentro do parentese escreva a URL da imagem como no exemplo abaixo.

`![Descrição da imagem](https://imagems.com/doguinho.png)`

---
---

<a id="emojis"></a>
# Emojis
Para adicionar um emoji ao seu texto no GitHub, utilize o padrão `:nome-emoji:`.
Repositório com a lista dos emojis: <https://github.com/ikatyang/emoji-cheat-sheet>.

Exemplo:

```
:smile:
:vulcan_salute:
:alien:
```

Visualização dos emojis:

:smile:
:vulcan_salute:
:alien:

---
---

<a id="quote"></a>
# Citação (Blockquote)
Para criar uma citação, basta adicionar um sinal de maior `>` na frente da frase.

Exemplo: 

```
> Developers developers developers, Steve Ballmer.
```

> Developers developers developers, Steve Ballmer.

---
---

<a id="codigo"></a>
# Destacar um código
Para destacar uma linha de código abra com uma crase escreva a linha e feche com outra crase.

Exemplo:

`System.out.print("Hello World!");`

Para destacar um trecho de código, abra três crases, escreva o código e feche com três crases. Você ainda pode especificar qual linguagem está sendo utilizada após as três primeiras crases, basta escrever o nome da linguagem.

```javascript
mundialPalmeiras == true ? 'Não tem mundial' : 'Tem mundial'
```

---
---

<a id="linha"></a>
# Linha horizontal
Utilize `---` ou `***` para criar uma linha horizontal.

Exemplo:

---
