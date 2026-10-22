# 🪕 Annie Cansada — Ficha Conceitual & Sugestões de Funções

> *"Mais uma canção? Tudo bem, mas depois eu vou tirar um cochilo..."*

---

## 1. Conceito Rápido

* **Arquétipo:** A Barda / Aventureira Exausta
* **Origem & Universo:** *Devilline HQ* (Forja dos Narradores)
* **Papel Narrativo:** Anfitriã relutante da taverna, barda contadora de histórias e cantora do palco público da guilda.
* **Personalidade:**
  * Talentosa e carismática, porém cronicamente exausta e sarcástica.
  * Reclama com frequência do trabalho acumulado, das loucuras dos aventureiros e da barulheira na taverna, mas no fundo cuida de todo mundo e entrega apresentações musicais impecáveis.
  * Tem apreço sincero pelo silêncio, uma boa caneca de café e pausas estratégicas para descanso.
* **Papel Conceitual no Discord:** Anfitriã do servidor e mestre de cerimônias musical. Conecta as pessoas através da música, humor irônico e acolhimento bem-humorado em canais de voz e texto.

---

## 2. Sugestões de Funções (Comandos & Features)

### 🎵 2.1 Músicas & Canções da Taverna (Áudio & Voz)
* **`/play [busca|url]`**: Toca músicas acompanhadas de comentários sonolentos ou cínicos da Annie anunciando o início da faixa.
* **`/pause` & `/resume`**: Pausa a reprodução sob o pretexto de que precisa tomar um café, esticar as costas ou dar um longo bocejo.
* **`/taverna-lofi`**: Ativa uma transmissão ambiente ininterrupta de melodias acústicas, chuva na janela da taverna e lofi medieval para estudo e foco.
* **`/afinacao`**: Aplica efeitos acústicos divertidos (eco de masmorra, afinação acelerada, reverberação de salão nobre).

---

### ☕ 2.2 Persona & Convivência
* **`/cafe`**: Permite aos membros oferecerem xícaras de café virtual para a Annie; sua energia e falas mudam temporariamente conforme a quantidade de café acumulada no dia.
* **`/desabafo`**: Espaço onde a Annie escuta os desabafos dos membros e responde com conselhos afiados, irônicos, mas acolhedores à sua maneira.
* **`/fofoca`**: Espalha boatos hilários e aleatórios sobre o que teria acontecido recentemente pelos cantos da taverna.
* **`/cochilo`**: Ativa um lembrete carinhoso de pausa, hidratação e descanso para quem estiver passando longas horas seguidas no servidor.

---

### 🎲 2.3 Jogos de Salão & Dados
* **`/dado [notacao]`**: Rolagem de dados de RPG com comentários da Annie lamentando o azar alheio ou surpresa com acertos críticos.
* **`/desafio-bardo`**: Minigame de adivinhação musical ou continuação de rimas entre os frequentadores da taverna.

---

### 🔄 2.4 Integração com a Guilda (RabbitMQ & Demais Bots)
* **Publicação de Eventos de Palco (RabbitMQ)**:
  * Publica eventos de início de festas, pedidos de música e convocações da taverna na fila de mensageria para outros bots responderem (ex: Mestre da Guilda anunciando brindes ou Dottie sincronizando efeitos sonoros).
* **Contracenação & Diálogos no Chat**:
  * Ao receber entregas ou cartas de missões de outros bots (como o Carteiro ou Finn), Annie solta comentários irônicos: *"Mais uma encomenda? Espero que dessa vez não seja outro artefato goblin fazendo barulho..."*.
  * Troca farpas amigáveis com Dottie sobre excesso de trabalho versus pausas essenciais para café.
