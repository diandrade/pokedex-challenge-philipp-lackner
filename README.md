# Jetpack Compose Pokedex

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg" alt="Pokémon 1" width="45%" />
  <img src="https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg" alt="Pokémon 2" width="45%" />
</div>

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg" alt="Pokémon 3" width="45%" />
  <img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg" alt="Pokémon 4" width="45%" />
</div>

## Visão Geral do Desafio

O objetivo do desafio era criar duas listas:

### 1. Lista de Pokémon

Esta lista é preenchida com Pokémon obtidos da [Pokémon API](inserir-link). Os usuários podem clicar em cada Pokémon para visualizar informações detalhadas.

### 2. Lista de Pokémon Salvos

Esta lista exibe os Pokémon que o usuário salvou ou marcou como favoritos.

## Informações do Pokémon

Para cada Pokémon, as seguintes informações obrigatórias são exibidas:
- **ID**
- **Nome**
- **Tipo** (grama, fogo, água)
- **Foto**

Além disso, seguindo o tutorial do Philipp, também incluímos os seguintes detalhes extras:
- **Peso**
- **Altura**
- **Estatísticas**

## Especificações Técnicas

As seguintes **tecnologias** e **padrões de design** foram usados no desafio:
- **MVVM** (Obrigatório)
- **Room** (Obrigatório)
- **Ktor** ou **Retrofit** (Obrigatório)
- **Corrotina** (Obrigatório)
- **Jetpack Compose** (Opcional)
- **Injeção de Dependência** (Opcional)

## Desafios Enfrentados

Embora tenha pesquisado bastante, várias mudanças nas tecnologias de desenvolvimento de aplicativos ocorreram desde os vídeos do Philipp. Como resultado, muitas vezes precisei pesquisar essas mudanças, como as do framework Coil. Além disso, houve mudanças na versão do projeto base, bem como nas versões atuais do Gradle, Kotlin e Hilt.

Um desafio notável foi criar a segunda lista. Mesmo após várias tentativas, enfrentei dificuldades ao usar **Room** com **Jetpack Compose**. Decidi focar em terminar a primeira lista e adicionar o recurso de favoritos como parte das próximas etapas.
