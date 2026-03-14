# ESSYN STUDIO — Estrutura Completa & Diferenciais

> "A plataforma que pensa como fotografo."

---

## O QUE E O ESSYN STUDIO

Plataforma SaaS completa para fotografos profissionais. Substitui 6+ ferramentas (WhatsApp, planilhas, Trello, Google Drive, PIX manual, email) por uma unica plataforma integrada com design premium Apple-quality e inteligencia artificial.

**Publico-alvo:** Fotografos profissionais e estudios de fotografia no Brasil.
**Posicionamento:** Premium, editorial, minimalista. "Feito por quem entende fotografia."

---

## ESTRUTURA DO APP

### Navegacao Principal (Sidebar)

O app possui **22+ modulos** organizados em 3 secoes na sidebar:

| Secao | Modulos |
|-------|---------|
| **OPERACAO** | Maia (IA), Projetos, Producao, Agenda, CRM, Galeria, Loja/Pedidos |
| **GESTAO** | Financeiro, Clientes, Contratos, WhatsApp, Time, Relatorios, Automacoes, Integracoes |
| **SISTEMA** | Configuracoes, Armazenamento, Notificacoes, Email Templates, Equipamentos |

### Rotas da Aplicacao

**19 rotas do app** (painel autenticado):
Dashboard, Projetos, Producao, Agenda, CRM, Clientes, Portal do Cliente, Galeria (gerenciamento), Galeria do Cliente (publica), Financeiro, Loja/Pedidos, Contratos, WhatsApp, Time, Relatorios, Automacoes, Integracoes, Configuracoes, Armazenamento, Notificacoes, Email Templates, Equipamentos

**6 rotas de marketing** (site publico V4):
Landing, Recursos, Casos de Sucesso, Planos, FAQ, Seguranca

**4 rotas de onboarding:**
Boas-Vindas, Criar Studio, Preferencias, Concluir

**4 rotas de autenticacao:**
Entrar, Criar Conta, Esqueci Senha, Verificar Email

**Outras:**
Checkout V4, Sucesso V4, QA V4

---

## MODULO POR MODULO — DETALHAMENTO

---

### 1. MAIA — ASSISTENTE IA

**O que e:** Assistente de inteligencia artificial integrada em todo o app. Nao e um chatbot generico — e uma especialista que muda de personalidade conforme o modulo em que o fotografo esta.

**Como funciona:**
- Ativada por Cmd+K em qualquer tela
- Dois modos: painel lateral (520px) e modo foco (tela cheia imersiva)
- Alimentada por Claude Haiku 4.5 com 16 ferramentas

**8 especialidades contextuais:**
1. **Dashboard** — Assistente geral: "Como posso ajudar?"
2. **Projetos** — Especialista em projetos: analisa contratos, prazos, entregas
3. **Financeiro** — Especialista financeiro: receitas, cobrancas, previsoes
4. **Agenda** — Especialista em agenda: compromissos, eventos, conflitos
5. **Producao** — Especialista em producao: fila, gargalos, equipe
6. **Galeria** — Especialista em galeria: selecoes, entregas, downloads
7. **CRM** — Especialista em CRM: leads, pipeline, follow-ups
8. **Configuracoes** — Assistente de setup: integracoes, equipe, preferencias

**16 comandos slash:**
- `/briefing` — Gera briefing pre-evento completo (local, equipe, checklist, kit)
- `/forecast` — Previsao de faturamento para 3 meses
- `/relatorio` — Relatorio completo do estudio
- `/cobrar` — Lista cobrancas pendentes com acao rapida
- `/equipe` — Distribuicao de carga por profissional
- `/entregas` — Proximas entregas e prazos
- `/pipeline` — Resumo do funil de vendas
- `/followup` — Follow-ups pendentes
- `/conversao` — Taxa de conversao por origem de lead
- `/inadimplentes` — Clientes com parcelas vencidas
- `/fluxo` — Fluxo de caixa previsto
- `/hoje` — Compromissos detalhados de hoje
- `/semana` — Visao da semana completa
- `/preparar` — Checklist para proximo evento
- `/pendentes` — Galerias pendentes de acao
- `/selecao` — Status das selecoes de clientes

**Respostas inteligentes incluem:**
- Blocos de KPIs com numeros reais do estudio
- Tabelas de dados formatadas
- Listas com status (ok, warning, error)
- Cards de briefing com checklist completo
- Graficos de previsao
- Botoes de acao (navegar, cobrar, enviar)

**Diferencial:** Nenhuma outra plataforma de fotografia tem IA contextual que entende cada area do negocio. A Maia nao e um ChatGPT generico — ela sabe que voce tem 3 parcelas vencidas, 2 entregas atrasadas e 1 evento sabado.

---

### 2. PROJETOS

**O que e:** Hub central de cada projeto fotografico. Cada projeto contem 5 abas que cobrem todo o ciclo de vida — do primeiro contato a entrega final.

**5 abas por projeto:**

**Aba 1 — Cadastro:**
- Dados do projeto (nome, tipo, data do evento, local)
- Informacoes do cliente (nome, email, telefone, endereco)
- Equipe designada (fotografo principal, segundo fotografo, editor, drone)
- Notas e observacoes
- Tags e categorias

**Aba 2 — Producao:**
- Pipeline de 7 etapas: Agendado → Captacao → Selecao → Edicao → Revisao → Entrega → Finalizado
- Progresso visual com barra de etapas
- Checklist por etapa
- Atribuicao de responsaveis
- Prazo por etapa com alertas de atraso

**Aba 3 — Financeiro:**
- Valor total do contrato
- Plano de parcelas (sinal + parcelas + final)
- Status de cada parcela (paga, pendente, atrasada, renegociada)
- Acoes: cobrar, marcar como paga, anexar comprovante
- Modal de criacao de parcelas (auto-divide o valor)
- Historico de pagamentos

