## Defeitos Identificados

### H1 - Como usuário eu gostaria de poder acessar o sistema via tela de login para utilizar as funcionalidades.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H1-001**    | Critérios de aceitação | Removida opção de login sem validação. Agora há autenticação mínima obrigatória para maior segurança. | Inconsistência |
| **H1-002**    | Critérios de aceitação | Login rápido agora especifica uso de autenticação biométrica e por PIN, eliminando a ambiguidade. | Ambiguidade |
| **H1-003**    | Regras de negócio | Restrição de e-mail apenas Gmail removida. Agora aceita múltiplos domínios com validação. | Informação Estranha |
| **H1-004**    | Regras de negócio | Senhas podem conter caracteres especiais, reforçando segurança sem limitar o usuário. | Fato Incorreto |
| **H1-005**    | Regras de negócio | Senhas aleatórias continuam permitidas, mas agora há recomendação para armazenamento seguro e recuperação eficiente. | Omissão |

### H2 - Como usuário eu gostaria que o sistema tivesse uma tela de cadastro para inserir minhas informações.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H2-006**    | Critérios de aceitação | Campos de nome do cachorro e tipo sanguíneo agora são opcionais, evitando obrigatoriedade inadequada. | Informação Estranha |
| **H2-007**    | Critérios de aceitação | Validação redundante de dados eliminada para melhorar eficiência no processo de cadastro. | Inconsistência |
| **H2-008**    | Regras de negócio | Especificado claramente o propósito do tipo sanguíneo no sistema, garantindo maior transparência. | Ambiguidade |
| **H2-009**    | Regras de negócio | Limitação de idade revisada para permitir maior flexibilidade conforme contexto de uso do sistema. | Informação Estranha |
| **H2-010**    | Regras de negócio | Nome do cachorro agora pode ser preenchido posteriormente sem conflito com requisitos anteriores. | Inconsistência |

### H3 - Como administrador do sistema, gostaria de recuperação de senha para poder recuperar meu acesso em caso de esquecimento.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H3-011**    | Critérios de aceitação | Métodos de recuperação de senha agora têm ordem de prioridade e verificação de segurança clara. | Ambiguidade |
| **H3-012**    | Critérios de aceitação | Termo "redefinição moderna e automática" foi substituído por uma definição técnica específica. | Informação Estranha |
| **H3-013**    | Critérios de aceitação | O sistema agora impede exibição de senha quando o e-mail não existir, garantindo mais segurança. | Fato Incorreto |
| **H3-014**    | Regras de negócio | Frase de segurança agora exige configuração prévia com regras de validação mínimas. | Omissão |
| **H3-015**    | Regras de negócio | Intervalo entre solicitações de redefinição ajustado para evitar abusos e ataques automatizados. | Inconsistência |

### H4 - Como médico, gostaria que o sistema tenha uma tela para cadastro de hábitos alimentares dos usuários, para poder avaliar sua rotina.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H4-016**    | Critérios de aceitação | Usuário não precisa informar todas as refeições dos últimos 30 dias; agora pode inserir registros parciais. | Informação Estranha |
| **H4-017**    | Critérios de aceitação | Critérios para análise de hábitos alimentares e sugestões de dieta foram claramente definidos. | Ambiguidade |
| **H4-018**    | Regras de negócio | Separação entre comida e bebida agora tem justificativa baseada em impacto nutricional. | Informação Estranha |
| **H4-019**    | Regras de negócio | O sistema agora permite que o usuário registre dias posteriores mesmo sem preenchimento de todos os anteriores. | Inconsistência |
| **H4-020**    | Regras de negócio | Definição de tipo de dieta não é mais obrigatória antecipadamente; o sistema sugere baseado nos hábitos registrados. | Omissão |

### H5 - Como usuário eu gostaria de poder inserir minhas atividades físicas para acompanhar minha evolução mensal.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H5-021**    | Critérios de aceitação | Removida opção "voar" das atividades físicas, substituída por um conjunto de exercícios reais. | Fato Incorreto |
| **H5-022**    | Critérios de aceitação | Sugestões de atividades agora incluem margem de erro ajustável e explicação técnica de como são calculadas. | Informação Estranha |
| **H5-023**    | Critérios de aceitação | Definição mais clara de "registro consistente", incluindo frequência mínima e critérios de validação. | Ambiguidade |
| **H5-024**    | Regras de negócio | A margem de erro de 5% foi especificada para determinar impacto em recomendações baseadas em dados. | Inconsistência |
| **H5-025**    | Regras de negócio | Explicado o que caracteriza inserção rápida e intuitiva de dados, com critérios de experiência de usuário. | Omissão |
