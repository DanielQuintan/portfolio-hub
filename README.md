# PortfolioHUB — Painel Centralizado de Projetos e Documentação

## 👤 Perfil do Desenvolvedor
* [cite_start]**Nome:** Daniel Nery Quintana [cite: 42]
* [cite_start]**Localização:** Brasília - DF [cite: 43]
* [cite_start]**Curso:** Engenharia de Software (Centro Universitário de Brasília - CEUB) [cite: 51, 52]
* [cite_start]**Objetivo:** Desenvolver soluções reais e evoluir como desenvolvedor de software[cite: 48, 49].

---

## 🚀 1. Planejamento da Implantação e Trilha com IA
A implantação do **PortfolioHUB** foi concebida para ser um ecossistema organizado que resolve o problema de fragmentação de entregas técnicos e documentais.
* **Configuração da Trilha:** Utilizou-se o **Google GEMINI** como arquiteto de suporte instrucional para modelar a estrutura de pastas do projeto, definir a tipagem polimórfica do arquivo de metadados (`projetos.json`) e garantir conformidade com padrões de Clean Architecture.

---

## 📂 2. Estrutura de Pastas de Metadados
Para garantir uma organização limpa, escalável e de fácil manutenção, o projeto adota o seguinte padrão estrutural:
```text
portfolio-hub/
├── .github/                  # Workflows de automação e CI/CD
├── data/                     # Camada de persistência local de dados
│   └── projetos.json         # Arquivo de metadados central unificado
├── public/                   # Elementos visuais estáticos e assets
└── README.md                 # Documentação oficial e vitrine do Hub
