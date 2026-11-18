# Wesley Xavier
<img src="perfil.jpg" alt="Descrição" width="300">

## Informações Pessoais

**Nome:** Wesley Xavier  
**Idade:** 34 anos  
**Tecnólogo em Análise e Desenvolvimento de Sistemas** — Fatec Jessen Vidal

## Histórico acadêmico

- Técnico em Desenvolvimento de Sistemas pela Etec Professora Ilza Nascimento Pintus.

## Motivação para entrar na Fatec

Sempre tive interesse pelas ciências exatas, especialmente pelo funcionamento dos computadores e dos sistemas computacionais. Depois de alguns anos considerando diferentes caminhos, decidi ingressar na Fatec para alcançar meus objetivos e desenvolver habilidades de programação que me permitam resolver problemas e criar ferramentas de impacto para a sociedade.

## Experiência profissional

- **Telefônica do Brasil LTDA — Estagiário**  
  15/08/2025–atualmente  
  Elaboro alguns slides e apoio na elaboração de outros. Produzo e envio diariamente relatórios por e-mail utilizando o Excel. Também consulto bancos de dados e trato os resultados no Excel ou com Python. Em conjunto com a equipe, desenvolvo sistemas para automatizar a coleta e o tratamento de dados, além de bots de alerta no Telegram e no WhatsApp para ocorrências relacionadas à fibra óptica.

- **Microcamp Educação Tecnológica — Professor de informática, robótica e games**  
  02/10/2021–13/09/2025  
  **Informática:** ministrei aulas sobre o pacote Microsoft Office (Word, Excel e PowerPoint), Adobe Photoshop, Adobe Illustrator, conteúdos de web e digitação.  
  **Robótica:** ministrei aulas de introdução à eletrônica; montagem, manutenção e diagnóstico de defeitos em computadores; manutenção de notebooks; substituição de telas, conectores e baterias de smartphones; projetos de robótica com Arduino; e uso de impressoras 3D.  
  **Games:** ensinei Photoshop, Unreal Engine 4 com Blueprints, modelagem 3D com Blender e lógica de programação com Blueprints.

- **Empório Verde — Atendente**  
  01/08/2011–07/05/2023  
  Atendia e orientava os clientes sobre os cuidados com as plantas e o plantio em vasos. Também ajudava na limpeza e organização dos produtos da loja e apoiava as entregas nas casas dos clientes.

## Informações de contato

