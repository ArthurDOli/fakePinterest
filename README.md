# FakePinterest

## Visão Geral
O FakePinterest é uma réplica do Pinterest realizada como parte do curso de Python da Hashtag Treinamentos. 
Nesse site é possível criar seu usuário, enviar imagens do seu computador e visualizar as imagens enviadas por você e por outros usuários, além de poder visualizar o perfil deles. 
Desenvolvido com **Python** com o framework **Flask** e junto do **SQLite**, que foi utilizado durante a fase de produção do projeto. Durante o processo de deploy ele foi substituido por um banco de dados **PostgreSQL**. 

## Funcionalidades Principais
- Autenticação de Usuários: Regristro de novos usuários com validação de dados e login seguro, utilizando criptografia de senhas com Flask-Bcrypt.
- Gerenciamento de Perfil: Cada usuário possui uma página de perfil individual onde pode visualizar suas próprias fotos e informações de conta.
- Feed de Fotos: Uma página principal que exibe todas as fotos postadas na comunidade em ordem cronológica reversa.
- Upload de Imagens: Usuários autenticados podem enviar suas próprias fotos, que são armazenadas localmente no servidor.
- Persistência de Dados: O projeto utiliza Flask-SQLAlchemy para gerenciar a conexão com o banco de dados e as tabelas de Usuario e Foto.

## Tecnologias Utilizadas
- Backend: Python, Flask
- Frontend: HTML, CSS, JavaScript
- Banco de Dados SQLite e PostgreSQL
