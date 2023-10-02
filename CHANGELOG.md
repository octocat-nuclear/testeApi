## 1.2.0
- [CIPSLC-38] - Ajuste CnpjBaseCreddr que estava validando pelo principal. ESLC0102

## 1.1.0
- [CIPSLC-11] - ASLC031 - Esta gerando RET aceito quando TpCt fora do dominio e Interoperabilidade igual a N
- [CIPSLC-21] - ASLC031 - Esta gerando RET aceito quando envia sem Conta Centralizadora e interoperabilidade = N
- [CIPSLC-22] - ASLC031 - Esta retornando RET aceito quando Tipo de Conta igual a CD e o parâmetro Tipo de Conta para Interoperabilidade no SLC igual a S
- [CIPSLC-23] - ASLC031 - Forma de transferência diferente de SILOC o sistema gera RET recusado
- [CIPSLC-26] - ASLC031 - Erro ao utilizar um valor grande
- [CIPSLC-29] - ASLC031 O sistema não está fazendo a "Validação do Campo “Data de Pagamento” para o Tipo Produto Antecipações de Cartões"
- [CIPSLC-31] - ASLC032 o campo TpCt não está sendo gerado na varredura quando é informado
- [CIPSLC-33] - ASLC032 o campo CtPgtoCentrlz não está sendo gerado na varredura quando é informado
- [CIPSLC-34] - ASLC033 Com participante cadastrado ao enviar o arquivo ASLC033 com a IF “00000000” está retornando Coderro “ESLC0118” - Participante não cadastrado no SLC
- [CIPSLC-37] - ASLC033 Não encontrado parâmetro "Confirmação do Lançamento Antecipação" no banco de dados
- [CIPSLC-39] - ASLC031 Os campos <TpCt> e <CtPgtoCentrlz> não são listados no RET recusado

## 1.0.3
- Atualização do XSD versão 1.5

## 1.0.2
- [CIPSLC-8] - ASLC031 - Ao processar arquivo ASLC031 esta salvando 'D' ao invés de 'A' na coluna TPPROD
- [CIPSLC-9] - ASLC031 O campo ISPBIFDEVDR<ISPBIFDevdr> da Tabela SLCLIQUID não está gravando
