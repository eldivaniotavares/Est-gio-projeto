# 🛠️ TechCare - Plataforma Web de Gestão de Suporte Técnico e Manutenção de TI

[![PHP Version](https://img.shields.io/badge/PHP-7.4%20%7C%208.x-777BB4?style=flat&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)](#)
[![Academic Project](https://img.shields.io/badge/Finalist%20Project-TCC%2FEst%C3%A1gio-success)](#)

O **TechCare** é uma solução web desenvolvida no âmbito do Trabalho de Conclusão de Curso (TCC) e Estágio Técnico de Informática. O projeto visa centralizar, organizar e automatizar o processo de reporte de avarias, diagnóstico e rastreabilidade de suporte técnico corporativo e institucional.

---

## 🚀 Funcionalidades Principais

* **🔒 Autenticação e Controlo de Acessos:** Controlo de sessões seguras em PHP para Clientes e Técnicos.
* **📝 Abertura de Chamados (Tickets):** Registo detalhado de falhas com descrição, nível de urgência e anexo de imagens.
* **📊 Rastreabilidade de Estados:** Acompanhamento transparente do ciclo de vida do pedido (`Pendente` ➔ `Em Análise` ➔ `Resolvido`).
* **💻 Painel do Técnico (Dashboard):** Visualização geral de incidentes, atribuição de diagnósticos manuais e encerramento de chamados.
* **📱 Interface Responsiva:** Protótipo visual desenhado no Figma com foco em usabilidade e desempenho.

---

## 🛠️ Tecnologias Utilizadas

### **Frontend**
* **HTML5 & CSS3:** Estruturação semântica e estilização customizada.
* **JavaScript (Vanilla):** Validação de formulários e dinamismo do lado do cliente.
* **Figma:** Prototipagem e design de interface (UI/UX).

### **Backend & Base de Dados**
* **PHP:** Lógica de negócio, gestão de sessões e rotas.
* **MySQL:** Base de dados relacional para persistência dos dados de utilizadores e tickets.

---

## 📂 Estrutura do Repositório

```text
techcare/
├── assets/
│   ├── css/          # Folhas de estilo (style.css)
│   ├── js/           # Scripts de validação e UI
│   └── img/          # Imagens de stock e upload de anexos
├── config/
│   └── db.php        # Conexão à base de dados MySQL (PDO / MySQLi)
├── includes/
│   ├── header.php    # Cabeçalho global
│   └── footer.php    # Rodapé institucional
├── views/
│   ├── login.php     # Ecrã de autenticação
│   ├── register.php  # Ecrã de registo de utilizadores
│   ├── dashboard.php # Painel principal de suporte
│   └── new_ticket.php# Formulário de abertura de chamados
├── index.php         # Landing Page principal
├── README.md         # Documentação do repositório
└── schema.sql        # Script SQL da base de dados
