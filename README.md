# 🚀 AvaliaNFC — Cada atendimento vira uma avaliação no Google

Este repositório contém o código-fonte da **Landing Page comercial** do AvaliaNFC, uma plataforma SaaS Multi-Tenant inovadora projetada para comércios locais (restaurantes, clínicas, varejo) otimizarem sua reputação digital e gestão de equipes através de cartões físicos com chip NFC.

🔗 **Acesse o projeto publicado aqui:** [https://avalianfc.netlify.app/)

---

## 🛠️ Tecnologias e Conceitos Aplicados (Perfil ADS)

Como estudante de Análise e Desenvolvimento de Sistemas, utilizei este projeto prático para consolidar competências de arquitetura, design e segurança exigidas pelo mercado corporativo:

- **Front-End Premium & UX:** Interface construída em modo escuro utilizando **Tailwind CSS**, aplicando conceitos de *Glassmorphism* (camadas translúcidas com profundidade visual) e micro-interações fluidas de estado (*hover states*) focadas na experiência do usuário em dispositivos móveis.
- **Engenharia de Usabilidade:** Encapsulamento dos Termos de Uso e Políticas de Privacidade em janelas modais via **JavaScript nativo**, limpando a rolagem da página principal e mantendo o foco 100% na conversão de vendas.
- **Hospedagem Automatizada:** Deploy contínuo e infraestrutura de nuvem segura em HTTPS utilizando o **Netlify**.
- **Modelagem de Negócios SaaS:** Lógica estruturada para faturamento recorrente mensal (MRR) baseada em 3 categorias de planos de assinatura (Start, Equipe e Escala) com travas de segurança por limites de funcionários ativos.

---

## ⚙️ Próximos Passos do Desenvolvimento Técnico (Back-End)
A infraestrutura traseira do ecossistema já está ativa e hospedada em um servidor em nuvem na região do Brasil (São Paulo) via **Supabase/PostgreSQL**, contendo:
- Criptografia ativa de senhas administrativas via **Blowfish (Bcrypt com custo 12)**;
- Segurança avançada de dados através de **Row Level Security (RLS)** para isolamento estrito de informações entre os estabelecimentos clientes;
- Gatilhos automáticos nativos (*Triggers*) para validação de CNPJ e imposição mecânica de limites de planos.

*A fiação da API e conexão assíncrona (async/await) entre esta interface e as tabelas do banco de dados estão em andamento!*

