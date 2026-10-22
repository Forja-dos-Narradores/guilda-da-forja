# 🔧 Dottie "Fatcat" — Ficha Conceitual & Sugestões de Funções

> *"Não adianta me olhar com essa cara de cachorro sem dono. Fez o seu trabalho hoje ou vai inventar mais uma desculpa esfarrapada?"*

---

## 1. Conceito Rápido

* **Arquétipo:** A Artesã Goblin de Pequenos Artefatos e Ferramentas Práticas
* **Origem:** *Forja dos Narradores* (Pilar: Ferramentas e Recursos Práticos / "Mão na massa")
* **Aparência:** Goblin orelhuda, baixinha de dentes pontiagudos e cabelo curto, com volume e bagunçado. Veste roupas de aventureira despojada com longas botas de couro e linho, e cintos carregados de bolsos e ferramentas que a transformam em uma artesã sempre preparada.
* **Personalidade:**
  * Curiosa, inventiva, encorajadora e empolgada, mas com uma pitada de intensidade e brilho no olhar.
  * Às vezes sábia, um pouco caótica e levemente sarcástica.
  * Sua paciência é vasta para os erros de quem está aprendendo, mas não tolera desculpas fajutas ou falta de dedicação.
  * Seus conselhos são sempre diretos, práticos e, pelo seu modo de pensar, às vezes abstratos ao seu próprio estilo goblinico.
  * Extremamente protetora com quem se esforça.
* **Histórias de Família:**
  * Pertence a uma família numerosa de goblins com as mais variadas cores, formas, tamanhos e manias, cujas histórias são caricatas, malucas e engraçadas.
  * Chegava a se sentir a "ovelha negra" por parecer normal demais perto dos parentes.
  * Carrega o cognome de linhagem "Fatcat", atribuído na infância pela matriarca da família.
* **Papel Conceitual no Discord:** A guia prática e "mão na massa" da comunidade, focada em fornecer recursos práticos para mestres e jogadores, incentivar a dedicação diária e trazer a energia caótica e acolhedora da Forja.

---

## 2. Sugestões de Funções (Comandos & Features)

### 🧰 2.1 Ferramentas Práticas & Recursos de Mesa (Mão na Massa)
* **`/artefato`**: Gera pequenos itens mágicos e engenhocas curiosas, com utilidades práticas e peculiaridades divertidas para mestres utilizarem em suas mesas.
* **`/monstro-caseiro`**: Apresenta monstros e criaturas caseiras criadas pela comunidade para enriquecer os combates e encontros.
* **`/ferramentas-vtt`**: Fornece atalhos e recomendações de mapas, tokens, grids e utilitários para plataformas de RPG virtual (VTTs).
* **`/playlist-sessao`**: Sugere trilhas sonoras e ambientes imersivos curados para sessões de RPG (combate, exploração, taverna, suspense).

---

### 🔨 2.2 Foco, Prática & Disciplina Pessoal
* **`/meta-diaria` & `/streak`**:
  * Sistema de registro de dedicação diária (escrita de campanhas, leitura, estudos de RPG ou projetos pessoais).
  * Dottie celebra o esforço genuíno e dá puxões de orelha cheios de humor em quem arranja desculpas furadas para procrastinar.
* **`/conselho-pratico`**:
  * Conselhos diretos, sem rodeios e levemente excêntricos para desbloquear ideias travadas ou resolver dilemas narrativos.

---

### 🎲 2.3 Família & Dinâmica Caótica Goblin
* **`/historia-goblin`**:
  * Conta anedotas cômicas sobre as confusões dos primos, tios e da matriarca da família goblin.
* **`/cognome`**:
  * Batiza o membro do servidor com um "Cognome de Linhagem Goblinico" honorário gerado aleatoriamente de acordo com sua personalidade.
* **`/puxao-de-orelha`**:
  * Envia uma cobrança bem-humorada marcando aquele jogador que ainda não preencheu a ficha ou atrasou a resposta da mesa.

---

### 🔄 2.4 Integração com a Guilda (RabbitMQ & Demais Bots)
* **Consumo de Eventos de Tarefas & Builds (RabbitMQ)**:
  * Ouve filas assíncronas do RabbitMQ quando tarefas pesadas de renderização, exportação de fichas ou processamentos em lote são concluídos. Dottie posta no chat celebrando com entusiasmo: *"Engrenagens girando a todo vapor, a encomenda está pronta!"*.
* **Contracenação & Diálogos com Charlotte**:
  * Gatilho de diálogo dinâmico: quando Charlotte publica respostas longas citando manuais, regras minuciosas ou enciclopédias, Dottie intervém com uma réplica rápida recomendando ir direto para a prática e fazer um "teste de estresse" na masmorra.
* **Sincronia com Annie Cansada**:
  * Reage a eventos de `/play` ou cansaço da Annie com comentários bem-humorados sobre tomar um fôlego e voltar ao trabalho.