**Aba 4 — Galeria:**
- Criacao e gerenciamento de galerias vinculadas ao projeto
- Contagem de fotos
- Status (rascunho, proofing, final, entregue)
- Link de compartilhamento

**Aba 5 — Documentos:**
- Contratos vinculados
- Propostas
- Briefings
- Arquivos anexados

**Tabela de projetos (visao geral):**
- Colunas: Projeto/Cliente, Data, Local, Equipe (avatares), Producao (barra de progresso), Financeiro (parcelas/vencidas), Status
- Filtros: ano, status (6 estados), tipo (Casamento, Corporativo, Aniversario, Ensaio, Batizado, Formatura)
- Busca por nome
- Filtro por periodo
- Ordenacao (data, nome, status)

**Smart Defaults:**
- Ao criar um novo projeto, o sistema preenche automaticamente campos baseado no tipo de evento
- Ex: Casamento → automaticamente sugere 2 fotografos, producao de 30 dias, sinal de 40%

**KPIs do modulo:**
- Confirmados
- Em Producao
- Atrasados
- Entregues

**Diferencial:** Nenhuma outra ferramenta conecta projeto ← financeiro ← producao ← galeria em 5 abas. O fotografo nunca precisa sair do contexto do projeto para ver parcelas, etapa de producao ou galeria.

---

### 3. PRODUCAO

**O que e:** Radar de producao que mostra todos os trabalhos em andamento. Visualizacao tipo "torre de controle" para gerenciar a fila de producao do estudio.

**7 fases do pipeline:**
1. **Agendado** — Evento confirmado, aguardando data
2. **Captacao** — Dia do evento, fotografando
3. **Selecao** — Escolhendo as melhores fotos
4. **Edicao** — Editando/retocando
5. **Revisao** — Cliente revisando ou fotografo fazendo QA
6. **Entrega** — Galeria publicada, aguardando download
7. **Finalizado** — Tudo entregue, projeto concluido

**Funcionalidades:**
- Header com KPIs: trabalhos na fila, atrasados, capacidade da equipe, entregas pendentes
- Filtros por fase e urgencia com contadores
- Linhas de producao com badges de tipo (Casamento, Corporativo, Ensaio, etc.)
- Selecao em lote com barra de acoes (avancar fase, atribuir equipe, definir prioridade)
- Badges de status com cores (agendado=azul, em andamento=amarelo, concluido=verde, atrasado=vermelho)
- Banners inline para gargalos e atrasos
- Atribuicao de equipe por trabalho (stack de avatares)
- Deep link: clica num trabalho → abre o drawer do projeto na aba Producao

**Diferencial:** Pipeline de 7 fases desenhado especificamente para o fluxo de trabalho fotografico. Nao e um Trello generico — cada fase tem acoes e checklists proprios da fotografia.

---

### 4. AGENDA

**O que e:** Calendario completo para fotografos de eventos, com 4 modos de visualizacao e controle de sabados.

**4 modos de visualizacao:**
1. **Mes** — Grade mensal com eventos compactos
2. **Semana** — Grade de 7 dias com timeline horaria
3. **Dia** — Timeline horaria detalhada
4. **Lista** — Cronologica, ideal para mobile

**Tipos de eventos:**
- Evento fotografico (casamento, ensaio, corporativo)
- Reuniao (com cliente, com equipe)
- Entrega (prazo de galeria, album)
- Bloqueio (dia indisponivel)
- Lembrete (follow-up, cobranca)

**Sidebar direita com:**
- **Proximo Projeto** — Painel com countdown para o proximo evento, checklist pre-evento:
  - Contrato assinado?
  - Sinal pago?
  - Equipe confirmada?
  - Local confirmado?
  - Kit preparado?
- **Timeline do dia** — Mini timeline dos compromissos de hoje
- **Resumo do mes** — Eventos por tipo
- **Disponibilidade de sabados** — Pills mostrando cada sabado:
  - Livre (verde)
  - Ocupado (vermelho)
  - Pre-reserva (amarelo)

**KPIs:**
- Hoje (quantos compromissos)
- Eventos do mes
- Sabados livres
- Total do mes

**Alerta contextual:** "2 itens pendentes para Casamento Oliveira — Evento em 6 dias"

**Diferencial:** O controle de SABADOS e exclusivo. Fotografos de casamento vivem e morrem pela disponibilidade de sabados. Nenhuma outra agenda mostra isso de forma visual. O checklist pre-evento integrado tambem e unico — saber se contrato, sinal e equipe estao ok ANTES do dia.

---

### 5. CRM & PIPELINE

**O que e:** Funil de vendas completo com Kanban de 7 estagios, gerenciamento de leads e conversao lead-para-projeto.

**7 estagios do pipeline:**
1. **Novo** — Lead acabou de chegar
2. **Contato** — Primeiro contato feito
3. **Reuniao** — Reuniao agendada ou realizada
4. **Proposta** — Proposta enviada
5. **Negociacao** — Em negociacao de valores
6. **Ganho** — Fechou! Virou projeto
7. **Perdido** — Nao fechou (com motivo)

**Card de lead inclui:**
- Nome do cliente
- Tipo de evento (Casamento, Ensaio, Corporativo...)
- Valor estimado
- Origem (Instagram, Indicacao, Site, Anuncio)
- Proxima acao com prazo (hoje, atrasado, esta semana)
- Tags (Premium, Album 30x40, Drone)

**Componentes visuais especializados:**
- `lead-stage-badge` — Badge colorido por estagio do pipeline
- `lead-source-tag` — Tag da origem do lead
- `lead-card` — Card completo do lead no Kanban

