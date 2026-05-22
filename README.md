# DIO-Bootcamp-Lupo_IA-Copilot_de_Vendas_com_IA
Desenvolvimento um Assistente de Vendas com IA para Atendimento em Loja, projetado para apoiar profissionais comerciais em interações reais com clientes. 

# 🤖 Lupo Conecta – Copiloto de Vendas Assistidas por IA

<p align="center">
  <img src="https://shields.io" alt="Projeto">
  <img src="https://shields.io" alt="IA">
  <img src="https://shields.io" alt="Plataforma">
</p>

## 📋 Sobre o Projeto

O **Lupo Conecta** é a solução oficial de inteligência de balcão projetada para transformar o atendimento nas lojas físicas da Lupo Sport. O ecossistema digital une a expertise técnica dos tecidos da marca à agilidade do atendimento humano.

O projeto é impulsionado pela engine de Inteligência Artificial **F.I.O.S. (Flexibilidade, Inovação, Otimização, Secagem)**, uma matriz conceitual que atua nos bastidores. Em vez de exigir digitações longas do vendedor, o sistema utiliza uma interface baseada em **menus de botões interativos** (árvore de decisão). O vendedor alimenta a **F.I.O.S.** com 3 cliques rápidos durante o atendimento e recebe instantaneamente na tela os melhores argumentos técnicos, produtos recomendados e estratégias de fechamento.

---

## 🎯 O Problema vs. A Solução

* **O Problema:** Vendedores em loja física enfrentam dificuldades para lembrar de todas as especificações técnicas de tecidos (*Seamless, Emana, Sanitized*) e frequentemente esquecem de oferecer itens complementares (como meias e acessórios), reduzindo o ticket médio da loja.
* **A Solução:** Um chatbot estruturado que transforma qualquer vendedor em um consultor de alta performance em menos de 10 segundos, automatizando a estratégia de *Upsell* e *Cross-sell* com base no esporte do cliente.

---

## 🧠 A Engine F.I.O.S. (Flexibilidade, Inovação, Otimização, Secagem)

A **F.I.O.S.** é o cérebro do projeto. O acrônimo resume os pilares de engenharia têxtil da marca em uma proposta de IA baseada em regras de negócio:
* **F**lexibilidade: Roupas que oferecem liberdade de movimento.
* **I**novação: Fios tecnológicos e bioativos de alta performance.
* **O**timização: Peças Seamless que otimizam o conforto e evitam atritos.
* **S**ecagem rápida: Gerenciamento eficiente da umidade do suor.

---

## 🛠️ Como Funciona na Prática (Simulação de Telas)

O sistema opera simulando caixas de mensagens e cliques rápidos no WhatsApp ou Tablet corporativo do vendedor. Abaixo está a simulação exata da jornada de atendimento:

### 📱 Tela 1: Inicialização do Sistema
O vendedor abre o chat com a inteligência F.I.O.S. para mapear o perfil do cliente.

```text
[F.I.O.S.]: Sistema Lupo Conecta Ativado! 🌟
Escolha uma das opções abaixo para iniciar o atendimento: Masculino Feminino Unissex

[Vendedor]: 1
```

### 📱 Tela 2: Filtro de Modalidade Esportiva
A F.I.O.S. avança o menu automaticamente após o primeiro clique do vendedor.

```text
[F.I.O.S.]: Ótimo. Selecione a modalidade esportiva do cliente: Corrida/Trilha Academia/Crossfit Beach Tennis/Tennis Casual/Dia a dia

[Vendedor]: 1
```

### 📱 Tela 3: Definição de Intensidade e Foco
O último filtro mapeia o nível do atleta para acionar o motor de recomendação.

```text
[F.I.O.S.]: Perfeito. Qual é o foco ou nível de intensidade do atleta? Iniciante/Conforto Avançado/Alta Performance

[Vendedor]: 2
```

### 📱 Tela 4: Resposta Inteligente Baseada em Dados
Ao receber a última opção, a engine F.I.O.S. cruza os dados, consulta a base de produtos e entrega o script de balcão mastigado para o vendedor aplicar com o cliente em loja:

