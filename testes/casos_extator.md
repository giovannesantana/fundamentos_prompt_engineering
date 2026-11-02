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
Locations: São Paulo | Rio de Janeiro

Who We Are

Boston Consulting Group partners with leaders in business and society to tackle their most important challenges and capture their greatest opportunities. BCG was the pioneer in business strategy when it was founded in 1963. Today, we help clients with total transformation-inspiring complex change, enabling organizations to grow, building competitive advantage, and driving bottom-line impact.

To succeed, organizations must blend digital and human capabilities. Our diverse, global teams bring deep industry and functional expertise and a range of perspectives to spark change. BCG delivers solutions through leading-edge management consulting along with technology and design, corporate and digital ventures—and business purpose. We work in a uniquely collaborative model across the firm and throughout all levels of the client organization, generating results that allow our clients to thrive.


We Are BCG X

 

We’re a diverse team of more than 3,000 tech experts united by a drive to make a difference. Working across industries and disciplines, we combine our experience and expertise to tackle the biggest challenges faced by society today. We go beyond what was once thought possible, creating new and innovative solutions to the world’s most complex problems. Leveraging BCG’s global network and partnerships with leading organizations, BCG X provides a stable ecosystem for talent to build game-changing businesses, products, and services from the ground up, all while growing their career. Together, we strive to create solutions that will positively impact the lives of millions.


What You'll Do

As a part of BCG’s X Delivery team, you will play a pivotal role in bridging technology and strategy. You will collaborate with premier consulting teams around the world, applying your software development expertise across a variety of ambitious and ground-breaking international projects. You will be instrumental in advancing BCG's Consulting and BCG X teams by providing critical software development insights and speeding up project execution.

 

As a Software Engineer, your role involves close collaboration with consulting teams to address complex and diverse technological challenges. You will apply your expertise in software development methodologies to add value to BCG's Consulting & BCG X teams and Practice Areas.

 

Each project offers a unique opportunity to showcase your skills and make a significant impact within BCG and our esteemed clientele.



What You'll Bring

We are seeking technologically adept engineers who bring strong experience and diverse skills to our dynamic team. This role is an outstanding opportunity for someone who is passionate about software development and embraces opportunities to learn and make an impact in a fast-paced, innovative environment. If you're driven by technology and ready for impactful challenges, our BCG X Delivery team could be a great match!

 

Technical Skills - Knowledge and Experience with: 

Coding Skills: Strong coding skills and proficiency in programming languages such as Python, Java, Kotlin, Node.js, Go, Ruby, Rust, C#, etc.. Experience with multiple languages preferred.
Web Development Expertise: Experience with Typescript or JavaScript frameworks such as React, Next.js, and Angular. Demonstrated projects or work experience are helpful.
API Development: Solid experience in creating APIs using REST or GraphQL.
Cloud Computing: Familiar with AWS, Azure, GCP, and capable of effective deployment on these platforms.
Database Management: Skilled in both relational and NoSQL databases, including MongoDB, Neo4j, and Redis.
Additional Skills:
Experience with Spark, Hadoop, or similar systems.
Practical knowledge of Docker, Kubernetes, or similar technologies.
Familiarity with CI/CD tools like CircleCI, Jenkins, etc.
Tech curiosity with interest and exposure to technologies like AR/VR, IoT, AI, Blockchain.
Knowledge of infrastructure as code practices using Terraform, Chef, Puppet, or Ansible.
Job requirements:
Bachelor's / Master's in Computer Science or a related field
Fluency in Portuguese and English
Proven background in end-to-end application development, preferably in a commercial or consulting environment.
Active contributions to open-source projects or technical communities are highly valued.
Core Attributes:
Software Development: Demonstrated experience in developing, testing, and deploying robust software. Examples of past projects or contributions are advantageous.
Full Lifecycle Experience: Active involvement in the complete software development lifecycle, showcasing skills from idea generation to deployment.
Efficiency Optimization: Experience in optimizing software for performance and efficiency.
Dynamic Adaptability: Ability to thrive in a fast-paced, client-facing environment. Experience in client interactions for product development is a plus.
Collaborative Skills: A track record of working effectively in team settings, sharing ideas, and co-developing solutions.
</vaga>

_Output:_

{“cargo”: “Software Engineer (BCG X Delivery)”, “empresa”: “Boston Consulting Group (BCG)”, “local”: “São Paulo | Rio de Janeiro”, “modalidade”: null, “salario”: null, “requisitos”: [“Bacharelado/Mestrado em Ciência da Computação ou área relacionada”, “Fluência em português e inglês”, “Sólida experiência em programação (Python, Java, Kotlin, Node.js, Go, Ruby, Rust, C#, etc.)”, “Experiência com Typescript ou JavaScript e frameworks como React, Next.js e Angular”, “Experiência em criação de APIs REST ou GraphQL”, “Familiaridade com AWS, Azure, GCP”, “Experiência com bancos relacionais e NoSQL (MongoDB, Neo4j, Redis)”, “Experiência comprovada em desenvolvimento de aplicações end-to-end, de preferência em ambiente comercial ou de consultoria”, “Experiência no ciclo completo de desenvolvimento de software”, “Experiência em otimização de software para performance e eficiência”, “Capacidade de atuar em ambiente dinâmico e voltado ao cliente”, “Habilidade de trabalho colaborativo em equipe”], “beneficios”: null}
