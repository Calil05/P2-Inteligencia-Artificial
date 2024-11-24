# Hill Climbing para Formação de Equipes

Este projeto implementa o algoritmo de **Hill Climbing** com recomeços aleatórios para resolver um problema de formação de equipes balanceadas. A solução busca minimizar o desvio padrão das habilidades entre as equipes, garantindo que todas sejam o mais equilibradas possível.

---

## Descrição do Problema

Dado um conjunto de pessoas, cada uma com uma habilidade representada por um valor numérico, o objetivo é dividir essas pessoas em um número fixo de equipes de modo que as equipes tenham habilidades equilibradas. Para isso, o desvio padrão das somas das habilidades entre as equipes deve ser minimizado.

#### Estrutura de Pessoas e Habilidades

O código utiliza uma estrutura simples para representar pessoas e suas habilidades. Cada pessoa possui um identificador único (`id`) e um valor associado (`valor`), que representa a "habilidade" ou "pontuação" dessa pessoa.

#### Estrutura de Dados

As pessoas são armazenadas em uma lista, onde cada pessoa é representada por um dicionário. Aqui está um exemplo de como a lista de pessoas é estruturada:

```python
pessoas = [
    {"id": 1, "valor": 85},
    {"id": 2, "valor": 67},
    {"id": 3, "valor": 42},
    {"id": 4, "valor": 93},
    {"id": 5, "valor": 58},
    # ... até o número total de pessoas definido no código
]

---

##  Funcionalidades

1. **Geração de dados**: Criação de um conjunto de pessoas com valores de habilidade aleatórios.
2. **Hill Climbing**:
   - Busca local para otimizar o balanceamento das equipes.
   - Minimização do desvio padrão das habilidades das equipes.
3. **Recomeços Aleatórios**:
   - Várias reinicializações para evitar convergência a mínimos locais.
4. **Visualização**:
   - Gráficos que mostram o desempenho do algoritmo ao longo das iterações e reinicializações.

---

## Tecnologias Utilizadas

- **Python**
- **Bibliotecas:**
  - `numpy`: Para cálculos matemáticos, incluindo o desvio padrão.
  - `matplotlib`: Para visualização gráfica.
  - `random`: Para geração de números aleatórios.

## Desenvolvido por

- [Gabriel Calil] (https://github.com/Calil05)
- [David Marques] (https://github.com/DavidMarqss)