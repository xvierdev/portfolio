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
