# Termo

**Disciplina**: FGA0210 - PARADIGMAS DE PROGRAMAÇÃO - T01 <br>
**Nro do Grupo (de acordo com a Planilha de Divisão dos Grupos)**: 04<br>
**Paradigma**: Funcional<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 20/0060783  |  Ana Beatriz Wanderley Massuh |
| 19/0026588  |  Davi Lima silva |
| 20/0057421  |  Delziron Braz de Lima |
| 20/0018060  |  Gabriel Ferreira da Silva |
| 20/0030264  |  Guilherme Nishimura da Silva |
| 18/0121847  |  Helder Lourenço de Abreu Marques |
| 18/0136925  |  Hugo Rocha de Moura |
| 19/0142260  |  Mateus de Almeida Dias |
| 20/0025791  |  Pablo Guilherme de Jesus Batista Silva |

## Sobre 

Termo é uma aplicação no estilo jogo que pretende simular um jogo de advinhação que consiste em que o jogador tente advinhar em no maximo 6 tentativas a palavra escolhida . A palavra tem um tamanho de 5 letras em que para auxiliar o jogador ao tentar advinhar a palavra ele recebe as seguintes instruções:

1-Caso a letra esteja em Verde 🟩 , significa que a letra se encontra na posição correta, 5 letras verdes corresponde ao acerto da palavra

2-Caso a letra esteja em amarelo 🟨,significa que essa letra se encontra nessa palavra porém em outra posição

3-Caso a letra esteja sem nenhuma das cores ,significa que essa letra nao se encontra na palavra

O jogador so obtem vitoria nesse jogo quando acerta as palavras antes de acabar as tentativas .O seguinte projeto tenta similar ao jogo [TERMO](https://term.ooo/) porém para linguagem huskel .

## Screenshots

![image](https://github.com/UnBParadigmas2024-1/2024.1_G4_Funcional_Termo/assets/78215376/60d4da2b-dbaa-40f4-994d-42b5e64d3711)

![image](https://github.com/UnBParadigmas2024-1/2024.1_G4_Funcional_Termo/assets/78215376/27eef21b-b468-45ba-a580-15caec6e179e)



.

## Instalação 
**Linguagens**: Haskell<br>
**Tecnologias**: Cabal<br>
Docker



### instalando o docker

[Windows](https://docs.docker.com/desktop/install/windows-install/)
[Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
[Manjaro linux](https://manjariando.com.br/docker/)

obs: verifique sua distro linux pois pode haver a necessidade de alguns passos extras ou permissões de administrador


## Uso 
Para rodar o código é necessária a instalação do docker.

### Vá para a pasta do game
    cd src
### Faça o build do projeto
    make build
### Rode o game
    make up

## Vídeo
Adicione 1 ou mais vídeos com a execução do projeto.
Procure: 
(i) Introduzir o projeto;
(ii) Mostrar passo a passo o código, explicando-o, e deixando claro o que é de terceiros, e o que é contribuição real da equipe;
(iii) Apresentar particularidades do Paradigma, da Linguagem, e das Tecnologias, e
(iV) Apresentar lições aprendidas, contribuições, pendências, e ideias para trabalhos futuros.
OBS: TODOS DEVEM PARTICIPAR, CONFERINDO PONTOS DE VISTA.
TEMPO: +/- 15min

## Participações
Apresente, brevemente, como cada membro do grupo contribuiu para o projeto.
|Nome do Membro | Contribuição | Significância da Contribuição para o Projeto (Excelente/Boa/Regular/Ruim/Nula) |
| -- | -- | -- |
| Pablo  |  Refatoração das funções makeAttempt e displayAttemptNumbers | Boa |
| Hugo  |  Pesquisa de projetos, pesquisa sobre o haskell e cabal, adequações iniciais do repositório, dockerização, elaboração do makefile, entre outros | Excelente |

## Outros 
Quaisquer outras informações sobre o projeto podem ser descritas aqui. Não esqueça, entretanto, de informar sobre:
(i) Lições Aprendidas;
(ii) Percepções;
(iii) Contribuições e Fragilidades, e
(iV) Trabalhos Futuros.

## Fontes

[Grupo 4 2023.1 termo](https://github.com/UnBParadigmas2023-1/2023.1_G4_Funcional_Termo/tree/main)

[Termo by ValdsonJr](https://github.com/Valdsonjr/termo-hs/tree/main)

[Documentação docker haskell](https://hub.docker.com/_/haskell/)

[Haskell Doc](https://www.haskell.org/documentation/)

[Linguagens de Programação Programação Funcional Haskell](http://profs.ic.uff.br/~bazilio/cursos/lp/material/ProgFuncional.pdf)

[Haskell: Uma introdução à programação funcional](https://pt.annas-archive.org/md5/f4b1fae5debfb88217490caaeccb8578)

[Segunda Parte do Post: Aprofundando-se em Haskell e Programação Funcional](https://blog.skill.dev/segunda-parte-do-post-aprofundando-se-em-haskell-e-programacao-funcional/)

[Termo](https://term.ooo/)
