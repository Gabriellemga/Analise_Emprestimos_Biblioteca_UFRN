# 📚 Análise da Distribuição de Empréstimos em Biblioteca Universitária (2010-2020)

Este projeto realiza a Análise Exploratória de Dados (AED) da distribuição de empréstimos do acervo circulante, segmentada por alunos de graduação e pós-graduação, ao longo de uma década (2010 a 2020). Esta análise faz parte do desafio #7daysofcode da Alura.

## 🌟 Visão Geral

O objetivo principal deste notebook é analisar e visualizar a série histórica de utilização do acervo para identificar tendências, variabilidade (dispersão) e o impacto de eventos externos — notadamente a queda drástica observada no ano de 2020 — no comportamento de empréstimos.

A análise é baseada em séries temporais, graficos de coluna, diagramas de caixa (Boxplots), que sumarizam a mediana, quartis e amplitude dos dados anuais.

### Como Executar

1.  **Abra o Notebook:** Clique no botão "Open In Colab" acima.
2.  **Conecte e Execute:** No ambiente Colab, clique em *Conectar* (para iniciar a VM) e, em seguida, execute todas as células (*Ambiente de Execução > Executar todas*).

## ⚙️ Tecnologias e Bibliotecas Utilizadas

O notebook foi desenvolvido em Python e utiliza as seguintes bibliotecas principais para manipulação de dados e visualização:

* **Pandas:** Essencial para o carregamento, manipulação e estruturação dos dados de empréstimo.
* **Seaborn:** Utilizada para gerar os gráficos de *boxplot* com alta qualidade estética e informativa.
* **Matplotlib:** Biblioteca base para configurações e ajustes finos nas visualizações.

## 📊 Estrutura da Análise

O notebook segue a seguinte estrutura lógica:

1.  **Carregamento de Dados:** Importação do(s) conjunto(s) de dados de empréstimos.
2.  **Visualização (Graduação):** Geração do boxplot para a distribuição anual dos empréstimos de alunos de **Graduação**.
3.  **Visualização (Pós-Graduação):** Geração do boxplot para a distribuição anual dos empréstimos de alunos de **Pós-Graduação**.
4.  **Conclusões:** Análise comparativa das tendências observadas em ambos os públicos.

## Visualizações

![]()


## ✨Conclusões Principais

* **Pico Histórico:** O maior volume de empréstimos para a **Graduação** ocorreu por volta de **2013**, enquanto para a **Pós-Graduação** foi mais estável entre 2013 e 2017.
* **Queda de 2020:** Ambos os grupos de estudantes registraram uma **queda drástica e sem precedentes** no volume de empréstimos em 2020, indicando um forte impacto da interrupção das atividades presenciais (provavelmente devido à pandemia de COVID-19) na utilização do acervo físico.

---

## 🧑‍💻 Autor

* [Márcia Gabrielle Apolinario / Gabriellemga]
