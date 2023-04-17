Web Scraping - LinkedIn Jobs
Esse projeto tem como objetivo realizar uma análise de vagas no LinkedIn na área de tecnologia da Informação para os cargos de Desenvolvimento e Análise de dados, visando quais são as tecnologias e frameworks que estão sendo mais solicitados aos candidatos, utilizando a técnica de Web Scraping para adquirir os dados para análise.

Descrição do algoritmo
O algoritmo realiza o Web Scraping da página de busca do LinkedIn e extrai as informações sobre o título da vaga, nome da empresa e localização da vaga. O resultado é salvo em um arquivo .csv

Pré-requisitos
Antes de utilizar o script, é necessário instalar as bibliotecas BeautifulSoup e Requests. Isso pode ser feito utilizando o seguinte comando:

pip install beautifulsoup4 requests pandas

Como utilizar
O script é bem simples de utilizar. Basta rodar o arquivo scraper.py para coletar as informações das vagas de emprego no LinkedIn. O arquivo scraper.py contém duas funções principais:

scrapper(): realiza a coleta das informações das vagas no LinkedIn e retorna o objeto BeautifulSoup com as informações coletadas.

extract(): recebe o objeto BeautifulSoup com as informações coletadas e extrai as informações relevantes, adicionando as informações a uma lista de dicionários.

O script atual está configurado para extrair informações sobre vagas na área de Desenvolvimento de Software no Brasil. Para alterar a área ou localização das vagas, basta alterar a URL dentro da função scrapper().

O número de páginas a serem extraídas pode ser configurado através da variável total_pages.

Ao final da execução do script, um arquivo CSV com as informações coletadas será gerado com o nome 'teste433.csv'.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou um pull request para ajudar a melhorar o script.

Dashboard
Os dados obtidos por meio do Web Scraping foram tratados e utilizados para construir um dashboard no aplicativo Power BI. O dashboard contém informações sobre a quantidade de vagas disponíveis, as empresas que mais contratam e as habilidades mais exigidas.
