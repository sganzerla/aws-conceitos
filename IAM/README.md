# iam - Identity and Access Management

Controle de acesso seguro aos recursos da AWS

- IAM User: Usuário ou aplicação que interage com a AWS
- Group: Coleção de usuários com permissões identicas
- Role: Privilégios temporários que uma entidade assume

## Usuário root

Usuário com permissão total aos serviços.

Recomenda-se:

- exclusão das chaves de acesso desse usuário
- criação de um usuário IAM
- conceder acesso administrador
- usar credenciais IAM para operar AWS
- habilitar autenticação de multiplos fatores

Boas práticas:

- deletar chaves de acesso usuário root AWS
- ativar autenticação MFA
- somente conceder permissões a usuários IAM quando eles precisarem
- utilizar roles para as aplicações
- revisar credenciais regularmente
- remover usuários e credenciais desnecessárias
- monitorar atividades na sua conta AWS
