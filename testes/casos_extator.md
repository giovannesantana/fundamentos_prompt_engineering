## Teste 3

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
https://bradesco.csod.com/ux/ats/careersite/1/home/requisition/94053?c=bradesco&cfdd[0][id]=634&cfdd[0][options][0]=1429
</vaga>

_Output:_

{“cargo”: “Data Scientist II”, “empresa”: “Bradesco”, “local”: null, “modalidade”: null, “salario”: null, “requisitos”: null, “beneficios”: null}
