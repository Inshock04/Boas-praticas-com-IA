# Boas-praticas-com-IA 

### Da ideia ao software: um guia prático de desenvolvimento assistido por IA

A Inteligência Artificial está transformando a forma como desenvolvemos software. Hoje, ferramentas de IA podem auxiliar no planejamento, criação de interfaces, escrita de código, testes, identificação de erros e implementação de funcionalidades.

Mas desenvolver com IA não significa apenas pedir que ela crie um sistema.

**O objetivo deste repositório é ensinar como utilizar a Inteligência Artificial de maneira estratégica, compreendendo as decisões técnicas, aplicando boas práticas e construindo aplicações funcionais, seguras e intuitivas.**

Este guia reúne conhecimentos, ferramentas e métodos que podem auxiliar estudantes, iniciantes e desenvolvedores durante todas as etapas de um projeto.

---

## 1. Antes de programar: entenda o problema

O primeiro passo não é escolher uma linguagem de programação nem abrir uma IDE.

É compreender o que você deseja desenvolver.

Antes de começar, responda:

- Qual problema o sistema pretende resolver?
- Quem utilizará a aplicação?
- Quais funcionalidades são realmente necessárias?
- Quais informações precisarão ser armazenadas?
- O sistema terá autenticação?
- Será necessário integrar APIs externas?
- Qual será a maneira mais simples de entregar uma primeira versão funcional?

### Utilize o ChatGPT para organizar suas ideias

O ChatGPT pode auxiliar na transformação de uma ideia inicial em um planejamento estruturado.

**Exemplo de prompt:**

> Quero desenvolver um sistema para gerenciamento de vendas.
>
> Atue como analista de requisitos e arquiteto de software.
>
> Analise minha ideia, identifique os requisitos funcionais e não funcionais e proponha uma arquitetura simples.
>
> Considere facilidade de manutenção, segurança, custos e possibilidade de expansão.
>
> Não adicione tecnologias ou funcionalidades desnecessárias. Explique suas decisões e identifique informações importantes que ainda estejam faltando.

**Dica:** não aceite automaticamente a primeira arquitetura apresentada. Peça alternativas, compare tecnologias e compreenda por que determinada solução foi escolhida.

---

## 2. Engenharia de prompts

A qualidade das instruções influencia a capacidade da IA de compreender e executar uma tarefa.

Uma estrutura útil é:

**Contexto + Objetivo + Instruções + Restrições + Formato + Critérios de qualidade**

Essa estrutura não precisa ser utilizada integralmente em todas as solicitações. A complexidade do prompt deve acompanhar a complexidade da tarefa.

### Técnicas recomendadas

- **Forneça contexto:** explique o projeto, as tecnologias utilizadas e o problema.
- **Defina o objetivo:** descreva claramente o resultado esperado.
- **Apresente exemplos:** demonstre comportamentos ou resultados desejados.
- **Estabeleça restrições:** informe o que não deve ser implementado.
- **Defina critérios de qualidade:** segurança, legibilidade, desempenho, acessibilidade e manutenção.
- **Divida tarefas complexas:** evite solicitar dezenas de funcionalidades simultaneamente.
- **Peça análise crítica:** permita que a IA questione decisões inadequadas.
- **Solicite verificação:** peça testes e explicações sobre limitações identificadas.

### Evite prompts excessivamente grandes

Mais texto não significa necessariamente melhores resultados.

Prompts com instruções redundantes, contraditórias ou desorganizadas podem prejudicar a execução.

O importante é fornecer informações relevantes e verificáveis.

### Trabalhe em ciclos

1. Apresente a ideia.
2. Solicite uma estrutura inicial.
3. Analise e corrija as propostas.
4. Defina as tecnologias e os requisitos.
5. Implemente funcionalidades progressivamente.
6. Execute testes e revise o resultado.

