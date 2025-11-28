27-11-2025 10:23

Tags: [[2 - Tipografia]] | [[Peso, Estilo e Shorthand]] | 

-----

# Conceito Geral

## O que aprendi? 

Aprendi que existem propriedades CSS que vão definir o peso da fonte, que é quando ela é mais fina ou mais gordinha, que é trabalhando com as famílias tipográficas. 

Também vi sobre estilo da fonte, que é usando o **font-style** que vai definir o estilo, por exemplo: Itálico. 

Aprendi a usar o **shorthand** que é definir várias coisas em uma só linha, por exemplo: peso, tamanho, estilo, tudo na mesma linha. 

----
#### Peso

O peso da fonte é definido com a propriedade **font-weight**, e temos os pesos literais e os pesos numéricos: 

**Literais**:
- lighter: O mais suave; 
- normal: Normal;
- bold: Negrito;
- bolder: Negrito forte.

**Numéricos**: 
 - Variam de 100 a 900, quanto maior mais negrito, quanto menor mais suave. 

**Exemplos**: 

```css

font-weight: 500; 

font-weight: bold; 

```


**Obs**: Nem toda fonte possui todos os pesos. 

-----
#### Estilo 

O estilo da fonte é definido com a propriedade **font-style**, onde podemos colocar o estilo, que seria **italic**, **normal** e etc.

**Exemplos**: 

```css

font-style: italic; 

```


----

#### Shorthand

O Shorthand é quando definimos tudo em uma só linha. Mas é muito importante saber a **ordem** das propriedades. 

No caso das fontes, a ordem é: 

 **font-style** --> **font-weight** --> **font-size** --> **font-family** 

**Exemplo**:

```css

/* font: font-style | font-weight | font-size | font-family */

font: italic bold 2em 'work sans', sans serif; 

```

----

# Referências 

Módulo 02 HTML e CSS: https://youtu.be/oHj5ez1bSkc