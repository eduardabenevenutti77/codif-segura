codificação segura: 

    - proteção de informações, sistemas, recursos e serviços;
    - reduz a probabilidade e o impacto de incidentes de segurança;

    confidencialidade (privacidade): protege as informações contra o acesso de qualquer pessoa (nível de acesso - rh server) - uid - apenas pessoas autorizadas tem acesso - leitura das informações;

    integridade: evita que dados sejam alterados ou excluídos sem a permissão, engloba dados/programas/documentações/registros, preocupa-se com a gravação e alteração de dados;

    - nunca deixar a segurança em apenas um lado (backend ou frontend);

    disponibilidade: protege os serviços no geral, garante que os dados estejam disponível ao usuário em qual momento, necessita de equipamentos tolerantes a falhas;

    consistência: certifica que o sistema atenda as expectativas dos usuários - todas as funcionalidades tem que realizar o que precisam fazer;

    isolamento/uso legítimo: regula o acesso ao sistema e as informações disponíveis para esse acesso, garante o isolamento das funcionalidades, evita adulteração ou deleção de dados, a quebra desse conceito gera problemas na integridade e na confidencialidade - LOG (identifica o usuário e o que ele fez dentro do sistema);

    auditoria: protege o sistema contra erros e atos maliciosos, uso de logs (o que foi, quem foi e quando foi), identifica os autores e suas ações - evita eventos indesejados, uso o monitoriamento de ações;

    confiabilidaade: garante que mesmo em condições erradas, o sistema atuará conforme o esperado;

    como escolher: depende da organização e em qual sistema será utilzado (caso do rh-server: integridade, isolamento, consistência);

    recurso: físico, aquilo que precisamos proteger;
    ameaça: evento ou atitude indesejável;
     - vazamento de informações voluntário (venda de informações pessoais entre empresas) ou involuntário (não é proposital), compromentimento de dados (violação da integridade), indisponibilidade, acesso/uso não autorizado;
    vulnerabilidade: fraqueza ou deficência em pode torna-se uma ameaça;
    ataque: ameaça concretizada;
     - pós ataque: mascaramento (um programa/pessoa se passa por outro), burla o sistema/log, violação autorizada (o usuário autorizado realiza atividades não autorizadas), ameaças programadas;
    impacto: consequência do ataque;
    probabilidade: a possibilidade de uma ameaça atacar com o sucesso o sistema computacional;
    risco: análise do tamanho da exposição que o sistema está sujeito, depende da probabilidade;

    por que não estamos seguros? 
    
      1º codificação mal-feita:
       - senha muito fácil;
       - muita permissão para usuário;
       - acesso aleatório na máquina;
       - porta de serviço sem proteção;
       - switches com usuário padrão (admin - admin);
       
      2º software com falha;
       
      3º redes desprotegidas:
       - uso de serviço sem segurança;
       - falha de criptografia;
       - spoofing;
       
      4ª falta de atualização:
       - atualizações não automáticas;
       - patches de segurança podem abrir novas falhas;
       - software muitooo antigo (windows XP);
       
      5º fator humano:
       - usuário roda um cavalo de tróia;
       - informações privilegiadas;
       - vazamento de especificações de um produto;
      
