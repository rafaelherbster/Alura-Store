# Alura-Store
Alura Store - Análise de Vendas
Bem-vindo ao Alura Store - Análise de Vendas, um projeto de ciência de dados desenvolvido como parte do Challenge Data Science da Alura. Este projeto analisa dados de vendas de quatro lojas virtuais, calculando o faturamento total e o ticket médio por loja, com visualização em gráficos.

# 📖 Sobre o Projeto
O projeto utiliza dados de vendas das lojas do sr. João, contendo informações como produto, preço, frete, data da compra, vendedor, localização e avaliações. O objetivo é realizar uma análise exploratória para calcular o faturamento total de cada loja e o ticket médio, além de gerar visualizações para insights sobre o desempenho das vendas.

A proposta do projeto é criar insights com os dados disponíveis e qualificar qual das loja o sr. João deve liquidar para levantar capital para um novo projeto.

# 🚀 Funcionalidades
- Importação de Dados: Carrega dados de vendas de quatro lojas a partir de arquivos CSV hospedados no GitHub.
- Cálculo de Faturamento: Calcula o faturamento total (preço + frete) de cada loja e exibe uma tabela com valores absolutos, percentuais e acumulados.
- Vendas por Categoria: Exibe valores do total de vendas de cada loja por categoria.
- Cálculo da Média de Avaliações: Calcula o valor da média de avaliações por loja.
- Produtos Mais Vendidos: Exibe os produtos mais vendidos e sua categoria por loja.
- Produtos Menos Vendidos: Exibe os produtos menos vendidos e sua categoria por loja.
- Cálculo da Média do Frete: Calcula o valor gasto com frete de cada loja.
- Ticket Médio: Calcula o ticket médio por loja e gera um gráfico de barras para visualização.
- Cálculo do Total de Vendas: Calcula o total de vendas de cada loja.
- Tratamento de Erros: Funções com tratamento de exceções para garantir robustez na análise.
- Valores Monetários: Exibe valores em reais (R$) sem problemas de formatação no Google Colab.

# 🛠️ Tecnologias Utilizadas
- Python 3: Linguagem principal para análise de dados.
- Pandas: Manipulação e análise de dados em DataFrames.
- Matplotlib: Geração de gráficos para visualização do ticket médio.
- Google Colab: Ambiente de execução do notebook.

# 📋 Pré-requisitos
Para executar o projeto localmente, você precisará de:

- Python 3.8 ou superior.
- Bibliotecas Python:
```bash
pip install pandas matplotlib
```
Opcional: Google Colab para executar o notebook diretamente no navegador.
Acesso à internet para carregar os dados dos arquivos CSV hospedados no GitHub.
⚙️ Instalação
Clone o repositório:
```bash
git clone https://github.com/rafaelherbster/Alura-Store.git
```

# 📊 Dados
Os dados são provenientes de quatro arquivos CSV (loja_1.csv, loja_2.csv, loja_3.csv, loja_4.csv) hospedados no repositório da Alura. Cada arquivo contém as seguintes colunas:

- Produto: Nome do produto vendido.
- Categoria do Produto: Categoria (ex.: eletrônicos, móveis).
- Preço: Valor do produto em reais (R$).
- Frete: Custo do frete em reais (R$).
- Data da Compra: Data da transação.
- Vendedor: Nome do vendedor.
- Local da compra: Estado (ex.: SP, RJ).
- Avaliação da compra: Nota de 1 a 5.
- Tipo de pagamento: Método de pagamento (ex.: cartão de crédito, boleto).
- Quantidade de parcelas: Número de parcelas.
- lat e lon: Coordenadas geográficas do local da compra.

# 📈 Resultados
Análise dos Resultados
1. Faturamento Total
- Loja 1: R\$ 1.616.346,99 (26,14% do total)
- Loja 2: R\$ 1.567.773,29 (25,35% do total)
- Loja 3: R\$ 1.542.047,52 (24,93% do total)
- Loja 4: R\$ 1.458.253,56 (23,58% do total)
  
Observação: A Loja 4 apresenta o menor faturamento total, contribuindo com apenas 23,58% do faturamento combinado das quatro lojas.

2. Vendas por Categoria
- Moveis: Loja 3 (499 vendas) e Loja 4 (480 vendas)
- Eletrônicos: Loja 1 (448 vendas) e Loja 4 (451 vendas)
- Brinquedos: Loja 4 (338 vendas)
- Eletrodomésticos: Loja 4 (254 vendas, a menor entre todas)
  
Observação: A Loja 4 tem desempenho variável por categoria, com destaque negativo em eletrodomésticos.

3. Média de Avaliação dos Clientes
- Loja 1: 3,98
- Loja 2: 4,04
- Loja 3: 4,05
- Loja 4: 4,00
  
Observação: A Loja 1 tem a menor média de avaliação, embora todas estejam próximas.

4. Produtos Mais Vendidos
- Loja 1: Micro-ondas (60 vendas)
- Loja 2: Livro "Iniciando em programação" (65 vendas)
- Loja 3: Kit banquetas (57 vendas)
- Loja 4: Cama box (62 vendas)
  
5. Produtos Menos Vendidos
- Loja 1: Headset (33 vendas)
- Loja 2: Jogo de tabuleiro (32 vendas)
- Loja 3: Blocos de montar (35 vendas)
- Loja 4: Guitarra (33 vendas)
  
Observação: A Loja 2 tem o produto menos vendido (Jogo de tabuleiro com 32 vendas).