**Drawer do lead (5 abas):**
1. **Resumo** — Dados de contato, evento, local, numero de convidados, notas
2. **Atividades** — Timeline completa (ligacoes, emails, WhatsApp, reunioes, notas)
3. **Proposta** — Gerenciamento de propostas
4. **Tarefas** — Lista de tarefas com prazos e checkboxes
5. **Notas** — Notas com autor e timestamp

**Conversao Lead → Projeto:**
- Botao "Criar Projeto" no lead ganho
- Auto-cria projeto com dados do lead
- Auto-gera parcelas (40% sinal + 60% final)
- Auto-envia notificacao
- Deep link: lead convertido → navega para o projeto

**KPIs:**
- Total de leads
- Valor do pipeline
- Taxa de conversao
- Leads com acao hoje

**Filtros:** Hoje, Atrasados, Sem proxima acao, Alto valor, Indicacao

**Diferencial:** Dados do lead sao especificos de fotografia (data do evento, local, convidados) — nao e um CRM generico. A conversao automatica lead → projeto com parcelas e unica. Timeline de atividades rastreia cada ponto de contato.

---

### 6. CLIENTES

**O que e:** Base de dados de clientes com historico completo, analytics de gasto e rastreamento de status VIP.

**Informacoes por cliente:**
- Nome, email, telefone, cidade
- Total de projetos
- Total gasto (historico)
- Ultimo projeto
- Ultima interacao
- Status: VIP (laranja), Ativo (verde), Inativo (cinza)
- Tipo de evento mais frequente

**Funcionalidades:**
- Busca por nome
- Filtro por status (VIP, Ativo, Inativo)
- Ranking por valor gasto
- Exportacao de dados
- Historico completo de projetos

**Diferencial:** Flagging de VIP para clientes de alto valor. Historico de gastos para saber quem sao os clientes mais valiosos. Rastreamento de ultima interacao para reengajamento.

---

### 7. PORTAL DO CLIENTE

**O que e:** Pagina publica onde o cliente acompanha tudo sobre seu projeto — contrato, pagamentos, galeria e pedidos — sem precisar ligar para o fotografo.

**4 secoes visiveis ao cliente:**

**Secao 1 — Contrato:**
- Status (pendente / assinado)
- Valor total
- Data de assinatura
- Visualizacao do contrato

**Secao 2 — Pagamentos:**
- Cronograma de parcelas
- Status de cada parcela (pago / pendente / atrasado)
- Valor e data de vencimento
- Historico de pagamentos

**Secao 3 — Galeria:**
- Acesso a galeria de fotos
- Contagem de fotos
- Status de protecao (senha / publico)
- Disponibilidade para download

**Secao 4 — Pedidos:**
- Rastreamento de pedidos (impressoes, albuns, downloads)
- Status: pendente → producao → enviado → entregue

**Caracteristicas:**
- URL unica por projeto (link compartilhavel)
- Sem necessidade de login
- Design premium (mesma qualidade do app)
- Isolamento de dados por projeto

**Diferencial:** Experiencia white-label premium. O cliente ve um portal profissional, nao um dashboard cru. Self-service completo — reduz mensagens "quando ficam prontas as fotos?" drasticamente.

---

### 8. GALERIA & ENTREGAS

**O que e:** Sistema profissional de galeria para entrega de fotos com 4 modos de visualizacao, proofing (selecao do cliente), loja integrada e rastreamento de atividade.

**4 modos de visualizacao:**
1. **Grid** — Layout responsivo de cards
2. **Lista** — Itens em linha
3. **Timeline** — Cronologica
4. **Masonry** — Layout Pinterest-style (favorito dos fotografos)

**Funcionalidades da galeria:**
- Cards ricos com: foto de capa, contagem de fotos, visualizacoes, downloads, favoritos, nome do cliente, badges de status/privacidade
- Acoes rapidas: compartilhar, duplicar, arquivar, deletar
- Command Palette interno (Cmd+K)
- Modo de selecao com barra de acoes em lote
- Menu de contexto (clique direito)
- Quick Preview (barra de espaco)
- Navegacao por teclado (setas + Enter)
- Painel de filtros avancados (status, privacidade, intervalo de datas, contagem de fotos, visualizacoes, cliente, tipo)
- Filtros inteligentes com pills de filtro ativo
- Drag-and-Drop para reordenacao de colecoes via react-dnd (HTML5 + Touch backends)

**Componentes visuais especializados:**
- `gallery-status-badge` — Badge de status da galeria
- `gallery-privacy-badge` — Badge de nivel de privacidade
- `gallery-metric-pill` — Pill com metricas (views, downloads, favoritos)
- `share-link-bar` — Barra de compartilhamento de link
- `upload-dropzone` — Componente de upload com 4 estados (idle, dragover, uploading, complete) e barra de progresso

**Niveis de privacidade:**
- Publico — qualquer um com o link
- Senha — precisa de senha
- Privado — apenas convidados

**Status da galeria:**
- Rascunho
- Proofing (selecao do cliente)
- Final
- Entregue

**Aba de Analytics por galeria:**
- Grafico de tendencia de visualizacoes diarias (AreaChart)
- Heatmap de engajamento por foto (BarChart)
- Funil galeria-para-loja (conversao de visualizacao em pedido)
- Breakdown por dispositivo (PieChart — desktop, mobile, tablet)

**Rastreamento de atividade do cliente:**
- "Ana Oliveira abriu a galeria" (com timestamp)
- "Favoritou 12 fotos"
- "Baixou 5 fotos"
- "Compartilhou o link"

**"Para Fazer" — Task cards inteligentes:**
- Galerias para entregar
- Aguardando selecao do cliente
- Projetos aguardando galeria
- Links vencendo
- Downloads bloqueados

