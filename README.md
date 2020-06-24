# Genexus_ViaCEP
XPZ (SDT, Proc e WebPanel) para ViaCEP

Modulo desenvolvido em GeneXus 16 (build 142128) para pesquisa de CEP (ViaCEP). Composto por:
* 2 Procedures (CepParaEndereco, EnderecoParaCep)
* 4 SDTs (Erro, EnderecoCompleto, Retorno, ListaEndereco)
* 1 WebPanel de pesquisa (WPviacep)
*1 Dominio (ReturnType)

Como utilizar:

Importar em Knowledge Manager > Import;
Dar "Build All".
Dar "Run With This Only" para testar.


Possui duas abas:
* Na primeira, a pesquisa é feita unicamente com o CEP.
* Na segunda, a pesquisa se dá pela utilização de "Logradouro", "Localidade" (Cidade) e "UF" (Estado), e retorna uma coleção de resultados que preenche um GRID.
