Criar uma API Java SpringBoot para cadastro de pessoa física.
Endpoint NEW:
Nome completo;
CPF; 
CEP;
Endpoint LIST:
Trazer todos os dados gravados em banco no formato JSON;
Endpoint DELETE:
Excluir um cadastro pelo ID;
Ao Gravar (NEW)
Verificar se o CPF é valido;
Fazer uma integração com o https://viacep.com.br/ para obter os dados de endereço e gravar 
em banco;
Gravar os campos retornados na integração:
Logradouro, Complemento, Bairro, Localidade, UF.
Gerar um ID do tipo GUID para cada cadastro.
Ao Excluir (DELETE)
Receber o ID como parâmetro e efetuar a exclusão física do dado.
Ao Listar (LIST)
Trazer todos os dados do cadastro (incluindo ID).