**Celebracao de entrega:** Animacao de confetti com canvas ao entregar galeria — celebra o momento com o fotografo.

**Diferencial:** 4 modos de visualizacao incluindo masonry. Rastreamento de atividade do cliente em tempo real (saber quando abriu, favoritou, baixou). Keyboard-driven UX para power users. Task cards inteligentes que mostram o que precisa de atencao. Analytics por galeria com funil de conversao.

---

### 9. GALERIA DO CLIENTE (Pagina Publica)

**O que e:** Pagina publica separada do painel de gerenciamento, onde o cliente final navega, favorita, seleciona e baixa suas fotos. Rota: `/galeria/cliente/:id`

**Caracteristicas:**
- Implementacao robusta com 1300+ linhas de codigo
- Layout proprio, sem sidebar do painel administrativo
- Interface dedicada ao cliente final
- Navegacao de fotos com favoritos e selecao
- Download de fotos (individual e em lote)
- Visualizacao otimizada para a experiencia do cliente
- Acesso por link compartilhado (com ou sem senha)

**Diferencial:** Separacao clara entre a interface de gerenciamento do fotografo e a experiencia do cliente. O cliente ve apenas o que importa — suas fotos — em um layout limpo e premium, sem distracao de menus administrativos.

---

### 10. FINANCEIRO

**O que e:** Gestao financeira completa 100% brasileira com 9 sub-abas cobrindo cada operacao financeira que um fotografo precisa.

**9 sub-abas:**

**1. Hoje (Centro de Execucao):**
- KPIs do dia
- Alertas de atraso
- Linhas de acao com niveis de urgencia:
  - Atrasada (vermelho) — acao imediata
  - Vence hoje (amarelo) — atencao
  - Pendencia (cinza) — acompanhar
- Acoes em lote: cobrar em lote, marcar como pago, emitir NF

**2. Receber (Contas a Receber):**
- Todas as entradas previstas
- Parcelas por projeto
- Filtros por status

**3. Pagar (Contas a Pagar):**
- Todas as despesas
- Categorias de gasto
- Controle de recibos

**4. Caixa (Fluxo de Caixa):**
- Visualizacao de fluxo de caixa
- Projecao de entradas e saidas
- Saldo previsto

**5. Conciliacao (Conciliacao Bancaria):**
- Cruzamento de pagamentos com extrato
- Match automatico
- Pendencias de conciliacao

**6. Cobranca:**
- Cobranca automatizada
- Templates de mensagem
- Historico de cobrancas
- Envio por WhatsApp/email

**7. Fiscal (NF-e):**
- Geracao de nota fiscal
- Gestao tributaria
- Historico de NFs

**8. Relatorios:**
- Graficos financeiros
- Tendencias
- Comparativos mes a mes

**9. Config:**
- Metodos de pagamento
- Configuracao fiscal
- Contas bancarias

**Sistema de parcelas:**
- Sinal (geralmente 40%)
- Parcelas intermediarias
- Parcela final (na entrega)
- Status: pendente, paga, atrasada, renegociada
- Metodos: PIX, cartao, dinheiro, transferencia, cheque

**KPIs:**
- A Receber
- A Pagar
- Saldo previsto
- Parcelas vencidas
- NFs pendentes

**Diferencial:** 100% BRASILEIRO. PIX integrado, boleto, sistema de parcelas (como fotografo realmente cobra), NF-e nativa, conciliacao bancaria. 9 sub-abas especializadas. Nao e um QuickBooks generico adaptado — foi construido para como o fotografo brasileiro cobra.

---

### 11. LOJA / PEDIDOS

**O que e:** Loja integrada na galeria onde clientes pedem impressoes, albuns, canvas e downloads digitais.

**Catalogo de produtos:**
- Impressao Fine Art (varios tamanhos, precos por tamanho)
- Canvas Premium
- Download Digital HD
- Album Fotografico
- Quadro Flutuante
- Fotolivro Pocket

**Funcionalidades:**
- Gerenciador de catalogo completo (CRUD)
- Cards de produtos com imagens, tamanhos, precos
- Categorias: Impressoes, Digital, Albuns
- Ativar/desativar produtos
- Disponibilidade por galeria
- Quantidade minima
- Precos por tamanho

**Pipeline de pedidos:**
- Pendente → Pago → Producao → Enviado → Entregue → Cancelado
- Detalhe do pedido com breakdown de itens
- Acoes: imprimir fatura, enviar email, gerar PDF, QR code

**KPIs:**
- Total de pedidos
- Receita
- Ticket medio
- Pendentes

**Notificacao em tempo real:** Quando um cliente faz um pedido pela galeria, aparece um toast no dashboard.

**Diferencial:** Transforma cada entrega de galeria em oportunidade de receita. O cliente navega, escolhe e pede diretamente da galeria — sem WhatsApp, sem email. Catalogo com precos por tamanho.

---

### 12. CONTRATOS

**O que e:** Gerenciamento de contratos digitais com templates por tipo de evento, preview A4, edicao e assinatura digital.

**4 templates prontos:**
1. **Casamento** — 12 clausulas especificas
2. **Corporativo** — 10 clausulas
3. **Ensaio Fotografico** — 8 clausulas
4. **Album & Impressoes** — 6 clausulas

**Status do contrato:**
- Rascunho
- Enviado
- Assinado
- Expirado

**Funcionalidades:**
- Preview do contrato em formato A4
- Editor completo de detalhes
- Assinatura digital com canvas de desenho
- Criar de template ou do zero
- Acoes: preview, enviar, download, copiar link, duplicar, reenviar, deletar
- Filtros por status + busca

