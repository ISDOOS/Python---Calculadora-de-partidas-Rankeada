# 🎮 Calculadora de Partidas Ranqueadas 🏆

## Objetivo

Crie uma função que determine o nível de um jogador com base em sua quantidade de vitórias e derrotas nas partidas ranqueadas de um jogo.

## Tecnologias Utilizadas

- 🐍 Python
- ➕ Variáveis
- ➗ Operadores
- 🔁 Laços de Repetição
- 🤔 Estruturas de Decisões
- ⚙️ Funções

## Funcionamento

Este notebook oferece duas opções para calcular o nível do jogador:

1. **Inserção Manual de Dados:**

   - Utilize a função `calcularNivel(vitorias, derrotas)` e insira manualmente a quantidade de vitórias e derrotas do jogador. A função calculará o saldo de vitórias e determinará o nível com base nas regras.

   Exemplo:

   ```python
   vit = 75  # Substitua com a quantidade de vitórias desejada
   der = 20  # Substitua com a quantidade de derrotas desejada

   resultado = calcularNivel(vit, der)
   print(resultado)

2. ## Importação de uma Base de Dados:

Importe uma base de dados contendo as estatísticas de vitórias e derrotas dos jogadores. A função calcularNivel pode ser aplicada a todos os registros da base de dados para calcular os níveis de todos os jogadores em massa.

    Exemplo: 

    # Importe sua base de dados aqui
```` python
for jogador in base_de_dados:
    saldo, nivel = calcularNivel(jogador["vitorias"], jogador["derrotas"])
    print(f"O Herói tem um saldo de {saldo} e está no nível de {nivel}")

