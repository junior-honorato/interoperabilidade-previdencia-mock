​🏛️ BACEN Res. 12: Protótipo de Interoperabilidade Previdenciária (Mock API)

​🔗 **[Acessar ao Protótipo Navegável (MVP em tempo real)](https://junior-honorato.github.io/interoperabilidade-previdencia-mock/)**

​Aplicação front-end (Vanilla JS) criada como Prova de Conceito (PoC) para tangibilizar a jornada operacional de backoffice exigida pela Resolução Conjunta nº 12 do BACEN (Interoperabilidade de Previdência e VGBL).

​📌 Problema
​A adaptação a normas regulatórias complexas gera frequentemente um gargalo de comunicação entre as áreas de Negócio, Compliance e Engenharia.
Neste cenário:
- ​A documentação técnica fornecida por parceiros integradores (como a câmara de compensação) chega num formato estritamente técnico (Swagger/OpenAPI e JSON).
- Ler dezenas de endpoints de mensageria assíncrona exige um esforço cognitivo elevado para entender como será o impacto real no ecrã do utilizador de operações.
- Iniciar o desenvolvimento de software sem validar a jornada e os tempos de resposta (SLAs) com a equipa de operações aumenta o risco de retrabalho técnico e desperdício de horas de Engenharia e Design (UX).

​🎯 Objetivo da Ferramenta
​Atuar como um acelerador de Product Discovery. A ferramenta traduz a complexidade da "sopa de letrinhas" das APIs regulatórias para uma interface gráfica tangível, permitindo à equipa de backoffice simular o fluxo de trabalho antes de escrever uma única linha de código oficial.
​A aplicação simula o motor de processos:
- ​Caixa de Entrada (Inbox): Fila de casos estruturada com filtros por status e prioridade.
- Gestão de SLAs: Relógio dinâmico que altera a criticidade do processo (alertas visuais) conforme o tempo de resposta exigido pela norma se esgota.

​- Mapeamento de Mensageria: Simula o ecossistema de requisição e resposta (Request/Response) de processos previdenciários, como:
 - ​101 ➝ 102 (Consulta de Garantias)
 - ​103 ➝ 104 (Pedidos de Trava/Bloqueio)
​
 - 105 ➝ 106 (Liquidação / Resgate)​
 - 107 ➝ 108 (Liberação)

​💼 Impacto no Negócio
- ​Eficiência de Engenharia (Shift-Left): Validação de regras de negócio, exceções e fluxos operacionais na fase de prototipagem, evitando refatorações dispendiosas durante a Sprint.
- Alinhamento com a Operação: Permite aos analistas de previdência interagir com o futuro sistema, garantindo que o desenho técnico atende às reais necessidades da esteira de aprovação.
- Redução de Fricção: Transforma fluxos assíncronos e complexos num modelo de aprovação (Aceito/Rejeitado) simples e à prova de falhas (Poka-Yoke).

​⚙️ Funcionalidades

​✔ Mapeamento do catálogo de mensagens regulatórias em formulários visuais.

✔ Sistema integrado de prevenção de erros operacionais (validação estrita de campos obrigatórios).

✔ Simulação assíncrona de cenários de sucesso e falha (Mock de RET).


✔ Dashboard com indicadores de volumetria e SLAs a vencer.

✔ Arquitetura em ficheiro único (HTML/JS/CSS) totalmente independente e de rápido carregamento.

​🛡️ Nota de Segurança e Compliance (Aviso Legal)
​Este projeto é um Protótipo Sanitizado. Com o objetivo de garantir a total Segurança da Informação corporativa e o respeito a NDAs:
- Todos os dados, chaves de integração, schemas JSON oficiais e endpoints reais (propriedade de parceiros e integradores como a NUCLEA/FenaPrevi) foram ofuscados, omitidos ou substituídos por Mocks genéricos.
- ​Nenhuma propriedade intelectual do ecossistema bancário real está exposta. Os CNPJs, processos SUSEP e dados de clientes utilizados são integralmente fictícios.

​🛠 Tecnologias Utilizadas

- HTML5 / CSS3 (Layout Responsivo e UI Corporativa)
- JavaScript (Vanilla JS para gestão de estados e Mocks)
- GitHub Pages (Hospedagem ágil para acesso do Stakeholder)

​🤖 Uso de Inteligência Artificial
​A IA Generativa foi utilizada como copiloto técnico pelo Product Manager para realizar o parsing e a tradução do esquema técnico original (Swagger) em componentes de front-end funcionais, acelerando a construção do protótipo em dezenas de horas. As validações operacionais, o modelo do dashboard e a arquitetura de estado da jornada de produto foram orquestrados e estruturados manualmente com base no conhecimento do negócio previdenciário.

​👤 Autor
​Arlindo Júnior Honorato
Technical Product Manager | Automação | IA aplicada a Produtos Financeiros e Eficiência de Backoffice
