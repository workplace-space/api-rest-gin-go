# API REST com Gin (Go)

Projeto criado para estudo de curso realizado na ALURA, utilizando o framework **Gin** em **Go**, com conexão ao banco de dados **PostgreSQL**, gerenciamento via **Docker Compose** e arquitetura organizada por camadas.

---

## Tecnologias Utilizadas

[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://golang.org/)
[![Gin](https://img.shields.io/badge/Gin%20Framework-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://gin-gonic.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![GORM](https://img.shields.io/badge/GORM-FF6347?style=for-the-badge&logo=go&logoColor=white)](https://gorm.io/)

---

## 📁 Estrutura de Pastas

```text
.
├── controllers         # Camada de controle (handlers)
│   └── controller.go
├── database            # Conexão com o banco de dados
│   └── db.go
├── docker-compose.yml  # Orquestração dos containers
├── go.mod              # Gerenciador de dependências (módulo Go)
├── go.sum              # Checksum das dependências
├── main.go             # Ponto de entrada da aplicação
├── models              # Definições das entidades (ORM)
│   └── aluno.go
├── README.md
└── routes              # Definição das rotas da aplicação
    └── routes.go
