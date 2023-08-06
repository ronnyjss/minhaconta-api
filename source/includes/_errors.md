# Código de erros Http

A API do Minhaconta usa os seguintes códigos de erro HTTP:

Código | Descrição
------ | ---------
200 | Tudo funcionou conforme o esperado.
201 | A requisição foi bem sucedida e um novo recurso foi criado.
304 | Não havia dados novos para retornar.
400 | Solicitação Inválida - Muitas vezes, falta um parâmetro obrigatório.
401 | Não autorizado - As credenciais de autenticação estavam faltando ou foram incorretas.
403 | Proibido - A requisição foi ok, mas foi recusado ou o acesso não foi permitido. Uma mensagem de erro que acompanha a mensagem explica o porquê.
404 | Não encontrado - A URI solicitada é inválida ou o recurso solicitado, como por exemplo, um beneficiario não existe ou foi excluído.
405 | Método não permitido - Você tentou acessar uma rota com um método inválido.
406 | Não aceitável - Você solicitou um formato que não é json.
410 | A solicitação de baixa da cobrança foi executada por nossos servidores.
429 | Muitas solicitações - Você está muito ansioso! Tente ir mais devagar!
500 | Erro interno do servidor - Tivemos um problema com nosso servidor. Tente mais tarde.
503 | Serviço não disponível - Estamos temporariamente offline para manutenção. Por favor, tente novamente mais tarde.
