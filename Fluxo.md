# Lógica de Usuários e Fluxo do Frontend

## Papéis de Usuário e Hierarquia

1. **Squad:** Membros fundadores da tecnologia com acesso a todas as funcionalidades e eventos. Algumas ações críticas requerem a validação de pelo menos 3 membros do Squad, funcionando como um conselho.  
2. **Team Member:** Colaboradores da plataforma com funções gerenciais. Podem ajudar na administração geral, mas têm menos privilégios que o Squad.  
3. **Client:** Promotor do evento. Responsável por criar e gerenciar eventos dentro da plataforma. Pode ser também um Team Member ou Squad.  
4. **Staff:** Equipe de apoio do evento. Auxilia na organização e execução do evento específico. Designados pelo Client.  
5. **User:** Participante do evento. Pode gerenciar seus NFTs e participar de eventos.

*Nota: Todos os papéis acima são atribuídos a pessoas físicas e um usuário pode acumular mais de uma designação (por exemplo, um Squad pode ser User em um evento).*

**Enterprise:** Instituição promotora do evento. Possui um Client como administrador e pode designar Staff. A Enterprise pode comprar créditos, criar eventos, atividades, publicar ativos (imagens/cards), gerenciar certificados, etc. Tem acesso apenas aos próprios eventos.

## Fluxo do Frontend por Papel de Usuário

### User (Participante do Evento)

**Funções Principais:**

* Cadastro/Login: Usuário se cadastra usando seu e-mail (ID único) e verifica o e-mail.

**Dashboard Pessoal:**

* Visualizar seus NFTs.  
* Visualizar eventos inscritos.  
* Explora eventos por interesse e geolocalização.

**Participação em Eventos:**

* Inscrever-se em eventos disponíveis.  
* Fazer check-in em eventos/atividades.  
* Resgatar NFTs (certificados, cards, etc.) após participação.

**Validação de NFTs:**

* Acessar área pública para validar autenticidade de NFTs (mesmo sem login).

**Fluxo de Uso:**

1. Acesso à Plataforma: Usuário acessa o site e visualiza eventos disponíveis.  
2. Cadastro/Login: Se necessário, o usuário se cadastra e verifica seu e-mail.  
3. Inscrição em Evento: Seleciona um evento e se inscreve.  
4. Participação: No dia do evento, faz check-in (pode ser via QR Code ou self-service).  
5. Resgate de NFTs: Após o evento ou atividade, resgata os NFTs associados.  
6. Gerenciamento de NFTs: Visualiza e gerencia seus NFTs no dashboard.

### Staff (Equipe de Apoio do Evento)

**Funções Principais:**  
Acesso ao Painel do Evento:

* Visualizar detalhes do evento.  
* Gerenciar check-ins dos participantes.

Gerenciamento de Atividades:

* Auxiliar na criação e configuração de atividades dentro do evento.  
* Publicar ativos relacionados às atividades (se autorizado).

Suporte aos Participantes:

* Ajudar usuários com dúvidas ou problemas antes e durante o evento.

**Fluxo de Uso:**

1. Login: Faz login na plataforma.  
2. Acesso ao Evento: Acessa o painel do evento ao qual foi designado.  
3. Gerenciamento:  
* Monitora check-ins.  
* Auxilia na execução das atividades.  
4. Interação com Participantes: Fornece suporte conforme necessário.

### Client (Promotor do Evento)

**Funções Principais:**  
Gerenciamento de Enterprise:

* Configurar perfil da Enterprise.  
* Gerenciar créditos (comprar créditos para usar serviços da plataforma).

Criação e Gerenciamento de Eventos:

* Criar novos eventos.  
* Configurar detalhes do evento (datas, locais, descrição).  
* Criar atividades dentro dos eventos.

Gerenciamento de Equipe:

* Designar Staff para eventos.  
* Atribuir permissões específicas.

Publicação de Ativos:

* Carregar imagens/cards para eventos, atividades e palestrantes.  
* Editar modelos/mockups de certificados.

Visualização de Relatórios:

* Acessar estatísticas do evento (número de participantes, check-ins, NFTs resgatados).

**Fluxo de Uso:**

1. Login: Faz login na plataforma.  
2. Configuração da Enterprise:  
* Atualiza informações da instituição.  
* Gerencia créditos.  
3. Criação de Evento:  
* Cria um novo evento e define suas configurações.  
* Adiciona atividades e define detalhes.  
4. Gestão de Equipe:  
* Convida e designa Staff para o evento.  
5. Publicação de Ativos:  
* Carrega imagens e modelos necessários.  
6. Monitoramento:  
* Acompanha inscrições e participação.  
* Gera certificados/NFTs.

### Team Member (Colaborador da Plataforma)

**Funções Principais:**  
Suporte Geral:

* Auxiliar no gerenciamento geral da plataforma.

Acesso a Eventos:

* Visualizar e gerenciar todos os eventos (ou conforme permissões).

Moderação:

* Aprovar ou revisar eventos criados por Clients (faz sentido?).

Suporte a Clients e Staff:

* Ajudar com problemas técnicos, suporte ou dúvidas.

**Fluxo de Uso:**

1. Login: Acessa a plataforma com credenciais de Team Member.  
2. Painel de Controle:  
   Visualiza visão geral da plataforma.  
3. Atividades:  
   Oferece suporte onde necessário.  
   Modera conteúdo e eventos.

### Squad (Membros Fundadores)

**Funções Principais:**  
Acesso Total:

* Acesso a todas as funcionalidades e eventos.

Validação de Ações Críticas:

* Participam da validação de ações que requerem aprovação (mínimo de 3 membros).

Gerenciamento de Plataforma:

* Tomam decisões estratégicas.  
* Gerenciam configurações globais.

Supervisão:

* Monitoram a atividade de outros papéis.  
* Garantem a segurança e integridade da plataforma.

Fluxo de Uso:

1. Login: Acessa com credenciais de Squad.  
2. Painel Avançado:  
   Acesso a todas as áreas da plataforma.  
3. Validações:  
   Recebem notificações de ações que requerem aprovação.  
   Validam ou rejeitam ações críticas.  
4. Gerenciamento:  
   Ajustam configurações da plataforma.  
   Supervisionam atividades.

### Visitante (Não Logado)

**Funções Principais:**  
Validação de NFTs:

* Acesso à área pública para verificar a autenticidade de um NFT.

Exploração de Eventos:

* Visualizar eventos disponíveis (com limitações).

Cadastro:

* Opção de se registrar na plataforma.

**Fluxo de Uso:**

1. Acesso à Plataforma: Entra no site sem estar logado.  
2. Validação de NFT:  
   Acessa a ferramenta de validação.  
   Insere dados necessários (código ou QR-Code) para verificar um NFT.  
3. Exploração:  
   Navega pelos eventos públicos.  
4. Cadastro Opcional: Decide se cadastrar para participar de eventos.

## Considerações Gerais do Frontend

* Design Responsivo: Interface adaptável para dispositivos móveis e desktops.  
* Segurança:  
  Verificação de e-mail no cadastro.  
  Autenticação segura.  
  Permissões definidas por papel.  
* Usabilidade:  
  Interfaces claras e intuitivas.  
  Feedback ao usuário em ações (ex: confirmações, erros).  
* Navegação:  
  Menu adaptativo conforme o papel do usuário.  
  Acesso rápido às principais funções.

### Fluxo de Navegação

1. Página Inicial:  
   Apresentação da plataforma.  
   Opção de login ou cadastro.  
   Eventos em destaque.  
2. Login/Cadastro:  
   Formulário de login.  
   Opção para recuperar senha.  
   Cadastro com verificação de e-mail.  
3. Painel do Usuário:  
   Diferenciado conforme o papel.  
   Acesso às funções principais.  
   Notificações (ex: eventos próximos, ações pendentes).  
4. Eventos:  
   Listagem de eventos disponíveis.  
   Detalhes do evento.  
   Opção de inscrição.  
5. Validação de NFT:  
   Ferramenta acessível publicamente.  
   Campo para inserir identificador do NFT.  
   Exibe informações de autenticidade.  
6. Administração (para Clients, Staff, Team Members, Squad):  
   Gestão de eventos e atividades.  
   Gerenciamento de usuários e equipes.  
7. Configurações e relatórios.

### Fluxo de Resgate de NFTs

1. Participação no Evento/Atividade:  
   Usuário faz check-in no evento ou atividade.  
   Pode ser via QR Code, código ou (?) Credenciamento \- presença registrada por Staff. (?)  
2. Geração de NFT:  
   Após confirmação de participação, sistema gera o NFT correspondente.  
   Pode ser imediato ou após o evento.  
3. Notificação ao Usuário:  
   Usuário é notificado (via e-mail ou dentro da plataforma) que o NFT está disponível.  
4. Resgate do NFT:  
   Usuário acessa seu dashboard.  
   Visualiza o NFT e pode realizar ações, como visualizar detalhes, compartilhar, etc.  
5. Exportação NFT:  
   Usuário solicita exportação  
   Confirma senha de login  
   Recebe código de validação por e-mail  
   Confirma operação e declara que esta ciente dos riscos  
   Gera em tela a chave privada e opções de transferência

### Áreas de Validação de NFTs

* Acesso Público:  
  Disponível na página inicial ou em menu dedicado.  
  Permite que qualquer pessoa verifique a autenticidade de um NFT emitido pela plataforma.  
* Processo de Validação:  
  Usuário insere o identificador do NFT ou QR-Code.  
  O sistema verifica no blockchain a autenticidade e exibe informações relevantes.