**Engenharia de prompt não é apenas escrever instruções detalhadas. É avaliar o comportamento da IA e aperfeiçoar as instruções conforme os resultados obtidos.**

---

## 3. Ferramentas que auxiliam na programação com IA

Não existe uma única ferramenta ideal para todas as etapas de desenvolvimento.

A combinação de ferramentas diferentes pode melhorar o planejamento, a qualidade visual, a implementação e a manutenção de um projeto.

### ChatGPT — Planejamento e engenharia de prompts

Site: https://chatgpt.com/

Utilize para:

- Estruturar ideias e projetos.
- Elaborar prompts para agentes de programação.
- Comparar linguagens, frameworks e arquiteturas.
- Explicar conceitos técnicos.
- Analisar regras de negócio.
- Identificar possíveis erros de planejamento.
- Organizar documentação e requisitos.
- Revisar abordagens técnicas.

**Recomendação:** utilize o ChatGPT para compreender e definir o que deverá ser desenvolvido antes de solicitar a implementação.

### Google Antigravity — Desenvolvimento com agentes de IA

Site: https://antigravity.google/

Ambiente de desenvolvimento com recursos de agentes capazes de trabalhar com arquivos, código, terminal e ferramentas de navegador.

Pode auxiliar em:

- Desenvolvimento de aplicações.
- Implementação de funcionalidades.
- Refatoração de código.
- Identificação e correção de bugs.
- Criação e execução de testes.
- Análise de projetos existentes.
- Revisão de alterações.

**Boa prática:** forneça ao agente o contexto do projeto, suas regras e os critérios de aceitação. Revise alterações importantes antes de aplicá-las.

### Google Stitch — Design de interfaces com IA

Site: https://stitch.withgoogle.com/

Ferramenta voltada à criação e exploração de interfaces de usuário utilizando Inteligência Artificial.

Pode auxiliar em:

- Criação de conceitos visuais.
- Desenvolvimento de layouts.
- Exploração de cores e componentes.
- Prototipação de telas.
- Experimentação de diferentes estilos.
- Geração de propostas de interface e código frontend.

**Recomendação:** antes de programar a interface, utilize o Stitch para explorar visualmente o projeto e decidir como o usuário deverá interagir com a aplicação.

### Google AI Studio — Prototipação e integração com IA

Site: https://aistudio.google.com/

Ambiente para experimentar modelos Gemini, testar prompts, criar protótipos e desenvolver aplicações com recursos de IA.

Pode auxiliar em:

- Experimentação com modelos Gemini.
- Desenvolvimento de protótipos.
- Testes de integração com a Gemini API.
- Criação de aplicações assistidas por IA.
- Avaliação de respostas de modelos.
- Exploração de funcionalidades multimodais.

**Recomendação:** utilize o AI Studio para experimentar funcionalidades de IA antes de incorporá-las a um sistema maior.

---

## 4. Inspiração visual e design amigável

Uma aplicação pode funcionar corretamente e ainda assim apresentar uma experiência ruim ao usuário.

A interface deve facilitar a compreensão e a execução das tarefas.

### Pinterest — Pesquisa de referências visuais

Site: https://www.pinterest.com/

O Pinterest pode auxiliar na descoberta de ideias para:

- Paletas de cores.
- Dashboards administrativos.
- Landing pages.
- Formulários.
- Interfaces minimalistas.
- Tipografia.
- Organização de componentes.
- Identidades visuais.

Pesquise termos como:

- `SaaS dashboard UI`
- `Minimal web design`
- `Modern admin dashboard`
- `Login page UI`
- `Mobile app UX`
- `Dark dashboard design`

Utilize as referências para compreender padrões e construir sua própria identidade visual.

**Atenção:** inspiração não significa copiar integralmente uma interface, ilustração ou identidade visual de terceiros. Verifique licenças e direitos de uso dos recursos.

### Outras ferramentas úteis

**Figma:** criação de protótipos, wireframes, componentes e sistemas de design.

