# Dados - Estudo

# Dados – Explicação Didática

## O que são dados?

Pense em dados como **pedaços de informação bruta**, que ainda não têm significado por si só.

- Podem ser **números, palavras, símbolos, imagens, sons** etc.
- Sozinhos, não dizem nada.

→ Exemplo: o número **30**.

Ele isolado não significa nada… 30 o quê? 30 reais? 30 anos? 30 graus?

Só quando damos contexto é que isso vira **informação**.

---

## Diferença entre **dado** e **informação**

- **Dado** → é a matéria-prima, algo cru e sem interpretação.
- **Informação** → é quando o dado é processado, organizado e recebe um **contexto que dá significado**.

→ Exemplo:

- **Dado:** 30
- **Informação:** "A temperatura é 30 °C"

Percebeu? O mesmo número ganha sentido quando explicamos **o que ele representa**.

---

## Tipos de Dados

Nos bancos de dados e na ciência de dados, classificamos em dois grandes grupos:

### 1) Dados **Quantitativos** (numéricos)

São aqueles que podem ser **contados ou medidos**.

- **Discretos:** contáveis (número de alunos, quantidade de peças).
- **Contínuos:** medidos em escala, podendo variar infinitamente (altura, peso, tempo).

→ Exemplos:

- Idade → 18 anos (discreto)
- Altura → 1,72m (contínuo)
- Preço → R$ 50,00 (contínuo)

---

### 2) Dados **Qualitativos** (descritivos)

Descrevem **características ou categorias**, não são números mensuráveis.

- **Nominais:** não têm ordem → cor do carro (azul, vermelho).
- **Ordinais:** têm ordem → nível de satisfação (ruim, médio, ótimo).

→ Exemplos:

- Gênero: masculino/feminino (nominal)
- Cor dos olhos: castanho, verde, azul (nominal)
- Nível de dor: leve, moderada, intensa (ordinal)

---

## Modelagem de Dados (visão inicial)

Quando guardamos dados em sistemas, precisamos **organizar**.

A modelagem de dados ajuda nisso, usando três conceitos principais:

1. **Entidade** → Em modelagem de dados, o conceito de **entidades** é fundamental para compreender como as informações são organizadas em um sistema de banco de dados. Uma entidade pode ser vista como um objeto ou conceito do mundo real que possui dados relevantes a serem armazenados e gerenciados. A seguir, vamos explorar de forma simplificada o que são entidades e como elas são utilizadas na modelagem de dados.
    
    → Ex.: Cliente, Produto, Pedido, Aluno.
    
2. **Atributos** → são as características que descrevem uma entidade.
    
    → Ex.: Cliente tem Nome, CPF, Endereço.
    
    → Aluno tem Matrícula, Data de Nascimento, Curso.
    
3. **Relacionamento** → é como as entidades se conectam.
    
    → Ex.:
    
    - Aluno **cursa** Disciplina.
    - Cliente **faz** Pedido.
    - Pedido **possui** Produto.

---

# Como explicar de forma natural

Se você precisar **explicar em voz alta**, pode usar essa sequência:

1. **Começa com algo simples e cotidiano:**
    
    "Dado é um fato cru, como o número 30. Sozinho, não tem significado."
    
2. **Mostra a diferença para informação:**
    
    "Quando eu digo '30 graus de temperatura', aí sim virou informação."
    
3. **Classifica os dados com exemplos fáceis:**
    - "Se for um número que dá pra contar ou medir, é quantitativo.
    - Se for uma característica, tipo cor ou opinião, é qualitativo."
4. **Fala de entidades, atributos e relacionamentos com um exemplo único:**
    
    "Num sistema escolar, a entidade é o Aluno, os atributos são Nome, Matrícula, Idade, e o relacionamento é que o Aluno faz uma Disciplina."
    

---

# Modelos de Dados (Resumo Didático)

### Principais modelos

