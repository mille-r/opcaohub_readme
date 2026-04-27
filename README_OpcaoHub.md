# 🟢 Opção Hub

**Opção Hub** é o portal central de ferramentas digitais desenvolvidas para a Opção Móveis. Ele reúne em um único lugar todos os sistemas criados para facilitar o dia a dia da assistência técnica — sem precisar lembrar de vários links, abrir múltiplas abas ou usar sistemas diferentes.

> Funciona como um site com menu lateral, onde cada opção leva diretamente a um dos sistemas integrados. Pode ser acessado pelo computador ou pelo celular.

---

## ✨ Recursos próprios do Hub

Além de ser a porta de entrada para todos os sistemas, o Hub tem recursos próprios que tornam o uso do dia a dia mais prático:

- **🤖 Assistente IA (Marquinhos)** — um assistente de inteligência artificial treinado com os processos, regras e casos da assistência técnica da Opção Móveis. Você pode perguntar sobre procedimentos, prazos, regras de aprovação de DVs, casos específicos e muito mais — sem precisar perguntar para ninguém ou procurar em documentos.
- **📧 E-mail dos Fabricantes** — lista completa de e-mails de fabricantes e representantes cadastrados, com busca e botão para copiar o contato com um clique. Sempre atualizada e acessível de qualquer lugar.
- **🗒️ Notas Rápidas** — bloco de notas pessoal dentro do Hub para anotar lembretes, observações e pendências sem sair da tela.
- **📢 Avisos Administrativos** — administradores podem publicar comunicados que aparecem na tela inicial para todos os usuários ao abrir o Hub.
- **⭐ Favoritos** — qualquer sistema pode ser marcado como favorito e aparece no topo do menu para acesso rápido, com ordem personalizável por arrastar.
- **⌨️ Atalhos de teclado** — navegue entre os sistemas sem usar o mouse (Alt+1 ao Alt+7, Ctrl+K para busca rápida).
- **🌙 Modo escuro** — alterna entre tema claro e escuro com um clique.
- **📋 Histórico de atualizações** — registro de todas as novidades e melhorias lançadas em cada versão.

---

## 🗂️ Sistemas integrados

O menu lateral está organizado em três seções:

