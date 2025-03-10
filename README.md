# Análise de Sentimentos com IA

Este repositório contém uma implementação de análise de sentimentos utilizando inteligência artificial (IA) para classificar textos em categorias **positivos**, **negativos** ou **neutros**. O projeto faz uso das ferramentas **Azure IA Speech** e **Azure Language Studio** para realizar a análise de sentimentos.


## Visão Geral

A análise de sentimentos é uma aplicação fundamental do Processamento de Linguagem Natural (PLN), que visa identificar e classificar as emoções expressas em textos. Esse tipo de tecnologia é amplamente utilizado para analisar feedbacks de clientes, comentários em redes sociais, avaliações de produtos, e-mails, entre outros.

Este projeto utiliza IA para classificar automaticamente o sentimento de textos em uma das três categorias: **positivo**, **negativo** ou **neutro**. A IA alimentada com textos pode fornecer insights valiosos para empresas, ajudando na tomada de decisões estratégicas.

O projeto integra modelos pré-treinados e APIs de IA da Azure, como a **Azure IA Speech** e o **Azure Language Studio**, para processar e analisar textos.

## Tecnologias Usadas

- **Azure Language Studio**: Serviço baseado em nuvem que fornece recursos de Processamento de Linguagem Natural (PLN) para entender, analisar e classificar textos com base em sentimentos e outros parâmetros linguísticos.
- **Azure IA Speech**: Serviço baseado em nuvem que fornece recursos de Processamento de Linguagem Natural (PLN) para entender, analisar e classificar textos com base em sentimentos e outros parâmetros linguísticos.

## Como funciona

  O processo básico de análise de sentimentos neste projeto é o seguinte:

- Coleta de Dados: O sistema coleta textos de diferentes fontes, como avaliações, comentários ou posts.
    
- Análise de Sentimentos: O texto é enviado para os serviços da Azure, que utilizam modelos de NLP (Natural Language Processing) para classificar o sentimento do texto.
    
- Classificação: O texto é classificado em uma das três categorias: positivo, negativo ou neutro.
    
- Resultado: O resultado da classificação é retornado ao usuário ou sistema que fez a requisição.

## Exemplo de testes
  Aqui estão alguns exemplos de como a análise de sentimentos pode funcionar com diferentes tipos de textos:

### Teste Positivo
- Teste em Português
![positivo](https://github.com/user-attachments/assets/b3c2fb61-cdaa-4c44-9c69-c4cad8e29393)

- Teste em Inglês 
![positivo ingles](https://github.com/user-attachments/assets/0fb78038-0b01-45a8-871f-65241caaf56a)


### Teste Neutro
- Teste em Português
![neutro](https://github.com/user-attachments/assets/dda64b69-8af3-4bcc-9255-e53381d80c34)

- Teste em Inglês
![neutro ingles](https://github.com/user-attachments/assets/d90088a0-2276-4ad6-a065-d67ab8bc34df)
  
### Teste Negativo
- Teste em Português
![negativo](https://github.com/user-attachments/assets/bcc8ca09-1f65-4e66-96da-cb858ae13749)

- Teste em Inglês 
![negativo ingles](https://github.com/user-attachments/assets/2fea4e08-b306-4fcf-8645-1c85863cdf08)

## Conclusão

Este repositório fornece uma base para análise de sentimentos com IA, utilizando poderosas ferramentas da Azure. Ao integrar Azure IA Speech e Azure Language Studio, você pode melhorar a forma como seu sistema interage com o usuário, fazendo análises rápidas e precisas de sentimentos expressos em textos.