- **Modelo Relacional:** organiza os dados em **tabelas** (linhas = registros, colunas = atributos). É o mais usado em bancos de dados tradicionais.
- **Modelos NoSQL:** usados para dados **não estruturados** ou **grandes volumes (Big Data)**. Principais tipos:
    - **Documentos:** armazenam dados em JSON/BSON.
    - **Chave-Valor:** pares simples, usados em cache e sessões.
    - **Colunar:** dados organizados em colunas, bom para análises.
    - **Grafos:** representam relações complexas, como em redes sociais.

---

### Características do Modelo Relacional

- **Estrutura em tabelas:** linhas (tuplas) e colunas (atributos).
- **ACID:** garante segurança nas transações:
    - Atomicidade (tudo ou nada)
    - Consistência (dados sempre válidos)
    - Isolamento (transações independentes)
    - Durabilidade (dados não se perdem).
- **SQL:** linguagem padrão para consultas e manipulação.
- **Normalização:** organiza dados para evitar redundância.
- **Relacionamentos:** permite ligar tabelas (ex.: cliente faz pedidos).

---

# Resumão de Modelagem de Dados

### Diagrama Entidade-Relacionamento (ER)

- **Para que serve:** mostra como entidades (objetos do mundo real) se relacionam entre si, ajudando a projetar bancos de dados.
- **Principais elementos:**
    - **Entidades** → objetos (ex.: Cliente, Produto).
    - **Atributos** → características da entidade (ex.: Nome, CPF).
    - **Relacionamentos** → ligações entre entidades (ex.: Cliente faz Pedido).
- **Cardinalidade:** indica a quantidade de instâncias que se relacionam (1:1, 1:N, N:N).

---

### Chaves em Banco de Dados

- **Chave primária:** identificador único de um registro (não se repete, não pode ser nulo).
- **Chave estrangeira:** campo que referencia a chave primária de outra tabela, criando vínculo e garantindo integridade.

---

### Normalização

- **O que é:** processo de organizar os dados em tabelas relacionadas para reduzir redundância e inconsistências.
- **Objetivo:** manter integridade e eficiência.
- **Formas normais (básicas):**
    - **1FN:** sem valores repetidos ou múltiplos na mesma célula.
    - **2FN:** cada coluna depende totalmente da chave primária.
    - **3FN:** elimina dependências de colunas que não são chave.

---

### Erros comuns na modelagem

- Falta de clareza do propósito.
- Não remover redundâncias.
- Nomenclatura confusa.
- Ignorar testes e validação.

**Impacto:** baixa confiabilidade, lentidão, custos extras, más decisões.

---

### Aplicações práticas

- **SGBDs (MySQL, PostgreSQL, etc.):** guardam e organizam dados em tabelas → usados em redes sociais, e-commerces etc.
- **Data Warehousing:** integração de dados para análises de negócio.
- **Saúde:** registros médicos organizados para acompanhamento de pacientes.

---

### Importância da modelagem

→ estrutura clara, menos erros, melhor desempenho e comunicação entre equipes.

---

## Etapas da Modelagem de Banco de Dados

### 1. Minimundo

- Representa um **recorte do mundo real** que será modelado.
- Consiste em compreender o **contexto** e identificar as **entidades relevantes** (objetos ou conceitos importantes para o sistema).
- Exemplo: em um sistema de biblioteca, o minimundo envolve livros, autores, usuários, empréstimos etc.

---

### 2. Levantamento de Requisitos

- **Objetivo:** descobrir **o que o sistema deve fazer** e quais informações são necessárias.
- Inclui:
    - Entrevistas com cliente/usuário.
    - Identificação das **funcionalidades**.
    - Definição de quais dados serão armazenados.
- Resultado: lista de **requisitos funcionais** (o que o sistema faz) e **requisitos não funcionais** (como o sistema deve se comportar, ex.: desempenho, segurança).

---

### 3. Definição de Atributos

