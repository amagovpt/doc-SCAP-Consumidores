
# Documentação técnica relativa ao Sistema de Certificação de Atributos Profissionais - vertente Consumidor de Atributos


## Introdução
O Sistema de Certificação de Atributos Profissionais possibilita a associação da identidade eletrónica de um cidadão (expressa nos certificados digitais no chip do Cartão do Cidadão e Chave Móvel Digital) aos papéis que o mesmo desempenha na sociedade.

Este sistema permite que, através da autenticação ou assinatura eletrónica de documentos, sejam certificados um conjunto de atributos (qualidades) que o cidadão tem e lhe estão atribuídos por Entidades Fornecedoras de Atributos. 

Mais informação sobre Sistema de Certificação de Atributos Profissionais (SCAP) em https://www.autenticacao.gov.pt/web/guest/a-autenticacao-de-profissionais.

Este repositório contêm a documentação técnica relativamente ao Sistema de Certificação de Atributos Profissionais na vertente de Consumidor de Atributos.

## Estrutura da documentação

* A pasta **Guidelines** contém um documento que elenca as guidelines de integração necessárias para certificação enquanto consumidor de atributos
* Na pasta **Especificação dos Serviços** encontram-se as encontram-se as especificações dos serviços em formato OpenAPI. 
	* **SCAP-SignatureService.json** - especificação da API do serviço de assinatura.
	* **SCAP-AttributeService.json** - especificação da API do serviço de atributos.
* A pasta **Exemplos** contém exemplos de pedidos e respostas.
* Na pasta **Serviços Deprecados** encontra-se a documentação relativa à primeira versão do serviço em SOAP.
* [Documento de Integração - Consumidores de Atributos (download pdf)](https://amagovpt.github.io/doc-SCAP-Consumidores/AMA&#32;-&#32;SCAP&#32;Documento&#32;de&#32;Integração&#32;-&#32;Consumidores&#32;de&#32;Atributos.pdf).


## Certificação
Para a certificação deverão ser fornecidas as seguintes evidências:
* Relatório assinado digitalmente (com LTV) com evidências de cumprimento das guidelines de integração.
* Vídeo demonstrativo da solução.
* Providenciar 5 exemplares de documentos assinados, em ambiente pré-produtivo.
* Código fonte da aplicação para certificação por parte da AMA (relativo à integração). Como alternativa, pode também ser pedida a certificação da aplicação a uma entidade externa independente e credenciada para auditorias eIDAS.

Após a receção das evidências, a Agência para a Modernização Administrativa (AMA IP)  precederá à avaliação.
No processo de avaliação está previsto: 
 - Possibilidade de requisição de acesso ao sistema, para validação das evidências e esclarecimento de dúvidas.
 - Possibilidade de solicitar:
	 -  Novo relatório corrigido.
	 - Evidências adicionais ou substituição das fornecidas.

**NOTA:** A configuração em ambiente produtivo é precedida da formalização de protocolo e de certificação.

## Outros recursos
A documentação técnica relativa ao Sistema de Certificação de Atributos Profissionais na vertente Fornecedor de atributos está disponível em https://github.com/amagovpt/doc-SCAP-Fornecedores

## Contactos
Para questões, sugestões ou comentários envie um e-mail para eid@ama.pt.