Projeto para disciplina MATC99 - Segurança e Auditoria de Sistemas de Informação

Este é um projeto para disciplina MATC99 - Segurança e Auditoria de Sistemas de Informação da UFBA, ministrado pelo professor Maycon Leone. O projeto consite em implementar um sistema de login com autenticação em 2 etapas utilizando a linguagem JavaScript.

Grupo 05: Bernardo Sabino, Drissa da Cunha, Maria Neilde Goes e Yan Rodrigues
Link para o relatório no Google Docs: https://docs.google.com/document/d/1oan8lK9l3kHZBhiqvcBQT-057eNspw-XWy3dHhvS3pA/edit?usp=sharing 

PASSO A PASSO PARA O FUNCIONAMENTO DO SISTEMA

Na tela inicial o usuário deve inserir o e-mail e a senha já cadastrada pelo administrador e pressionar o botão de login.
Ao pressionar o botão o usuário será redirecionado a página de autenticação, onde deve inserir o código que recebeu por e-mail, que consiste nos 4 primeiros caracteres da senha convertido na tabela ASCII.
Caso o código esteja correto o usuário seguirá para tela de boas vindas, caso o código esteja incorreto o usuário receberá um alerta com a mensagem “Código Incorreto, Tente novamente mais tarde!” e retornará a página inicial.

USUÁRIOS/PERSONAS 
- Administradores do sistema:  Todas as permissões e gestão do Sistema;
- Funcionários Administrativos:  Tem permissões para criar o modificar documentos da base de dados geral
- Funcionários Geral:  Tem permissões para visualizar os documentos da base de dados geral