- Cada entidade recebe **atributos** que descrevem suas características.
- Os atributos devem ser:
    - **Relevantes** (não guardar informações inúteis).
    - **Consistentes** (um mesmo dado não deve estar em locais diferentes de forma redundante).
- Exemplo: na entidade *Usuário*, atributos podem ser *nome, CPF, endereço, telefone*.

---

### 4. Modelagem Conceitual

- Criação do **Modelo Conceitual** (normalmente usando o **DER – Diagrama Entidade-Relacionamento**).
- Representa **entidades, atributos e relacionamentos** de forma visual.
- Foco: **clareza e abstração** (sem ainda pensar em tabelas ou tecnologia específica).
- Exemplo: mostrar que um *Usuário* pode realizar vários *Empréstimos* e cada *Livro* pode estar em apenas um *Empréstimo* por vez.

---

### 5. Escolha da Ferramenta de Modelagem

- Existem diferentes ferramentas (Astah, Draw.io, MySQL Workbench, DBDesigner etc.).
- A escolha deve considerar:
    - **Facilidade de uso.**
    - **Colaboração da equipe.**
    - **Compatibilidade** com o SGBD que será usado.
- Cada ferramenta tem **vantagens e limitações**, então a decisão deve alinhar-se ao fluxo de trabalho da equipe.

---

### MER — Modelo Entidade Relacionamento

O Modelo Entidade-Relacionamento (MER) é uma abordagem teórica usada para descrever e especificar a estrutura de dados de um sistema de banco de dados. O MER ajuda a identificar os dados que devem ser armazenados no banco de dados e a definir as relações entre esses grupos de dados. No MER, os dados são organizados em entidades, atributos e relacionamentos:

- **Entidades:** São objetos ou conceitos do mundo real que possuem dados que precisam ser armazenados. Exemplos de entidades podem ser 'Cliente', 'Pedido', ou 'Produto'.
- **Atributos:** São as propriedades ou características de uma entidade. Por exemplo, a entidade 'Cliente' pode ter atributos como 'Nome do Cliente', 'Endereço' e 'Telefone'.
- **Relacionamentos:** Descrevem como as entidades estão conectadas entre si e interagem. Por exemplo, um relacionamento entre 'Cliente' e 'Pedido' pode ser descrito como um cliente que 'realiza' um pedido.

exemplo de perguntas a se fazer para o levantamento de requisitos de dados: “Quais são os objetivos principais deste projeto?”, “Quais são os dados que devem ser armazenados”.

abstração —> isolar os dados importantes, buscando apenas o que é necessário para o projeto.

---

## **Diagrama Entidade-Relacionamento (DER)**

O Diagrama Entidade-Relacionamento (DER) é a representação gráfica do MER. O DER utiliza um conjunto de símbolos gráficos como retângulos, losangos e linhas para representar entidades, relacionamentos e atributos, respectivamente. O objetivo do DER é fornecer uma visualização clara e compreensível da estrutura do banco de dados, facilitando a compreensão das relações entre os dados, mesmo para aqueles sem conhecimento técnico profundo.

Por exemplo, num DER:

- **Retângulos** representam as **entidades**.
- **Losangos** representam os **relacionamentos**.
- **Oval** representa os **atributos**.
- **Linhas** conectam entidades com seus atributos e relacionamentos.

## **Importância do MER e do DER**

- **Comunicação e Planejamento:** MER e DER são ferramentas essenciais para comunicar a estrutura de dados proposta entre os desenvolvedores e stakeholders do projeto, incluindo analistas de sistemas, gerentes de projeto e clientes. Eles facilitam a discussão e o planejamento antes da implementação do banco de dados.
- **Organização e Design:** Ajudam na organização dos dados de forma lógica, garantindo que todas as informações necessárias sejam capturadas e corretamente interligadas.
- **Prevenção de Erros:** Usar MER e DER na fase de design pode ajudar a identificar e corrigir potenciais erros de modelagem, como redundâncias de dados ou relações mal definidas, antes que o banco de dados seja fisicamente implementado.