### Aplicativos
| Sistema | O que faz em uma linha |
|---|---|
| 📦 [Estoque da Assistência](#-estoque-da-assistência) | Controle de peças em estoque com rastreabilidade completa de movimentações |
| 📋 [Controle de Assistências](#-controle-de-assistências) | Registro e acompanhamento das ordens de assistência em tempo real |
| 📤 [Assistências Solicitadas](#-assistências-solicitadas) | Acompanhamento das assistências enviadas para os fabricantes |

### Planilhas
| Sistema | O que faz em uma linha |
|---|---|
| 📦 [Separação](#-separação) | Controle de separação de cargas por motorista e cidade, com mensagem automática de status |
| 🛒 [E-commerce](#-e-commerce) | Controle de etiquetas e assistências de pedidos do e-commerce |
| 🚚 Vale Frete | Controle de vales-frete emitidos |
| 📋 [Recebimento de Assistências](#-recebimento-de-assistências) | Registro de peças recebidas dos fabricantes |
| 📅 Agenda de Cargas | Agendamento e controle de cargas |
| 📋 NF de Devolução | Controle de notas fiscais de devolução |

### Grades
Acesso direto às grades de entrega das transportadoras parceiras: **Dominalog**, **Granado**, **Lima** e **RX**.

---

## 📦 Estoque da Assistência

**O problema que resolve:** O estoque de peças da assistência técnica era controlado de forma manual e sem registro formal. Não havia como saber quem retirou uma peça, quando, para qual assistência, ou qual era o saldo real disponível.

**O que o sistema faz:**

Aplicativo web e mobile para controlar todas as peças disponíveis para atender as ordens de assistência técnica. Cada movimentação exige o PIN pessoal do responsável, garantindo que tudo fique registrado com nome, data e motivo.

---

### Peças de Assistência

A tela principal mostra todos os fabricantes cadastrados. Ao clicar em um fabricante, ele expande e mostra os produtos. Ao clicar em um produto, abre o painel com todas as peças e seus respectivos saldos em estoque.

- **Busca** por nome do produto, código interno ou código do fabricante.
- **Filtro** para mostrar apenas fabricantes que têm peças cadastradas.
- **Adicionar estoque:** registra a entrada de uma ou mais unidades de uma peça. Requer confirmação por PIN.
- **Retirar do estoque:** registra a saída de peças, com campo de observação para identificar para qual finalidade foram retiradas. Requer PIN.
- **Cadastrar nova peça:** adiciona uma nova peça ao produto (número da peça, descrição e quantidade inicial).

---

### Devolvidos ao Estoque

Registra produtos que retornaram ao estoque geral após uma assistência — por exemplo, um produto que foi separado mas não foi utilizado.

- Exibe o histórico das últimas 50 devoluções com produto, quantidade, responsável e data.
- Registros podem ser excluídos com confirmação por PIN.

---

### Transferências

Registra produtos retirados do estoque para atender diretamente uma assistência específica, vinculando o produto ao número da assistência. Enquanto a transferência está ativa, o produto aparece como "em uso".

- O botão **Devolver** encerra a transferência (produto voltou ao estoque).
- Exibe as últimas 100 transferências com produto, número da assistência, responsável e data.

---

### Histórico de Movimentações

Registro completo e permanente de tudo que aconteceu no estoque: entradas, saídas, exclusões, transferências e devoluções.

- Filtros por tipo de ação (entrada, saída, exclusão, estoque, transferências).
- Busca por texto dentro do campo de observação.
- Cada registro mostra: tipo da ação, fabricante, produto, peça, quantidade, responsável e data/hora exata.

---

### Analytics

Painel com indicadores de movimentação do estoque:

- Total de peças retiradas e adicionadas no mês atual.
- Total de transferências realizadas e devolvidas.
- Ranking das 5 peças mais movimentadas nos últimos 30 dias.
- Ranking das 5 peças mais retiradas nos últimos 30 dias.

---

### Configurações

- Cadastro e gerenciamento de fabricantes.
- Cadastro de usuários com PIN individual de 4 dígitos.
- **Importação em massa via CSV:** envie uma planilha com código do produto, código do fabricante, descrição e marca — o sistema importa todos os produtos automaticamente, cria os fabricantes que ainda não existem e ignora produtos já cadastrados. Compatível com diferentes formatos de planilha (separador por vírgula, ponto e vírgula ou tabulação, codificações UTF-8 e ISO-8859-1).

---

## 📋 Controle de Assistências

**O problema que resolve:** O acompanhamento das ordens de assistência era fragmentado e sem visibilidade central. Não havia registro digital do que estava pronto para entrega, o que estava aguardando envio para fábrica, ou o histórico completo das assistências processadas.

**O que o sistema faz:**

Sistema com login individual para registro e acompanhamento completo das ordens de assistência técnica. Funciona em **tempo real** — qualquer alteração feita por um usuário aparece imediatamente na tela de todos os outros.

---

### Registro de nova assistência

Formulário no lado esquerdo da tela para registrar uma nova OS:

- Número da OS, nome do cliente, descrição do produto e defeito.
- Marcação se é um **pedido de fábrica** (produto a ser enviado ao fabricante).
- Marcação se é um pedido de **e-commerce**, com campos de dimensões (altura, largura, comprimento, peso, volume) para facilitar a emissão de etiqueta.

---

### Acompanhamento das assistências (lado direito)

Lista as assistências registradas, organizadas por data, em três abas:

- **Prontas:** assistências verificadas e aguardando entrega ao cliente.
- **Fábrica:** assistências cujo produto precisa ser enviado ao fabricante.
- **E-commerce:** assistências originadas de pedidos de e-commerce.

Ações disponíveis por assistência:

- **Verificar / Desverificar:** marca a assistência como conferida, registrando quem verificou e quando. Administradores podem remover a verificação se necessário.
- **Embalar (Fábrica):** registra que o produto foi embalado para envio ao fabricante, com data e responsável. Para e-commerce, solicita as dimensões da embalagem antes de confirmar.
- **Editar:** altera os dados da assistência.
- **Excluir:** remove a assistência com confirmação.
- **Exportar para Excel:** gera uma planilha `.xlsx` com todas as assistências do período filtrado.

---

### Pesquisa

Busca em todos os registros históricos por número de OS, nome do cliente ou qualquer campo registrado.

---

### Analytics

Painel com gráficos e indicadores de desempenho:

- Total de assistências por período (diário, semanal, mensal).
- Volume por dia da semana e tendência ao longo do tempo.
- Percentual de assistências de e-commerce.
- Dia com maior volume de embalagens registradas.

---

### Perfis de acesso

| Perfil | O que pode fazer |
|---|---|
| **Administrador** | Acesso completo, incluindo desverificação e gerenciamento de usuários |
| **Usuário comum** | Registro, verificação e embalagem de assistências |
| **E-commerce Viewer** | Visualização restrita à aba de e-commerce |

---

## 📤 Assistências Solicitadas

Módulo que exibe o acompanhamento das assistências que foram solicitadas e enviadas para os fabricantes, permitindo visualizar o status de cada solicitação sem precisar navegar para outra tela.

---

## 📦 Separação

**O problema que resolve:** A separação de produtos nas cargas diárias era anotada em papel ou de forma informal, sem registro de qual assistência foi para qual motorista ou cidade, sem controle de conferência e sem padronização na comunicação do status para o cliente.

**O que o sistema faz:**

Sistema para organizar e registrar a separação de mercadorias por carga. Cada separação tem motoristas, cidades e os números das assistências que vão em cada carga — com controle de conferência item a item e geração automática de mensagem de status para enviar ao cliente.

---

### Lista de separações

- Exibe todas as separações salvas com data e número.
- Busca por número de separação ou data.
- Opções de abrir, editar ou excluir cada separação.

---

### Dentro de uma separação

- **Motoristas:** adicione quantos motoristas ou transportadoras forem necessários.
- **Cidades:** cada motorista tem suas cidades de entrega.
- **Assistências:** cada cidade tem os números das assistências que seguem na carga.
- **Conferência por item:** três estados alternados com um clique — ✅ conferido / ❌ com problema / ⬜ pendente.
- **Mensagem automática:** ao marcar um item como conferido, a mensagem de status é gerada automaticamente no formato correto, pronta para copiar e enviar ao cliente:
  - *"Seguiu via Dominalog."*
  - *"Seguiu na carga do motorista João."*
  - *"Seguiu na carga do motorista do Depósito."*
- **Copiar mensagem:** um clique copia o texto gerado.
- **Imprimir:** gera uma visualização formatada da separação para impressão.

Transportadoras reconhecidas automaticamente: Dominalog, Jadlog, Granado, Lima, RX e Depósito.

---

### Analytics

Gráficos com estatísticas das separações: volume por período, transportadoras mais utilizadas, ranking de motoristas, tendências e indicadores de performance.

---

## 🛒 E-commerce

**O problema que resolve:** O controle das etiquetas e do status das assistências de pedidos do e-commerce era feito de forma manual e descentralizada, sem visibilidade de cada etapa do processo — do cadastro até a finalização.

**O que o sistema faz:**

Sistema para controlar o fluxo completo das assistências de e-commerce, da emissão da etiqueta até a finalização.

---

### Abas de acompanhamento

| Aba | O que mostra |
|---|---|
| **Emitir etiqueta** | Assistências que ainda precisam de etiqueta |
| **Etiqueta emitida** | Assistências com etiqueta emitida mas não colada |
| **Aguardando** | Etiqueta emitida e colada, aguardando finalização |
| **Finalizadas** | Assistências concluídas |

Em cada aba é possível selecionar múltiplos registros para aplicar ações em lote (finalizar, excluir). Filtro por transportadora e busca por qualquer campo.

---

### E-commerce Consulta

Ferramenta para responder clientes que perguntam sobre o andamento do pedido:

- Adicione números de assistências para consulta rápida de status.
- O status é cruzado automaticamente com a base de dados.
- A resposta no formato padrão é gerada automaticamente ("Etiqueta emitida via Dominalog.", "Assistência aguardando emissão de etiqueta/NF.").
- O texto da resposta pode ser editado antes de copiar.

---

## 📋 Recebimento de Assistências

**O problema que resolve:** O controle das peças enviadas pelos fabricantes era feito em planilhas manuais, sem visibilidade clara de quais peças chegaram, quais não vieram e quais já foram processadas.

**O que o sistema faz:**

Sistema para registrar e acompanhar o recebimento de peças enviadas pelos fabricantes para atender as ordens de assistência.

---

### Aba: Recebimentos

- Lista todos os recebimentos registrados com fabricante, NF, número de assistência, data e status.
- **Agrupamento dinâmico:** visualize os registros por data de recebimento ou por fabricante, alternando com um botão.
- **Edição direta na tabela:** clique em qualquer campo para editar sem precisar abrir janelas. Enter confirma, Escape cancela.
- **Status por peça** com indicação visual: `Pendente`, `Finalizada`, `Impresso`, `Não veio (não cobrado)`, `Não veio (cobrado)`.
- **Resumo no topo:** contagem de registros por status sempre visível.
- **Novo recebimento** em duas etapas: primeiro informa fabricante e data, depois adiciona as peças (NF + número de assistência) uma a uma antes de salvar tudo de uma vez.
- Busca por número de assistência, NF ou fabricante.

---

### Aba: Analytics

Gráficos e métricas de recebimentos por fabricante e por período.

---

## 💡 Como acessar

O Opção Hub é acessado por um link no navegador — no computador ou no celular. Após o login com e-mail e senha, o sistema detecta automaticamente o perfil do usuário e libera os módulos correspondentes.

**Não é necessário instalar nada.** Basta abrir o link e fazer login.

---

## ⚠️ Observações

- Todos os sistemas do Hub compartilham o mesmo banco de dados, garantindo que as informações estejam sempre atualizadas e sincronizadas em tempo real entre todos os usuários simultaneamente.
- O acesso é protegido por login individual. Algumas ações dentro dos apps exigem confirmação por PIN pessoal, garantindo rastreabilidade de quem fez cada movimentação.
- O sistema funciona em computadores e celulares. A interface se adapta automaticamente ao tamanho da tela.

---

*Idealizado e desenvolvido por Rodrigo Miller — Opção Móveis*
