# 💰 Financial Manager

Um sistema de gerenciamento financeiro simples, desenvolvido com **JSP** e **JDBC**, onde é possível:

- Criar uma conta e realizar login.
- Cadastrar e visualizar transações financeiras.
- Adicionar receitas e despesas.

## 🖥️ Tecnologias Utilizadas

- **Java**: Linguagem principal para a implementação do backend.
- **JSP (JavaServer Pages)**: Para renderização de páginas dinâmicas no frontend.
- **JDBC (Java Database Connectivity)**: Conexão com o banco de dados.
- **HTML/CSS**: Estrutura e estilização das páginas.
- **MySQL**: Banco de dados relacional para armazenamento das transações.

## 🌟 Funcionalidades

### 🔒 Autenticação de Usuário
- **Cadastro**: Crie uma nova conta para começar a usar o sistema.
- **Login**: Acesse sua conta de forma segura.

### 📊 Gestão de Transações
- **Listar Transações**: Visualize todas as transações financeiras cadastradas.
- **Adicionar Receita**: Cadastre uma nova receita com descrição, valor e data.
- **Adicionar Despesa**: Registre uma nova despesa com descrição, valor e data.

### 💾 Armazenamento e Persistência
- O sistema utiliza **JDBC** para interagir com o banco de dados **MySQL**, garantindo a persistência dos dados de transações e informações de login.

![Login](https://github.com/user-attachments/assets/0c0c2ff8-0880-44e5-b6ac-4f2e33a854b8)
![signup](https://github.com/user-attachments/assets/04fcd226-0b69-4ede-b220-ff3c04ba24b7)
![main2](https://github.com/user-attachments/assets/8e332c3c-d297-4af2-ad19-0abe10b37028)
![main1](https://github.com/user-attachments/assets/128b818b-0e13-4f7e-815c-0ed5b74dfe68)


## 🚀 Como Configurar o Projeto

### 1. Pré-requisitos
- **Java JDK 8+**
- **Apache Tomcat 9+**
- **MySQL** (ou outro banco de dados relacional de sua preferência)
- **IDE** (IntelliJ, Eclipse ou NetBeans)

### 2. Clonar o Repositório

```bash
git clone https://github.com/Aversii/FIAP-Fintech-v1
cd FIAP-Fintech-v1
```

### .3 Configurar a Conexão com o Banco de Dados
Abra o arquivo ConnectionFactory.java no pacote de conexão com o banco de dados.
Altere os valores para a URL de conexão, o nome de usuário e a senha do seu banco de dados:

```bash
private static final String URL = "sua conexão";
private static final String USERNAME = "seu_usuario";
private static final String PASSWORD = "sua_senha";
```

### .4 Rodar a aplicação pela IDE da sua preferencia

    