**Google Fonts:** escolha de fontes adequadas ao estilo e à legibilidade do sistema.

**Lucide:** biblioteca de ícones consistente e adequada para interfaces modernas.

**Coolors:** exploração e construção de paletas de cores.

**Mobbin:** referência para estudar padrões de interfaces e fluxos de experiência do usuário.

### Princípios para criar boas interfaces

**Simplicidade**

Evite elementos desnecessários. A interface deve mostrar o que é importante para o usuário.

**Consistência**

Utilize padrões de cores, botões, tipografia, espaçamentos e componentes.

**Hierarquia visual**

As ações mais importantes precisam ser fáceis de encontrar.

**Feedback**

Informe ao usuário quando uma ação foi concluída, quando houve um erro ou quando uma operação está em andamento.

**Responsividade**

Garanta que a aplicação funcione adequadamente em computadores, tablets e celulares.

**Acessibilidade**

Considere contraste, navegação por teclado, rótulos de formulários e compatibilidade com tecnologias assistivas.

**Desempenho**

Evite animações pesadas, imagens desnecessariamente grandes e efeitos que dificultem a navegação.

### Exemplo de prompt para design

> Desenvolva uma proposta de interface para um sistema administrativo de vendas.
>
> O público será composto por pessoas com diferentes níveis de conhecimento tecnológico.
>
> Utilize um design moderno, minimalista, responsivo e acessível.
>
> Priorize navegação intuitiva, formulários claros, boa hierarquia visual e feedback para ações importantes.
>
> Evite animações excessivas, elementos decorativos desnecessários e telas com informações demais.
>
> Organize a experiência para que as funcionalidades mais utilizadas sejam encontradas facilmente.

---

## 5. Escolhendo as tecnologias do projeto

Uma das decisões mais importantes é selecionar tecnologias compatíveis com o problema.

Não existe uma stack universalmente superior.

A escolha deve considerar os requisitos, a complexidade, a familiaridade da equipe, a manutenção e os custos.

### Frontend

Responsável pela interface e pela interação do usuário.

Tecnologias comuns:

- HTML, CSS e JavaScript.
- React.
- TypeScript.
- Tailwind CSS.
- Next.js.

### Backend

Responsável pelas regras de negócio, autenticação, processamento e comunicação com serviços externos.

Exemplos:

- FastAPI com Python.
- Express com Node.js.
- NestJS com TypeScript.
- Spring Boot com Java.

### Banco de dados

Responsável pela persistência das informações.

Exemplos:

- PostgreSQL.
- MySQL.
- SQLite.
- Supabase, como plataforma baseada em PostgreSQL.

### Deploy e hospedagem

Ferramentas e serviços como Vercel, Railway e Render podem auxiliar na publicação de aplicações, dependendo dos requisitos.

**Importante:** não utilize uma arquitetura complexa apenas porque a IA recomendou. Para projetos pequenos, uma solução simples e bem estruturada costuma ser mais adequada.

---

## 6. Desenvolvendo com agentes de IA

Ferramentas como o Google Antigravity podem executar tarefas que envolvem múltiplos arquivos e etapas.

Entretanto, agentes de programação precisam de instruções, contexto e limites claros.

### Antes de solicitar uma implementação

Informe:

1. O objetivo da funcionalidade.
2. A estrutura atual do projeto.
3. As tecnologias utilizadas.
4. As regras de negócio.
5. Os arquivos ou módulos envolvidos.
6. As restrições de segurança.
7. Os critérios de aceitação.

### Exemplo de prompt

> Analise a estrutura atual deste projeto antes de modificar qualquer arquivo.
>
> Quero implementar uma funcionalidade de cadastro de usuários.
>
> Utilize a arquitetura e os padrões já existentes.
>
> Valide as informações no backend, proteja as credenciais e implemente controles adequados de autenticação e autorização.
>
> Não altere funcionalidades que não estejam relacionadas à tarefa.
>
> Crie testes para os principais comportamentos e situações de erro.
>
> Ao finalizar, apresente os arquivos modificados, as decisões técnicas, os testes executados e possíveis limitações.

