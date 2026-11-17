
# AutoManager 🚗🔧

Sistema desktop de gerenciamento de oficina mecânica, desenvolvido em **Java** com **PostgreSQL**.

Este é o meu **primeiro projeto no GitHub**. Ele nasceu como um projeto de estudo, para praticar Java com banco de dados, e foi crescendo conforme eu aprendia: telas, conexão com o banco, pesquisa, alteração, exclusão e o próprio uso do Git para versionar tudo.

## 📋 Sobre o projeto

O AutoManager organiza o dia a dia de uma oficina, ligando clientes, veículos, mecânicos, serviços e ordens de serviço em um só sistema.

## ✨ Funcionalidades

- **Cadastros** de cliente, veículo, mecânico, serviço e ordem de serviço
- **Consultas** com tabela, pesquisa por vários critérios e botão de atualizar
- **Alteração e exclusão** de registros direto pela tabela
- **Ordens de serviço** com cliente, veículo, mecânico, serviço, diagnóstico, status, valor e datas de abertura e conclusão
- **Tela de ajuda** dentro do sistema
- Validação dos dados antes de salvar (datas, valores, campos obrigatórios)

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| Java | Linguagem principal |
| Java Swing | Interface gráfica |
| NetBeans | IDE do projeto |
| PostgreSQL | Banco de dados |
| JDBC | Conexão entre o Java e o banco |
| Git e GitHub | Versionamento do código |

## 🗂️ Estrutura

```
src/
├── conexao/   → classe de conexão com o PostgreSQL
├── tela/      → telas de cadastro e consulta (JFrame)
└── imagem/    → imagens usadas na interface
```



## 📚 O que aprendi

- Conexão com banco de dados usando JDBC e `PreparedStatement`
- Comandos `SELECT`, `INSERT`, `UPDATE` e `DELETE`, além de `JOIN` entre tabelas
- Montar telas com Java Swing e preencher `JTable` com dados do banco
- Tratamento de erros e validação de dados
- Versionamento com Git e GitHub

## 🖼️ Telas do sistema
<img width="1221" height="813" alt="image" src="https://github.com/user-attachments/assets/f9b302e9-3ba8-4245-a896-b41744c342c9" />
<img width="1249" height="905" alt="image" src="https://github.com/user-attachments/assets/d5c7afeb-2e35-4e48-bc76-c341da65551b" />
<img width="1159" height="853" alt="image" src="https://github.com/user-attachments/assets/d62612a4-9d6a-4f0a-8bf1-267ddd13422e" />
<img width="993" height="685" alt="image" src="https://github.com/user-attachments/assets/3ea26650-0d8a-4fed-bd8e-9c472fc44b68" />



## 👨‍💻 Autor

Desenvolvido por **Gustavo Santos**.
