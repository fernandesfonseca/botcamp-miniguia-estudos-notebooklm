# 📚 Miniguia de Estudos com NotebookLM

> Demonstração prática de aplicação de IA no fluxo de desenvolvimento - Bootcamp CI&T: Do Prompt ao Agente

## 🎯 Contexto e Objetivos

### Assunto Escolhido
Qualidade de Software tradicional e Qualidade de Software com IA 

### Objetivos de Estudo
- [x] Objetivo 1: Qualidade de software tradicional 
- [x] Objetivo 2: Qualidade de Software com IA 
- [x] Objetivo 3: Diferança entra a qualidade de software tradicional com a qualidade de software com ia 

**Justificativa**: Escolhi esse temo por ser minha áera de atuação, pois atuou como analisata de qualidade de software senior e venho cada dia mais aplicando o uso de IA no meu dia a dia, tanto para automação de testes como para aceler processos e entregas. O tema estudado, posso ajudar novos QA Junior e Pleno a evoluirem no contexto. 

---

## 📖 Curadoria de Fontes

Abaixo estão as 3-5 fontes abertas que foram selecionadas e carregadas no NotebookLM para este estudo:

| # | Título | Tipo | Link | Descrição |
|---|--------|------|------|-----------|
| 1 | [Pirâmide de Testes: Uma Estratégia para Qualidade de Software] | Artigo | [[Link da Fonte](https://www.linkedin.com/pulse/pir%C3%A2mide-de-testes-uma-estrat%C3%A9gia-para-qualidade-software-fonseca-zxzqf)] | A Pirâmide de Testes é uma representação gráfica que organiza os tipos de testes em camadas. Sua principal função é orientar os QAs e a equipe de desenvolvimento na definição de estratégias de qualidade |
| 2 | [Automação de Testes: Quando? Como? O que Automatizar? Vale a Pena ou Não?] | Artigo | [[Link da Fonte](https://www.linkedin.com/pulse/automa%C3%A7%C3%A3o-de-testes-quando-como-o-que-automatizar-vale-fonseca-dtdyf)] | Este artigo tem como objetivo explorar as perguntas fundamentais: Quando, como e o que automatizar? E, claro, se vale a pena. |
| 3 | [Diferenciando Bugs, Incidentes e Sugestões de Melhoria na Qualidade de Software] | Artigo | [[Link da Fonte](https://www.linkedin.com/pulse/diferenciando-bugs-incidentes-e-sugest%C3%B5es-de-melhoria-fonseca-fmbdf)] | uem nunca passou por uma situação em uma daily, retrospectiva ou reunião em que um bug/incidente é cadastrado e surgem divergências sobre como classificá-lo? Seria realmente um bug/incidente ou apenas uma sugestão de melhoria? |
| 4 | [O Futuro do QA em 2026: As Ferramentas de Inteligência Artificial que Redefinem a Qualidade] | Artigo | [[Link da Fonte](https://www.linkedin.com/pulse/o-futuro-do-qa-em-2026-ferramentas-de-intelig%C3%AAncia-artificial-borba-vy9ef)] | Breve descrição do conteúdo |
| 5 | [Qualidade de Software do ZERO: Curso Completo em Vídeo ] | Video | [[Link da Fonte](https://www.youtube.com/watch?v=fN3bxqICfvw)] | Este material é parte de um projeto contínuo de melhoria de conteúdos didáticos oferecidos gratuitamente no canal, que vem evoluindo ao longo dos semestres com base no feedback dos estudantes. |

**Critério de Seleção**: 
Utilizei algumas fotes que sempre consumo e utilizo para transmitir para colegas que estão iniciando na área de Qualidade de Software. Acredito que elas ajudam bastante na base 
---

## 🔧 Engenharia de Prompts e "Cicatrizes"

Esta seção documenta a jornada de experimentação com prompts, incluindo testes, dificuldades encontradas e as soluções desenvolvidas.

### Evolução dos Prompts

#### Prompt v1.0 - Primeira Tentativa
```
[Você é um analista de qualidade senior e com base nos seus conhecimenos, me de um resumo sobra a área de qualidade de software do modo tradicional com a inovação e uso de IA]
```
**Resposta Obtida**: [No modo tradicional, a qualidade de software foca em garantir que o produto atenda aos requisitos funcionais e não funcionais do cliente, com bom custo-benefício e ausência de falhas críticas
. Historicamente, essa área atua em duas frentes principais: a verificação (garantir que o produto está sendo construído corretamente através de inspeções e análises estáticas de código) e a validação (garantir que é o produto certo para o usuário, através de testes dinâmicos e de aceitação)
.
A estratégia tradicional baseia-se fortemente na Pirâmide de Testes, que organiza os esforços focando em testes unitários rápidos e baratos na base, seguidos por testes de integração no meio, e testes de ponta a ponta (E2E) mais custosos e lentos no topo
. Além disso, a gestão da qualidade é guiada por processos rigorosos e modelos de maturidade, como ISO (ex: ISO 9001, ISO 25000), CMMI e o MPS.BR, que buscam padronização, planejamento e melhoria contínua
. A automação de testes tradicional exige um alto investimento inicial, criação manual de scripts de automação e manutenção contínua de código e infraestrutura
.
A Inovação e o Uso de Inteligência Artificial (IA) A Inteligência Artificial está redefinindo o cenário de Quality Assurance (QA), resolvendo desafios crônicos como a alta manutenção de testes e a necessidade de velocidade nos pipelines de entrega contínua (CI/CD)
. As principais inovações incluem:
IA Agêntica e Automação Codeless (Sem Código): A IA deixa de ser apenas uma ferramenta de suporte para se tornar um agente autônomo. Plataformas como ACCELQ e TestRigor permitem a criação de testes complexos simulando interações humanas através de linguagem natural ("Plain English"), eliminando a necessidade de codificação tradicional de scripts
.
Auto-recuperação (Auto-Heal): Ferramentas como Tricentis Testim e Mabl utilizam IA generativa para testes adaptativos. Se um elemento na tela (como o ID de um botão) mudar, a IA reconhece o botão pelo seu contexto visual e função, corrigindo o script automaticamente para que o teste não falhe
.
Agentes Copilotos e Geração de Cenários: Modelos de linguagem (LLMs) como ChatGPT, Claude e LambdaTest KaneAI atuam como copilotos. Eles podem gerar casos de teste estruturados (ex: testes de segurança OWASP), auxiliar na documentação ou traduzir comandos naturais em scripts prontos em linguagens como Java com JUnit
.
Análise Preditiva e Detecção Precoce: A IA processa grandes volumes de dados em tempo real para identificar ineficiências e vulnerabilidades logo no início do ciclo de desenvolvimento, prevendo falhas e economizando tempo
.
O Novo Papel do Profissional de QA Com a IA assumindo as tarefas manuais, a escrita massiva de scripts e os testes repetitivos, o papel do profissional de QA sofre uma transformação. O analista passa a ter um foco muito mais estratégico
. Apesar da autonomia das ferramentas, o fator humano continua insubstituível
. O pensamento crítico, a perspectiva real do usuário e a supervisão humana são exigidos para analisar os dados gerados, garantir a segurança das respostas dadas pela IA e assegurar que a automação esteja, de fato, agregando valor ao produto final
.]
**Análise**: [Funcionou muito bem inclusive, deu excelentes sugestões para proximas perguntas]
**Referências Usadas**: [Foram sitadas todas as fontes adicioandas como base]

#### Prompt v2.0 - Refinamento
```
[Com base em seus conhecimentos como analista de qualidade de software senios, quais são os 7 principais fundamentos dos testes de software e como podemos aplicar o uso da IA neles aproveite e explique junto os paradoxos da pesticida na manutenção de testes e como a ia pode ajudar]
```
**Resposta Obtida**: [Os 7 princípios fundamentais dos testes de software, conforme estabelecidos pelo Syllabus, são:
O teste mostra a presença de defeitos e não a sua ausência
.
Testes exaustivos são impossíveis
. Como não é viável testar todas as combinações, deve-se usar a análise de risco e as prioridades para concentrar os esforços de teste
.
O teste inicial economiza tempo e dinheiro
.
Defeitos se agrupam
.
Cuidado com o paradoxo do pesticida
.
O teste depende do contexto
.
Ausência de erros é uma ilusão
.
Como aplicar a IA nestes fundamentos: A Inteligência Artificial está redefinindo o Quality Assurance (QA) e pode potencializar esses princípios automatizando processos e analisando dados.
Para o teste inicial, a IA fornece detecção precoce de bugs e análise preditiva
. Ela processa grandes volumes de dados para prever falhas e identificar vulnerabilidades logo no início do ciclo de desenvolvimento, economizando tempo e custos
.
Como testes exaustivos são impossíveis, a IA otimiza o foco priorizando testes críticos e garantindo uma cobertura adequada
. Plataformas como o ACCELQ Autopilot podem aprender um fluxo de negócios inteiro e gerar cenários de testes modularizados e escaláveis com um clique, cobrindo o processo de ponta a ponta sem que o humano precise codificar tudo exaustivamente
.
Como os defeitos se agrupam, ferramentas de IA analisam padrões em tempo real para encontrar essas áreas problemáticas e ineficiências na aplicação
.
O Paradoxo do Pesticida e o Desafio da Manutenção: O quinto princípio exige "cuidado com o paradoxo do pesticida"
. (Nota: embora as fontes citem o nome do princípio, a sua definição exata não está descrita nelas. Na engenharia de software, este paradoxo afirma que repetir exatamente os mesmos testes continuamente fará com que eles deixem de encontrar novos defeitos, exigindo a criação frequente de novos cenários).
Isso se choca diretamente com um dos maiores desafios crônicos do QA atual: a alta manutenção dos testes
. Atualizar roteiros constantemente para criar]
**Análise**: [Forneci um direcionamento melhor para a pergunta]
**Referências Usadas**: [Todas as fontes cadastradas foram utilizadas]


## 🎓 Reflexão Final

[O projeto desenvolvido durante este bootcamp me proporcionou ampliar meu conhecimento sobre Inteligência Artificial e seus motores de funcionamento, além de compreender melhor o processo de criação de agentes inteligentes.

Um dos pontos mais relevantes da atividade foi a possibilidade de utilizar uma base de conhecimento própria para compartilhar informações e descobertas com os demais colegas, utilizando o NotebookLM como ferramenta de apoio.

Durante o desenvolvimento do projeto, foi possível explorar diferentes possibilidades oferecidas pela ferramenta, percebendo como ela pode ser aplicada para transformar conteúdos em diversos formatos de entrega. Entre eles, apresentações, áudios e até mesmo vídeos, ampliando as formas de comunicação e disseminação do conhecimento.

Essa experiência reforçou o potencial das ferramentas de IA não apenas como apoio ao aprendizado, mas também como meio de estruturar e compartilhar conhecimento de forma mais dinâmica e acessível.]

---

## 🚀 Como Usar Este Repositório

1. **Para Aprender**: Leia os resumos estruturados e consulte o glossário
2. **Para Revisar**: Use os prompts reutilizáveis no NotebookLM ou ChatGPT
3. **Para Ensinar**: Compartilhe sua jornada de aprendizado via repositório
4. **Para Evoluir**: Expanda os prompts para casos de uso ainda não explorados

---

## 📊 Status do Projeto

- [x] Estrutura básica criada
- [x] Curadoria de fontes finalizada
- [x] Engenharia de prompts documentada
- [x] Miniguia de estudo completo
- [x] Reflexão final escrita

---

## 🙋 Contribuições e Feedback

Tem sugestões de melhorias? Encontrou um erro? Abra uma issue ou entre em contato!

---

**Última atualização**: 2026-05-13  
**Bootcamp**: CI&T - Do Prompt ao Agente  
**Autor**: fernandesfonseca
