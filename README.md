# Pokémon do Dia

Um pequeno projeto Java que sorteia um Pokémon aleatório usando a [PokéAPI](https://pokeapi.co) e exibe informações no console.  
O resultado também é salvo no arquivo `pokemon_do_dia.txt`.

---

## 📦 Tecnologias e Dependências

- Java 17+ (ou compatível)
- Maven
- Bibliotecas externas:
  - [OkHttp](https://square.github.io/okhttp/) → para requisições HTTP
  - [Gson](https://github.com/google/gson) → para parsear JSON

---

## 📂 Estrutura do Projeto

---

pokemon-do-dia/
├── src/
│ └── main/java/com/exemplo/PokemonDoDia.java
├── pom.xml
└── .gitignore

## ⚙️ Como Rodar

1. Clone ou extraia o projeto.
2. Abra um terminal na pasta raiz do projeto.
3. Compile e gere o `.jar`:

```bash
mvn clean package

