## Histórico de Versões

Data|Versão|Descrição|Autor
-|-|-|-
17/02|0.1|Abertura do Documento de Visão| Equipe|
04/03|0.2|Adição dos itens 5, 6 e 7| Roberto|
26/03|0.2|Atualizando contéudo da página| Rodrigo|


## 1. <a name="1">Introdução</a>

### 1.1 <a name ="1_1">Propósito</a>

<p align="justify"> &emsp;&emsp; Este documento tem por objetivo estabelecer um posicionamento sobre a aplicação, suas características e seu desenvolvimento em questão. Também expondo as suas funcionalidades e definindo seus requisitos em termos de necessidade para usuários finais.</p>

### 1.2 <a name="1_2">Escopo</a>

<p align="justify"> &emsp;&emsp; Um dos fatores que definem o sucesso acadêmico de um estudante da Universidade de Brasília são seus professores, pois, dependendo deles, o aluno terá uma experiência diferente em relação à disciplina. Alguns professores cobram mais e outros menos, de fato o aprendizado de um estudante não depende apenas dele mesmo e sim de um conjunto de aspectos incluindo o seu professor. Sendo a finalidade desse projeto, disponibilizar uma forma confiável dos estudantes escolherem seus próprios professores.</p>

### 1.3 <a name=1_3>Definições, acrônimos e abreviações</a>

* FGA - Faculdade do Gama (UnB)
* UnB - Universidade de Brasília
* MDS - Métodos de Desenvolvimento de Software

### 1.4 <a name="1_4">Visão geral</a>
<p align="justify"> &emsp;&emsp; Este documento é dividido em 5 tópicos descrevendo os detalhes das características do software proposto.
Sendo dividido em:</p>

* **Introdução:** é apresentado os detalhes gerais sobre a visão do projeto;
* **Posicionamento:** é descrito o problema, o produto e a oportunidade de negócio;
* **Descrição dos envolvidos:**  são detalhados os envolvidos no projeto;
* **Visão Geral:** fornece uma visualização das capacidades do produto, interfaces e configurações dos sistemas;
* **Recursos:** são descritos os recursos do produto;
* **Restrições:** são apresentadas as restrições do projeto;
* **Requisitos:** são apresentadas as funcionalidades do projeto e suas prioridades;
___

## 2. <a name="2">Posicionamento</a>
<p align="justify">&emsp;&emsp; A maior parte dos estudantes entram na universidade com um grande anseio por conhecimento, porém com o tempo, esse desejo acaba sendo anulado por professores que não possuem uma boa didática, ou não se dedicam a ajudar o estudante, ou apenas docentes que possuem uma metodologia que não compatível à alguns dos alunos.</p>

### 2.1 <a name="2_1">Oportunidade de Negócio</a>

<p align="justify">&emsp;&emsp; O projeto dá ao aluno a opção de escolher com mais segurança o professor com o qual deseja aprender naquele semestre, baseando-se na análise de quem já tinha tido alguma experiência com esse docente. Além de que, a aplicação visa disponibilizar de maneira rápida, fácil, respeitável e democrática, um feedback àqueles que se dedicam a ensinar.</p>

### 2.2 <a name="2_2">Descrição do problema</a>

|**Questão**|**Informações do Produto**|
|:-|:-|
|**O Problema é**|Falta de conhecimento prévio sobre os professores e as disciplinas.|
|**Que afeta**|A comunidade acadêmica. |
|**Cujo impacto é**|O aluno não encontrar uma metodologia de ensino compatível com si mesmo.|
|**Uma boa solução seria**|Uma aplicação que permita os alunos compartilharem entre si as experiências com as disciplinas e professores.|

### 2.3 <a name="2_3">Descrição da Posição do Produto</a>

<p align="justify">&emsp;&emsp;A aplicação, quando desenvolvida, se posicionará no mercado como uma aplicação web que pode ser usada facilmente em navegadores mobile proporcionando uma experiência muito parecida a de um app nativo. Isso proporciona que os alunos troquem experiências de suas disciplinas realizadas de forma eficiente e rápida, possibilitando que os alunos encontrem metodologias de ensino compatíveis com si mesmo.</p>


## 3. <a name="3">Descrição dos Envolvidos</a>

|**Nome**|**Descrição**|
|:-|:-|
| Estudantes da UnB| Estudantes procurando um bom professor ou metodologia. |
|Professores da UnB| Professores com desejo de melhorar a própria avaliação. |

