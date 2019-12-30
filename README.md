# Trabalho de Conclusão de Curso (TCC)



No Brasil, muitos cursos de graduação exigem a elaboração de um Trabalho de Conclusão de Curso (TCC) como requisito para a colação de grau. Além disso, exige-se que o trabalho seja feito dentro dos padrões ABNT (Associação Brasileiras de Normas Ténicas).

Ao final da minha graduação, tive que fazer um TCC como requisito para a colação de grau nos cursos de Direito e de Matemática Aplicada da Fundação Getúlio Vargas (FGV). Como estava no programa de dupla-graduação, fiz apenas um trabalho para os dois cursos.

Por enquanto eu fazia a tarefa, lembro que a linguagem LaTeX junto da biblioteca ABNTeX muito me ajudaram. Eu perdi pouco tempo organizando questões relacionadas à formatação.

Alguns colegas vieram me pedir o meu *source* para usar de referência. Criei esse repositório com o intuito de disponibilizar isso para outras pessoas.



## Link no Overleaf

O *source* do LaTeX pode ser encontrado no [link do overleaf](https://www.overleaf.com/read/frsdddmzbhnr) . Com esse link é possível vizualizar o código. No entanto, não é possível editá-lo.



## Formato final

A versão final do trabalho em PDF está na [biblioteca digital da FGV](http://bibliotecadigital.fgv.br/dspace/bitstream/handle/10438/24728/PEDRO%20DELFINO.pdf?sequence=1&isAllowed=y).

Os metadados da bibliteconomia podem ser encontrados [aqui](http://bibliotecadigital.fgv.br/dspace/handle/10438/24728).

### Avisos

Foi preciso fazer algumas levas alterações no *default* do AbntTex.  Por default, o padrão de citação é numérico. Assim, no texto, temos algo como:

```
	"Como apontado em [2] , bla bla bla [...]"
```

 E, lá no final do texto, nas referências bibliográficas, temos:

```markdown
[2] DELFINO, Pedro. "Construindo o Primeiro Algoritmo Aprovado no Exame da OAB", 2018.
```

Esse padrão de citação é pouco comum no Direito e, como meu trabalho foi direcionado para duas comunidades acadêmicas distintas, achei que era melhor usar o padrão autor-data. Nesse caso teríamos:

```
	"Como apontado em (DELFINO,2018) , bla bla bla [...]"
```

Isso pode ser alterado.



### Agradecimento

Assim como fiz na seção de agradecimentos do meu TCC, aproveito para parabenizar as pessoas responsáveis pelo pactote ABNTex (Absurdas Normas para Tex). Aliás, o trocadilho no nome é muito bom.

Em especial, @laurocesar. Por sinal, Lauro também tem contribuições para o LexML, outro software que utilizei na pesquisa do meu TCC. Esse repositório é só mais um ponteiro no palheiro da *Web* para divulgar o bom trabalho desse pessoal.