### Utilize documentação de contexto

Arquivos como `README.md`, `AGENTS.md` e documentos de arquitetura podem ajudar agentes compatíveis a compreender o projeto.

Mantenha documentadas as tecnologias, regras, convenções e decisões importantes.

Não conceda permissões irrestritas para comandos destrutivos ou acesso a dados sensíveis.

---

## 7. Segurança no desenvolvimento com IA

Código gerado por IA não é necessariamente seguro.

A segurança deve fazer parte do planejamento, implementação, testes e publicação.

### Boas práticas essenciais

- Nunca exponha senhas, tokens privados ou chaves secretas no frontend.
- Não publique credenciais em repositórios.
- Valide entradas no servidor.
- Utilize consultas parametrizadas para prevenir SQL Injection.
- Proteja a aplicação contra XSS.
- Implemente autenticação e autorização corretamente.
- Utilize algoritmos adequados para hash de senhas.
- Proteja operações contra CSRF quando aplicável.
- Configure HTTPS e cookies de autenticação de maneira segura.
- Não exponha informações sensíveis em mensagens de erro ou logs.
- Verifique vulnerabilidades nas dependências utilizadas.
- Revise permissões e regras de acesso ao banco de dados.

### Prompt base de segurança

> Ao implementar funcionalidades, considere princípios de segurança desde o início.
>
> Identifique riscos relacionados a autenticação, autorização, validação de dados, injeções e exposição de credenciais.
>
> Utilize mecanismos de proteção apropriados para a arquitetura do projeto.
>
> Não considere uma funcionalidade segura apenas porque o código foi gerado sem erros.
>
> Crie testes apropriados e apresente vulnerabilidades conhecidas, limitações e verificações que ainda precisam ser realizadas.

### Referência

OWASP Cheat Sheet Series: https://cheatsheetseries.owasp.org/

**Uma instrução de segurança não substitui auditorias, testes e revisão técnica.**

---

## 8. Testes e qualidade de software

Não basta verificar se uma aplicação abre no navegador.

Um sistema precisa se comportar corretamente diante de situações normais e inesperadas.

### O que testar?

- Regras de negócio.
- Campos e formulários.
- Autenticação e autorização.
- Comunicação com APIs.
- Integrações com banco de dados.
- Tratamento de erros.
- Comportamento em dispositivos móveis.
- Segurança e acessibilidade.

### Ferramentas úteis

**Vitest / Jest:** testes automatizados em projetos JavaScript e TypeScript.

**Pytest:** testes em aplicações Python.

**Playwright:** testes de navegação e fluxos completos no navegador.

**Postman:** exploração e testes de APIs.

**GitHub Actions:** automação da execução de testes e verificações.

### Boas práticas

Solicite à IA que identifique casos de teste relevantes, mas não confie somente na avaliação do mesmo agente que implementou o código.

Sempre que possível:

- Execute os testes em um ambiente controlado.
- Revise o que cada teste realmente verifica.
- Inclua cenários de falha.
- Teste os principais fluxos manualmente.
- Verifique se alterações não quebraram funcionalidades anteriores.

---

## 9. Controle de versão e publicação

Utilize Git e GitHub desde o início do desenvolvimento.

Eles permitem acompanhar alterações, trabalhar em equipe e recuperar versões anteriores.

### Recomendações

- Faça commits pequenos e descritivos.
- Revise alterações geradas por IA antes de confirmar.
- Utilize branches para funcionalidades maiores.
- Configure um `.gitignore` apropriado.
- Não envie arquivos contendo credenciais.
- Documente as instruções de instalação e execução.
- Configure testes automatizados quando possível.

