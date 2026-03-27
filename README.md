# 🗺️ Problema do Caixeiro Viajante (TSP): Análise de Algoritmos
## Força Bruta, Algoritmo Memético e Vizinho Mais Próximo

## 📌 Sobre o Projeto
Problemas de otimização são amplamente encontrados no mundo real e envolvem a identificação da melhor solução possível dentro de um conjunto de restrições. Muitos desses problemas, como o clássico Problema do Caixeiro Viajante (TSP - Traveling Salesman Problem), são classificados como NP-Completos devido à sua alta complexidade computacional. O objetivo do TSP é encontrar a rota mais curta que permita a um caixeiro visitar um conjunto de cidades exatamente uma vez e retornar à cidade de origem.

Este repositório contém um estudo comparativo e a implementação computacional de três abordagens distintas para resolver o TSP, avaliando a viabilidade, eficiência e escalabilidade de cada método através de análise de dados e gráficos ilustrativos.

## 👥 Autores
### Pesquisa e desenvolvimento realizados por:

- Hivison Silva

- [Igor Queiroz](https://github.com/IgorBLQ?tab=repositories&q=caix&type=&language=&sort=)

- Yonara Silva

## 🌟 Minha Participação **(Igor Queiroz)**
Construção da metaheurística base deste projeto (o Algoritmo Genético)

O foco desta etapa foi criar uma base matemática e algorítmica robusta em Python puro, sem a utilização de bibliotecas externas de otimização, comprovando o domínio em estruturas de dados e lógica de programação complexa.

**Principais frentes técnicas desta implementação:**
* **Ciclo Evolutivo Completo:** Estruturação do fluxo de gerações, englobando população inicial, cálculo de *fitness* (distância Euclidiana), e seleção de sobreviventes com taxa de Elitismo.
* **Operadores Genéticos Customizados:** Implementação da lógica de seleção por Torneio e Roleta, além do desenvolvimento de algoritmos de cruzamento (Crossover) adaptados para rotas, garantindo que nenhuma cidade fosse visitada duas vezes ou esquecida.
* **Ordenação de Baixo Nível:** Em vez de utilizar funções nativas de ordenação do Python, foi implementado o algoritmo **Heap Sort** do zero para ranquear a população a cada geração, evidenciando forte conhecimento em complexidade de algoritmos.
* **Fundação para o Memético:** Toda essa estrutura orientada a funções foi desenhada para ser escalável, servindo como o "motor principal" onde a Busca Local foi posteriormente acoplada para gerar o Algoritmo Memético.
