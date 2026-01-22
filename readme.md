Aviation Safety Management System - Situational Awareness (SA) Tool

📌 Sobre o Projeto

Esta ferramenta é uma implementação técnica de uma metodologia de Gerenciamento de Segurança Operacional, baseada em pesquisa de Mestrado realizada no ITA (Instituto Tecnológico de Aeronáutica). Trata-se de uma Single Page Application (SPA) projetada para mitigar falhas cognitivas e elevar a Consciência Situacional (SA) em operações críticas de aviação agrícola.

O sistema transpõe conceitos complexos de Aviation Safety para uma interface funcional, permitindo que o operador realize uma análise preditiva de riscos antes de cada missão.

🛠️ Destaques Técnicos & Decisões de Engenharia
Diferente de checklists comuns, este projeto foi estruturado com foco em resiliência de dados e UX crítica:

Persistência de Estado (State Management): Implementação de lógica para salvar o progresso automaticamente no localStorage do navegador. Isso garante que, em caso de fechamento acidental ou falha de conexão, os dados críticos de segurança não sejam perdidos.

Visualização de Dados em Tempo Real: Integração com a biblioteca Chart.js para gerar um gráfico de radar (Radar Chart) que sintetiza os quatro pilares da prontidão operacional.

Design Responsivo e Off-line: Construído com Tailwind CSS para garantir legibilidade total em dispositivos móveis no campo, além de possuir um layout otimizado para impressão de relatórios físicos.

Rigor Metodológico: A lógica do software é dividida nos três níveis de Consciência Situacional definidos por Endsley: Percepção, Compreensão e Projeção.

🚀 Arquitetura e Tecnologias
O projeto adota uma abordagem zero-dependency para o núcleo da lógica, garantindo portabilidade absoluta:

Core: Vanilla JavaScript (ES6+).

Estilização: Tailwind CSS (via JIT/CDN).

Gráficos: Chart.js.

Persistência: Web Storage API.

📂 Estrutura de Categorias Analisadas
O sistema avalia dinamicamente quatro domínios críticos para a segurança:

Saúde do Piloto: Fatores fisiológicos e humanos.

Meteorologia: Variáveis ambientais e climáticas.

Envelope de Aplicação: Parâmetros técnicos da aeronave e sistemas.

Gerenciamento de Risco: Identificação de áreas sensíveis e planos de mitigação.

🏗️ Roadmap de Evolução (Backend Focus)
Este repositório é o primeiro módulo de um ecossistema de segurança maior. As próximas etapas incluem:

[ ] API Rest: Migração da lógica de persistência para um backend em Java / Spring Boot.

[ ] Autenticação: Implementação de segurança JWT para acesso de frotas.

[ ] Histórico: Integração com banco de dados PostgreSQL para análise histórica de tendências de risco.

👨‍💻 Autor
Matheus Guerra – M.Sc. em Aviation Safety (ITA) e Desenvolvedor Backend focado em sistemas críticos. [LinkedIn](https://linkedin.com/in/guerramatheus) | [GitHub](https://github.com/GuerraMath)

Disclaimer: Este software é uma ferramenta de apoio à decisão e deve ser utilizado como complemento aos Manuais de Operações (SOP) e regulamentações da ANAC/EASA/FAA.
