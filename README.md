# portal-academico
 
### Dependências do sistema de login
 
npm i passport passport-local express-session bcryptjs
 
# Passport
(http://www.passportjs.org/docs/dowloads/html/)

Passport é autenticação middleware para Node. Ele foi projetado para servir a um propósito singular: 
autenticar pedidos. Ao escrever módulos, o encapsulamento é uma virtude, então o passport delega todas 
as outras funcionalidades para o aplicativo.
Essa separação de preocupações mantém o código limpo e mantenedor, e torna o Passport extremamente
facil de integrar em um aplicativo.

O passport reconhece que cada aplicativo tem requisitos exclusivos de autenticação. Os mecanismos de 
autenticação são conhecidos como "estratégias".
 
# passport-local
Estratégias do passport para autenticação com nome de usuário e senha.

# Express-session
Quando o cliente faz uma solicitação de login no servidor, o servidor criará uma sessão e armazenará 
no lado do servidor. Quando o servidor responde ao cliente, ele envia um cookie.

# Mysql 2

npm install mysql2