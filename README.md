# Pokedex em Jetpack Compose

<div style="display: flex; justify-content: space-between;">
<img src="[https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg](https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg)" alt="Pokémon 1" width="45%" />
<img src="[https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg](https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg)" alt="Pokémon 2" width="45%" />
</div>
<div style="display: flex; justify-content: space-between;">
<img src="[https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg](https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg)" alt="Pokémon 3" width="45%" />
<img src="[https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg](https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg)" alt="Pokémon 4" width="45%" />
</div>

## Visão Geral do Desafio

O objetivo do desafio foi criar duas listas principais:

### 1. Lista de Pokémon

Esta lista é populada por Pokémon buscados diretamente da [Pokémon API](https://www.google.com/search?q=insert-link). O usuário pode clicar em cada Pokémon para visualizar informações detalhadas.

### 2. Lista de Pokémon Salvos

Esta lista exibe os Pokémon que o usuário salvou ou marcou como favoritos.

## Informações dos Pokémon

Para cada Pokémon, as seguintes informações obrigatórias são exibidas:

* **ID**
* **Nome**
* **Tipo** (grama, fogo, água, etc.)
* **Foto**

Adicionalmente, seguindo o tutorial do Philipp, incluí os seguintes detalhes extras:

* **Peso**
* **Altura**
* **Estatísticas (Stats)**

## Especificações Técnicas

As seguintes **tecnologias** e **padrões de projeto** foram utilizados no desafio:

* **MVVM** (Obrigatório)
* **Room** (Obrigatório)
* **Ktor** ou **Retrofit** (Obrigatório)
* **Coroutines** (Obrigatório)
* **Jetpack Compose** (Opcional)
* **Injeção de Dependência** (Opcional)

## Desafios Enfrentados

Apesar de muita pesquisa, diversas mudanças nas tecnologias de desenvolvimento de apps ocorreram desde os vídeos do Philipp. Como resultado, precisei pesquisar atualizações constantes, como as mudanças no framework **Coil**. Além disso, houve alterações na versão base do projeto, bem como nas versões atuais do **Gradle**, **Kotlin** e **Hilt**.

Um desafio notável foi a criação da segunda lista. Mesmo após várias tentativas, enfrentei dificuldades na integração do **Room** com o **Jetpack Compose**. Decidi focar na finalização da primeira lista e pretendo adicionar a funcionalidade de favoritos como um próximo passo.

---