**KPIs:**
- Total de contratos
- Assinados
- Pendentes
- Expirados

**Diferencial:** Templates especificos de fotografia com clausulas pre-escritas. Assinatura digital integrada — o cliente assina sem sair da plataforma. Nao precisa de DocuSign ou Adobe Sign separado.

---

### 13. WHATSAPP

**O que e:** Integracao completa com WhatsApp Business com interface dual-pane, respostas rapidas e contatos vinculados a projetos.

**Fluxo de conexao:**
1. Pagina de introducao
2. Scan de QR Code
3. Animacao de conexao
4. Conectado!

**Interface conectada:**
- KPIs: Conversas, Nao lidas, Contatos, Enviadas hoje
- Layout dual-pane: Lista de contatos (esquerda, 340px) + Chat (direita)
- Lista de contatos com busca, badges de nao lido, status online/away/offline, conversas fixadas
- Nome do projeto vinculado a cada contato
- Bolhas de mensagem com timestamps e confirmacoes de leitura (enviado/entregue/lido)
- 6 respostas rapidas pre-configuradas:
  - "Sua galeria esta pronta! Enviei o link por email"
  - "Confirmado! Ate la!"
  - "Obrigado pela preferencia!"
  - E mais 3...
- Input de mensagem com emoji, anexos, gravacao de voz

**Diferencial:** Contatos vinculados a projetos — cada conversa mostra de qual projeto o cliente faz parte. Respostas rapidas pensadas para fotografos. Design autentico do WhatsApp.

---

### 14. TIME / EQUIPE

**O que e:** Gerenciamento de equipe com papeis especificos de fotografia, status online, carga de trabalho e monitoramento de atividade.

**4 papeis especificos:**
1. **Admin** — Acesso total (icone Shield)
2. **Fotografo** — Producao e agenda (icone Camera)
3. **Editor** — Edicao e entrega (icone Palette)
4. **Atendimento** — CRM e clientes (icone Headphones)

**Por membro da equipe:**
- Nome, email, papel
- Status online: Online (verde) / Ausente (amarelo) / Offline (cinza)
- Projetos ativos
- Horas semanais
- Ultima atividade
- Especialidade

**5 niveis de permissao:**
- Admin
- Financeiro
- Atendimento
- Producao
- Contador

**Componentes visuais especializados:**
- `permission-role-badge` — Badge visual do papel/permissao
- `availability-pill` — Pill de disponibilidade do membro

**Diferencial:** Papeis especificos de fotografia (Fotografo, Editor, Atendimento) — nao e "Member" generico. Visibilidade de carga de trabalho para saber quem esta sobrecarregado.

---

### 15. RELATORIOS

**O que e:** Dashboard de analytics completo com graficos, rastreamento de receita, analise de origem de leads e performance de catalogo.

**Componentes:**
- 6 KPIs hero com indicadores de tendencia
- Grafico de area de receita (7d, 30d, 90d, 12m)
- Grafico donut de origem de leads (Instagram, Indicacao, Site, Anuncio)
- Grafico de barras horizontais dos top produtos
- Funil de vendas — leads por estagio do pipeline
- Top clientes por receita
- Tabela de performance do catalogo

**Diferencial:** Analytics especificos de fotografia — receita por tipo de evento, ROI por canal de marketing, performance do catalogo de produtos.

---

### 16. AUTOMACOES

**O que e:** Construtor visual de automacoes com regras trigger-condicao-acao, templates e logs de execucao.

**Estrutura:** Trigger → Condicao (opcional) → Acao

**Templates de automacao:**
- Auto-enviar link de galeria quando pronta
- Lembrete de parcela vencida
- Follow-up apos evento
- Notificacao de novo lead
- Lembrete de checklist pre-evento

**Funcionalidades:**
- Toggle ativo/inativo por regra
- Log de execucao com status (sucesso/erro/pulado)
- Acao "Executar agora" manual
- KPIs: Regras ativas, Execucoes hoje, Taxa de sucesso

**Diferencial:** Templates de automacao especificos para fluxos de fotografia. Nao e Zapier — e automacao embutida que entende o contexto do negocio.

---

### 17. INTEGRACOES

**O que e:** Hub de integracoes com terceiros com fluxo de conexao/desconexao, configuracao por integracao, webhooks e gestao de API keys.

**Categorias:**
- Produtividade (Google Calendar, etc.)
- Comunicacao (WhatsApp, Email)
- Pagamentos (PIX, gateways)
- Armazenamento (Cloud storage)
- Marketing (Instagram, Meta Ads)
- Automacao (webhooks, APIs)

**Status:** Conectado, Desconectado, Erro, Sincronizando

**Diferencial:** Integracoes pensadas para o ecossistema do fotografo brasileiro.

---

### 18. CONFIGURACOES

**O que e:** Central de configuracoes completa do estudio com multiplas secoes cobrindo todos os aspectos da plataforma.

**Secoes:**
- Conta & Assinatura
- Galeria (customizacao visual)
- Financeiro (metodos de pagamento, fiscal)
- Equipamentos
- Usuarios & Permissoes
- Templates
- Documentos
- Assinatura & Faturas
- Notificacoes
- Dominio
- Armazenamento
- SMTP
- Central de Ajuda

**Seguranca e 2FA:**
- Autenticacao de dois fatores (2FA)
- Logs de acesso com historico
- Gerenciamento de sessoes ativas

**Workflows de Producao:**
- 5 workflows reutilizaveis pre-configurados
- Customizaveis por tipo de evento

**Templates de Cobranca:**
- 3 templates de cobranca com auto-descontos e lembretes automaticos

**Templates de Mensagem:**
- 8 templates pre-construidos para WhatsApp, email e SMS

**Categorias Financeiras:**
- 14 categorias (receita e despesa) pre-configuradas

