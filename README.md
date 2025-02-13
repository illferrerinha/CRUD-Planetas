# 🌍 CRUD Planetas

Este repositório contém um sistema CRUD (Create, Read, Update, Delete) para gerenciamento de planetas. O projeto permite adicionar, visualizar, atualizar e remover planetas de um banco de dados.

## 🚀 Tecnologias Utilizadas
- **Linguagem**: Dart (Flutter)
- **Banco de Dados**: SQLite (usando sqflite)
- **Gerenciamento de Estado**: Stateful Widgets

## 📦 Funcionalidades
- Criar um novo planeta
- Listar planetas existentes
- Atualizar informações de um planeta
- Deletar um planeta do banco de dados

## 📂 Estrutura do Projeto
```
📁 crud_planetas
├── 📂 lib
│   ├── main.dart (código principal da aplicação Flutter)
│   ├── 📂 controles
│   │   ├── controle_planeta.dart (lógica de controle do banco de dados)
│   ├── 📂 modelos
│   │   ├── planeta.dart (modelo de dados do planeta)
│   ├── 📂 telas
│   │   ├── tela_planeta.dart (tela para cadastro/edição de planeta)
├── README.md (este arquivo)
```

## 🔧 Como Executar
### 1️⃣ Clonar o Repositório
```bash
git clone https://github.com/illferrerinha/CRUD-Planetas.git
cd crud-planetas
```
### 2️⃣ Instalar Dependências
```bash
flutter pub get
```
### 3️⃣ Executar o Aplicativo
```bash
flutter run
```

## 📌 Estrutura do Banco de Dados
O banco de dados SQLite está estruturado da seguinte forma:
```sql
CREATE TABLE planetas (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nome TEXT NOT NULL,
    tamanho REAL NOT NULL,
    distancia REAL NOT NULL,
    apelido TEXT
);
```

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para usá-lo e contribuir!

---
Feito por Vinicius Ferreira (https://github.com/illferrerinha).