```text
🤖 [LUPO CONECTA - RECOMENDAÇÃO INTELIGENTE]

🚨 DIAGNÓSTICO DO ATLETA:
Cliente maratonista ou corredor de alto rendimento. Necessita de alta dissipação de calor, zero atrito mecânico para evitar assaduras e proteção extrema contra bolhas nos treinos longos.

👕 OFERTA PRINCIPAL (High Ticket):
Bermuda de Compressão Emana Masculina (ID: M002). A tecnologia Emana estimula a microcirculação sanguínea, retardando a fadiga muscular e aumentando o rendimento nas passadas.

🧦 CROSS-SELL INTELIGENTE (Low Ticket):
Meia Lupo Sport Performance Cano Médio (ID: ME001) da linha Máximo. Possui amortecimento anatômico e tecnologia Dry, mantendo o pé seco e evitando as bolhas da fricção.

🗣️ SCRIPT DE BALCÃO (O que o vendedor deve falar):
"Olha, como o seu foco é maratona e alta performance, eu recomendo fortemente você levar a nossa Bermuda de Compressão com tecnologia Emana. Ela melhora a circulação e adia aquela sensação de cansaço na musculatura durante os quilômetros finais. E para fazer o par perfeito, os corredores levam essa meia da linha Máximo, que tem um tecido respirável que não deixa o pé escorregar e evita completamente as bolhas."
```

---

## 🛡️ Matriz de Contorno de Objeções da F.I.O.S.

A F.I.O.S. também mune o vendedor com argumentos rápidos para rebater as principais hesitações dos clientes focando em **Valor** e não em **Preço**:

* **Objeção de Preço (Roupas):** Foco na tecnologia *Seamless* (Sem Costura). Justifica o investimento pela alta durabilidade e ausência de assaduras no treino.
* **Objeção de Preço (Meias):** Foco na tecnologia *Dry* (Poliamida Premium). Justifica mostrando que o algodão causa bolhas e retém suor, enquanto a poliamida protege o pé.
* **Objeção de Mau Odor:** Foco na tecnologia *Sanitized* (Antimicrobiano). Justifica provando que o tecido impede a proliferação das bactérias que causam o cheiro ruim de suor.

---

## 💾 Base de Dados de Amostra (`produtos_lupo.json`)

Esta é a estrutura de dados que a inteligência **F.I.O.S.** consome nativamente para cruzar os filtros e gerar as respostas:

```json
{
  "loja": "Lupo Sport",
  "catalogo": {
    "high_ticket": {
      "categorias": {
        "masculino": [
          {
            "id": "M001",
            "nome": "Camiseta Dry-Fit Seamless Masculina",
            "tecnologia": "Seamless",
            "modalidades": ["Treino", "Corrida"],
            "beneficio": "Evita o atrito com a pele e acelera a evaporação do suor."
          },
          {
            "id": "M002",
            "nome": "Bermuda de Compressão Emana Masculina",
            "tecnologia": "Emana / Alta Compressão",
            "modalidades": ["Corrida", "Ciclismo"],
            "beneficio": "Melhora a circulação sanguínea e reduz a fadiga muscular."
          }
        ]
      }
    },
    "low_ticket": {
      "meias": [
        {
          "id": "ME001",
          "nome": "Meia Lupo Sport Performance Cano Médio",
          "linha": "Maximo",
          "cano": "Cano médio",
          "modalidades": ["Corrida", "Treino"],
          "beneficio": "Tecnologia Dry com amortecimento anatômico que evita bolhas."
        }
      ],
      "acessorios": [
        {
          "id": "AC005",
          "nome": "Garrafa Térmica Inox Lupo Sport",
          "modalidades": ["Treino", "Corrida", "Beach Tennis"],
          "beneficio": "Mantém a hidratação gelada por até 24 horas."
        }
      ]
    }
  }
}
```

---

## 📊 Principais Indicadores de Sucesso (KPIs)

A implementação deste repositório visa impactar diretamente as métricas de negócio do varejo:
* **Aumento de PA (Peças por Atendimento):** Meta de +25% de anexação de meias/acessórios.
* **Aumento do Ticket Médio:** Elevação do valor total gasto por cliente na loja física.
* **Redução do TTM (Time-to-Market de Treinamento):** Integração e rampa de novos vendedores de forma instantânea.

---

## 📄 Licença

_Projeto desenvolvido para o Desafio Final do Bootcamp-Lupo_IA da DIO._

## 👨‍💻 Autor

**Ricardo Werner**  
Desenvolvedor Front-end com foco em acessibilidade, UX e inclusão digital. 
</br>
Apaixonado por mergulho, fotografia, tecnologia e inovação.



