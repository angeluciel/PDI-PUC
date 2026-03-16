# Plano de Desenvolvimento Individual
Meu PDI para 2026-01 (primeiro semestre de 2026).
## Objetivo do semestre
Minha principal motivação nesta disciplina é construir uma base sólida na resolução de problemas complexos e na otimização de código. Desejo dominar estruturas não-lineares, especialmente travessia em grafos e técnicas de programação dinâmica. Esse aprofundamento é essencial para o meu desenvolvimento em engenharia de software e arquitetura de sistemas, conectando-se diretamente com o meu TCC em andamento, onde a estruturação de um backend em camadas e o uso do modelo C4 exigem decisões arquiteturais baseadas em algoritmos eficientes e performáticos.

## Diagnóstico inicial
### Análise de complexidade:
* O que sei: Compreendo a notação Big-O e consigo analisar algoritmos iterativos simples (O(n), O(n²)).
* Dificuldade: Tenho dificuldade em calcular a complexidade de tempo e espaço em algoritmos recursivos complexos ou que envolvem múltiplas chamadas de divisão e conquista.

### Divisão e conquista:
* O que sei: Entendo a lógica por trás de Merge Sort, e sei implementar a parte de Divisão.
* Dificuldade: Implementar como implementar completamente independentemente, e onde utilizar em produção esses algoritmos.

### Recursão:
* O que sei: Consigo implementar chamadas recursivas básicas e entendo a pilha de execução (call stack).
* Dificuldade: Definir casos base (condições de parada) em problemas muito abstratos e evitar o estouro de pilha (Stack Overflow) otimizando o código.

### Programação dinâmica:
* O que sei: Compreendo o conceito de memoization (guardar estados passados para evitar recálculo).
* Dificuldade: É o ponto de maior desafio. Montar a relação de recorrência e a tabela (bottom-up) do zero em problemas que nunca vi antes.

### Estruturas de dados:
* O que sei: Tenho bom domínio prático sobre estruturas lineares (Listas, Pilhas, Filas, Hash Tables).
* Dificuldade: Preciso aprofundar a implementação e o balanceamento de Árvores e Heaps.

### Grafos:
* O que sei: Não sei praticamente nada, só a teoria e como funcionam algoritmos como A* e Busca Gulosa.
* Dificuldade: Entender como aplicar no código, e onde seria utilizado na prática (em produção).

## Metas técnicas
### Meta 1: Domínio Prático em Travessia de Grafos
**Contexto:** Fundamental para resolver problemas de redes, rotas e dependências.

**Descrição:** Implementar e dominar os algoritmos de Busca em Largura (BFS) e Busca em Profundidade (DFS).

**Plano de ação:** Codificar as estruturas do zero, sem uso de bibliotecas prontas. Aplicar os algoritmos em pelo menos 3 problemas online (como LeetCode).

**Medição:** Código implementado, testado e commitado no repositório do PDI.

***Prazo: 31/03/2026.***

### Meta 2: Excelência em Estratégias Avançadas
**Contexto**: A transição do meio do semestre exige domínio sobre otimização (Programação Dinâmica e Divisão e Conquista).

**Descrição**: Criar uma base sólida para resolver problemas de otimização identificando subestruturas ótimas.

**Plano de ação**: Resolver uma bateria de 10 exercícios clássicos de Programação Dinâmica. Fazer testes de mesa e documentar as relações de recorrência.

**Medição:** Alcançar nota superior a 8.0 na avaliação N2.

***Prazo: 25/05/2026.***

### Meta 3: Integração Algoritmo-Arquitetura
**Contexto**: Fechar o ciclo da disciplina aplicando os conhecimentos teóricos em um contexto de engenharia de software e backend.

**Descrição:** Estruturar a documentação final dos projetos integrando a justificativa das escolhas algorítmicas com o design do sistema em camadas.

**Plano de ação**: Revisar o código construído ao longo do semestre, garantir que a complexidade está documentada e gerar os diagramas necessários refletindo a arquitetura. =

**Medição:** Entrega da documentação final revisada e aprovada, com os artefatos de software anexados.

***Prazo: 21/07/2026.***

## Rotina semanal de estudo
### Segunda-Feira (15:00 - 17:00): Teoria e Modelagem
Leitura dos conceitos da semana *(ex: travessia de grafos, programação dinâmica)*, criação de resumos e realização de testes de mesa no papel.

### Terça-feira (15:00 - 17:00): Implementação Base
Traduzir a teoria estudada na segunda-feira para o código. Focar em implementar as estruturas de dados e os algoritmos base do zero, sem bibliotecas.

### Quarta-Feira (15:00 - 17:00): Resolução de Problemas (x1)
Aplicar os algoritmos em problemas (LeetCode).

### Quinta-feira (14:00 - 18:00): Resolução de Problemas (x2) + Refatoração.
Continuar a resolução de exercícios mais complexos. Revisar o código escrito na terça e quarta, buscando otimizações na complexidade de tempo e espaço.

### Sexta-Feira (15:00 - 17:00): Revisão, Integração e Documentação
evisar os tópicos da semana, conectar o aprendizado com as decisões arquiteturais do TCC e atualizar o repositório do PDI com os códigos e anotações.


## Plano de uso de IA
### Como pretendo usar:
Como um tutor particular para desconstruir conceitos complexos\
***(ex: "Me explique a relação de recorrência deste problema passo a passo")***\
e como uma ferramenta de code review para apontar ineficiências na complexidade de tempo do meu código.

**Momentos de apoio:** Geração de casos de teste difíceis *(edge cases)* para validar minhas implementações de grafos ou programação dinâmica, e na ajuda para debugar loops infinitos em funções recursivas.

**Limites impostos:** É estritamente proibido pedir à IA para gerar a resposta de um exercício ou a implementação de um algoritmo base antes de eu tentar resolvê-lo sozinho por pelo menos 45 minutos. O código final commitado no projeto e no TCC deve ser de minha autoria e total compreensão.