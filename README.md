# [Formação_Alura_Data_Science](https://cursos.alura.com.br/formacao-data-science)

# [Curso_alura_Data_Science_Explorando_e_Analisando_dados](https://cursos.alura.com.br/course/data-science-explorando-analisando-dados)

Este repositório tem como objetivo fazer parte da minha trajetória em busca de conhecimento em Ciência de Dados, onde escolhi a [Alura](https://www.alura.com.br/) como uma das minhas fontes de aprendizado.

## 1. Conhecendo os dados
Nessa aula, aprendi a:
 - Importar a biblioteca pandas para a análise exploratória dos dados;
 - Ler um conjunto de dados no formato .csv, compreendendo a sua estrutura;
 - Fazer upload de arquivos para o Google Colab e reconhecer a importância de verificar se a máquina virtual está ativa ou se precisa ser reiniciada;
 - Renomear as colunas de um DataFrame e rodar códigos para contagem e descrição dos dados;
 - Identificar o que é uma Series e DataFrame;
 - Melhorar a visualização das informações e gerar os primeiros visuais para observação dos dados.

Clique [aqui](./Modulos/01_Conhecendo_os_Dados.ipynb) para acessar o Módulo 1.

## 2. Analisando os dados
Nessa aula, aprendi a:
 - Trabalhar com o método query() para filtrar linhas de um DataFrame com base em uma expressão;
 - Realizar o agrupamento dos dados a partir de uma coluna por meio do método groupby();
 - Extrair dados filtrando uma única coluna;
 - Modificar os “bins” (intervalos) de um histograma verificando o seu comportamento;
 - Identificar as diferentes bibliotecas de visualização, como Matplotlib e Seaborn;
 - Inserir textos no notebook para explicar os dados e criar um storytelling de nossas análises.

Clique [aqui](./Modulos/02_Analisando_os_dados.ipynb) para acessar o Módulo 2.

## 3. Entendendo os tipos de variáveis
Nessa aula, aprendi a:
 - Identificar o tipo de variável observando seu conteúdo;
 - Diferenciar uma variável categórica (qualitativa) nominal de uma ordinal;
 - Compreender o que é uma variável quantitativa contínua e discreta e visualizar a diferença entre intervalos.

Clique [aqui](./Modulos/03_Entendendo_os_Tipos_de_Variaveis.ipynb) para acessar o Módulo 3.

## 4. Visualizando os dados
Nessa aula, aprendi a:
 - Comparar categorias gerando um visual de gráfico de barras pelo barplot() e countplot();
 - Transformar uma Series em DataFrame pela função to_frame() e criar um DataFrame por meio de um dicionário pela classe pd.DataFrame();
 - Compreender que para comparação de dados o uso de áreas é bem complexo e contra-indicado, pois o conceito de área não é tão natural para visualização dos dados;
 - Compreender que em visualização de dados devemos colocar como foco a mensagem que queremos passar, adequando-a ao tipo de visual correspondente;
 - Ajustar os dados para construir um visual de acordo com o que queremos informar.

Clique [aqui](./Modulos/04_Visualizando_os_dados.ipynb) para acessar o Módulo 4.

## 5. Ajustando os visuais
Nessa aula, aprendi a:
 - Ajustar as escalas de um gráfico aproveitando o espaço e melhorando a visualização dos dados;
 - Ordenar os dados de um gráfico dando uma coesão a representação desses dados;
 - Alterar cores e tons de um gráfico destacando elementos e melhorando a sua estética visual;
 - Representar um gráfico de colunas com dados absolutos e relativos (porcentagem).

Clique [aqui](./Modulos/05_Ajustando_os_Visuais.ipynb) para acessar o Módulo 5.

## 6. Estatísticas dos dados
Nessa aula, aprendi a:
 - Diferenciar as medidas de tendência central e compreender o que cada uma representa;
 - Utilizar a biblioteca Numpy para cálculos de média, mediana e desvio padrão de listas;
 - Reconhecer a importância de trabalhar com as medidas de tendência central junto a dispersão de dados, a fim de comparar também como estes dados estão distribuídos;
 - Comparar diferentes registros e investigar as diferenças entre eles visualmente por meio das medidas de tendência central e gráficos de distribuição de dados.

Clique [aqui](./Modulos/06_Estatística_dos_Dados.ipynb) para acessar o Módulo 6.

## Filtrando os filmes com mais de 19 notas

No final do curso o professor verificou que muitos filmes tinham apenas uma ou poucas notas, assim prejudicando a média das notas dos filmes. Com isso apliquei um filtro para os filmes com mais de 19 notas, mostrando um gráfico mais limpo, onde as notas 3.0 e 4.0 já não eram tão concentradas como imaginavamos que eram.

Clique [aqui](./Modulos/Filtrando_filmes_com_notas_maiores_que_19.ipynb) para acessar o filtro.