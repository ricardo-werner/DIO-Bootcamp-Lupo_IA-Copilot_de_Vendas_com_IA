# 📝 PRD (Product Requirement Document)

**Nome do Projeto:** Lupo Conecta  
**Core sistema IA:** F.I.O.S. (Flexibilidade, Inovação, Otimização, Secagem)  
**Status:** Em Definição  
**Autor:** Ricardo Werner  
**Versão:** 3.4 (Mapeamento de Escopo de Longo Prazo)

---

## 1. Visão Geral e Conclusão Executiva

### A) As Dores do Mercado (O Problema)

- **Esquecimento do Cross-sell:** Vendedores em loja física, no calor do atendimento, focam apenas no produto principal (High Ticket) e esquecem de oferecer meias e acessórios (Low Ticket), diminuindo o faturamento potencial da unidade.
- **Falta de Domínio Técnico:** Roupas esportivas premium da Lupo Sport possuem tecnologias complexas (_Seamless, Dry-fit, Proteção UV_). Vendedores iniciantes ou pouco treinados não conseguem explicar esses benefícios de forma convincente, perdendo vendas por objeção de preço.
- **Atendimento Genérico:** Falta de uma personalização rápida no balcão de atendimento que conecte o produto exato e sua tecnologia à modalidade esportiva real e intensidade de treino do cliente.

### B) A Ideia Central (A Solução)

Implementar o **Lupo Conecta**, uma solução de Venda Assistida integrada ao WhatsApp ou tablet corporativo da loja física, impulsionada pela sistema de inteligência artificial **F.I.O.S. (Flexibilidade, Inovação, Otimização, Secagem)**.

Através de um fluxo rápido de perguntas estruturadas em botões (interface estilo árvore de decisão), o vendedor alimenta o sistema em apenas três cliques durante o atendimento. A inteligência **F.I.O.S.** processa essas variáveis, varre o catálogo real em JSON e devolve instantaneamente na tela do dispositivo: o diagnóstico do atleta, a oferta de vestuário ideal (High Ticket), o cross-sell perfeito (Low Ticket) com seus respectivos códigos de ID e preços, e um roteiro com os argumentos tecnológicos exatos para o vendedor fechar a venda de forma consultiva no balcão.

### C) O Resultado Esperado (O Impacto)

- **Aumento do Ticket Médio:** Elevação do indicador de PA (Peças por Atendimento) através de ofertas complementares altamente lógicas e baseadas em dados reais de estoque.
- **Rampa de Aprendizado Rápida:** Redução drástica no tempo de treinamento de novos vendedores, que se tornam "consultores especialistas" desde o primeiro dia com o apoio da inteligência F.I.O.S.
- **Aumento da Conversão:** Contorno de objeções eficiente baseado em valor tecnológico real, e não em concessão de descontos, protegendo a margem de lucro da loja.

---

## 2. Objetivos do Produto (KPIs)

- **Aumentar o PA (Peças por Atendimento):** Meta de crescer em 25% a inclusion de meias e acessórios nos carrinhos de roupas da loja.
- **Reduzir o Tempo de Atendimento:** O fluxo de botões interativos deve ser totalmente resolvido pelo vendedor em menos de 10 segundos.
- **Taxa de Adoção da Ferramenta:** Garantir que pelo menos 80% dos atendimentos diários de balcão utilizem o copiloto.

---

## 3. Personas (Usuários do Sistema)

- **O Vendedor de Loja:** Necessita de uma interface ultra-rápida, com cliques simples e textos curtos e escaneáveis. Ele não tem tempo para ler parágrafos longos ou digitar relatórios enquanto o cliente espera na arara de roupas.
- **O Gerente / Lojista:** Necessita de relatórios consolidados simples para entender quais modalidades esportivas e perfis de intensidade estão sendo mais buscados em sua loja física, direcionando com precisão as futuras compras de estoque.

---

## 4. Requisitos Funcionais (O que o sistema deve fazer)

