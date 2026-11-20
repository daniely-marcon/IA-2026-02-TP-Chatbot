# Declaração de uso de Inteligência Artificial generativa

## 1. Ferramentas usadas

| Ferramenta (nome e versão/modelo)     | Como acessaram | Quem usou  |
|---------------------------------------|---|------------|
| OpenRouter, modelo openai/gpt-6-luna_ | _chave do grupo, via código_ | _todos_    |
| _Gemini (versão Plus)_                | _navegador_ | _Daniely_  |
| _Claude (Gratis)_                              | _navegador_ | _Giovanna e Rodnilson_ |
| _Claude (Anthropic)_                              | _navegador_ | _Mamadu_ |
| _GitHub Copilot_                              | _VSCode_ | _Mamadu_ |  
| _Copilot_                              | _embutido no navegador_ | _Daniely_ |  
| _Canva ia_                              | _navegador_ | _Daniely_ |  


## 2. Usos, um por linha

| #    | Etapa                     | O que a IA fez                                                                                      | Prompt (ou resumo + link para o registro)                                                                                                                       | O que o grupo fez com o resultado                              |
|------|---------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| 1    | _Dados de treino_         | _gerou as perguntas para adicionar ao formulário de coleta de dados._                               | _ver `https://share.gemini.google/Q2kbRdishjdc`_                                                                                                                | _Foram revisadas e ajustadas para o contexto que desejávamos_  |
| 2    | _Chatbot_                 | _Redige as respostas das intenções e do chitchat_                                                   | _prompts em `chatbot/llm.py` + persona do `grupo.yaml`_                                                                                                         | _Ajustamos a persona 3 vezes após testes (seção X do artigo)_  |
| 3    | _Código_                  | _Sugeriu a função que plota a curva de validação_                                                   | _"como plotar o resultado do GridSearchCV em função de C"_                                                                                                      | _Adaptamos nomes e eixos; entendemos e testamos_               |
| 4    | _Escrita_                 | _Revisou a gramática da Introdução_                                                                 | _"revise a gramática sem mudar o conteúdo: ..."_                                                                                                                | _Aceitamos parte das sugestões_                                |
| 5    | _Mapeamento dos documentos_ | _Elucidou porque o chtabot não estava acessando os documentos_                                    | _prompt :'como faço para o meu chat mapear corretamente as pastas ?  as fontes sao  descritas'link: https://claude.ai/share/4db7d3f2-04bb-4fc2-ac26-7fb25f484e61_ | _Corrigiu a rota no yaml e no arquivo Fontes_             |
| 6    | _Teste de rotas_            | _identificou que a função quebra_em_trechos() estava impedindo a leitura dos documentos corretamente_ | _link:' https://chatgpt.com/share/6aff22b5-1d70-83e8-b493-ccae270b4c5c_                                                                                   | _Removeu os marcadores do texto e deixou somente o titulo com #_ |
| 7    | _Escrita_                |   _Sugeriu estrutura de desenvolvimento da escrita da introdução e fundamentação_                    | _ver https://share.gemini.google/jdIrjA5GODQk_                                                                            |  _Foi ajustado durante o processo de escrita para cumprir com os requisitos._|                                                                                                                                                                |                                                                |
| 8    | _Artigo_                |   _Análise do artigo escrito e refatoração para melhoramento da fluidez_                    | _"Com base no trecho do meu aritof abaixo, corrija os erros e melhore na fluidez"_                                                                            |  _Verificou se não houve perda de sentido e se estava melhor que a versão anterior_| 
| 9  | _Entender Requisitos_                |   _Entender com maior nível de detalhes e de forma mais direta o que era necessário ser feito em cada seção._                    | _"Me auxilie com base no documento de descrição de trabalho em anexo a entender cada seção que devo realizar de forma mais direta possível."_                                                                            |  _Foram verificadas as informações e validadas entre colegas._|  
| 10   | _Aprofundamento_                |   _Código do aprofundamento A5 (contexto de conversa) , ajudou a implementar o mecanismo que guarda o histórico recente e mantém a intenção ativa entre as mensagens_                    | _foi iniciado com o prompt "Me ajude a entender como realizar o contexto de conversa que foi selecionado como aprofundamento nesse trabalho" e foram sendo tiradas as dúvidas posteriormente conforme foram realizadas. Infelizmente o chat foi perdido._                                                                            |  _Verificou-se se as alterações q estavam sendo citadas faziam sentido ou não para o que desejvamos realizar com discussoes em grupo._|  
| 11    | _Resumo de artigos de citação_                |   _Foi utilizado para resumir os artigos que foram mencionados pelo professor e que foram utilizados como citação._                    | _resuma os principais topicos desse arquivo_             |  _Verificou quais trechos faziam sentido para aquele ponto do artigo e se aprofundou na sessão especificamente._|  
| 12    | _Slides_                |   _Foi utilizado para gerar o prompt que foi utilizado para gerar o slide no canva ia, pois ele permite a personalização dos dados_                    | _https://share.gemini.google/WYWtmcjRWkre_             |  _Validou se estava dentro do desejado_|
| 13    | _Slides_                |   _Foi gerado os slides com base no prompt gerado pelo gemini_                    | _foi utilizado o prompt gerado na conversa acima, nao vou colocar pois é muito longo e o também não possui um link compartilhavel._             |  _Ajustamos os dados para melhor representar o nosso trabalho._|
| 14    | _Seção de uso de ia do artigo_                |   _Foi gerado um resumo baseado nesse documento para anexarmos ao artigo_                    | _https://share.gemini.google/XLZ8OTi0QhLS_             |  _Os dados coletados foram validados para o que melhor representou o contexto de utilização._|


## 3. O que NÃO foi feito com IA

- A definição do tipo das inteções por frase coletada;
- A definição de quais documentos iriam ser utilizados;
- A verificação de frases duplicadas no processo de classificação de dados;
- A verificação de dados gerados por ia;
- Testes manuais de desempenho do chatbot;
- Definição de quais classificações e representação de dados iriam ser utilizados;
- Conclusões tomadas com base nos dados

## 4. Reflexão (2 a 4 frases)
A IA nos ajudou principalmente na redução de retrabalho, entender o que precisavamos fazer e como fazer. Além disso, foi uma ferramenta poderosa na correção de bugs encontrados durante o desenvolvimento, atuando como uma ferramenta fundamental para a entrega completada do trabalho no tempo proposto.

