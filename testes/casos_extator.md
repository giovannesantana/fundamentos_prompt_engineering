## Teste 5

_Input:_

Você é um assistente que extrai dados de anúncios de vaga.
Leia o anúncio dentro das tags <vaga> e extraia os campos abaixo.
Regras:
- Responda APENAS com um JSON válido, sem texto antes ou depois.
- Use exatamente estes campos: cargo, empresa, local, modalidade, salario, requisitos, benefícios.
- "modalidade" deve ser um destes campos: "presencial", "hibrido", "remoto" ou null.
- "requisitos" e "beneficios" são listas de texto curtos.
- Se uma informação NÃO estiver  no texto, use null. Nunca invente.
Exemplo:
<vaga>
Estagiário de Dados John Deere (Indaiatuba, presencial). Bolsa R$1.800. Requisitos: Power BI e Excel. Benefícios: Recesso remunerado e Wellhub.
</vaga>
Resposta:
{"cargo": "Estagiário de Dados", "empresa": "John Deere", "local": "Indaiatuba", "modalidade": "presencial", "salario": "R$ 1.800", "requisitos": ["Power BI", "Excel"], "beneficios": "["Recesso remunerado", "Wellhub"]}
Agora extraia desta vaga:
<vaga>
Nosso Modo de Fazer no Time:
Transforme sua carreira com o iFood! Somos uma empresa brasileira de tecnologia referência na América Latina. Por meio de soluções inovadoras, conectamos milhares de restaurantes a milhões de consumidores diariamente com uma média de 100 milhões de pedidos mensais. Além do delivery de comida, também somos Mercado, Farmácia e Pet. Temos também o iFood Pago, nossa Fintech, que engloba o iFood Benefícios, o vale alimentação e refeição do iFood e o próprio iFood Pago, o banco do restaurante. Junte-se a nós e faça parte de uma equipe que está sempre à frente com tecnologia de ponta e inovação constante.

Seu Cardápio Diário:
O Data Security Specialist é um profissional técnico responsável pela execução e operação dos controles de segurança de dados corporativos e de produção do iFood. Essa posição atua na interseção entre engenharia de segurança, proteção de dados e execução técnica — implementando controles, investigando incidentes e operando as ferramentas que protegem os ativos de dados do iFood.O Data Security Specialist executa as operações de segurança de dados, impulsiona a adoção de AI nos fluxos de trabalho diários de segurança e garante que as capacidades de proteção de dados acompanhem o crescimento do iFood. É uma posição de contribuidor individual que exige experiência prática comprovada em engenharia de segurança de dados, com capacidade de atuar tanto no ambiente corporativo quanto no de produção.

Segurança de Dados Corporativos
Operar e evoluir os controles de DLP (Data Loss Prevention) e ZTNA (Zero Trust Network Access) para endpoints, aplicações em cloud e canais de comunicação — implementando políticas, ajustando regras e executando as prioridades trimestrais.
Implementar e fazer cumprir políticas de classificação de dados e procedimentos de tratamento para usuários internos e terceiros, garantindo alinhamento com LGPD, GDPR e requisitos regulatórios (BACEN, PCI-DSS, entre outros).
Configurar e manter os controles de segurança para plataformas corporativas de SaaS: Databricks, Salesforce, Google Workspace, outras plataformas e ferramentas emergentes baseadas em AI — estabelecendo baselines de hardening, controles de acesso e governança de configuração.
Implementar e fazer cumprir políticas de Document Retention & Disposal — estabelecendo cronogramas de retenção, procedimentos de descarte e mecanismos automatizados de aplicação.
Executar o programa de insider threat: ajustar regras de behavioral analytics, conduzir cadências de análise de anomalias e coordenar com HR e Legal os casos de risco elevado.
Gerenciar políticas de device posture e a aplicação de ZTNA, garantindo o acesso de dispositivos em conformidade em todo o ambiente corporativo.
Segurança de Dados de Produção
Conduzir revisões de segurança da arquitetura de dados de produção: avaliar integrações de dados entre sistemas internos, parceiros e clientes, identificando riscos em APIs, pipelines de ETL e padrões de transferência de arquivos.
Executar o workstream de Data Security no processo de Third-Party Risk Management (TPRM), atuando de forma cross-functional com a equipe de IT Risk e contribuindo continuamente para a melhoria dos security review gates, dos requisitos contratuais de segurança e do monitoramento contínuo dos arranjos de troca de dados com terceiros.
Promover security-by-design nas equipes de engenharia e dados: incorporar requisitos de proteção de dados aos padrões de desenho de integrações, aos frameworks de governança de APIs e aos controles de data residency.
Garantir que data residency, criptografia em trânsito e em repouso e modelos de controle de acesso atendam às obrigações regulatórias e contratuais em todos os ambientes de produção.
Apoiar os programas de conformidade regulatória (LGPD, GDPR, PCI-DSS) relacionados à proteção de dados, atuando como ponto de contato técnico de Data Security para as equipes de Legal, Compliance e Audit.
Adoção de AI e Resultados Mensuráveis
Impulsionar a adoção de AI nos fluxos de trabalho de Data Security: implementar ferramentas de AI para detecção de padrões anômalos de dados, classificação automatizada de dados, ajuste de políticas de DLP e aceleração de investigações — com melhorias mensuráveis na velocidade de detecção, na redução de falsos positivos e na produtividade dos analistas.
Contribuir para o workstream de Data Security para AI Security, atuando de forma cross-functional com a equipe de AI Security para melhorar continuamente a governança e definir requisitos de proteção de dados para ferramentas de AI, incluindo casos de uso aprovados, tratamento de dados sensíveis em prompts, controles de acesso, monitoramento e padrões de adoção.
Acompanhar e reportar os resultados impulsionados por AI: quantificar o tempo economizado, os riscos detectados mais cedo e as melhorias na precisão da classificação atribuíveis às ferramentas de AI.
Colaboração Cross-functional e Resposta a Incidentes
Atuar como referência técnica de Data Security para as equipes adjacentes: traduzir cenários complexos de riscos relacionados a dados em atualizações claras e contextualizadas pelo impacto no negócio para o Data Security Manager e para os times de segurança.
Construir e manter o dashboard operacional de Data Security: tendências de risco, taxas de violações de políticas, SLAs de remediação, métricas de adoção de AI e status operacional.
Participar de iniciativas cross-functional de Data Security: coordenar com Legal, Product, Engineering e IT para equilibrar requisitos de segurança e velocidade do negócio — encontrando o caminho seguro que viabilize a entrega de produtos.
Gerenciar solicitações de exceção de Data Security: avaliar exceções baseadas em risco às políticas de segurança, documentar recomendações e acompanhar o ciclo de vida das exceções.
Atuar na resposta a incidentes como referência técnica de Data Security: conduzir a frente de investigação específica de dados durante incidentes de grande impacto, coordenar com o CSIRT e comunicar o impacto do risco relacionado a dados ao Data Security Manager.
Operação Técnica de Programas
Executar o roadmap técnico de Data Security: traduzir as metas estratégicas em tarefas operacionais, gerenciar o acompanhamento de dependências e reportar o progresso ao Data Security Manager.
Conduzir iniciativas de Sensitive Data Mapping: executar a descoberta, classificação e catalogação cross-functional de dados nos ambientes corporativos e de produção.
Construir e manter métricas de Data Security: índices de exposição a riscos, tendências de violações de políticas, taxas de encerramento de alertas de DLP, SLAs de remediação e velocidade operacional.
Documentar e manter runbooks, playbooks e procedimentos operacionais padrão para as operações de Data Security.
 

Ingredientes Que Buscamos:
Experiência comprovada como Data Security Specialist, Analyst ou Engineer — com histórico de responsabilidade técnica por um domínio de Data Security.
Forte experiência em proteção de dados, DLP, ZTNA e governança de segurança da informação.
Sólida compreensão dos princípios de arquitetura Zero Trust e de sua implementação prática: ZTNA, conditional access, device posture e identity-based segmentation.
Conhecimento profundo de hardening de segurança de SaaS corporativo: Google Workspace, Salesforce, Databricks, outras plataformas e plataformas emergentes baseadas em AI.
Conhecimento de conceitos de arquitetura de dados: APIs, pipelines de ETL, data warehouses, plataformas de dados em cloud e padrões de troca de dados de produção.
Familiaridade com frameworks regulatórios: LGPD, GDPR, PCI-DSS e requisitos regulatórios do BACEN e do PROUF.
Experiência prática com ferramentas de AI para Data Security: detecção de anomalias, classificação automatizada, ajuste de DLP ou aceleração de investigações — com resultados tangíveis e mensuráveis documentados.
Sólidas habilidades analíticas e investigativas: capacidade de rastrear um vazamento de dados, desde o sinal até a causa-raiz, e traduzir as descobertas em recomendações sistêmicas.
Capacidade de colaboração cross-functional: aptidão para conduzir resultados técnicos em colaboração com Legal, Engineering, Product e IT, equilibrando requisitos de segurança e velocidade do negócio.
Habilidade de documentação e criação de runbooks, playbooks e procedimentos operacionais para Data Security.
Inglês avançado (obrigatório).
 
Para Realçar o Sabor: 
Experiência com plataformas SASE (Netskope, Zscaler ou similares) e ferramentas de DSPM (Netskope, Cyera, Wiz ou similares).
Experiência em data engineering ou analytics — compreensão dos fluxos de dados por dentro, incluindo arquitetura de pipelines, data warehousing e plataformas de dados em tempo real.
Experiência na adoção de AI em Data Security: implementação de ferramentas de AI para operações de segurança, mensuração de ganhos de produtividade e iteração das estratégias de adoção.
Certificações: CISM, CDPSE, CISSP ou equivalente.
Experiência em um setor regulado (fintech, banking, payments, health tech), com exposição prática à conformidade regulatória.
 

 

Buscamos uma pessoa apaixonada por segurança em tecnologia, que esteja sempre em busca de novos aprendizados e que goste de desafios. Se você se identifica com este perfil, adoraríamos conhecer você!
</vaga>

_Output:_

{“cargo”: “Data Security Specialist”, “empresa”: “iFood”, “local”: null, “modalidade”: null, “salario”: null, “requisitos”: [“Experiência comprovada como Data Security Specialist, Analyst ou Engineer”, “Forte experiência em proteção de dados, DLP, ZTNA e governança de segurança da informação”, “Sólida compreensão de arquitetura Zero Trust: ZTNA, conditional access, device posture e identity-based segmentation”, “Conhecimento profundo de hardening de segurança de SaaS corporativo: Google Workspace, Salesforce, Databricks e plataformas baseadas em AI”, “Conhecimento de arquitetura de dados: APIs, pipelines de ETL, data warehouses, plataformas de dados em cloud e padrões de troca de dados de produção”, “Familiaridade com LGPD, GDPR, PCI-DSS e requisitos regulatórios do BACEN e do PROUF”, “Experiência prática com ferramentas de AI para Data Security, com resultados mensuráveis documentados”, “Sólidas habilidades analíticas e investigativas”, “Capacidade de colaboração cross-functional com Legal, Engineering, Product e IT”, “Habilidade de documentação e criação de runbooks, playbooks e procedimentos operacionais”, “Inglês avançado (obrigatório)”], “beneficios”: null}