**Centros de Custo:**
- 4 centros de custo para controle granular

**Regras de Conciliacao:**
- Conciliacao automatica de pagamentos (Beta)

**Branding da Galeria:**
- Upload de logo
- Cores personalizadas
- Dominio custom
- Estilo visual da galeria

**Privacidade:**
- Privacidade padrao para novas galerias (publico, senha, privado)

**Watermark:**
- Watermark automatico para proofing
- Watermark para downloads

**Modelos de Contrato:**
- 3 modelos de contrato com clausulas editaveis
- Assinatura digital integrada

**Modelos de Documentos:**
- 6 modelos: orcamentos, recibos, termos, propostas, etc.

**PlanBanner:**
- Informacao do plano atual
- Data de renovacao
- Link para gerenciamento da assinatura

---

### 19. NOTIFICACOES (Centro de Notificacoes)

**O que e:** Sistema completo de notificacoes com pagina dedicada em `/notificacoes` e popover no topbar (NotificationCenter).

**Pagina de Notificacoes:**
- Pagina completa acessivel via sidebar
- Filtros por tipo: pagamentos, producao, leads, entregas, galerias, pedidos
- Acoes globais: marcar tudo como lido, limpar tudo
- Historico agrupado por tempo (hoje, ontem, esta semana, etc.)
- Deep links — cada notificacao leva ao modulo relevante

**KPIs:**
- Total de notificacoes
- Nao lidas
- Pagamentos (notificacoes financeiras)
- Producao (notificacoes de producao)

**6 tipos de notificacao:**
1. `lead_converted` — Lead convertido em projeto
2. `payment_received` — Pagamento recebido
3. `production_advanced` — Producao avancou de fase
4. `delivery_ready` — Entrega pronta
5. `gallery_created` — Galeria criada
6. `order_received` — Pedido recebido na loja

**3 niveis de prioridade:**
- Alta — destaque visual, acao imediata
- Media — atencao recomendada
- Baixa — informativo

**NotificationCenter (Popover no Topbar):**
- Icone de sino com badge de contagem
- Popover com lista das notificacoes mais recentes
- Acesso rapido sem sair da pagina atual
- Separado da pagina completa de notificacoes

**Diferencial:** Deep linking bidirecional — cada notificacao navega diretamente para o modulo relevante. Priorizacao inteligente para que o fotografo veja primeiro o que importa.

---

### 20. ARMAZENAMENTO (Gestao de Armazenamento)

**O que e:** Pagina completa de gestao de armazenamento em `/armazenamento` com visibilidade total do uso de espaco.

**Funcionalidades:**
- Barra de progresso de uso (GB usado / limite do plano)
- Breakdown por categoria:
  - Galerias — fotos de clientes
  - Projetos — arquivos de projeto
  - Backups — copias de seguranca
  - Temporarios — cache e arquivos temporarios
- Itens individuais com:
  - Contagem de arquivos
  - Tamanho total
  - Ultima modificacao
- Acoes de limpeza:
  - Remover itens individuais
  - Limpar cache temporario
  - Identificar arquivos grandes para revisao

**Diferencial:** Visao clara de onde o espaco esta sendo usado, com acoes de limpeza diretas. O fotografo sabe exatamente quanto cada galeria ou projeto ocupa.

---

### 21. EMAIL TEMPLATES (Editor de Templates de Email)

**O que e:** Editor visual de templates de email em `/email-templates` com sistema block-based e preview ao vivo.

**Editor visual block-based:**
- Blocos disponiveis:
  - Header (logo + titulo)
  - Texto (paragrafo com formatacao)
  - Imagem (com upload)
  - Botao (CTA com link)
  - Divisor (separador visual)
  - Footer (informacoes de contato + legal)
- Drag-and-drop para reordenar blocos
- Painel de preview ao vivo (atualiza em tempo real)

**Templates pre-construidos:**
1. **Galeria Pronta** — Notificar que a galeria esta disponivel
2. **Confirmacao de Pedido** — Confirmar pedido da loja
3. **Lembrete de Evento** — Lembrar cliente sobre evento proximo
4. **Lembrete de Cobranca** — Lembrar sobre parcela pendente

**CRUD completo:**
- Criar template do zero ou a partir de pre-construido
- Editar conteudo e layout
- Duplicar template existente
- Deletar template

**Variaveis de template:**
- `{{nome}}` — Nome do cliente
- `{{numero}}` — Numero do projeto/pedido
- `{{evento}}` — Nome/data do evento
- Substituicao automatica ao enviar

**Diferencial:** Editor visual intuitivo, nao precisa de HTML. Templates pensados para os fluxos reais do fotografo. Variaveis dinamicas para personalizacao.

---

### 22. EQUIPAMENTOS (Gestao de Equipamentos)

**O que e:** Inventario completo de equipamentos fotograficos com CRUD, registros de manutencao e alertas.

**Categorias de equipamento:**
- Cameras
- Lentes
- Iluminacao
- Acessorios
- Audio

**Campos por equipamento:**
- Marca e modelo
- Numero de serie
- Condicao (4 niveis): Excelente, Bom, Regular, Manutencao
- Data de compra
- Valor de aquisicao

**Registros de manutencao:**
- Tipos: Revisao, Calibracao, Reparo, Limpeza
- Prestador de servico
- Custo da manutencao
- Data de realizacao
- Proxima manutencao prevista

**Alertas:**
- Alerta de proxima manutencao programada
- Equipamentos em condicao "Manutencao" destacados

**Diferencial:** Controle patrimonial completo do estudio. Saber quanto cada equipamento custou, quando foi a ultima revisao e quando precisa da proxima. Essencial para seguros e controle financeiro.

---

