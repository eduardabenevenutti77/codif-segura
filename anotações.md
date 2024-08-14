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
      
 Política de Segurança: 
  pdca: planejar, desenvolver e corrigir;
  planejar: com base na ISO 27002
  implementação: coloca em prática, treinamento de usuário, divulgação da PSI, definir documentação de normas;
  avaliação e ação corretiva: valida se a seguraça está atendendo os requisitos, análise critica por meio de auditória;
  níveis de maturidade:
   1º - problemas de segurança de forma pontual é baseada no individuo envolvido, pouca ou nenhuma documentação
   2º - tem política, tem plano de contorno, procedimento bem documentado e não possui monitoriamento de segurança
   3º - segurança integrada, tem medidas corretivas, classfica conforme os requisitos de segurança, testes de segurança são frequentes, verificação de ameaças e atualizações de segurança
   4º - segurança é vista como parte de um negócio, tudo tem uma análise de segurança e conseguimos analisar um problema antes que ele aconteça

  É um documento que registra o que a empresa deseja com a segurança, detalha o que busca proteger, onde e quem é o responsável pela gestão, não deve ser estático - mudanças são necessárias!

   - organização da segurança;
   - classificação e controle de ativos;
   - aspectos humanos;
   - segurança do ambiente fisíco;
   - segurança do ambiente lógico;
   - segurança das comunicações;
   - prevenção e tratamento de incidentes;
   - desenvolvimento, implementação e correção de sistemas;
   - gestão de continuidade;
   - conformidade;

   divulgação: realização de treinamento sobre a política de segurança, tão importante quanto a política, pode ser separada conforme os setores;
   
plano de continuidade: estratégia e planos de ação que previnem e garantem o funcionamento dos serviços, criação de normas e padrões para contornar estas situações;
    - análise de riscos e mapeamento;
    - análise de impactos;
    - planejamento estratégico;

    deve ter um plano de emergência (usado em últimos casos);
    deve ter um plao de administração (define funções a serem realizadas durante o plano de emergência);
    deve ter um plano de recuperação de desastre (prd - planejamento que controla a recuperação de dados);
    deve ter um plano de continuidade operacional (pcd - restabelecer o funcionamento das principais funções que suportam as operações, isso reduz o tempo de queda e os impactos pelo acidente)

como classificar os ativos: não há um padrão, normalmente usa a ISO 27002 como referência (contabilzar e classificar por prioridades)