## 4. <a name="4">Visão Geral</a>
<p align="justify"> &emsp;&emsp; A aplicação tem como objetivo criar um ambiente específico para que haja uma troca de informações entre os alunos da UnB a respeito dos professores e suas metodologias de ensino, tornando viável que qualquer aluno possa escrever suas próprias avaliações de maneira anônima e ler as avaliações feitas por outros alunos.
</p>

## 5. <a name="5">Recursos do Produto</a>

### 5.1 <a name="5.1">Recursos dos Discentes</a>

<p align="justify"> &emsp;&emsp; Os alunos poderão se cadastrar na aplicação. Quando cadastrados e logados, poderão ter acesso aos seguintes recursos:</p>

* Fazer avaliação dos professores;
* Visualizar avaliações feitas sobre outros professores;
* Concordar ou discordar do comentário de outros discentes;
* Visualizar a quantidade de alunos que concordam e discordam desses comentários;
* Pesquisar os professores por ranking;
* Denunciar avaliações ofensivas de outros alunos;

### 5.2 <a name="5.2">Recursos dos Docentes</a>

<p align="justify"> &emsp;&emsp; Os professores poderão também se cadastrar na aplicação. Quando cadastrados e logados, terão acesso às seguintes funcionalidades:</p>

* Visualizar o feedback dos estudantes;
* Visualizar a sua pontuação na aplicação;
* Denunciar avaliações ofensivas feitas por alunos;

## 6. <a name="6">Restrições</a>

### 6.1 <a name="6.1">Restrições de Implementação</a>

<p align="justify">&emsp;&emsp;O sistema será implementado usando ReactJS, Flask e Python, e será desenvolvido de forma remota devido à pandemia.</p>

### 6.2 <a name="6.2">Restrições Externas</a>
<p align="justify">&emsp;&emsp;O grupo não tem muita experiência com as tecnologias utilizadas.</p>

### 6.3 <a name="6.3">Restrições de Design</a>
<p align="justify"> &emsp;&emsp;Toda experiência com a aplicação deve ser limpa e natural. O usuário não deve ter dificuldades de entender o que ele pode fazer, e como encontrar determinada funcionalidade. Além disso, a aplicação será destinada aos usuários web.</p>

### 6.4 <a name="6.4">Restriçõs de Uso</a>
<p align="justify"> &emsp;&emsp;É necessário que os usuários (a comunidade acadêmica) tenham acesso à um computador ou smartphone com acesso à internet para usar todos os recursos da aplicação.</p>

## 7. <a name="7">Requisitos do Produto</a>

### 7.1 <a name="7.1">Lista de categorias dos requisitos do produto:</a>

|**Prioridade**|**Descrição**|
|:-|:-|
| Alta| Requisito indispensável para o funcionamento do sistema|
| Média| Requisito importante, mas a sua não implementação não compromete o funcionamento da aplicação |
| Baixa| Requisito não usado com muita frequência e não é tão necessário para a satisfação do usuário com o projeto |

### 7.2 <a name="7.2">Lista de Requisitos:</a>

|**Identificador**|**Requisito**|**Prioridade**|
|:-|:-|:-|
| RF01| Permitir que o usuário crie uma conta, edite, faça login e a delete| Alta|
| RF02| Permitir que o usuário pesquise professores| Alta|
| RF03| Permitir que o usuário discente crie uma avalição e a delete| Alta|
| RF04| Permitir que o aluno concorde ou discorde do comentário de outro aluno| Alta|
| RF05| Exibir pontuação média e rank dos professores para todos os usuários | Alta|
| RF06| Permitir que os discentes façam avaliações anônimas | Média|
| RF07| Exibir quantidade de avaliações que o usuário discente já realizou| Média|
| RF08| A aplicação deve ter a experiência de uso simples e fluída, de linguagem fácil intuitiva| Alta|
| RF09| Permitir o usuário a denunciar um comentário| Média|
| RF10| Permitir que o docente veja as avaliações sobre si mesmo| Média|  
| RF11| Exibir ao aluno a quantidade de pessoas que concordam e discordam dos seus comentários| Baixa|  

## 8. Referências

CARVALHO, Durval; et al. Documento de Visão - Acacia. Disponível em: <https://fga-eps-mds.github.io/2019.2-Acacia/#/vision_documents>. Acesso em: 04 mar 2021.

FÉLIX, Bruno; et al. Documento de Visão - Vamos Cuidar. Disponível em: <https://fga-eps-mds.github.io/2020.1-VC_Usuario/#/docs/Documento_de_Visao>. Acesso em: 04 mar 2021.

LUCAS, Jõao; et al. Documento de Visão - ArBC. Disponível em: <https://jlucassr.github.io/ArBC-Pages/mds/Documento_de_visao/>. Acesso em: 04 mar 2021.