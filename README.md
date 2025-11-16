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

## 📈 Visualizações

![](https://github.com/Gabriellemga/Analise_Emprestimos_Biblioteca_UFRN/blob/main/graficos/grafico1.png)

Pode-se observar que de 2010 a 2013 o número de empréstimos cresceu, mas apartir de 2013 houve uma queda suave e em 2017 a diminuição da quantidade de empréstimos foi bastante acentuada.

O ano de 2020 não há dados suficientes para serem avaliados.

É necessário uma investigação para averiguar a razão do declínio do número de empréstimos apartir de 2017.

---

![](https://github.com/Gabriellemga/Analise_Emprestimos_Biblioteca_UFRN/blob/main/graficos/grafico2.png)

Pode-se visualizar que os meses com maiores números de exemplares emprestados foram em março e agosto.

Nota-se que há um crescente no número de empréstimos ates dos meses os quais ocorrem os picos de empréstimo e após uma queda na quantidade exemplares alugados.

Cabe aqui uma investigação para averiguar a razão deses dois meses terem o maior número de emprestimos e logo após diminuição no número de empréstimos.

Os meses com o menor número de empréstimos foram janeiro, julho e dezembro por se tratar de meses de férias.

Pode-se desenvolver estratégias e ações de marketing da biblioteca para que se aumente o número de exemplares emprestados.

Como por exemplo: uma ação para que sejam realizados empréstimos de livros para a leitura nas férias de julho.

---
![](https://github.com/Gabriellemga/Analise_Emprestimos_Biblioteca_UFRN/blob/main/graficos/grafico3.png)

Através do gráfico é possível identificar que os períodos das 10 h e 16 h são os de maior pico no atendimento de empréstimos.

Períodos do começo da manhã (entre 7h e 9) e da noite (entre 19h e 22) podem ser os melhores horários para que se realizem as demais atividades além do atendimento.

---
![](https://github.com/Gabriellemga/Analise_Emprestimos_Biblioteca_UFRN/blob/main/graficos/grafico4.png)

O gráfico de boxplot (diagrama de caixa) apresenta a Distribuição dos empréstimos do acervo circulante dos alunos de graduação ao longo dos anos, de 2010 a 2020.

Cada caixa resume a distribuição dos empréstimos em um determinado ano, mostrando a mediana, os quartis e os valores atípicos (outliers).

Há uma tendência de crescimento entre 2010 e 2013 , indicando que, na metade dos anos, o número de empréstimos aumentou.

De 2013 a 2018, há uma relativa estabilidade, com exceção de 2017, onde se observa uma queda leve antes de um novo aumento.

---

![](https://github.com/Gabriellemga/Analise_Emprestimos_Biblioteca_UFRN/blob/main/graficos/grafico5.png)

Ao contrário do gráfico de Graduação, o volume de empréstimos na Pós-Graduação é significativamente menor.

Há um crescimento entre os anos de 2010 e 2013, e uma estabilidade até o ano de 2017.

O ano de 2018 apresenta uma queda que os anos seguintes acompanham.

---
##  Frequência por tipo de vinculo de usuário

| Tipo vinculo usuário	|Quantidade	| Percentual % | 
|-----------------------|-------------|-------------|
|ALUNO DE GRADUAÇÃO	|1612324	 | 77.80 |
|ALUNO DE PÓS-GRADUAÇÃO	|302541|	14.60|
|	DOCENTE|	70981|	3.42|
|SERVIDOR TÉCNICO-ADMINISTRATIVO|	32184|	1.55|
|	ALUNO MÉDIO/TÉCNICO|	28029|	1.35|
|	DOCENTE EXTERNO	|23949|	1.16|
|	USUÁRIO EXTERNO|	2509|	0.12|
|	OUTROS	|5	|0.0|

O maior público da biblioteca são de fato os alunos de graduação com aproxidamente 77.80%, o segundo maior público é o de pós-graduação com aproximadamente 14.60%.

A diferença se deve pela maior quantidade de alunos de graduação presente na universidade.

---

## Frequência por coleção


|Colecao|Quantidade|	Percentual %|
|--------|----------|-------------|
|Acervo Circulante	|2053120	|99.06|
|	Multimeios	|7954	|0.38|
|	Monografias|	4021|	0.19|
|	Dissertações	|2406|	0.12|
Obras de Referência|	1954|	0.09|
|Publicações de Autores do RN|	866|	0.04|
|Publicações da UFRN|	764|	0.04|
|Teses|	714	|0.03|
|Folhetos|	271|	0.01|
|Necessidades Educacionais Específicas|	130|	0.01|
|Trabalho Acadêmico|	115|	0.01|
|Eventos|	101|	0.00|
|Coleção Mossoroense|	44	|0.00|
|Coleção Zila Mamede|	30|	0.00|
|Literatura de Cordel|	24|	0.00|
|Obras Raras|	8	|0.00|

A principal coleção é a própria circulante o que se cria um alerta, pois está com 99% de todos os exemplares empréstados, pois é importante verificar se há exemplares em quantidades suficientes para atende a demanda.

As coleções: Coleção Mossoroense, Coleção Zila Mamede, Literatura de Cordel, Obras Raras devem ter uma atenção especial em entender a razão que estão com números tão pequenos de frequência.

Entretanto é importante verificar se esses documentos não estão disponíveis na coleção online e por este motivo não é emprestada fisicamente.

---

## Frequência por biblioteca

| Biblioteca                                                                 | Quantidade  | Percentual (%) |
|---------------------------------------------------------------------------|-------------|----------------|
| Biblioteca Central Zila Mamede                                            | 1.426.122   | 68,81          |
| Biblioteca Setorial do Centro Ciências da Saúde                          | 118.614     | 5,72           |
| Biblioteca Setorial da Faculdade de Ciências da Educação                 | 77.609      | 3,74           |
| Biblioteca Setorial Prof. Alberto Moreira Campos                         | 66.447      | 3,21           |
| Biblioteca Setorial Profª. Maria Lúcia da Costa                          | 61.478      | 2,97           |
| Biblioteca Setorial Bertha Cruz Enders - Escola de Música                | 46.040      | 2,22           |
| Biblioteca Setorial do Centro de Ciências Humanas                        | 40.744      | 1,97           |
| Biblioteca Setorial Dr. Paulo Bezerra - EMCM/RN                          | 32.097      | 1,55           |
| Biblioteca Setorial Profª. Maria José Mamede Galvão                      | 29.089      | 1,40           |
| Biblioteca Setorial Prof. Rodolfo Helinski - Escola Agrícola             | 27.219      | 1,31           |
| Biblioteca Setorial Prof. Francisco Gurgel De Farias                     | 26.923      | 1,30           |
| Biblioteca Setorial do Núcleo de Educação da Infância                    | 23.656      | 1,14           |
| Biblioteca Setorial Prof. Ronaldo Xavier de Araújo                       | 22.749      | 1,10           |
| Biblioteca Setorial Pe. Jaime Diniz - Escola de Enfermagem               | 21.476      | 1,04           |
| Biblioteca Setorial do Departamento de Artes                             | 17.099      | 0,83           |
| Biblioteca Setorial Prof. Leopoldo Nelson - Centro de Tecnologia         | 12.900      | 0,62           |
| Biblioteca Setorial do Centro Ciências Sociais Aplicadas                 | 10.533      | 0,51           |
| Biblioteca Setorial Prof. Dr. Marcelo Bezerra de Melo                    | 5.057       | 0,24           |
| Biblioteca Setorial Prof. Horácio Nicolas Solis                          | 4.098       | 0,20           |
| Biblioteca Setorial Moacyr de Góes - CE                                  | 1.036       | 0,05           |
| Biblioteca Setorial Árvore do Conhecimento - Instituto do Cérebro        | 919         | 0,04           |
| Biblioteca Setorial do Núcleo de Ensino Superior do Seridó               | 617         | 0,03           |
A Biblioteca Central lidera o ranking com o maior porcentual de empréstimos.Isso já era esperado por a maior e a principal, com maior número de usuários cadastrados.

Vale lembrar que essa metrica considera valores absolutos. 

Para uma avaliação mais enriquecedora podemos considerar o numero de usuarios cadastros por biblioteca, o número de empéstimos esperados e ações de markenting de cada biblioteca.

---
## Frequência por CDU

| CDU                                     | Quantidade  | Percentual (%) |
|-----------------------------------------|-------------|----------------|
| Ciências aplicadas.                     | 1.425.473   | 68,78          |
| Ciências sociais.                       | 369.536     | 17,83          |
| Matemática e ciências naturais.         | 68.744      | 3,32           |
| Generalidades. Ciência e conhecimento   | 62.521      | 3,02           |
| Religião.                               | 62.295      | 3,01           |
| Filosofia e psicologia.                 | 60.563      | 2,92           |
| Geografia. Biografia. História.         | 7.989       | 0,39           |
| Belas artes.                            | 7.911       | 0,38           |
| Linguagem. Língua. Linguística.         | 7.490       | 0,36           |

De maneira geral podemos observar que há uma grande diferença entre os temas.

Será importante entender a razão de materiais do tema de Geografia/Biografia/História, Belas artes e Linguagem estão com números tão baixos.

## ✨Conclusões Principais

* **Pico Histórico:** O maior volume de empréstimos para a **Graduação** ocorreu por volta de **2013**, enquanto para a **Pós-Graduação** foi mais estável entre 2013 e 2017.
* **Queda de 2020:** Ambos os grupos de estudantes registraram uma **queda drástica e sem precedentes** no volume de empréstimos em 2020, indicando um forte impacto da interrupção das atividades presenciais (provavelmente devido à pandemia de COVID-19) na utilização do acervo físico.

---

## 🧑‍💻 Autor

* [Márcia Gabrielle Apolinario / https://github.com/Gabriellemga]
