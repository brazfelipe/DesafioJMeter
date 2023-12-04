# Felipe Braz - Desafio JMeter
## Compra de passagem aérea - Passagem comprada com sucesso

Endpoint ultilizado: www.blazedemo.com

### Pré execução
    Em cada arquivo JMX mudar o valor da variável "path" para o caminho da pasta onde o projeto esta salvo.

### Instruções para a execução dos scripts

    Abrir um terminal na pasta bin do jmeter
    Executar os comandos a seguir 

````
Ensaio
    ./jmeter -n -t /path/PassagemAerea.jmx -l /path/ensaio.csv -e -o /path/ensaioReport

Carga
    ./jmeter -n -t /path/PassagemAerea-Carga.jmx -l /path/carga.csv -e -o /path/cargaReport

Pico
    ./jmeter -n -t /path/PassagemAerea-Pico.jmx -l /path/pico.csv -e -o /path/picoReport
````


### Relatório de execução dos testes
    Após as execuções os resultados dos testes podem ser consultados via arquivo html nas pastas ensaioReport, cargaReport e picoReport.

    
### Demais considerações 
    Existem 3 arquivos .jmx no projeto um para ensaios e outros dois para cada tipo de teste (Carga e Pico).
    Um relatório executivo sobre a execução pode ser consultado em: 
    https://docs.google.com/document/d/1tVk4M-zMFwwbBffLX6_WVsb_x3FlMDBc4lrfITzl0SE/edit?usp=sharing


### Para dúvidas ou contato 

Linkdin: https://www.linkedin.com/in/felipe-braz/