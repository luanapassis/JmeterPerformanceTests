#Executar Jmenter por linha de comando

-n: Essa opção diz para o JMeter ser executado apenas por linha de comando (sem a interface gráfica)

-t: Seu script plano de teste (arquivo JMX)

-l: Arquivo log de resultados do seu teste (arquivo JTL)

-j: Arquivo log de execução do JMeter.

-r: opção para execução remota, usando os servidores especificados na propriedade "remote_hosts"

-R: executa em um servidor específico

-g: Arquivo CSV file, para geração do dashboard

-o: Pasta de saída onde será gerado o dashboard. Pasta não pode existir ou deve estar vazia

-H: proxy server hostname

-P: proxy server porta


Passo 1
ir para o diretório onde estas os testes
C:\Users\xxx\Desktop\xxx\Teste Desempenho\teste relatorios

Passo 2
executar a linha de comando (primeiro argumento é onde esta o bat do jmeter)
C:\automacao\jmeter\apache-jmeter-5.3\bin\jmeter.bat -n -t 1-LoginMantis.jmx -l resultado.jtl -e -o relatorioLogin