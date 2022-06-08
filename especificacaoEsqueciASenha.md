# Especificação de caso de uso 
## ESQUECI A SENHA 

##### Objetivo:
Usuário conseguir solicitar uma nova senha ao sistema e recebê-la em seu e-mail 

##### Requisitos: 
Clicar em 'Esqueci a senha' e inserir e-mail ou cpf da conta cadastrada 
##### Atores:
Usuários (aluno, professor orientador, gerente de estágio) 
##### Pré-condições: 
Usuário deve estar cadastrado no sistema 
##### Pós-condições: solicitação é enviada ao sistema, usuário permanece na mesma tela 

##### Fluxo principal: 
1. O sistema apresenta a tela inicial ao usuário; 
2.  O usuário clica em esqueci a senha; 
3. O usuário insere seu e-mail ou CPF; 
4. O usuário clica em enviar; 
5. A solicitação é feita ao sistema; 
6. O usuário permanece na mesma tela. 
##### Fluxo alternativo: Usuário usou dados errados.

5. 1. O sistema retorna erro de usuário não encontrado.
   2. O usuário permanece na mesma tela e é solicitado que verifique os dados.
#####  Fluxo alternativo:  Usuário não esqueceu a senha
3. 1. O usuário clica em retornar; 
   2. O usuário retorna para a tela inicial.


>Ênio Ferreira da Silva
