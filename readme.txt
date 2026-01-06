# Ferramenta de Consciência Situacional para Aviação Agrícola

Este repositório contém uma **Ferramenta de Consciência Situacional (SA)** interativa, desenvolvida como uma aplicação web de página única (SPA). O objetivo da ferramenta é auxiliar pilotos de aviação agrícola na avaliação da sua prontidão e segurança antes do voo, baseada em conceitos académicos de *Aviation Safety*.

> **Nota:** Esta ferramenta é uma representação interativa baseada na pesquisa de Mestrado em *Aviation Safety* de **Matheus Guerra** (Instituto Tecnológico de Aeronáutica - ITA).

## 📋 Funcionalidades

A aplicação oferece uma interface intuitiva para realizar avaliações pré-voo críticas, divididas em quatro pilares fundamentais:

1.  **Check-list Interativo Pré-Voo**:
    * **Saúde do Piloto**: Avaliação de fatores fisiológicos (fadiga, nutrição, hidratação).
    * **Meteorologia**: Verificação de condições atmosféricas (vento, temperatura, humidade).
    * **Envelope de Aplicação**: Conferência técnica da aeronave e sistema de pulverização.
    * **Gerenciamento de Risco**: Análise de toxicidade, áreas sensíveis e planos de contingência.

2.  **Visualização de Prontidão (Radar Chart)**:
    * Gera automaticamente um gráfico de radar que exibe o nível de prontidão em cada uma das categorias acima, permitindo uma visualização rápida dos pontos fortes e de atenção.

3.  **Recursos Educativos**:
    * Explicação integrada sobre os três níveis de Consciência Situacional: *Percepção*, *Compreensão* e *Projeção*.

4.  **Funcionalidades de Usabilidade**:
    * **Persistência de Dados**: O progresso é salvo automaticamente no navegador (`localStorage`), permitindo retomar o preenchimento mais tarde.
    * **Modo de Impressão**: Layout otimizado para impressão do relatório de voo.
    * **Design Responsivo**: Funciona em desktops, tablets e dispositivos móveis.

## 🚀 Como Usar

Não é necessária instalação de servidor ou dependências complexas.

1.  Faça o download do arquivo `checklist_Version3.html`.
2.  Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3.  Preencha os itens do checklist clicando nas opções.
4.  Observe o gráfico de radar atualizar-se em tempo real ao final da página.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído focando na simplicidade e portabilidade (arquivo único):

* **HTML5 & CSS3**: Estrutura e estilização.
* **Tailwind CSS** (via CDN): Framework de utilitários para design responsivo e moderno.
* **Chart.js** (via CDN): Biblioteca para renderização do gráfico de radar.
* **JavaScript (Vanilla)**: Lógica de interação, manipulação do DOM e persistência local.

## 📄 Créditos e Referência Académica

* **Pesquisa Original**: Matheus Guerra, M.Sc. em Aviation Safety.
* **Instituição**: Instituto Tecnológico de Aeronáutica (ITA).

---
*Este software é uma ferramenta de auxílio à tomada de decisão e não substitui os procedimentos operacionais padrão (SOP) ou regulamentações oficiais da aviação civil.*