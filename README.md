# Análise PostMortem


### "É melhor prevenir do que remediar"

Qualquer médico lhe dirá isso. E o mesmo acontecerá com qualquer paciente doente. Então, por que uma sabedoria milenar como essa raramente é praticada?

- Poucas pessoas se exercitam e se alimentam bem antes de perceberem que sua saúde está ruim;
- Você raramente vê alguém fazer a manutenção do carro antes que ele estrague;
- Ninguém troca o teto até a água pingar na cabeça.

O que é curioso sobre esses problemas é que eles raramente surgem do nada. Eles não são surpresas;

- Você pode sentir-se lentamente saindo de forma.
- Você sabe que se você nunca trocar seu óleo, seu carro vai estragar.
- Todos os dias você chega em casa e, por uma fração de segundo, percebe um problema no teto antes de passar para assuntos mais urgentes.

Felizmente,  há uma coisa simples que você pode fazer para salvar qualquer projeto do desastre. Dedicar um tempo para refletir sobre essa questão é o que nós, no mundo do gerenciamento de produtos, podemos chamar de pre-mortem.

Uma pré-morte é o oposto hipotético de uma pós-morte. Um post-mortem em um ambiente médico permite que os profissionais de saúde e a família aprendam o que causou a morte de um paciente. Todos se beneficiam, exceto, é claro, o paciente. Uma pré-morte em uma configuração de negócios ocorre no início de um projeto e não no final, para que o projeto possa ser aprimorado em vez de autopsiado.

Podemos considerar que o pré-mortem de hoje é parte do pós-mortem de ontem. Pois se aplica em identificar as causas de erros ocorridos no passado. Por isso, é importante que o Pós-Mortem seja realizado para buscar o sucesso no desenvolvimento de software.

---------

## Post-Mortem no Desenvolvimento de Software
> Atividade de aprendizado coletivo, a qual pode ser organizada para projetos seja quando  termina uma fase ou quando é finalizado. A principal motivação é refletir sobre o que aconteceu no projeto, de forma que se possa aprimorar práticas futuras - para os indivíduos que dele participaram e para a organização como um todo.

### A única coisa pior do que cometer erros, é cometer os mesmos novamente...



Um bom profissional, de qualquer área, aprende com os próprios erros. Realizar uma análise post-mortem ao final de um projeto ou demanda pode ajudar a aprender com os acertos e, mais importante, com os erros.

---


## Análise Postmortem ou Revisão de Projeto

[Alguns artigos](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.19.9762&rep=rep1&type=pdf)  definem  a  APM  com  palavras  diferentes,  tais  como  "Revisão  de Projeto",  "Auditorias  de   Projeto",  "Lições  Aprendidas",  dentre   outras.   Todas  as  definições possuem  um  objetivo  único,  retirar  experiências  vividas  em  projetos  e  disseminá-las aos outros  projetos  de  uma  organização,  para  que  a  organização  aprenda  com  os  seus  erros, mitigando-os  e  repetindo  o  que  deu  certo  como  boas  práticas.  Em  projetos  de  software  essa abordagem é mais conhecida como Análise Postmortem (APM).



---


## 

A  APM  é  um  método  ágil,  de  custos  e  complexidade  baixos  adequado para se iniciar a Gestão do Conhecimento em projetos de software. As principais técnicas de coleta e análise de experiências utilizadas são o "Método KJ" e o "Diagrama de Ishikawa".

[O Método KJ](https://www.researchgate.net/publication/243785588_The_KJ_Method_A_Technique_for_Analyzing_Data_Derived_from_Japanese_Ethnology#:~:text=The%20KJ%20method%20is%20a,writing%20of%20explanations.%20...), proposto por [Kawakita](https://www.google.com/search?q=Jiro+Kawakita&sourceid=chrome&ie=UTF-8), consiste de quatro passos:
- Passo  1: As  informações  relevantes  sobre o problema  em  questão  são  escritas  em cartões. Cada cartão contém somente uma observação relacionada ao problema;
- Passo   2: Os   cartões   são   agrupados   por   afinidades.   Os   grupos   resultantes   são destacados e recebem títulos, que são escritos em novos cartões.
- Passo  3: Os  grupos  são  relacionados  através  de  linhas  e  setas,  revelando  as  inter-relações (causa e efeito, ordem de ocorrência, etc), surgindo o diagrama KJ.
- Passo  4: O  diagrama  é  explicado  verbalmente,  constituindo  uma  síntese  dos  dados observados. A explanação detalha os relacionamentos do diagrama de forma precisa e lógica.

[O  Diagrama  Ishikawa](https://www.siteware.com.br/metodologias/diagrama-de-ishikawa/),  criado  em  1943  por  Ishikawa,  é  também  conhecido  como "Diagrama  de  Causa  e  Efeito"  e  "Diagrama  de  Espinha  de  Peixe".  O  diagrama  estrutura hierarquicamente  as  causas  de  determinado  problema  de  forma  gráfica  e  sintética  [8], facilitando  a  compreensão  do  problema  sob  análise,  permitindo  assim  o  estabelecimento  de melhorias no processo adotado [7].
São 8 passos para desenvolver um diagrama de Ishikawa:
- Passo 1: Descrever o tópico (fato, sintoma) sob análise à direita do diagrama;
- Passo 2: Traçar uma seta horizontal apontando para a incidência. Essa seta é a espinha dorsal a partir da qual as causas serão desenvolvidas;
- Passo 3: Identificar as causas em potencial e agrupá-las em grandes categorias.
- Passo  4:  Realizar brainstorming   para   revelar  as  causas  das  grandes  categorias identificadas.  Adicionar  as  novas  causas  em  linhas  que  se conectam  às  respectivas  linhas  de grandes categorias.
- Passo 5: Identificar as causas de maior prioridade para investigação mais detalhada.
- Passo 6: Utilizar de votação caso não haja consenso acerca das causas prioritárias.
- Passo 7: Discutir o impacto de cada causa identificada.
- Passo 8: Criar um plano de ação para resolver a causa.

------------------------------

À medida que as equipes aprimoram seus próprios processos pré-mortem, as empresas estão vendo resultados. O Airbnb fez isso em um nível mais amplo, pedindo que os [funcionários mudassem sua mentalidade](https://www.inc.com/adam-vaccaro/airbnb-demise.html) para pensar sobre as formas pelas quais a empresa poderia ir. Nos anos desde que isso tem sido uma prática, seu negócio tem obtido grande sucesso. Então, isso deixa a pergunta: o que pode te derrubar?

----
- https://www.fernandoike.com/pt/2017/08/21/blameless-a-culpa-nao-e-sua/
- https://www.fernandoike.com/pt/2017/09/07/blameless-postmortem/