Ao publicar, verifique também configurações de produção, variáveis de ambiente, logs e permissões de acesso.

---

## 10. Método prático: da ideia à aplicação

Uma sugestão de processo para utilizar as ferramentas em conjunto:

**Etapa 1 — Planejamento com ChatGPT**

Transforme sua ideia em objetivos, requisitos e regras de negócio.

**Etapa 2 — Pesquisa visual com Pinterest**

Busque referências para compreender estilos e soluções de interface.

**Etapa 3 — Prototipação com Stitch**

Crie propostas de telas e refine o design pensando na experiência do usuário.

**Etapa 4 — Experimentação com Google AI Studio**

Teste protótipos e recursos de IA que poderão fazer parte da aplicação.

**Etapa 5 — Desenvolvimento com Antigravity**

Implemente as funcionalidades conforme a arquitetura e os requisitos definidos.

**Etapa 6 — Testes e revisão**

Valide funcionalidades, segurança, experiência do usuário e comportamento do sistema.

**Etapa 7 — GitHub e deploy**

Versione, documente e publique a aplicação.

As etapas podem ser repetidas conforme o projeto evolui.

---

## 11. Aprenda a questionar a IA

Uma das habilidades mais importantes no desenvolvimento assistido por IA é saber avaliar as sugestões recebidas.

Não aceite automaticamente uma solução apenas porque ela foi apresentada com confiança.

Um assistente útil deve identificar limitações, questionar premissas e justificar decisões técnicas.

### Prompt para comportamento crítico

> Atue como um assistente técnico crítico e colaborativo.
>
> Priorize precisão, simplicidade, segurança e qualidade.
>
> Não concorde automaticamente com minhas decisões.
>
> Quando identificar uma solução inadequada, explique o problema e apresente alternativas.
>
> Não adicione complexidade desnecessária ao projeto.
>
> Quando houver informações insuficientes, explicite suas suposições e solicite esclarecimentos apenas quando forem essenciais.
>
> Para tarefas complexas, proponha uma estratégia e realize a implementação de forma organizada.
>
> Ao finalizar, diferencie claramente o que foi implementado, o que foi testado e o que ainda precisa ser validado.
>
> Meu objetivo não é apenas receber código funcional, mas compreender as decisões e aprender durante o desenvolvimento.

---

## 12. Limitações da programação com IA

A Inteligência Artificial pode acelerar o desenvolvimento, mas também pode introduzir problemas.

Alguns riscos:

- Geração de bibliotecas ou métodos inexistentes.
- Utilização de dependências inadequadas ou desatualizadas.
- Alterações não solicitadas.
- Introdução de vulnerabilidades.
- Criação de arquiteturas excessivamente complexas.
- Testes superficiais.
- Falta de compreensão das regras de negócio.
- Consumo desnecessário de tokens e recursos.

**Utilize a IA como ferramenta de desenvolvimento, não como substituta da validação técnica e da responsabilidade sobre o software.**

---

## Conclusão

Programar com Inteligência Artificial envolve muito mais do que escrever prompts.

É saber transformar problemas em requisitos, escolher tecnologias adequadas, projetar interfaces amigáveis, implementar funcionalidades, testar resultados e manter aplicações seguras.

Ferramentas como ChatGPT, Antigravity, Stitch e Google AI Studio podem contribuir em diferentes etapas desse processo.

O diferencial está em saber quando utilizar cada ferramenta, compreender suas limitações e manter o controle das decisões.

**O objetivo não é apenas fazer a IA escrever código. É aprender a construir software de qualidade com o auxílio dela.**

---

## Autor

**Inshock04**

Estudante de Análise e Desenvolvimento de Sistemas, com interesse em Inteligência Artificial, desenvolvimento de aplicações e automação de processos.

GitHub: https://github.com/Inshock04

Material educacional desenvolvido para compartilhar conhecimentos, experiências práticas e boas práticas de programação assistida por IA.
