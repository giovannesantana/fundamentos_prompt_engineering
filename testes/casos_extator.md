## Teste 4

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
Sobre o Bradesco

A gente acredita no poder da confiança. Confiança que aproxima, orienta e transforma a vida das pessoas no dia a dia. Entrar no Bradesco é fazer parte de um momento real de transformação. Um ambiente que combina a solidez de uma história construída ao longo de décadas com a evolução constante de quem está sempre olhando para frente. Aqui, você encontra espaço para aprender, crescer e assumir protagonismo na sua trajetória, com apoio, estrutura e oportunidades que acompanham o seu desenvolvimento. Mais do que trabalhar em uma grande instituição, é sobre fazer parte de um time que impacta milhões de pessoas, contribui para o desenvolvimento do país e constrói, todos os dias, um futuro mais acessível e sustentável para a sociedade.

Sobre a área

 Gerenciamento de Riscos Financeiros: Responsável pelo monitoramento e controle dos riscos financeiros da instituição, incluindo mercado, crédito, liquidez e capital. Desenvolve modelos, métricas e ferramentas para mensuração e acompanhamento desses riscos, apoiando a tomada de decisão e a gestão eficiente das exposições. Contribui para a solidez financeira e a sustentabilidade do banco.

Como será seu dia a dia?

Como Data Scientist II, você atuará na área de Dados e suas principais atividades serão: 

·       Realizar análises técnicas para suporte à tomada de decisão executiva, envolvendo modelos de risco de crédito, políticas de crédito, rentabilidade e pricing;

·       Identificar oportunidades de otimização do custo de crédito por meio da revisão de parâmetros, premissas e metodologias de Perda Esperada (PD, LGD e EAD);

·       Desenvolver estudos analíticos e simulações de impacto financeiro para suportar decisões estratégicas relacionadas à concessão e gestão do crédito

·       Monitorar indicadores de desempenho das carteiras e identificar desvios, tendências e oportunidades de melhoria;

·       Elaborar apresentações executivas e recomendações com foco na geração de valor e mitigação de riscos;

·       Participar da avaliação de novas estratégias de crédito, apoiando análises de viabilidade, riscos e impactos em resultados;

·       Interagir com áreas de Negócios, Produtos, Modelagem, Cobrança e Finanças para construção de soluções integradas.

Modelo de trabalho

Híbrido - 2x Presencial

Unidade: Osasco/SP

Perfil que buscamos

Valorizamos quem entende o cliente em profundidade, trabalha em parceria e transforma conhecimento em entregas com impacto. Profissionais com senso de dono, consistência na execução e foco em resultado, que evoluem continuamente, compartilham aprendizados e usam tecnologia para transformar desafios em soluções relevantes para o negócio.

Requisitos

·       Ensino superior completo em Estatística, Matemática, Engenharias, Ciência de Dados, Economia ou áreas correlatas; 

·       Conhecimento em modelos de Credit Score, Behavior Score, Collection Score e Pricing; 

·       Vivência com grandes volumes de dados e construção de análises para suporte à tomada de decisão; 

·       Conhecimento em métricas e indicadores de risco de crédito; 

·       Experiência com Modelos de Perda Esperada (Resolução CMN 4.966 e IFRS 9); 

·       Proficiência em Databricks; 

·       Capacidade de traduzir análises complexas em recomendações executivas e orientadas a negócio. 

Será um diferencial se você tiver:

·       Experiência na criação de modelo do zero;

·       Vivência em modelo de perda esperada (4966/IFRS9).

O que você encontra aqui

Cuidar de você

·        Plano de saúde e odontológico

·        Seguro de vida

·        Viva Bem: programa de saúde, bem-estar e qualidade de vida

·        TotalPass

Crescer com você

·        Universidade corporativa Bradesco (Unibrad)

·        Parcerias educacionais

Segurança para o seu futuro

·        Participação nos lucros ou Bônus (conforme a elegibilidade de cargo)

·        Previdência privada

·        Condições especiais em produtos e serviços

·        Isenção de Tarifas: condições especiais em diversos produtos e serviços

Apoio à sua vida e à sua família

·        Vale alimentação e refeição

·        13ª cesta alimentação

·        Auxílio creche ou babá

·        Licença Maternidade de 180 dias, acompanhamento assistencial da gestação até o pós-parto

·        Licença Paternidade estendida de 20 dias

·        Vale transporte opcional

Tudo pensado para apoiar sua jornada de crescimento com equilíbrio, segurança e oportunidade.
</vaga>

_Output:_

{“cargo”: “Data Scientist II”, “empresa”: “Bradesco”, “local”: “Osasco/SP”, “modalidade”: “hibrido”, “salario”: null, “requisitos”: [“Ensino superior completo em Estatística, Matemática, Engenharias, Ciência de Dados, Economia ou áreas correlatas”, “Conhecimento em modelos de Credit Score, Behavior Score, Collection Score e Pricing”, “Vivência com grandes volumes de dados e construção de análises para suporte à tomada de decisão”, “Conhecimento em métricas e indicadores de risco de crédito”, “Experiência com Modelos de Perda Esperada (Resolução CMN 4.966 e IFRS 9)”, “Proficiência em Databricks”, “Capacidade de traduzir análises complexas em recomendações executivas e orientadas a negócio”], “beneficios”: [“Plano de saúde e odontológico”, “Seguro de vida”, “Viva Bem: programa de saúde, bem-estar e qualidade de vida”, “TotalPass”, “Universidade corporativa Bradesco (Unibrad)”, “Parcerias educacionais”, “Participação nos lucros ou Bônus (conforme a elegibilidade de cargo)”, “Previdência privada”, “Condições especiais em produtos e serviços”, “Isenção de Tarifas”, “Vale alimentação e refeição”, “13ª cesta alimentação”, “Auxílio creche ou babá”, “Licença Maternidade de 180 dias”, “Licença Paternidade estendida de 20 dias”, “Vale transporte opcional”]}
