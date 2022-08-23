# ASPNETCore6-MVC-AzureEventHubs-AppInsightsConnString_SitePesquisaInteresses
Exemplo de geração de eventos envolvendo o voto em uma questão sobre interesses pessoais e utilizando o Azure Event Hubs em uma Web App criada com o .NET 6 + ASP.NET Core. Inclui o uso de um Dockerfile para geração de imagens Linux, além de monitoramento da aplicação com o Azure Application Insights (utilizando Connection String).

Worker Service para consumo dos eventos:

**https://github.com/renatogroffe/DotNet6-Worker-AzureEventHubs-SqlServer-Dapper-AppInsightsConnString-Processor_PesquisaInteresses**

Function App para consumo dos eventos:

**https://github.com/renatogroffe/DotNet6-AzureFunctions-Isolated-AzureEventHubs-SqlServer-Dapper_PesquisaInteresses**
