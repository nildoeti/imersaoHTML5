# imersaoHTML5

Repositório para a prática e construção das estruturas das HTML'S

### Propriedades relacionadas ao Flex Box

#### Display

Define o elemento como um flex container, tornando os seus filhos  [flex-itens](https://github.com/nildoeti/imersaoHTML5/blob/main/flex-box/0-display-flex.html).

#### flex-direction

Estabelece o eixo principal do container, defindo assim a direção que os flex items são colocados no [flex container](https://github.com/nildoeti/imersaoHTML5/blob/main/flex-box/1-flex-direction.html).

```css
flex-direction: row
// Os itens ficam em linha
```

```css
flex-direction: column;
// Os itens ficam em uma única coluna, um embaixo   do outro.
```
```css
flex-direction: column-reverse;
// Os itens ficam em única coluna, um embaixo do outro, em ordem reversa: 3, 2 ...
```
### Exemplo do arquivo 1-flex-direction.html do projeto
![flex-direction](https://github.com/nildoeti/imersaoHTML5/blob/main/flex-box/img/1-flex-direction.jpg)

### flex-wrap
```css
flex-wrap: nowrap;
// Não permite a quebra de linha

flex-wrap: wrap;
// Gera a quebra de linha assim que um dos flex items não poder mais ser compactado.

flex-wrap: wrap-reverse;
// Gera a quebra de linha assim que um dos flex items não poder mais ser compactado, porém na direção contrária, uma linha acima.
```
-   flex-flow
-   justify-content
-   align-items
-   align-content

### Propriedades relacioadas aos Flex Items

-   flex-grow
-   flex-basis
-   flex-shrink
-   flex
-   order
-   align-self
