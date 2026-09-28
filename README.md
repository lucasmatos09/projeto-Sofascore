# SofaScore School App ⚽

## Sobre o projeto

Este projeto foi desenvolvido como uma atividade escolar de Desenvolvimento de Interfaces para Android.

A proposta foi criar um aplicativo de resultados esportivos inspirado visualmente no Sofascore, utilizando Kotlin, XML e ConstraintLayout.

O foco principal do trabalho é a criação da interface, buscando deixar o aplicativo moderno, organizado e semelhante a aplicativos esportivos reais.

## Tecnologias utilizadas

- Android Studio
- Kotlin
- XML
- ConstraintLayout
- Android SDK
- Material Design

## Funcionalidades

O aplicativo possui:

- Tela inicial com partidas de futebol
- Categorias de esportes
- Seleção entre Ontem, Hoje e Amanhã
- Cards com partidas
- Escudos dos times
- Resultado das partidas
- Tela de detalhes da partida
- Abas de Resumo, Estatísticas, Escalações e Classificação
- Campo de futebol com escalação
- Jogadores organizados em formação 4-3-3
- Perfil de jogador
- Estatísticas individuais
- Navegação inferior
- Botão para voltar entre as telas
- Scroll para conteúdos maiores que a tela

## ConstraintLayout

As telas principais utilizam ConstraintLayout.

Os componentes são posicionados através de constraints, como:

- top
- bottom
- start
- end

Não foram utilizadas coordenadas absolutas para posicionar os elementos.

Isso permite que a interface se adapte melhor a diferentes tamanhos de tela.

## Telas

### Tela principal

Apresenta as categorias esportivas, seleção de data e os principais jogos.

### Detalhes da partida

Mostra o placar, os times e informações da partida.

Exemplo:

Manchester City 2 x 1 Arsenal

Status: Encerrado

### Escalações

Apresenta os jogadores posicionados em um campo de futebol utilizando uma formação 4-3-3.

Também possui uma área para os jogadores reservas.

### Perfil do jogador

Apresenta informações individuais do jogador, como:

- Nome
- Número
- Posição
- Idade
- Nacionalidade
- Time
- Altura
- Partidas
- Gols
- Assistências
- Nota média

## Estrutura principal

SofaScoreSchoolApp/

app/
src/
main/

java/com/example/sofascoreschool/
- MainActivity.kt
- MatchDetailsActivity.kt
- PlayerProfileActivity.kt

res/layout/
- activity_main.xml
- activity_match_details.xml
- activity_player_profile.xml

res/drawable/
- Ícones
- Escudos
- Avatares
- Fundos
- Elementos visuais

res/values/
- colors.xml
- strings.xml
- styles.xml
- themes.xml

AndroidManifest.xml

## Como executar

1. Abra o Android Studio.
2. Selecione "Open".
3. Abra a pasta do projeto.
4. Aguarde o Gradle carregar.
5. Selecione um emulador Android, como o Pixel 4.
6. Clique no botão Run ▶.
7. Aguarde o aplicativo ser instalado no emulador.

## Objetivo

O objetivo deste projeto é praticar conceitos de desenvolvimento de interfaces Android, principalmente:

- ConstraintLayout
- XML
- Responsividade
- Organização de componentes
- Navegação entre Activities
- Eventos de clique
- Design de interfaces

## Observação

Este é um projeto escolar inspirado visualmente em aplicativos de resultados esportivos, especialmente o Sofascore.

O projeto não possui vínculo oficial com o Sofascore e foi desenvolvido somente para fins educacionais.
