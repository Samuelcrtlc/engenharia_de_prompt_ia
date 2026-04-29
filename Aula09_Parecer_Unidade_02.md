# Parecer Individual — Unidade II: Programação Assistida por Inteligência Artificial

**Aluno:** Samuel Natalicio da Silva  
**Disciplina:** Engenharia de Prompt e Aplicações em IA  

---

## Práticas Realizadas

Ao longo da Unidade II, desenvolvi quatro atividades práticas distribuídas entre as aulas, que evoluíram progressivamente em complexidade.

Na **Aula 06/04**, escolhi o mini-projeto de nível básico: uma **Calculadora Simples**, onde implementei as quatro operações matemáticas com tratamento de erros via `try/except`, incluindo validação de divisão por zero e entradas inválidas — exatamente como sugerido pelo slide da aula.

Na **Aula 14/04 (Sprint de Automação)**, realizei as três missões propostas. A **Missão 1** consistiu em um script de automação de arquivos usando as bibliotecas `os` e `shutil`, que organiza arquivos de uma pasta desordenada em subpastas por extensão — criando pastas como `PDF`, `JPG`, `MP3` e movendo os arquivos corretamente, atendendo todos os requisitos de sucesso. A **Missão 2** foi a consulta à API pública ViaCEP, onde desenvolvi um sistema robusto com múltiplos blocos `except` tratando erros de timeout, conexão, HTTP e JSON inválido. A **Missão 3** foi um sistema autônomo de monitoramento que simula leituras de métricas a cada 2 segundos e dispara alertas no console quando o valor ultrapassa um limiar crítico, utilizando um loop infinito interrompível por `KeyboardInterrupt`.

---

## Relação com o Conteúdo da Unidade

O conteúdo das aulas foi diretamente aplicado nas missões. O conceito de **workflow Humano-IA** — onde o humano formula o problema e a IA gera e refatora o código — foi vivenciado na prática: utilizei a IA como copiloto para sugerir estruturas, completar funções auxiliares e melhorar a legibilidade do código. O ciclo de colaboração apresentado nos slides (Instrução → Processamento → Revisão → Ajuste) foi seguido em todas as atividades.

Sobre as ferramentas, o **GitHub Copilot** foi utilizado no VS Code para sugestões inline e refatoração, o **Google Colab (Jupyter)** serviu como ambiente de desenvolvimento e execução dos notebooks, o **Claude** também foi usado como uma segunda etapa de verficação para os códigos.

Em relação à **ética e aos limites da automação**, o conteúdo deixou claro que a IA entrega velocidade e sintaxe, mas falha em contexto de negócio, segurança e decisões arquiteturais. Isso ficou evidente na Missão 2, onde foi necessária intervenção humana para definir quais erros tratar e como formatar a saída — a IA não sabia o que era mais útil para o usuário final.

---

## Transparência sobre Ferramentas e Fontes

As atividades foram desenvolvidas com suporte das seguintes ferramentas de IA:

- **GitHub Copilot** — Algumas vezes usado para diferentes pontos de vista + explicação
- **Claude (Anthropic)** — explicação do código caso o Progamador não tenha entendido alguma linha, servindo como uma segunda etapa de verificação contra erros, e também usado para ajudar a resumir este conteúdo nesta atividade
- **Google (Coolab)** — Principal peça de todo o conteúdo para comentar o codigo e sugestões de código

Os slides das aulas de 06/04 e 14/04 da Profª. Kadidja Valéria foram as principais referências de conteúdo.

---

> *"A IA não substitui o desenvolvedor, mas amplia sua capacidade criativa e produtiva. O papel humano é decidir, validar e dar direção."*
