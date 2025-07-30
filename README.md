# Uab
Master MEMC in Universidade Aberta

Este repositório acompanha a dissertação de Mestrado em Estatística, Matemática e Computação apresentada na Universidade Aberta por Ricardo Abreu, com o objetivo de estudar a dinâmica entre tokens de blockchain de Camada 1 (L1) e Camada 2 (L2), utilizando técnicas avançadas de séries temporais.

🎯 **Objetivo do Projeto**
A investigação foca-se em três objetivos principais:

Analisar as relações dinâmicas entre tokens L1 e L2, utilizando modelos VAR e VECM;

Estudar padrões de volatilidade e efeitos de spillover, através de modelos multivariados GARCH (DCC-GARCH);

Identificar relações de cointegração e causalidade, recorrendo a testes de Johansen, Granger e Toda-Yamamoto.

🧠 **Enquadramento**
A economia de tokens tem vindo a ganhar importância no contexto da blockchain, com tokens L2 como Optimism e Polygon a complementarem protocolos de base como Ethereum. A complexidade destas relações justifica o uso de abordagens estatísticas e de aprendizagem profunda, como ARIMA-LSTM, para prever comportamentos e estudar dependências.

📁 **Estrutura do Repositório**
 
🔍 **Modelos Estatísticos Utilizados**
Modelos ARIMA e GARCH: Para previsão de séries e análise da volatilidade.

VAR/VECM: Para explorar interdependências e relações de longo prazo.

Testes de Cointegração (Johansen) e Causalidade de Granger.

Modelos Híbridos ARIMA-LSTM: Para captar relações não-lineares e de longo prazo em dados financeiros voláteis.

📈 **Resultados Principais**
Não foi encontrada cointegração entre ETH e MATIC, nem entre ETH e OP.

Detetou-se causalidade bidirecional entre ETH e OP, sugerindo forte interdependência.

O modelo ARIMA-LSTM superou os modelos tradicionais em precisão de previsão.

A análise DCC-GARCH evidenciou persistência elevada de volatilidade em ETH e padrões distintos nos tokens L2.

🛠️ **Tecnologias**
Linguagem: R

Pacotes principais: vars, urca, rugarch, rmgarch, forecast, keras, tensorflow

Fontes de dados: CoinGecko API (ou equivalentes)

📚 **Referência Académica**
Este trabalho foi desenvolvido como parte da dissertação de Mestrado em Estatística, Matemática e Computação (MEMC), sob orientação do(a) Prof.(a) Doutor(a) [Nome do(a) Orientador(a)], Universidade Aberta, 2025.

Para mais detalhes teóricos e empíricos, consulte a dissertação completa incluída neste repositório.

📬 Contacto
📧 
🔗 
🌐 [
