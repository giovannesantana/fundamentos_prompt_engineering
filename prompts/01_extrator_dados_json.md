## v2

Input:
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
https://carreiras.itau.com.br/vaga/sao-paulo/anl-engenharia-ti-jr-dados/35299/101004728032
</vaga>

Output:
{“cargo”: “ANL ENGENHARIA TI JR - DADOS”, “empresa”: “Itaú Unibanco”, “local”: “São Paulo, Brasil (Jabaquara/SP)”, “modalidade”: “hibrido”, “salario”: null, “requisitos”: [“Ensino superior completo em áreas de tecnologia”, “Conhecimento em Python”, “Conhecimento em AWS”, “Conhecimento em SQL”, “Experiência com Git e GitHub”, “Conhecimentos de lógica de programação”, “Interesse em práticas modernas de engenharia de software e desenvolvimento em nuvem”], “beneficios”: [“Vale-Transporte”, “Vale-Refeição / Vale-Alimentação”, “Plano médico (Fundação Saúde Itaú ou Central Nacional Unimed)”, “Plano odontológico (Odontoprev ou Interodonto)”, “Seguro de Vida”, “PLR - Participação nos Lucros e Resultados”, “Previdência privada”, “Descontos exclusivos em produtos financeiros”, “Licença maternidade e paternidade estendida”, “Auxílio Creche / Babá”, “Incentivo a estudos”, “Wellhub ou TotalPass”, “Acesso aos Clubes de Lazer Itaú”]}

Resultado: 10/10
Mudanças: A primeira linha define o papel da IA e qual será a tarefa; A Tag "Vaga" separa as instruções do exemplo e dos dados a serem lidos para não confundir o modelo; Regras bem formuladas como "Responda APENAS com um JSON válido" que definem o output;
