# eventCity
https://github.com/rodrock95/eventCity/blob/main/LICENSE

# Sobre o projeto
Nesta aplicação, estamos interessados em implementar diferentes níveis de acesso ao sistema Event-City (vide detalhes no  modelo 
conceitual), onde somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). Usuários CLIENT podem 
também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN. A implementação do sistema será feita 
via TDD, ou seja, pelo princípio do desenvolvimento baseado em testes. O sistema também contempla regras de validação conforme veremos
adiante

## Regras de validação

Validação de City:
- Nome não pode ser vazio

Validações de Event:
- Nome não pode ser vazio
- Data não pode ser passada
- Cidade não pode ser nula

# Modelagem conceitual

![eventCity - Copia](https://github.com/rodrock95/eventCity/assets/79290866/ea6f8157-f33a-4787-a766-90dc8b04a163)

# Competências

Modelo de dados de usuários e perfis

Validação com Bean Validation
- Annotations
- Customizando a resposta HTTP
- Validações personalizadas com acesso a banco
  
Autenticação e autorização
- Spring Security
- OAuth 2.0
- Token JWT
- Autorização de rotas por perfil
