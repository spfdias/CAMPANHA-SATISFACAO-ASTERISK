# CAMPANHA-SATISFACAO-ASTERISK
CAMPANHA PARA PESQUISA DE SATISFACAO ASTERISK


1 - ACESSAR O DIRETORIO /ETC/ASTERISK E ADICIONAR AO ARQUIVO ( VIM EXTENSIONS_CUSTOM.CONF )

#include pesquisaprovedor.conf

2 - AINDA NO DIRETORIO /ETC/ASTERISK, CRIAR O ARQUIVO  ( VIM PESQUISAPROVEDOR.CONF )

vim pesquisaprovedor.conf

3 - ADICIONAR AO ARQUIVO OS  DADOS QUE ESTAO EM ( PESQUISAPROVEDOR.CONF ), ATENTE-SE AOS DADOS DE CONEXAO AO SEU BANCO DE DADOS.

4 - ESTE SCRIPT É EXECUTADO, APÓS A SECRETARIA FINALIZAR O ATENDIMENTO. O CLIENTE É TRANSFERIDO PARA A PESQUISA, ONDE RESPONDE AS QUESTOES COM OPCOES DE 1 A 5. CASO O LADO DO CLIENTE DESLIGUE A CHAMADA, ELA É ARMAZENADA AO BANCO COMO ABANDONADA.

5 - VOCE PODE CRIAR UMA INTERFACE GRAFICA PARA QUE ESSES DADOS SEJAM VISIVEIS.

6 - OBSERVACAO : CRIE AS VARIAVEIS NO BANCO DE DADOS ( RAMAL, CALLERID, NOTA, OS, IDSISTEMA ( CASO USE UM SISTEMA DE TERCEIROS ) )