- [github.com/xvierdev](https://github.com/xvierdev)
- [linkedin.com/in/xvierbr/](https://www.linkedin.com/in/xvierbr/)
- [wesley.xvier@gmail.com](mailto:wesley.xvier@gmail.com)

## Meus Principais Conhecimentos

Minhas experiências profissionais e minha formação técnica envolvem desenvolvimento de sistemas, automação de processos, análise de dados e uso de ferramentas digitais. Entre os conhecimentos que utilizei no trabalho e nos cursos que ministrei estão:

- **Análise e automação de dados:** consultas a bancos de dados, tratamento de resultados no Excel e com Python, elaboração de relatórios e desenvolvimento em equipe de automações para coleta e tratamento de dados.
- **Python:** extração, limpeza e análise de grandes volumes de dados (ETL), desenvolvimento de APIs REST com FastAPI e Flask e estudo de algoritmos para maratonas de programação.
- **Redes e hardware:** configuração de redes e equipamentos, instalação e configuração de sistemas Linux, configuração de firewalls e controles de acesso e preparação de ambientes de desenvolvimento para Python, Node.js e Java.
- **Desenvolvimento web:** desenvolvimento de interfaces com React e TypeScript e criação de aplicações e APIs com Node.js e Express.
- **Metodologia Ágil (Scrum):** vivência direta na organização e liderança de projetos como Desenvolvedor, Scrum Master ou Product Owner.

## Projetos API

### API 1 — 1º semestre (2024-2): Scrum360

#### Instituição parceira e responsável pelo desafio

- **Instituição parceira:** Fatec São José dos Campos (Fatec-SJC).
- **Responsável pelo desafio e pelos requisitos:** Prof. Antônio Egydio.

#### Problema

Quem está começando a estudar Scrum pode conhecer os nomes dos papéis, eventos e artefatos sem saber como aplicá-los em conjunto durante um projeto. Sem relacionar os conceitos a situações práticas, torna-se difícil transferir o que foi estudado para projetos futuros. Sem verificar o conhecimento adquirido, o aprendiz também pode não identificar quais conceitos e práticas ainda precisa compreender melhor.

#### Solução

**Nome:** Scrum360<br>
**Tipo:** aplicação web educacional.

- Organiza o conteúdo em módulos sobre Scrum, Product Owner, Scrum Master e time de desenvolvimento.
- Apresenta conceitos e exemplos práticos em páginas de conteúdo, com áudios de apoio.
- Oferece uma avaliação parcial de dez questões para cada módulo e exibe a pontuação do usuário.
- Registra o progresso e libera o exame final quando o usuário acerta pelo menos seis questões em cada módulo.
- O exame final contém vinte questões para revisar os conhecimentos apresentados.

[foto]

#### Link do Repositório Git

- [Repositório do projeto](https://github.com/xvierdev/FATEC-API-Under_Devs)

#### Tecnologias utilizadas

| Tecnologia | Onde foi utilizada |
|---|---|
| Python | Lógica do servidor e processamento das rotas da aplicação. |
| Flask | Rotas, renderização dos templates, recebimento das pontuações e armazenamento do progresso em sessão. |
| HTML5 e Jinja2 | Estrutura das páginas e templates renderizados pelo Flask. |
| CSS3 e Tailwind CSS | Estilização das páginas e componentes da interface. |
| Flowbite | Componentes de interface carregados na base dos templates. |
| JavaScript | Navegação entre questões, verificação das respostas, cálculo dos acertos e envio dos resultados. |
| AWS | Hospedagem e execução da aplicação web. |

#### Contribuições pessoais

##### Papel no Scrum

Atuei como Desenvolvedor, com atribuições de backend e conteúdo, conforme a identificação da equipe no repositório.

##### Principais contribuições

- Estruturei páginas e rotas da aplicação Flask, conectando as páginas de conteúdo e avaliações ao servidor.
- Implementei a lógica em JavaScript das avaliações parciais, incluindo a verificação das respostas e a contagem de acertos.
- Desenvolvi o processamento dos resultados no backend e o registro das pontuações em sessão para acompanhar o progresso nos módulos.
- Implementei e integrei o exame final de vinte questões, incluindo o envio e a apresentação da pontuação.
- Contribuí para a regra de progressão que libera o exame final após a aprovação nas quatro avaliações parciais.
- Produzi a primeira versão e revisei conteúdo didático sobre Scrum, incluindo seus papéis, eventos, artefatos e valores.
- Fiquei responsável pela elaboração dos questionários e pelos cálculos das notas; alinhei com a equipe quais questões seriam válidas e a quantidade adequada para cada avaliação.
- Os artefatos que produzi foram o backend e as rotas em `Frontend/app.py`, a lógica de correção em `Frontend/static/scripts.js`, a página de acompanhamento em `Frontend/templates/Modulos.html`, as páginas dos questionários parciais e do exame final em `Frontend/templates/evaluations/` e o conteúdo didático em `Documentação/5. Conteudo SCRUM.md`. Nessas contribuições, utilizei Python, Flask, JavaScript, HTML e CSS.

#### Hard skills

| Tecnologia ou habilidade técnica | Nível de proficiência | Evidência de uso no projeto |
|---|---|---|
| Python | Consigo ensinar | Implementação de rotas e processamento de dados no servidor Flask. |
| Flask | Faço/uso com autonomia | Criação de rotas, renderização de páginas e gerenciamento das pontuações em sessão. |
| JavaScript | Consigo ensinar | Lógica das avaliações parciais e do exame final. |
| HTML e CSS | Consigo ensinar | Construção e estilização das páginas e dos questionários. |

#### Soft skills

Durante a elaboração dos questionários e a definição do cálculo das notas, foi necessário decidir com a equipe quantas perguntas teria cada avaliação e quais seriam consideradas válidas. Como fiquei responsável por elaborar os questionários e calcular as notas, usei *comunicação* para esclarecer os critérios em discussão, *persuasão* para defender uma seleção de perguntas adequada ao conteúdo avaliado e *resolução de conflitos* para lidar com as diferenças de opinião durante os ajustes. Esse alinhamento permitiu definir quais questões seriam utilizadas e como elas seriam consideradas nas avaliações.

### API 2 — 2º semestre (2025-1): UnderDevs IDE

#### Instituição parceira e responsável pelos requisitos

- **Instituição parceira:** Fatec São José dos Campos (Fatec-SJC).
- **Cliente (P2) e responsável pelos requisitos:** Prof. Giuliano Bertoti.

#### Problema

Desenvolvedores que trabalham com Python precisam dedicar tempo à criação de testes unitários repetitivos para verificar o comportamento do código. Também enfrentam dificuldade para avaliar o próprio código quanto à qualidade, à segurança, à legibilidade e à manutenibilidade. Sem avaliações cuidadosas, falhas e oportunidades de melhoria podem passar despercebidas, aumentando o esforço para manter o código confiável e facilitar sua evolução.

#### Solução

**Nome:** UnderDevs IDE (IDE em Java para Python com assistência de inteligência artificial)<br>
**Tipo:** aplicação desktop.

- Oferece um editor para criar, abrir e salvar arquivos Python.
- Executa scripts Python e exibe os resultados em uma janela própria.
- Integra-se ao Ollama, com o modelo Qwen2.5-Coder, para gerar testes unitários e sugerir melhorias no código.
- Também permite solicitar documentação e explicações do código.
- Mantém prompts de inteligência artificial no MySQL e permite consultá-los, criá-los, editá-los e excluí-los.

[foto]

#### Link do Repositório Git

- [Repositório do projeto](https://github.com/xvierdev/FATEC-API2ADS-UnderDevs)

#### Tecnologias utilizadas

| Tecnologia | Onde foi utilizada |
|---|---|
| Java e Swing | Desenvolvimento da aplicação desktop e da interface gráfica. |
| Ollama, Ollama4j e Qwen2.5-Coder | Integração com o modelo local para geração de testes, sugestões de melhoria, documentação e explicações do código. |
| Python | Linguagem dos arquivos editados e executados na IDE, incluindo os testes gerados. |
| MySQL e JDBC | Armazenamento e gerenciamento dos prompts utilizados pela aplicação. |
| Maven | Gerenciamento das dependências e configuração do build Java. |
| Git e GitHub | Versionamento e hospedagem do código-fonte. |
| Jira | Organização do backlog e acompanhamento do planejamento das Sprints. |
| Figma | Prototipação da interface. |
| Markdown | Documentação do projeto e do backlog. |

#### Contribuições pessoais

##### Papel no Scrum

Atuei como Scrum Master, com responsabilidades de planejamento e acompanhamento da equipe, além de contribuir com o backend e a integração das interfaces.

##### Principais contribuições

- Planejei e acompanhei o andamento das atividades, reorganizando prioridades e apoiando a equipe na busca pelas entregas das Sprints.
- Integrei ações da interface Swing às rotinas do backend Java, conectando os controles da IDE às funcionalidades de execução e assistência por IA.
- Implementei a comunicação com o Ollama por meio do Ollama4j e integrei prompts para geração de testes, melhorias, documentação e explicações do código.
- Contribuí para a abertura e o salvamento de arquivos Python, a execução de scripts e a exibição dos resultados nas janelas da aplicação.
- Participei da implementação do gerenciamento de prompts no MySQL, incluindo operações para consultar, cadastrar, atualizar e excluir registros.
- Os artefatos que produzi incluem a interface principal (`MainInterface.java`), a integração com o Ollama (`OllamaInterface.java`), os utilitários de arquivos e execução (`FileUtils.java`), as janelas de saída e gerenciamento de prompts (`OutputTest.java`, `OutputUI.java` e `PromptManager.java`), o acesso aos dados (`PromptDao.java`) e os arquivos de prompts para testes, melhorias, documentação e explicação. Nessas contribuições, utilizei Java, Swing, Ollama/Ollama4j, MySQL/JDBC, Python e Maven; também usei Git/GitHub, Jira, Figma e Markdown no versionamento, planejamento, prototipação e documentação.

#### Hard skills

| Tecnologia | Nível de proficiência | Evidência de uso no projeto |
|---|---|---|
| Java | Faço/uso com ajuda | Implementação e integração de funcionalidades da aplicação desktop. |
| Swing | Ouvi falar | Componentes da interface gráfica da IDE. |
| Ollama/Ollama4j | Faço/uso com autonomia | Integração com o modelo para processar prompts relacionados ao código. |
| MySQL/JDBC | Faço/uso com autonomia | Persistência e gerenciamento dos prompts. |
| Python | Consigo ensinar | Execução de scripts e geração de testes para código Python. |
| Maven | Faço/uso com ajuda | Gerenciamento de dependências e configuração do projeto Java. |
| Git/GitHub | Consigo ensinar | Versionamento e colaboração no repositório do projeto. |
| Jira | Faço/uso com autonomia | Organização do backlog e acompanhamento das Sprints. |
| Figma | Faço/uso com autonomia | Prototipação da interface da aplicação. |
| Markdown | Faço/uso com autonomia | Elaboração da documentação e do backlog do projeto. |

#### Soft skills

Durante uma das Sprints, algumas ausências reduziram a disponibilidade da equipe e exigiram a reorganização das tarefas. Como Scrum Master, redistribuí atividades, acompanhei o progresso e procurei manter o time motivado enquanto alinhava as expectativas sobre as entregas. Nessa situação, usei *liderança* para orientar a equipe, *comunicação* para compartilhar mudanças e cobrar atualizações, e *flexibilidade* para adaptar a distribuição do trabalho à disponibilidade dos integrantes. Essa reorganização ajudou o time a manter o andamento das atividades e seguir em direção às entregas previstas.

### API 3 — 3º semestre (2025-2): Radar Entrenova

#### Empresa parceira

- **Empresa parceira:** Entrenova — agência de conteúdos estratégicos e treinamento corporativo, com produção de conteúdos educativos em formatos audiovisuais e transmídia.

#### Problema

Na Entrenova, a identificação das necessidades de treinamento das empresas clientes era feita manualmente, por meio de entrevistas e do acompanhamento direto dos processos pelos responsáveis. Esse trabalho consumia tempo e fazia com que a prospecção e a qualificação de potenciais clientes dependessem da atuação direta da equipe. Com isso, era mais difícil estruturar um funil para distinguir empresas com maior potencial de contratação daquelas que ainda estavam em uma etapa inicial, especialmente entre pequenos e médios negócios.

#### Solução

**Nome:** Radar Entrenova<br>
**Tipo:** aplicação web.

- Oferece um diagnóstico inicial para ajudar pequenas e médias empresas a identificar necessidades de treinamento.
- Realiza uma entrevista aprofundada com inteligência artificial e gera relatórios personalizados sobre a organização.
- Produz relatórios de diagnóstico em PDF e os envia por e-mail.
- Recomenda trilhas de aprendizagem que podem ser atribuídas aos funcionários, com acompanhamento do progresso.
- Disponibiliza painéis para consultar empresas, diagnósticos, potenciais clientes e informações sobre as trilhas.

[foto]

#### Link do Repositório Git

- [Repositório do projeto](https://github.com/EquipeEcho/EchoNova)

#### Tecnologias utilizadas

| Tecnologia | Onde foi utilizada |
|---|---|
| JavaScript e TypeScript | Implementação da lógica da aplicação, das interfaces e das rotas. |
| React e Next.js | Construção da interface web e das páginas e rotas da aplicação. |
| Node.js | Execução das rotas de backend e dos serviços do Next.js. |
| MongoDB e Mongoose | Persistência dos dados de empresas, diagnósticos, funcionários e trilhas. |
| OpenAI, Gemini e Ollama | Integração com provedores de inteligência artificial ao longo das etapas do projeto; Ollama foi usado inicialmente, e OpenAI foi adotado após autorização da cliente devido ao desempenho. |
| Tailwind CSS | Estilização das páginas e dos componentes da interface. |
| jsPDF | Geração de relatórios de diagnóstico em PDF. |
| Nodemailer | Envio de relatórios e mensagens por e-mail. |
| Git e GitHub | Versionamento e hospedagem do código-fonte. |
| Jira | Organização do backlog e acompanhamento das atividades. |

#### Contribuições pessoais

##### Papel no Scrum

Atuei como Desenvolvedor.

##### Principais contribuições

- Trabalhei principalmente no diagnóstico aprofundado com inteligência artificial, criando e ajustando prompts e contribuindo para o fluxo de entrevista e suas rotas de API.
- Contribuí para a integração dos provedores de IA utilizados nas diferentes etapas do projeto, incluindo Ollama, Gemini e OpenAI.
- Participei da implementação do diagnóstico inicial, do processamento das respostas e da apresentação dos resultados para as empresas.
- Contribuí para a geração dos relatórios em PDF e para o envio dos resultados por e-mail.
- Desenvolvi e ajustei telas administrativas e rotas para consultar e gerenciar empresas, diagnósticos, leads e trilhas de aprendizagem.
- Também contribuí para funcionalidades de cadastro e login de funcionários, atribuição de trilhas e acompanhamento do progresso.
- Entre os artefatos em que trabalhei estão as rotas do diagnóstico inicial e aprofundado (`app/src/app/api/diagnostico/route.ts` e `app/src/app/api/diagnostico-ia/route.ts`), a interface do diagnóstico aprofundado (`app/src/app/diagnostico-aprofundado/page.tsx`), os prompts e a integração com IA (`app/src/lib/prompts.ts` e `app/src/lib/ai/`), a geração e o envio de relatórios (`app/src/lib/pdfGenerator.ts` e `app/src/app/api/send-diagnostico/route.ts`), o painel e o login administrativos (`app/src/app/admin/page.tsx` e `app/src/app/admin/login/page.tsx`), as rotas administrativas (`app/src/app/api/admin/`), o login de funcionários (`app/src/app/api/login-funcionario/route.ts`) e as telas e rotas de funcionários e trilhas (`app/src/app/gerenciar-funcionarios/page.tsx`, `app/src/app/funcionario/trilha/[id]/page.tsx` e `app/src/app/api/funcionarios/`). Nessas contribuições, utilizei JavaScript, TypeScript, React, Next.js, Node.js, Tailwind CSS, OpenAI, Gemini, Ollama, jsPDF, Nodemailer, Git/GitHub e Jira.

#### Hard skills

| Tecnologia ou habilidade técnica | Nível de proficiência | Evidência de uso no projeto |
|---|---|---|
| JavaScript | Faço/uso com autonomia | Desenvolvimento de lógica e funcionalidades da aplicação. |
| TypeScript | Faço/uso com autonomia | Implementação de interfaces, rotas e funcionalidades web. |
| React | Faço/uso com autonomia | Construção de interfaces e componentes. |
| Next.js | Faço/uso com ajuda | Desenvolvimento de páginas e rotas de backend. |
| Node.js | Faço/uso com autonomia | Execução das rotas e serviços do backend. |
| Tailwind CSS | Faço/uso com ajuda | Estilização de páginas e componentes. |
| OpenAI | Faço/uso com autonomia | Integração e uso de IA no diagnóstico aprofundado. |
| Ollama | Faço/uso com autonomia | Uso inicial de IA no diagnóstico e avaliação de respostas dos modelos. |
| Git/GitHub | Consigo ensinar | Versionamento e colaboração no repositório. |
| Jira | Faço/uso com autonomia | Organização e acompanhamento das atividades do projeto. |

#### Soft skills

Durante a implementação do diagnóstico com IA, tivemos que lidar com a demora nos retornos da Entrenova e com respostas inconsistentes do Ollama, enquanto uma mudança na composição da equipe exigia redistribuir as tarefas. Participei do remanejamento e continuei avançando principalmente nos prompts, nas rotas de API e nas telas administrativas; a equipe também ajustou os provedores utilizados, passando a utilizar o provedor da OpenAI após autorização da cliente. Essa experiência exigiu *inteligência emocional* para lidar com as mudanças no grupo, *comunicação* para alinhar a redistribuição das responsabilidades e *resiliência* para seguir ajustando a implementação apesar das dificuldades.
