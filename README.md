Web Scraper para coletar informações de vagas no LinkedIn
Este script em Python utiliza a biblioteca BeautifulSoup e a biblioteca Requests para coletar informações sobre vagas de emprego na plataforma LinkedIn. As informações coletadas incluem o título da vaga, a empresa que está contratando e a localização da vaga.

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