6. Frete Médio
- Loja 1: R\$ 34,69
- Loja 2: R\$ 33,62
- Loja 3: R\$ 33,07
- Loja 4: R\$ 31,28
  
Observação: A Loja 4 tem o menor frete médio, o que pode indicar eficiência logística ou localização vantajosa.

7. Ticket Médio
- Loja 1: R\$ 685,18
- Loja 2: R\$ 664,59
- Loja 3: R\$ 653,69
- Loja 4: R\$ 618,43
  
Observação: A Loja 4 tem o menor ticket médio, indicando que os clientes gastam menos por compra.

8. Total de Vendas
- Loja 1: 2359 vendas
- Loja 2: 2359 vendas
- Loja 3: 2359 vendas
- Loja 4: 2358 vendas
  
Observação: A Loja 4 tem uma venda a menos que as outras, diferença insignificante.

# 📷 Demonstração
O gráfico do faturamento é gerado usando Matplotlib e exibido no notebook. Para visualizar, execute a função `grafico_faturamento(lista)` no ambiente do Colab ou Jupyter.

<img src="https://github.com/rafaelherbster/Alura-Store/blob/main/src/grafico_pizza_faturamento.png" alt="gráfico de pizza, informando as porcentagens do faturamento de cada loja e seu respectivo valor em relação ao faturamento total.">

O gráfico da média de avaliação por loja é gerado usando Matplotlib e exibido no notebook. Para visualizar, execute a função `grafico_med_avalicao(lista)` no ambiente do Colab ou Jupyter.
O gráfico foi aprimorado para que, independente da quantidade de lojas, ele sempre exiba os gráficos corretamente. 

<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_avaliacao_loja1.png" alt="gráfico dot plot, informando as médias de avaliação da loja 1.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_avaliacao_loja2.png" alt="gráfico dot plot, informando as médias de avaliação da loja 2.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_avaliacao_loja3.png" alt="gráfico dot plot, informando as médias de avaliação da loja 3.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_avaliacao_loja4.png" alt="gráfico dot plot, informando as médias de avaliação da loja 4.">

O gráfico da média do frete é gerado usando Matplotlib e exibido no notebook. Para visualizar, execute a função `grafico_med_frete(lista)` no ambiente do Colab ou Jupyter.

<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_frete_loja1.png" alt="gráfico dot plot, informando as médias do valor do frete da loja 1.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_frete_loja2.png" alt="gráfico dot plot, informando as médias do valor do frete da loja 2.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_frete_loja3.png" alt="gráfico dot plot, informando as médias do valor do frete da loja 3.">
<img src="https://github.com/Bainazz/Alura-Store-Herbster/blob/main/src/media_frete_loja4.png" alt="gráfico dot plot, informando as médias do valor do frete da loja 4.">

O gráfico de ticket médio é gerado usando Matplotlib e exibido no notebook. Para visualizar, execute a função `grafico_ticketMedio()` no ambiente do Colab ou Jupyter.

<img src="https://github.com/rafaelherbster/Alura-Store/blob/main/src/grafico_barras_ticket_medio.png" alt="gráfico de barras, informando o valor do ticket médio de cada loja.">

# ✏️ Conclusão e Recomendação
Com base nos dados analisados, a Loja 4 se destaca negativamente em vários indicadores:

- Menor faturamento total (23,58% do total).
- Menor ticket médio (R$ 618,43), indicando menor valor por venda.
- Desempenho inferior em categorias como eletrodomésticos (254 vendas, a menor entre todas).
- Apesar de ter o menor frete médio, o que pode ser um ponto positivo, os demais indicadores sugerem que a Loja 4 é a menos lucrativa.

Portanto, recomenda-se que o Sr. João considere liquidar a Loja 4 para levantar capital para o novo investimento, mantendo as outras três lojas que apresentam desempenho superior.

Considerações Finais

Antes de tomar a decisão final, sugere-se uma análise adicional sobre custos fixos e variáveis de cada loja, bem como a localização e potencial de crescimento. No entanto, com os dados disponíveis, a Loja 4 é a candidata mais adequada para liquidação.

# 🤝 Como Contribuir
Faça um fork do repositório.
Crie uma branch para sua feature ou correção:
```bash
git checkout -b minha-nova-feature
```
Faça suas alterações e commit:
```bash
git commit -m "Adiciona minha nova feature"
```
Envie para o repositório remoto:
```bash
git push origin minha-nova-feature
```
Abra um Pull Request no GitHub.
Por favor, siga as diretrizes de contribuição e mantenha a formatação do código consistente.

# 📜 Licença
Este projeto está licenciado sob a MIT License.

# 🙌 Agradecimentos
À Alura pelo Challenge Data Science e pelos dados fornecidos.

À comunidade Python pelas bibliotecas Pandas e Matplotlib.

# 💡 Nota sobre Formatação de Valores Monetários no Google Colab
Para evitar que o caractere $ seja interpretado como LaTeX no Google Colab, use `\$` , como R\$. Exemplo em uma célula de texto:

```markdown
O faturamento é R\$1,616,346.99.
```
Alternativamente, envolva o texto em crases (`) para exibir como código:

```markdown
`R$1,616,346.99`
```
⭐ Se achou este projeto útil, deixe uma estrela no repositório!

Todos os direitos reservados. Rafael Herbster de Sena Maciel. 2025.

Email: rafaelherbster8@gmail.com 

Linkedin: www.linkedin.com/in/rafael-herbster
