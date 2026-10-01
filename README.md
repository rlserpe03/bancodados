# 📚 Guia SQL para Alunos — Tabela de Cadastro Escolar

Uma página web interativa e responsiva desenvolvida para disponibilizar scripts SQL aos alunos. O projeto abrange desde a criação da tabela de cadastro escolar (`CREATE TABLE`) até a inserção de dados (`INSERT`) e consultas (`SELECT`).

---

## 🚀 Funcionalidades

* **Navegação por Abas**: Organização clara dos conteúdos em três seções (Criação da Tabela, Inserção de Dados e Consultas SELECT).
* **Cópia em Um Clique**: Botão "Copiar Código" integrado a cada bloco de script com feedback visual instantâneo.
* **Design Moderno (Dark Mode)**: Interface agradável para leitura prolongada, inspirada nos temas mais utilizados por desenvolvedores.
* **Destaque de Sintaxe (Syntax Highlighting)**: Visualização colorida dos comandos SQL para facilitar o aprendizado.
* **Explicações Didáticas**: Cada bloco de código vem acompanhado de explicações sobre a estrutura e os tipos de dados utilizados.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação semântica da página.
* **CSS3**: Estilização com variáveis CSS, Flexbox, Grid e animações.
* **JavaScript (Vanilla)**: Lógica de alternância de abas e manipulação da Clipboard API para cópia de código.

---

## 📂 Estrutura do Projeto

```text
.
├── index.html   # Arquivo principal (HTML, CSS e JS integrados)
└── README.md    # Documentação do projeto

```

---

## 💻 Como Executar o Projeto

Como a página é composta por código estático, não é necessário instalar dependências ou configurar servidores backend:

1. Baixe ou clone este repositório.
2. Dê um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador de preferência.
3. *(Opcional)* Se estiver usando o VS Code, você pode abrir com a extensão **Live Server**.

---

## 🎓 Conteúdo Abordado na Página

1. **`CREATE TABLE alunos`**:
* Chave primária (`ID AUTO_INCREMENT`)
* Restrições de unicidade (`UNIQUE` para RA e CPF)
* Tipos de dados (`VARCHAR`, `CHAR`, `TIMESTAMP`)
* Endereço estruturado (Logradouro, Número, Bairro, Cidade, Estado e CEP)


2. **`INSERT INTO`**:
* Inserção em lote de 5 registros de alunos fictícios.


3. **`SELECT`**:
* Consultas gerais, busca por ID/RA, filtros por estado (`WHERE`) e busca textual (`LIKE`).
