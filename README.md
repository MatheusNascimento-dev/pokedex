# Pokedex
Uma Pokedex simples criada com HTML, CSS e JavaScript que permite visualizar informações sobre vários Pokémon.
Este é um projeto simples de Pokedex desenvolvido usando HTML, CSS e JavaScript. Ele exibe informações sobre diferentes Pokémon em cards coloridos. O gradiente de fundo do projeto muda de acordo com a cor predominante do Pokémon quando você passa o mouse sobre ele.

# Tecnologias Utilizadas
![HTML5](https://img.shields.io/badge/HTML5-000?style=for-the-badge&logo=html5) 
![CSS3](https://img.shields.io/badge/CSS3-000?style=for-the-badge&logo=css3&logoColor=264CE4) 
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript) 

# Características do Projeto
Lista de Pokémon: O projeto exibe uma lista de Pokémon com suas informações, incluindo nome, número, tipo e uma imagem.

Cores Personalizadas: Cada card de Pokémon possui uma cor de fundo personalizada com base em seu tipo. As cores são selecionadas de acordo com uma paleta predefinida de cores realistas.

Gradiente de Fundo Animado: Quando você passa o mouse sobre um card de Pokémon, o gradiente de fundo da página inteira se ajusta automaticamente à cor predominante do Pokémon, criando uma animação suave.

Nomes de Pokémon Ajustáveis: Os nomes dos Pokémon são ajustados para caber nos cards e exibem reticências (...) quando são muito longos.

# Paleta de Cores de Pokémon

A paleta de cores das Pokémon é definida no JavaScript com os códigos hexadecimais das cores para cada tipo de Pokémon. 
As cores foram escolhidas para representar os tipos de forma mais realista possível.

# Imagem do Projeto

![image](https://github.com/MatheusNascimento-dev/pokedex/assets/141882739/107e491a-a65a-4c3d-914d-d8ccd311e414)
![image](https://github.com/MatheusNascimento-dev/pokedex/assets/141882739/0475b4c7-9567-419a-9d1d-08608866a5e4)


# Como Usar
Clone ou faça o download deste repositório para o seu computador.

Abra o arquivo index.html no seu navegador para visualizar a Pokedex.

Passe o mouse sobre os cards de Pokémon para ver a animação de gradiente de fundo.

Exemplo de uso: 

```
// Obtém as informações do Pokémon e cria um card com a cor de fundo personalizada
const PokemonCard = (poke) => {
    // ...
    const type = pokemonTypes.find(type => pokeTypes.indexOf(type) > -1);
    const color = colors[type];
    card.style.backgroundColor = color;
    // ...
}
```

Adicionando novos Pokémon:<br>

Se você deseja adicionar mais Pokémon à Pokedex, siga estas etapas:

1. Abra o arquivo script.js.

2. Vá até a variável pokemonCount e ajuste o número total de Pokémon que deseja exibir.

```
const pokemonCount = 1281; // Altere para o número desejado de Pokémon

```
3. Salve o arquivo e atualize a página.

Personalizando cores de fundo:<br>

Você pode personalizar as cores de fundo dos Pokémon editando o objeto colors no arquivo script.js. Cada cor corresponde a um tipo de Pokémon. Por exemplo:
```
const colors = {
  fire: '#FFA07A',      // Cor para Pokémon tipo fogo
  water: '#87CEFA',     // Cor para Pokémon tipo água
  // Adicione mais cores conforme necessário
};

```
Personalizando estilos CSS:

Você pode personalizar ainda mais a aparência da Pokedex editando o arquivo style.css. Você pode ajustar estilos como fontes, espaçamento e sombreamento para atender às suas preferências.

# Autor 
Matheus Nascimento
