No teste é simulado o acesso de 20 usuários em 10 segundos à um vídeo do youtube. Numeo de loops : 300.    
São utilizados os listeners 'View result tree', e 'View Results in table'. Que são relatórios que exibem os resultados em árvore e em tabela.    
O response body e response headers estão na aba 'response data' da 'View results tree'.    
São gerados também relatórios dos listeners Graph results e aggregate report
    
Tempo médio para resposta da requisição : variaram entre 4ms e 14419ms. A média foi de 2290ms  . Exibidos no 'Summary Report'    
Status code : 200   . na aba Sampler Result     
    
    

  ![Captura de tela de 2024-06-17 17-45-04](https://github.com/klausmerini/JMeterTests/assets/109608171/71eccb0f-e2fb-4f4c-8d16-7a698ae1dd58)    

   ![Captura de tela de 2024-06-18 17-58-01](https://github.com/klausmerini/JMeterTests/assets/109608171/e374ba86-a858-40aa-9f28-f2a60b52a72e)   
   
  ![Captura de tela de 2024-06-17 17-44-53](https://github.com/klausmerini/JMeterTests/assets/109608171/3b55671c-63b3-46cb-b7ce-3391c90a457d)    

    É gerado um relatório, pode ser uma planilha .csv    
    
![Captura de tela de 2024-06-18 18-33-22](https://github.com/klausmerini/JMeterTests/assets/109608171/c6d418d5-7a7a-4833-a118-aa9848635055)    
    
    Foram criado os Assertions :    
- Response assertion : para verificar o status code
- Duration Assertion : Configurado para um máximo de 10000ms ou 10 segundos.
  Todas requisições passaram nos testes\assertions
  Os resultados são exibidos no listener 'Assertion Result'
![Captura de tela de 2024-06-18 18-52-58](https://github.com/klausmerini/JMeterTests/assets/109608171/847678a1-fb85-4027-af66-69892d7f5dd2)