## DASHBOARD — CENTRAL DE COMANDO

**O que e:** Centro de comando diario do fotografo. Saudacao personalizada, resumo do dia, widgets de acao.

**Componentes do dashboard:**
- Saudacao personalizada: "Bom dia, Marina" com linha de contexto
- KPIs: Projetos Ativos, A Receber (com destaque de atrasos), Producao em andamento, Compromissos de hoje
- Widget "Agenda de Hoje" com timeline (componente `today-timeline-item`)
- Widget "Tarefas Urgentes" com indicadores de SLA (componente `next-action-pill`)
- Widget "Atividades Recentes"
- Widget "Sugestao da Maia" (IA)
- Widget "Pedidos Recentes"
- Widget "Notificacoes"
- Banners de alerta inline
- Botoes de acao rapida: Cobrar, Agendar, Enviar Fotos, Novo Projeto
- Notificacao simulada de novo pedido (push)

**Cards "Explorar por Area":**
- Visao Geral, Producao, Financeiro, Agenda, Galeria, Projetos, CRM, Entregas
- Cada card com icone colorido, nome e preview de dado

**"Pergunte a Maia":**
- 4 sugestoes de pergunta
- Input para perguntar qualquer coisa
- "Ver instrucoes" para comandos slash

---

## FLUXOS ESPECIAIS

### Paywall Flow

Sistema completo de paywall para features premium com controle granular por plano.

**Componentes:**
- **PaywallProvider** — Provider com feature registry definindo quais features requerem qual plano
- **PaywallDrawerSheet** — Slide-over premium que aparece ao tentar acessar feature bloqueada
- **PaywallModalDialog** — Modal de upgrade com comparativo de planos

**Comportamento:**
- Modulos bloqueados mostram estado "locked" com visual elegante
- Callback de upgrade direciona para pagina de planos
- Configuracao por feature com planos requeridos (Core, Pro, Studio)

### Checkout Flow

- **CheckoutV4Page** — Pagina completa de checkout para assinatura de planos
- **SucessoV4Page** — Pagina de confirmacao pos-checkout
- Fluxo integrado com a tabela de precos

### Gallery Delivery Celebration

- Animacao de confetti com canvas ao entregar galeria
- Celebra o momento com o fotografo — reforco positivo na conclusao do trabalho

### Cross-module Sync (AppStore)

- **AppStore** com sessionStorage para sincronizacao de estado entre modulos
- Fluxo completo: lead → projeto → producao → financeiro → galeria → pedidos
- Quando um lead converte, os dados fluem automaticamente por todos os modulos relevantes

---

## FLUXO END-TO-END

```
1. CAPTAR → Lead chega (Instagram, Indicacao, Site)
      |
2. ORGANIZAR → CRM Pipeline (7 estagios)
      |
3. FECHAR → Proposta + Contrato Digital + Parcelas
      |
4. PLANEJAR → Projeto criado (5 abas) + Agenda + Checklist
      |
5. PRODUZIR → Pipeline de 7 fases + Equipe + Prazos
      |
6. COBRAR → PIX + Parcelas + NF-e + Cobranca automatica
      |
7. ENTREGAR → Galeria Premium + Selecao + Download
      |
8. VENDER → Loja de impressoes e albuns na galeria
      |
9. FIDELIZAR → Portal do Cliente + Pos-venda + Automacoes
```

---

## DESIGN & EXPERIENCIA

**Estetica:**
- Apple Premium — design limpo, editorial, sofisticado
- Tipografia: Instrument Serif (headlines), Inter (body), JetBrains Mono (dados)
- Cores: Dark ink #1D1D1F, Surface #F5F5F7, Gold accent #9C8B7A
- Dark mode completo em toda a aplicacao
- Animacoes spring-based (motion v12, importado como "motion/react")
- Glassmorphism sutil em paineis
- Zero transparencia (regra de ouro do design)

**Dark Mode:**
- **DarkModeProvider** com persistencia em localStorage
- **DarkModeToggle** animado (icones Sun/Moon com transicao suave)
- Hook `useDk()` utilizado em 40+ componentes para estilizacao condicional
- Cobertura completa em toda a aplicacao

**117+ componentes UI primitivos** no diretorio `ui/`, incluindo:
- `permission-role-badge`, `availability-pill`
- `production-stage-badge`, `production-action-row-item`
- `lead-stage-badge`, `lead-source-tag`, `lead-card`
- `gallery-status-badge`, `gallery-privacy-badge`, `gallery-metric-pill`
- `workflow-progress-pill`, `pipeline-stage-header`
- `share-link-bar`, `upload-dropzone`
- `subnav-segmented`, `today-timeline-item`, `next-action-pill`
- WidgetCard, WidgetSkeleton, WidgetEmptyState (Apple Kit)
- Apple-style drawer (slide-over panel)
- Apple-style modal
- Apple-style table
- Apple-style toast (Sonner)
- Editorial buttons magneticos
- Paywall drawer/modal premium

**Upload Dropzone:**
- Componente dedicado com 4 estados visuais:
  - Idle — area de drop com instrucoes
  - Dragover — destaque visual ao arrastar arquivo sobre a area
  - Uploading — barra de progresso com percentual
  - Complete — confirmacao com preview

**UX diferenciada:**
- Command Palette global (Cmd+K)
- Global Search (separado do Command Palette):
  - Hook `useGlobalSearch` indexando projetos, clientes, eventos, financeiro, galerias
  - `SearchResults` com resultados categorizados e icones por categoria
  - Busca unificada em todo o app
- Navegacao por teclado (atalhos em todo o app)
- Quick Preview (barra de espaco na galeria)
- Pull-to-refresh com `PullToRefreshIndicator` (estilo Apple para mobile)
- Skeleton loading (nao spinners)
- Dark mode automatico com toggle

