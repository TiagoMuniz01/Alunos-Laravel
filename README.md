# Projeto Laravel - Alunos

Este projeto foi criado com o framework **Laravel 12**, utilizando o banco de dados **MySQL**. Ele tem como objetivo o gerenciamento de uma tabela chamada `alunos`.

---

## ✅ Pré-requisitos

- PHP (versão 8.1 ou superior)
- Composer instalado
- MySQL instalado e rodando
- Editor de código (recomendado: VS Code)
- Git (para versionamento)

---

## Tutorial da atividade

 - Acesse o xampp/php/php.ini e pesquise por ;extension=zip, depois retire o “;”.
 - Crie uma pasta no xampp/htodcs e crie uma pasta

### 1 Instalação do Laravel

 Faça a instalação do Laravel pelo terminal do VScode: 
 ```bash
composer global require laravel/installer 
 ```
 Se der certo aparecerá dessa maneira
 <CriaçãoProjeto1>

### 2 Criação do projeto
 
 Crie um projeto laravel dentro da pasta criada em xampp/htodcs:
 ```bash
 laravel new Alunos-Laravel
 ```
 Se der certo deverá aparecer dessa meneira: 
 <instalacaoLaravel>

 Você deverá escolher as mesmas opções da imagem quando o laravel requisitar.
 Após isso fará mais essas perguntas: 
 <CriaçãoProjeto2>

 ### 3 Realizando as migrations

 Acesse a pasta do projeto
  ```bash
  cd Alunos-Laravel
  ```

  Esse comando de migrações, publica suas modificações no banco escolhido (nesse caso MySql). Ele localiza o banco declarado no .env e suas configurações.
  Gere uma tebela alunos nas migrations
  <Criacao migration aluno>

  Acesse o arquivo de migration nas migrations no projeto
  <EstruturaDePastasaMigration>

  Insira as seguintes colunas na tabela:
  <migrationAluno>

  Por fim, para atualizar sua tabela insira o comando:
  <ExecucaoMigrateAluno>

  Confira as alterações no PHPMyAdmin do xammp:
  