| ID       | Requisito                        | Descrição                                                                                                                                                       | Prioridade      |
| :------- | :------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------- |
| **RF01** | Interface por Botões             | O sistema deve guiar o vendedor usando caixas de seleção rápida (Menus de WhatsApp/Tablet) para evitar qualquer tipo de digitação manual de texto.              | P0 (Crítico)    |
| **RF02** | Filtro de 3 Camadas              | O fluxo obrigatório de botões deve coletar sequencialmente três variáveis: 1) Gênero/Público, 2) Modalidade Esportiva, 3) Nível de Intensidade.                 | P0 (Crítico)    |
| **RF03** | Motor de IA Integrado (F.I.O.S.) | Após a seleção da terceira escolha pelo vendedor, o sistema deve acionar automaticamente a sistema F.I.O.S. para processar a matriz de decisão.                 | P0 (Crítico)    |
| **RF04** | Entrega de Scripts de Balcão     | A resposta final gerada pela IA deve conter um roteiro com aspas pronto para o vendedor falar diretamente para o cliente em loja ("Diga isso ao cliente...").   | P1 (Importante) |
| **RF05** | Módulo de Objeções Rápido        | Exibir um botão fixo de acesso rápido chamado "Ver Objeções" para munir o vendedor com argumentos de tecnologia (Seamless/Dry) caso o cliente conteste o preço. | P2 (Desejável)  |

---

## 5. Requisitos Não-Funcionais (Como o sistema deve se comportar)

- **Tempo de Resposta (Latência):** A recomendação final da IA F.I.O.S. deve aparecer na tela em, no máximo, 3 segundos após o último clique no botão do menu.
- **Disponibilidade:** O sistema deve ser responsivo e funcionar perfeitamente em dispositivos móveis (smartphones e tablets) operando em sistemas Android e iOS.
- **Interface Clean:** Uso obrigatório de emojis estruturados como _visual anchors_ (âncoras visuais) e amplo espaçamento no texto para facilitar a leitura dinâmica de balcão.

---

## 6. Fluxo do Usuário (User Journey)

1. O vendedor aborda o cliente no chão de loja e descobre que ele busca roupas para **Corrida de Alta Performance**.
2. O vendedor abre o chat com o robô no tablet e clica no botão: **[Masculino]** _(Menu 1)_.
3. O robô exibe o próximo menu de opções e o vendedor clica em: **[Trilha]** _(Menu 2)_.
4. O robô exibe o último filtro de nível e o vendedor clica em: **[Alta Performance]** _(Menu 3)_.
5. A inteligência **F.I.O.S.** processa instantaneamente as variáveis, cruza os dados com o catálogo real em JSON e exibe o bloco estratégico estruturado na tela: Diagnóstico, Jaqueta Masculina LSport RunStorm (ID: M005 - R$ 369,90) como Oferta Principal, e a Meia Performance Cano Médio (ID: ME001 - R$ 46,90) como Cross-sell.
6. O vendedor utiliza os argumentos e o script de balcão gerados na tela, oferece o combo tecnológico completo ao cliente e fecha a venda de alto valor.
7. Caso o cliente questione o preço, o vendedor clica no botão de acesso rápido "Ver Objeções" e utiliza os argumentos de tecnologia (como durabilidade do _Seamless_ ou eficiência do _Dry-fit_) para contornar a objeção sem precisar oferecer desconto.

---

## 7. Próximos Passos (Roadmap de Produto - Fase 2)

Para além do MVP (Mínimo Produto Viável), o amadurecimento estratégico da ferramenta prevê a transição de um sistema focado em objeções elementares de preço para um mapeamento analítico da psicologia do consumidor de varejo físico:

- **Objeções de Confiança e Ajuste (Fit):** Estruturação de respostas para inseguranças anatômicas do cliente (transparência em agachamentos, compressão excessiva em cinturas).
- **Objeções de Hábito e Concorrência:** Argumentação de superioridade tecnológica de tecelagem para migração de clientes fidelizados a marcas esportivas concorrentes.
- **Objeções de Logística e Imediatismo:** Soluções de contorno de indisponibilidade física cruzando dados em tempo real com o estoque central da marca para entregas no dia seguinte.
- **Objeções Estéticas e Estilo:** Criação de algoritmos de substituição cromática para sugerir opções alternativas de cores mantendo os mesmos benefícios esportivos buscados.
- **Objeções de Sustentabilidade e Consciência Ambiental:** Argumentação baseada em dados de impacto ambiental reduzido da produção das peças Lupo Sport para clientes com perfil eco-friendly.
