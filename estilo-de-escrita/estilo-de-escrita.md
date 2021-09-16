---
description: >-
  Essa é uma tentativa de padronizar as nomeclatoras de variaveis, objetos,
  classes, arquivos, colunas e linhas de tabelas.
---

# Estilo de escrita

## Introdução

        A forma como lemos e entendemos o mundo ao nosso redor é derivado de padrões. Ao vermos sistematicamente caracteristicas conceituais de uma determinada forma, aprendemos e associamos estas caracteristicas como uma representação generalizada deste item. Como exemplo: você provavelmente consegue identificar um palhaço apenas olhanndo para ele 🤡. As forma de se vestir, os adornos e a maquiagem permite que você separe alguém vestido de palhaço de um empresário qualquer.

        Na escrita, esse fato também acontece. O simples fato de você ler este texto demonstra o quão importante é manter os padrões. Se os simbolos  de uma escrita variassem em relação a cada escritor, jamais seriamos capaz de transmitir conhecimento. 

        Nas linguagens computacionais este fato é uma meia verdade. Apesar de as regras de escrita de que cada linguagem mantenha padrões obrigatórios, os programadores são livres para definir a nomeclatura de variaveis, objetos, arquivos, etc. Para melhor visualizarmos esse fato, imaginemos que um progrador queira salvar um vetor contendo nome de três alunas de graduação em uma variavel qualquer. Então ele pode salvar algo como:

```text
nA
Alunasghs
variavelDEnomes
ALUNAS_nomes
NomAluNEsa
Variavel1
X
nomealunas
nomeAlunas
NomeAlunas
nome.alunas
nome_alunas
NOMEALUNAS
```

        Percebemos então que apesar de ser uma variavel contendo três nomes, a nomeclatura para ela pode variar de acordo com cada autor. A tentativa deste capitulo não é ter um padrão obrigatório quanto a escrita e quais nomes devem ser usados, mas um guia para auxiliar a escrita mais eficaz dos nomes.

## Princiapais estilos

Não me aprofundarei na história ou a motivação de cada um dos estilos que citarei a seguir. Alguns dos principais estilos de escrita na programação e seus respectivos exemplos:

| Estilo | Exemplo |
| :--- | :--- |
| Lower Case | nomealunas |
| Upper Case | NOMEALUNAS |
| Mixed Case | nOmEaLuNa |
| Lower Upper | nomeALUNA |
| Upper Lower | NOMEaluna |
| Camel Case | nomeAlunas |
| Pascal Case | NomeAlunas |
| Snake Case \(under\) | nome\_aluna |
| Snake Case \(upper\) | NOME\_ALUNA |
| Kebab Case | nome-aluna |
| Dot Case | nome.aluna |

## Geral

Não deve-se usar:

* Pontos
* Caracteres especiais
* Espaço
* Simbolos
* Acentos
* Palavras fora de contexto
* Preposições \(de, do, da\)

Pode-se usar

* Letras
* Palavras
* Numeros
* Os sibolos  **-**   e   **\_**

## **Pastas**

Um estilo de padronização de pastas para dois projetos que usam o mesmo banco de dados. A pasta input são dos dados corrigidos , filtrados ou separados do banco de dados original. Os arquivos output são as saidas finais para os arquivos. Estou tentando criar uma pasta chamada "processados" para os processos intermediarios, mas sem eficacia para saida final, como por exemplo: Na pasta dados tenho um raster. Em input tenho um recorte do raster especificando a área de interesse. Em "processados" tenho o filtro para retirada de outliers do raster. Em output os arquivos processados do raster. Em entrega os produtos de interesse finalizados. Essa organização permite com que os dados sejam consultados pelo caminho relativo "../../dados". 

Os dados brutos devem ser apenas para leitura. 

```text
PROJETOS COM MESMO BANCO DE DADOS

Pasta raiz
+-- local-01
|    +-- dados
|    |   +-- imagem
|    |   +-- tabela
|    |   +-- video
|    |   +-- vetor
|    \-- projetos
|        +-- inventario_florestal
|         |    +-- 00_scripts
|         |    +-- 01_input
|         |    |   +-- tb
|         |    |   +-- geo
|         |    |   +-- obj
|         |    +-- processados
|         |    +-- 02_output
|         |    |   +-- grafico
|         |    |   +-- tabela
|         |    |   +-- geo
|         |    +-- 03_entrega
|         \-- cubagem_arvores
\-- local-02


PROJETOS COM DIFERENTES BANCOS DADOS

+-- local-01
    +-- scripts
    +-- output
    +-- dados
    |   +-- brutos
    |   +-- processados
    \-- entrega
        +-- relatorio
```

As pastas podem ser escritas seguindo as regras gerais. Preferencialemente devem ser escritas em sneak\_case com letras minúsculas. Recomendo usar underline \( \_ \) para criação de contexto e traço \( - \) para sequenciamento, referencias geografica, data ... Exemplo:

* projeto\_carbono-01
* projeto\_carbono-02
* mapas-MG
* mapas-RJ
* mapas\_minas_\__gerais-BH
* faturamento-2021-08-13

## Arquivos

Os arquivos seguem a mesma terminologias que o 

## Tabelas

## No R



Singular ID



Referências

&lt;https://www.youtube.com/watch?v=wXIuvdhMOsE&list=TLPQMTMwOTIwMjGPNNiIEa2kEA&index=9&gt;



