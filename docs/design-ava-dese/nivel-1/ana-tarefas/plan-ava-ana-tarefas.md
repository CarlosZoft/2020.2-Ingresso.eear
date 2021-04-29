## Introdução
&emsp;&emsp;Em um processo de desenvolvimento de sistemas interativos de alta qualidade de uso, faz-se fundamental e muito necessária a valiação de IHC. Alguns dos métodos de avalição de IHC permitem usar como objetos de estudo desde uma lista de tarefas a serem realizadas individualmente até a usabilidade geral do sistema.<br>
&emsp;&emsp;Sendo assim, esse documento visa destrinchar o planejamento da avaliações do artefato de [análise de tarefas](../../../analise-de-requisitos/analise-de-tarefas.md) e o relato de seus resultados.

## Metodologia
&emsp;&emsp;Antes de se aplicar uma metodologia de avaliação de IHC, seja na usabilidade em si do sistema ou em algum artefato gerado no processo, é preciso se definir o objetivo dessa avaliação. Posto isso, tem-se que o objetivo definido pela equipe para essa avalição será: 

- **Checar a coerência da análise de tarefas e sua fidelidade com a utilização do sistema.**

&emsp;&emsp;Definido o objetivo, para partir ao planejamento da avaliação, será necessário definir também um método de avaliação. Sendo assim, levando em consideração o contexto e que se trata de uma avalição de um artefato sobre as tarefas realizadas no sistema, a equipe optou por utilizar o método de inspeção denominada __Percurso Cognitivo.__<br>
&emsp;&emsp;Através da exploração de interface, essa técnica visa a avaliação da facilidade de aprendizado do sistema. O percurso cognitivo guia a inspeção da interface pelas tarefas do usuário o que facilitará na avaliação da análise de tarefas.<br>
&emsp;&emsp;Para se aplicar a avaliação, serão seguidas as seguintes etapas:

|Atividade|Tarefas|
|--|--|
|Preparação|- Definir as tarefas que serão avaliadas;<br>- Definir o perfil do usuário e identificar a persona que será utilizada na avaliação;<br>- Descrever as ações que serão necessárias para realizar a tarefa;<br>- Realizar um teste piloto.|
|Coleta de dados|- Percorrer a interface de acordo com a sequência de ações necessárias para realizar cada tarefa;<br>- Para cada ação enumerada, analisar se o usuário executaria a ação corretamente, respondendo e justificando a resposta às seguintes perguntas:<br>- P1: Essa ação está representada de alguma forma no diagrama HTA?<br>- P2: Os objetivos e operações estão corretamente representados e descritos?<br>- P3: As relações entre os subobjetivos está correta?<br>- P4: A descrição textual está correta?|
|Interpretação e Consolidação dos resultados|Sintetizar resultados sobre:<br>- A conformidade do diagrama e da descrição do HTA com a realidade;<br>- O que precisa ser modificado no diagrama e na descrição do hta.|
|Relato dos resultados|O relato dos resultados do percurso cognitivo podem conter:<br>- Os objetivos e escopo da avaliação;<br>- Uma breve descrição do método de percurso cognitivo, incluindo as perguntas que devem ser respondidas;<br>- O número e o perfil de avaliadores;<br>- A descrição das tarefas analisadas.<br>Para cada tarefa analisada, o relatório deve conter:<br>- Um resumo de como o diagrama e a descrição do hta estão ou não condizentes com a realidade;<br>- Um resumo do que precisa ser modificado no diagrama e na descrição do hta;<br>- Sugestões de solução.|

&emsp;&emsp;Os tópicos a seguir irão abordar o planejamento das etapas das avaliações que serão realizadas.

## Preparação
&emsp;&emsp;Na etapa de preparação, o avaliador deve organizar os objetos do estudo, preparar o material de apoio e realizar um teste piloto.

