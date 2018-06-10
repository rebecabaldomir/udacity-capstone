
# Nanodegree Engenheiro de Machine Learning

## Capstone
Rebeca Andrade Baldomir  
Junho, 2018

### Proposta
Esse projeto irá resolver o problema de reserva de novos usuários do Airbnb (https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings), procurando prever em qual país esses novos usuários irão procurar reservas.

### Instalação
Este projeto requer o Python 2.7 e as seguintes bibliotecas do Python instaladas:
 - NumPy
 - Pandas
 - matplotlib
 - scikit-learn

Também é necessário ter o software instalado para executar um Jupyter Notebook.

### Execução
Em uma janela de terminal ou linha de comando, navegue até o diretório de projeto de nível superior capstone/ (que contém este README) e execute o seguinte comando:

    jupyter notebook capstone.ipynb

Isso abrirá o software do Notebook Jupyter e o arquivo de projeto em seu navegador .

### Conjunto de Dados
O conjunto de dados dos Airbnb inclui uma lista de usuários, além de dados demográficos, registros de sessões da Web e algumas estatísticas de resumo. É possível fazer o download desses dados acessando https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data.

Existem 12 resultados possíveis do país de destino: 'EUA', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL', 'DE', 'AU', 'NDF' e 'outro'. Note que 'outro' significa que houve uma reserva, mas é para um país não incluído na lista, enquanto 'NDF' significa que não houve uma reserva.

#### Features
-   id
-   date_account_created
-   timestamp_first_active
-   date_first_booking
-   gender
-   age
-   signup_method
-   signup_flow
-   language
-   affiliate_channel
-   affiliate_provider
-   first_affiliate_tracked
-   signup_app
-   first_device_type
-   first_browser

#### Target
-   country_destination
