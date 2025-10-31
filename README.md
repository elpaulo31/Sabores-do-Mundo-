📋 Sobre o Projeto
O Sabores do Mundo é um sistema mobile desenvolvido para otimizar e modernizar a gestão de redes de restaurantes, integrando todos os processos operacionais em uma plataforma única e intuitiva.

🎯 Objetivo do Projeto
Desenvolver um sistema mobile completo para gestão de uma rede de restaurantes, aplicando os conceitos aprendidos na disciplina de Desenvolvimento Mobile.

👥 Equipe de Desenvolvimento
Nome	Responsabilidade
Gabrielle de Melo Nascimento	Desenvolvimento
Brunno Barbosa de Lima Assunção	Desenvolvimento
Igor Gabriel Soares de Almeida Araújo	Desenvolvimento
Lucas de Araujo dos Prazeres	Desenvolvimento
Nayane Maria Lopes dos Santos	Módulo de Funcionários
Paulo Thiago Santos da Silva	Desenvolvimento
🎓 Contexto Acadêmico
Disciplina: Desenvolvimento Mobile

Professor: Diógenes Martins

Instituição: UNIT - PE

Período: 5º período - Manhã

🛠️ Especificações Técnicas
Tecnologias Utilizadas
Plataforma: Android

Linguagem: Kotlin/Java

Banco de Dados: SQLite

Arquitetura: MVVM (Model-View-ViewModel)

Ferramentas: Android Studio

Requisitos do Sistema
Android API 21+

Conexão com banco de dados local

Interface responsiva

Controle de acesso por perfis

📦 Módulos do Sistema
🔐 Módulo de Autenticação
Tela de login com validação de perfis

Controle de acesso por tipo de usuário

Gestão de sessão de usuário

📦 Módulo de Estoque
Responsável: Igor Gabriel 

Controle de produtos em tempo real

Sistema de alertas de reposição

Integração com fornecedores

👥 Módulo de Funcionários
Responsável: Nayane Lopes

Cadastro e gestão de equipes

Escalas de trabalho

Avaliações de desempenho

🍳 Módulo de Produção
Responsável: Lucas de Araújo

Receitas padronizadas

Controle de cardápio

Monitoramento de produção

📊 Módulo de Relatórios
Responsável: Paulo Thiago

Análise de vendas

Métricas de estoque

Dashboard gerencial



📱 Protótipo da Interface
Telas Principais
Login - Acesso com diferentes perfis

Dashboard - Visão geral por perfil

Gestão de Estoque - Controle de produtos

Gestão de Pessoal - Administração de equipes

Produção - Controle do cardápio e receitas

Relatórios - Análises e métricas

🗃️ Modelo do Banco de Dados
Tabelas Principais
Tabela	Descrição
Usuarios	Controle de acesso e perfis
Produtos	Cadastro de itens do estoque
Funcionarios	Dados da equipe
Fornecedores	Cadastro de parceiros
Receitas	Instruções de preparo
Pedidos	Controle de vendas
🚀 Como Executar o Projeto
Pré-requisitos
Android Studio

SDK Android 21+

Dispositivo ou emulador Android

Instalação
bash
# Clone o repositório
git clone https://github.com/equipe-sabores-mundo/sabores-do-mundo.git

# Abra no Android Studio
# Sincronize o projeto
# Execute em um dispositivo/emulador
📁 Estrutura do Projeto
text
app/
├── src/main/java/com/saboresdomundo/
│   ├── data/
│   │   ├── database/     # SQLite Database
│   │   ├── entities/     # Entidades do banco
│   │   └── dao/         # Data Access Objects
│   ├── repository/      # Camada de repositório
│   ├── viewmodel/       # ViewModels
│   ├── ui/
│   │   ├── auth/        # Autenticação
│   │   ├── dashboard/   # Dashboard principal
│   │   ├── estoque/     # Módulo de estoque
│   │   ├── funcionarios/ # Módulo de funcionários
│   │   ├── producao/    # Módulo de produção
│   │   └── relatorios/  # Módulo de relatórios
│   └── utils/           # Utilitários e helpers

📄 Licença
Este projeto é desenvolvido para fins acadêmicos na disciplina de Desenvolvimento Mobile sob orientação do professor Diógenes.

© 2025 - Equipe de Desenvolvimento Mobile - Todos os direitos reservados
