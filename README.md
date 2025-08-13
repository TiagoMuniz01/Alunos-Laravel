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
 
 <img width="334" height="429" alt="instacaoLaravel" src="https://github.com/user-attachments/assets/d02621fa-a61d-41fc-8e19-2f158e6ff962" />


### 2 Criação do projeto
 
 Crie um projeto laravel dentro da pasta criada em xampp/htodcs:
 ```bash
 laravel new Alunos-Laravel
 ```
 Se der certo deverá aparecer dessa meneira: 
 
 <img width="604" height="303" alt="CriaçãoProjeto1" src="https://github.com/user-attachments/assets/d38339c3-8322-4606-bc7d-1f6507211b0a" />

 Você deverá escolher as mesmas opções da imagem quando o laravel requisitar.
 Após isso fará mais essas perguntas: 

 <img width="588" height="301" alt="CriaçãoProjeto2" src="https://github.com/user-attachments/assets/bb8ab85d-7ff7-431b-9602-f6704f4d5e90" />


 ### 3 Realizando as migrations

 Acesse a pasta do projeto
  ```bash
  cd Alunos-Laravel
  ```

  Esse comando de migrações, publica suas modificações no banco escolhido (nesse caso MySql). Ele localiza o banco declarado no .env e suas configurações.
  Gere uma tebela alunos nas migrations

  <img width="689" height="66" alt="CriaçãoMigrationAluno" src="https://github.com/user-attachments/assets/58ac176e-e88b-403b-af33-d939e5055da8" />


  Acesse o arquivo de migration nas migrations no projeto

  <img width="205" height="223" alt="estruturaDePastaMigration" src="https://github.com/user-attachments/assets/7d3fc497-170b-4b19-b391-bba9b33d711d" />
  

  Insira as seguintes colunas na tabela:
  
  <img width="479" height="310" alt="MigrationAluno" src="https://github.com/user-attachments/assets/719c8ae1-768b-4fe8-9272-9acfc5d1ee8e" />


  Por fim, para atualizar sua tabela insira o comando:
  
  <img width="695" height="109" alt="ExecucaoMigrateAluno" src="https://github.com/user-attachments/assets/6c58ed18-5204-4e98-b785-c289cb1a6386" />


  Confira as alterações no PHPMyAdmin do xammp:
  
  <img width="668" height="236" alt="alunoPHPMyAdmin" src="https://github.com/user-attachments/assets/82dcfb48-daa8-4142-9285-5ceaf189b472" />

  



