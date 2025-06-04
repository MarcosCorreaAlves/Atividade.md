## Defeitos Identificados

### H1 - H1 - Como usuário eu gostaria de poder acessar o sistema via tela de login para poder utilizar as funcionalidades.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H1-001**    | Critérios de aceitação | O critério que permite login sem validação em casos de pressa pode comprometer a segurança. | Inconsistência |
| **H1-002**    | Critérios de aceitação | O requisito sobre login rápido em qualquer lugar é muito vago, sem especificações técnicas claras. | Ambiguidade |
| **H1-003**    | Regras de negócio | A exigência de que o e-mail seja do Gmail limita os usuários, sem justificativa clara. | Informação Estranha |
| **H1-004**    | Regras de negócio | A regra que impede caracteres especiais na senha pode reduzir a segurança do sistema. | Fato Incorreto |
| **H1-005**    | Regras de negócio | Permitir senhas aleatórias pode dificultar a memorização pelos usuários, afetando a experiência de uso. | Omissão (não considera facilidade de uso) |

### H2 - Como usuário eu gostaria que o sistema tivesse uma tela de cadastro para inserir minhas informações.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H2-006**    | Critérios de aceitação | Exigir que todos os usuários preencham nome do cachorro e tipo sanguíneo pode ser inviável, pois alguns podem não ter essas informações. | Informação Estranha |
| **H2-007**    | Critérios de aceitação | A validação dos dados é feita duas vezes sem justificativa clara, o que pode gerar redundância no processo. | Inconsistência |
| **H2-008**    | Regras de negócio | O campo "Tipo sanguíneo é muito importante" é vago e não especifica claramente sua relevância para o sistema. | Ambiguidade |
| **H2-009**    | Regras de negócio | A restrição da idade para no máximo 60 anos pode ser inadequada, dependendo do contexto de uso do sistema. | Informação Estranha |
| **H2-010**    | Regras de negócio | Permitir que o nome do cachorro seja preenchido posteriormente contradiz o requisito anterior que o define como obrigatório. | Inconsistência |

### H3 - Como administrador do sistema, gostaria de recuperação de senha para poder recuperar meu acesso em caso de esquecimento.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H3-011**    | Critérios de aceitação | O sistema deve enviar a senha para múltiplas formas de contato, mas não especifica qual método tem prioridade ou se há segurança suficiente para cada opção. | Ambiguidade |
| **H3-012**    | Critérios de aceitação | O critério afirma que a redefinição de senha será moderna e automática, mas não define o que caracteriza "moderna". | Informação Estranha |
| **H3-013**    | Critérios de aceitação | O sistema mostrará a nova senha mesmo quando o e-mail não existir, o que pode comprometer a segurança. | Fato Incorreto |
| **H3-014**    | Regras de negócio | O requisito exige que a frase de segurança seja informada, mas não especifica se deve ser configurada previamente ou se há validações mínimas. | Omissão |
| **H3-015**    | Regras de negócio | A regra que define o intervalo de 10 minutos entre solicitações pode ser insuficiente para evitar abuso do sistema. | Inconsistência |

### H4 - Como médico gostaria que o sistema tenha uma tela para cadastro de hábitos alimentares dos usuários, para poder avaliar sua rotina.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H4-016**    | Critérios de aceitação | Exigir que o usuário informe todas as refeições dos últimos 30 dias pode ser excessivo e inviável. | Informação Estranha |
| **H4-017**    | Critérios de aceitação | O critério que afirma que os hábitos alimentares serão analisados para sugerir uma dieta ou não não define os critérios de análise nem quando a sugestão será feita. | Ambiguidade |
| **H4-018**    | Regras de negócio | A separação entre comida e bebida não tem justificativa clara e pode ser confusa para o usuário. | Informação Estranha |
| **H4-019**    | Regras de negócio | O sistema impedir o usuário de informar dias posteriores caso falte um registro anterior pode causar frustração e limitar a experiência. | Inconsistência |
| **H4-020**    | Regras de negócio | A exigência de informar o tipo de dieta antecipadamente pode limitar usuários que ainda não têm essa informação definida. | Omissão |

### H5 - Como usuário eu gostaria de poder inserir as minhas atividades físicas, para poder acompanhar minha evolução mensal.

| ID da História | Localização | Descrição do Defeito | Natureza do Defeito |
|---------------|------------|----------------------|--------------------|
| **H5-021**    | Critérios de aceitação | A opção de atividades físicas inclui "voar", que não é uma atividade convencional para humanos, tornando o requisito incoerente. | Fato Incorreto |
| **H5-022**    | Critérios de aceitação | O sistema promete sugerir atividades físicas automaticamente e sem margem de erro, o que é uma afirmação absoluta sem espaço para ajustes ou personalização. | Informação Estranha |
| **H5-023**    | Critérios de aceitação | Não há uma definição clara do que significa "registro consistente" das atividades físicas, deixando o requisito vago. | Ambiguidade |
| **H5-024**    | Regras de negócio | A margem de erro de 5% não explica como será aplicada, nem quais aspectos da sugestão de atividades podem ter essa variação. | Inconsistência |
| **H5-025**    | Regras de negócio | A exigência de que a inserção dos dados seja rápida e intuitiva não especifica critérios técnicos ou métricas para garantir essa usabilidade. | Omissão |

