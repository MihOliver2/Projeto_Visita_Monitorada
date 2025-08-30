# Respostas com análise de sentimento - Pesquisa Visita Monitorada

## Contextualização
Os visitantes do Santuário Nacional de Aparecida têm a oportunidade de conhecer de perto as fachadas da Basílica por meio de visitas monitoradas, nas quais é apresentada a história e o significado das obras de arte que compõem o local. Ao final da experiência, os participantes são convidados a responder uma pesquisa de satisfação sobre o serviço. Todo o processo de coleta das respostas e geração das visualizações é automatizado.

## Objetivo
Aplicar análise de sentimentos na Pesquisa Visita Monitorada para identificar as percepções dos visitantes que participam da Visita, destacando os pontos mais valorizados da experiência. Além disso, monitorar possíveis problemas ou oportunidades de melhoria e alertar a gestão em caso de feedbacks negativos, garantindo tempo hábil para ações corretivas.

## Visão Geral do fluxo
- __Entrada:__ Respostas na plataforma SurveyMonkey com integração em planilhas Excel Online.
- __Processamento:__ Azure AI Language (Text Analytics).
- __Saída:__ Sentimento gravado em planilha ou enviado para o Power BI.

## Etapas Detalhadas
1 - Recebimento de respostas automaticamente (com alimentação diária) em planilha Excel Online.
2 - Enviar para o Azure para que seja feita a análise de sentimentos utilizando de Power Automate e alimentação do resultado na planilha Excel Online.
3 - Integração do arquivo com Power BI para visualização dos resultados.
4 - Disparo de e-mails automáticos para gestão, melhorando tempo hábil de ação em casos de avaliações negativas.

## Resultado final
Cada resposta classificada como positiva, negativa ou neutra, com base na análise feita pelo Azure. Isso dá ao usuário uma visão emocional poderosa sobre o que os respondentes estão sentindo.
