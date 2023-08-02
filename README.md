<div align="center">
<img  alt="logo Markdown" src="./src/img/markdown.png"/>
</div>

<br>

<h1 align="center">Markdown Sintaxe Básica</h1>

O que e **Markdown**? é uma linguagem de marcação leve e fácil de usar, criada por **_John Gruber_** em 2004 com colaborações de **_Aaron Swartz_**. Markdown converte seu texto em HTML válido. É projetado para ser fácil de ler e escrever, mais usado para formatar arquivos **README** entre outros. Sua sintaxe é intuitiva e compreensível.

<div align="center">
 <img width="150" alt="Good" src="./src//img/good.gif"/>
 </div>

 <br>

 ## ☄️ Títulos

Para criar uma estrutura clara e organizada no seu documento. Use de um a seis sinais de cerquilha `#` para indicar diferentes níveis de títulos.

```
# Título de nível 1
## Título de nível 2
### Título de nível 3
#### Título de nível 4
##### Título de nível 5
###### Título de nível 6
```

_**ou**_

```
Título de nível 1
==

Título de nível 2
--
```

👇

![Titulos](./src/img/titulos.png 'exemplos de Cabeçalho')

<br>

## ☄️ Citações 

Para criar uma citação, adicione um `>` na frente do parágrafo.

```
> Não gosto de domingo, é o dia mais _modorrento_ da semana.
```

A saída renderizada fica assim👇

> Não gosto de domingo, é o dia mais _modorrento_ da semana.

<br>

## ☄️ Emojis 👋😎 

Há duas maneiras de adicionar emoji a arquivos _Markdown_: **copiar** e **cola**r o emoji em seu texto formatado em Markdown ou digitar **códigos** de acesso de emoji .

+  💻`:computer: `

+ 🔗 [Emojipedia](https://emojipedia.org/ 'emojipedia') 

<br>

## ☄️ Ênfase 

Ao combinando negrito e itálico, dê preferência ao uso de três **asteriscos**, para evitar problemas de compatibilidade com aplicativos Markdown  
Ex:

#### **_Italico&negrito_**

```
 ***Italico&negrito***
```

#### _Italico_

```
 *Italico*
```

#### **NEGRITO**

```
 **NEGRITO**
```

#### ~~TACHADO~~

```
 ~~TACHADO~~
```
<br>

## ☄️ Imagens 

Você pode exibir uma imagem adicionando `!` e colocando uma descrição entre `[ ]`, o texto alternativo equivalente às informações da imagem. Em seguida, coloque o link da imagem entre parênteses `()`.
Sintaxe de imagem se assemelha à sintaxe para links, permitindo dois estilos.

```
![descrição](/img.png)
```

_**ou**_

```
![descrição](URL da imagem "texto opocional")
```

![if](./src/img/if.png "Qual opção?")

###### passe o mause sobre a imagem

<br>

## ☄️ Links 

Existe duas formas de inserir link em **Markdown**, através de um link direto ou usando um texto-âncora.

**Link direto**: envolva o endereço da web em chaves `<>` , o endereço ficará visível e será clicável pelo usuário.

🔗 <https://duckduckgo.com>

```
	<https://duckduckgo.com>
```

**Texto-âncora:** `[]()`

🔗 [Duck Duck Go](duckduckgo.com 'mecanismo de buscas com mais privacidade')

```
  [Duck Duck Go](https://duckduckgo.com "mecanismo de busca com mais privacidade")
```

💡 **Dica:** Para inserir uma frase informativa quando o usuário passar o mouse sobre o **link**. Coloque entre **aspas** `" "` após o **URL**.

<br>

## ☄️ Listas 


Crie listas com um hífen `-` , `+` ou `*` seguido de um espaço

#### Lista não ordenada

```
- Javascript
+ Typescript
* React
```

- Javascript
- Typescript
- React

#### Lista Ordenada

coloque um número na frente de cada linha seguindo de um ponto `.`

1. Ruby
2. Node.js
3. PHP

#### Listas aninhadas

1. Fullstack
   - Front End
     - Back End

```
1. Fullstack
   - Front End
     - Back End
```

#### Listas de tarefas

```
- [x] #739
- [ ] klll
- [ ] Add delight
```

<br>

## ☄️ Régua Horizontal

Insira uma linha horizontal para separar seções no seu documento usando três hífens `---` ou asteriscos `***` ou `___` .

**Dessa forma:**

```
---
```
💡***Dica: Em uma unica linha.***

A saída será assim 👇

---

<br>

## ☄️ Tabelas
Crie tabelas organizadas com barras verticais `|` e hífens `-` para delimitar as células e dois pontos `:` como abaixo.

```
| Dev       |   Local    | Quant |
| --------- | :--------: | ----: |
| Front End |   Remoto   |  3500 |
| Back End  |  Híbrido   |   200 |
| FullStack | Presencial |    40 |
```

| Dev       |   Local    | Quant |
| --------- | :--------: | ----: |
| Front End |   Remoto   |  3500 |
| Back End  |  Híbrido   |   200 |
| FullStack | Presencial |    40 |

💡 **_Dica: Para alinha o texto use_** `:` 👇

```
A esquerda   |:----|
Centralizado |:---:|
A direita    |----:|
```
<br>

### Teste seu Markdown:

#### Editor de codigo 
[Visual Studio Code](https://code.visualstudio.com/)

#### Editores online

- [Dillinger](https://dillinger.io/)
- [Markdown Preview](https://markdownlivepreview.com/)
- [Meditor](https://pandao.github.io/editor.md/en.html)