### Tarefa: [Efetuar a inscrição em concurso;](../../../../analise-de-requisitos/analise-de-tarefas/#efetuar-a-inscricao-em-concurso)
#### Persona: [Cristina Guerra](../../../../analise-de-requisitos/personas/#cristina-guerra)
#### Ações:
1. Acessar a plataforma ingresso.EEAR;
2. Clicar em "Efetuar Inscrição" ou em "Área do candidato";
3. Informar os dados de usuário;
4. Informar o texto da imagem;
5. Clicar no botão entrar;
6. Acessar a tela de exames com incrições abertas;
7. Selecionar um exame;
8. Declarar que leu as instruções;
9. Preencher o formulário de inscrição;
10. Clicar em "Submit Querry".

### Tarefa: [Acompanhar inscriçao em concurso.](../../../../analise-de-requisitos/analise-de-tarefas/#acompanhar-inscricao-em-concurso)
#### Persona: [Alberto da Silva](../../../../analise-de-requisitos/personas/#alberto-da-silva)

#### Ações:
- 1 Acessar a plataforma ingresso.EEAR;
- 2 Clicar em Área do Candidato;
- 3 Clicar em Local das Provas Escritas;
- 4 Clicar em Solicitação de Recursos;
- 5 Preencher os campos do usuário;
- 6 Clicar em Entrar nas Inscrições;
- 7 Visualizar a tela com os Concursos Inscritos;
- 8 Selecionar Concurso em que está Inscrito;
- 9 Visualizar as informações do Concurso.

### Teste Piloto
&emsp;&emsp;O presente teste piloto foi realizado com o untuito de identificar e corrigir potenciais erros no planejamento da avaliação.

- [Teste Piloto](./resultados/teste-piloto-ana.md)
## Coleta de Dados
&emsp;&emsp;Nas atividades de coleta de dados, o avaliador deverá se colocar no lugar do usuário de forma a levar em consideração e se embasando na persona definida para a tarefa que será avaliada. Feito isso deverá ser feita a **simulação da execução das tarefas** que fazem parte do escopo de avaliação.<br>
&emsp;&emsp;Para cada ação, o avaliador deverá responder, justificando a resposta, às seguintes perguntas:

- Essa ação está representada de alguma forma no diagrama HTA?
- Os objetivos e operações estão corretamente representados e descritos?
- As relações entre os subobjetivos está correta?
- A descrição textual está correta?

### Interpretação e Consolidação dos Resultados
&emsp;&emsp;Nessa etapa, os avaliadores devem **analisar as histórias de sucesso e insucesso** sobre a realização das tarefas levando em consideração a conformidade do diagrama e da descrição do HTA com a realidade e o que precisa ser modificado no diagrama e na descrição do hta.

### Relato dos resultados
&emsp;&emsp;Para o relato dos resultados, o avaliador terá que redigir um relatório sintetizando as percepções que teve na avaliação e consolidando os problemas encontrados e as sugestões de correção.
 
## Resultados
&emsp;&emsp;A seguir estão as avaliações com suas etapas detalhadas e os resultados de cada tarefa avaliada;

- [Avaliação 1: Efetuar a inscrição em Concurso;](./resultados/avaliacao-efetua.md)
- [Avaliação 2: Acompanhar inscrição em Concurso.](./resultados/avaliacao-acompanha.md)

## Bibliografia
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) *Interação Humano-Computador e Experiência do usuário.*
## Versionamento

|Versão|Data|Modificação|Autor|
|:-:|--|--|--|
|1.0|04/04/2021|Abertura do documento| Bruno F., Daniel P. |
|1.1|06/04/2021|Adição da introdução, da argumentação pré planejamento e do tópico de preparação| Daniel P. |
|1.2|08/04/2021|Adição do tópico de Coleta de Dados, Interpretação e Consolidação dos Resultados, Relato dos resultados| Bruno F. |
|1.3|08/04/2021|Correção de erros de digitação| Daniel P. |
|1.4|14/04/2021|Adição das análises|Daniel P.|
|1.5|22/04/2021|Ajustes no planejamento para avaliação de artefato| Daniel P.|
|2.0|27/04/2021|Refatoração do planejamento após feedback| Daniel P.|