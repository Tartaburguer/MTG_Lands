# MTG_Lands
ESPECIALIZAÇÃO EM ENGENHARIA DE DADOS

Projeto da disciplina Redes Neurais
O projeto de conclusão da disciplina de Redes Neurais, consiste na construção (e treinamento) de um modelo de classificador de imagens.

O objetivo é criar um classificador que classifique entre ao menos dois tipos de categorias (gatos e cachorros, cadeira e mesa, casa e carro por exemplo)

A única restrição é a necessidade da construção de um dataset customizado

Equipe: Renato Lopes

Janeiro / 2022

Montagem do Dataset

Para a construção do dataset customizado foi utilizado imagens de cards de terreno basico do jogo de cartas Magic the gathering.

As imagens foram baixadas do site https://mtgrex.com/?land=plains&land=island&land=swamp&land=mountain&land=forest&perPage=100 mas existem uma infinidade de sites onde é possivel baixar imagem de cartas do jogo

Para auxiliar no dowload das imagens foi utilizado o plugin Ftkun Batch Download image do google chrome.

Após o download das imagens as mesmas foram separadas em cinco categorias de terrenos basicos:

Mountain - Swamp - Plains - Island - Florest

Após a separação nos folders de cada categoria, foi criado o github com o dataset https://github.com/RenatoDLopes/MTG_Lands

Para treinar a rede neural é só executar em ordem sequencial os codigos do phyton.