**OnboardingTooltip/Banner:**
- Dicas contextuais de primeiro uso em cada pagina
- Dismissible pelo usuario
- Estado persistido em localStorage (nao reaparece apos fechar)
- Guia o fotografo nas primeiras interacoes com cada modulo

---

## MARKETING SITE (18 paginas V4)

O site de marketing usa o sufixo V4 e cobre toda a jornada do visitante ate a conversao:

**Paginas principais:**
- **LandingV4Page** — Pagina inicial com hero, features, depoimentos, CTA
- **RecursosV4Page** — Detalhamento de todos os recursos da plataforma
- **CasosV4Page** — Casos de sucesso de fotografos reais
- **PlanosV4Page** — Tabela comparativa de planos e precos
- **FaqV4Page** — Perguntas frequentes
- **SegurancaV4Page** — Detalhes sobre seguranca e privacidade dos dados

**Autenticacao:**
- **EntrarV4** — Login
- **CriarContaV4** — Registro
- **EsqueciSenhaV4** — Recuperacao de senha
- **VerificarEmailV4** — Verificacao de email

**Onboarding (pos-registro):**
- **BoasVindasV4** — Boas-vindas ao novo usuario
- **CriarStudioV4** — Configuracao do estudio (nome, tipo, preferencias)
- **PreferenciasV4** — Preferencias iniciais
- **ConcluirV4** — Conclusao do onboarding

**Checkout:**
- **CheckoutV4** — Pagina de pagamento
- **SucessoV4** — Confirmacao de compra

**Outros:**
- **QAV4** — Quality assurance / testes

---

## ONBOARDING

**Fluxo em 4 passos (V4):**
1. Boas-vindas (BoasVindasV4)
2. Criar estudio (CriarStudioV4 — nome, tipo, preferencias)
3. Preferencias (PreferenciasV4)
4. Concluir e comecar (ConcluirV4)

**Caracteristicas:**
- Barra de progresso visual
- Opcao "Pular configuracao"
- Design minimalista (520px centralizado, fundo branco)
- Verificacao de email
- Recuperacao de senha

---

## PRECOS

| | Core | Pro | Studio |
|---|---|---|---|
| **Mensal** | R$ 49 | R$ 99 | R$ 199 |
| **Anual** | R$ 39 | R$ 79 | R$ 159 |
| **Projetos** | 5 | Ilimitados | Ilimitados |
| **Producao** | Sim | Sim | Sim |
| **Agenda** | Sim | Sim | Sim |
| **Galeria** | 3 colecoes | Ilimitadas | Ilimitadas + Pro |
| **Financeiro** | Nao | Completo | Completo |
| **CRM** | Nao | Sim | Sim |
| **Portal Cliente** | Nao | Sim | Sim |
| **Relatorios** | Nao | Sim | Sim |
| **Armazenamento** | 5GB | 20GB | 50GB |
| **Usuarios** | 1 | 2 | Ate 10 |
| **Permissoes** | Nao | Nao | 5 papeis |
| **Automacoes** | Nao | Nao | Sim |
| **Maia IA** | Basica | Avancada | Completa |
| **Suporte** | Email | Prioritario | Prioritario |

**Add-ons:**
- Galeria Pro: +R$39/mes
- Equipe Extra: +R$29/membro
- +50GB Storage: +R$19/mes
- Automacao & IA: +R$49/mes

**Trial:** 14 dias gratis em qualquer plano. Sem cartao de credito.

---

## 15 DIFERENCIAIS COMPETITIVOS

1. **"6 apps em 1"** — Substitui WhatsApp + Planilhas + Trello + Drive + PIX manual + Email
2. **Financeiro 100% Brasileiro** — PIX, boleto, parcelas, NF-e, conciliacao bancaria
3. **Maia IA Contextual** — 8 especialidades, 16 comandos, entende cada area do negocio
4. **Controle de Sabados** — Crucial para fotografos de casamento
5. **Fluxo End-to-End** — Lead → Projeto → Producao → Financeiro → Galeria → Pedido
6. **Portal do Cliente** — Experiencia premium self-service
7. **Loja na Galeria** — Impressoes, albuns e downloads direto da entrega
8. **Design Apple-Quality** — UI premium que fotografos tem orgulho de mostrar
9. **WhatsApp Integrado** — Contatos vinculados a projetos
10. **Automacoes Inteligentes** — Follow-ups, cobrancas, notificacoes automaticas
11. **Contratos com Assinatura Digital** — Templates especificos + assinatura sem sair do app
12. **Dark Mode Completo** — DarkModeProvider com 40+ componentes, toggle animado
13. **117+ Componentes UI** — Biblioteca de componentes especializados para fotografia
14. **Paywall Inteligente** — Upgrade flow premium com feature gating por plano
15. **Cross-module Sync** — Dados fluem automaticamente entre todos os modulos

---

## TECNOLOGIA

- **Frontend:** Vite + React + React Router 7 + Tailwind CSS
- **Animacoes:** motion v12 (rebranded Framer Motion), importado como "motion/react"
- **Backend:** Supabase (Auth, DB, Storage, Edge Functions)
- **IA:** Claude Haiku 4.5 (Maia — 16 tools)
- **Deploy:** Vercel (app.essyn.studio)
- **Design:** Figma
- **Banco:** PostgreSQL (via Supabase) com RLS
- **Drag-and-Drop:** react-dnd (HTML5 + Touch backends)
- **Graficos:** Recharts (AreaChart, BarChart, PieChart)
- **25+ tabelas** no banco de dados
- **25k+ linhas** de codigo fonte
- **22+ modulos** funcionais
- **117+ componentes** UI primitivos
