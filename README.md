![Pescador](https://github.com/Antonino-Marques-Jares/pescadores/blob/main/barco_de_pesca.jpg)

# Pescadores
O mapa visa mapear e analisar a distribuição geográfica dos pescadores profissionais no Brasil.

# Passo 1
Baixe arquivos :
- https://github.com/kelvins/municipios-brasileiros/blob/main/csv/estados.csv
- https://github.com/kelvins/municipios-brasileiros/blob/main/csv/municipios.csv
- Todos csv's em https://www.areadetrampo.com.br/mapa-de-pescadores-no-brasil/ salvando na pasta csv dentro do projeto

# Passo 2
Montaremos df_municipios que terá as colunas UF,	MUNICIPIO,	LATITUDE e	LONGITUDE

# Passo 3
Montaremos df_brasil que tem as informações dos pescadores com as colunas UF, MUNICIPIO,	TIPO e	QTD (QTD é o somatório e quantidade de pescadores agrupado por UF, MUNICIPIO e TIPO)

# Passo 4
Pivotando nossos dados
Ficamos com o df_pivot com as colunas 
TIPO,  UF, MUNICIPIO,  LATITUDE,  LONGITUDE,  DESEMBARCADO (QTD DESEMBARCADO) e  EMBARCADO (QTD EMBARCADO)

# Passo 5
Criamos u arquivo JSON que será lido pelo html mapa_pescadores.html

# Visualize o MAPA em:

[Visualize o Mapa aqui](https://www.areadetrampo.com.br/mapa-de-pescadores-no-brasil/)

# Visualize o JSON em:

Apresenta o resumo das informações constantes em **Dados Abertos - GOV.BR**, somado a isso, posições geográficas dos Municípios.

[JSON pescadores](https://www.areadetrampo.com.br/wp-content/uploads/2025/07/dados_pescadores_no_brasil_08_07_2025.json)

# Motivação

1º Concurso de Reúso de Dados Abertos da CGU

### Informações de latitude e longitude dos Municípios Brasileiros

* https://github.com/kelvins/municipios-brasileiros/blob/main/csv/estados.csv
* https://github.com/kelvins/municipios-brasileiros/blob/main/csv/municipios.csv
  
### Informações de quantidade de pescadores nos Municípios
[![Gov Br](govbr.webp)](https://dados.gov.br/dados/conjuntos-dados/base-de-dados-dos-registros-de-pescadores-e-pescadoras-profissionais)
  
# Autor:

**Antonino Marques Jares**

# Atualizado em:

**08/07/2025**
