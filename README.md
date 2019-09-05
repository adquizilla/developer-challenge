# Grupo de Serviços SLC

## SLC - Serviço de Liquidação Centralizada

O SLC - Serviço de Liquidação Centralizada - é o grupo de serviços operado pela CIP para processamento da compensação e da liquidação das ordens eletrônicas de crédito ou de débito entre instituições financeiras e/ou instituições de pagamento participantes de um mesmo arranjo de pagamento integrante do SPB, conforme dispõem os arts. 25 e 26 do Regulamento Anexo à Circular nº 3.682, de 24 de novembro de 2013, com as alterações da Circular nº 3.765, de 25 de setembro de 2015.

As mensagens deste grupo de serviços pertencem ao domínio de sistema SPB01. As mensagens informativas referentes a arquivos deste grupo de serviço (por exemplo, GEN0015) trafegarão no domínio de sistema MES01.

## Liquidação Financeira Multilateral
SLC0001 - SLC informa movimentos bilaterais de liquidação multilateral no dia 

**Fonte:** 
[Catalogo_de_servicos](https://www.bcb.gov.br/content/estabilidadefinanceira/cedsfn/Catalogos/Catalogo_de_Servicos_do_SFN_Volume_II_Versao_413.pdf) - Página 298



# O desafio

***Consiste em criar uma rotina que irá carregar o arquivo SLC0001-modelo.xml que se encontra nesse repositório para 
um banco de dados e disponibilizar em um micro serviço.***
