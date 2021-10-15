# super_mario_class

<img width="600px" src="https://user-images.githubusercontent.com/73259056/137406586-e301891f-ea6e-4cab-ba64-305a88e6a307.png"/>

Contadores = ['vidas', 'estrelas', 'moedas', 'pontos', 'tempo']


<img width="600px" src="https://user-images.githubusercontent.com/73259056/137403088-df14b905-a102-42af-b8e7-9a63481aaef3.png"/>

Contador de moedas:

> Se contador passar de 99 -> reseta contagem de acordo com a coleta de moedas -> Contador de vidas recebe mais 1


<img width="600px" src="https://images.mariouniversalis.fr/images/jeux/104/smw15.PNG"/>

> Se Mario Andar -> Mario cai no abismo -> Mario morre

> Se Mario Pular

>> Se pular o suficiente -> Mario não cai no abismo

>> Se não pular o suficiente

>>> Se Mario não tiver Yoshi -> cai no abismo -> Mario morre

>>> Se Mario tiver Yoshi

>>>> Se Mario abandonar Yoshi -> Mario não cai no abismo

>>>> Se Mario não abandonar Yoshi -> cai no abismo -> Mario morre

<img width="600px" src="https://user-images.githubusercontent.com/73259056/137403278-e78b84bf-fb8d-47e7-b9a8-c5f2bbcdd2bc.png"/>

Classes = ['heroi', 'lacaio', 'chefe']

<img width="600px" src="https://user-images.githubusercontent.com/73259056/137404710-a6ab9a14-8437-48f1-b356-ef37db5212b4.png"/>

power_ups = ['super_cogumelo', 'flor_de_fogo', 'pena_capa', 'super_estrela']

life_ups: ['cogumelo_1Up', 'lua_3Up']

metodos_heroi = ['normal', 'pegar_item', 'super_cogumelo', 'flor_de_fogo', 'pena_capa', 'super_estrela']


<img width="600px" src="https://user-images.githubusercontent.com/73259056/137421450-57423511-c833-4838-89e3-92826602b7d0.png"/>

<img width="600px" src="https://mario.wiki.gallery/images/6/6e/ValleyOfBowser.png"/>


<img width="600px" src="https://user-images.githubusercontent.com/73259056/137402425-3b813ca9-336e-4fea-9b98-84ee45c2ac1e.png"/>

> Se Mario usa método pegar_item -> Verifica se está em power_ups ou life_ups

>> Se item_atual está em life_ups -> Contador de vida recebe +1 ou +3

>> Se item_atual está em power_ups -> recebe o item pego

>>> Se O item em item_atual for diferente de vazio -> ativar o método de acordo

>>> Se item atual for igual a vazio -> método atual é normal


<img width="600px" src="https://user-images.githubusercontent.com/73259056/137402836-b1ca33d6-b42c-44c0-aa2b-3e572c3fcfc0.png"/>
Quando Mario é atingido:

> Se método atual do Mario for igual a normal -> Mario morre

> Se método atua do Mario for igual a super_estrela -> Inimigo morre

>> Senão -> método atual do Mario recebe normal 

<img width="600px" src="https://user-images.githubusercontent.com/73259056/137419024-45a6c536-a963-4872-a338-9cbbf2a40a27.png"/>

Função de criar blocos
