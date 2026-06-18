# 🧠 Miniguia de Estudos — Paradigma POO com NotebookLM

> Projeto prático: uso do NotebookLM como ferramenta de aprendizagem ativa sobre o paradigma de Programação Orientada a Objetos (POO).

<br>

---

## 📌 1. Contexto e Objetivos

**Tema escolhido:** Paradigma de Programação Orientada a Objetos (POO)

**Por que esse tema?**  
A escolha do Paradigma de POO foi pelo fato dele ser o paradigma mas cobrado e utilizado no mercado muldial, ser amplamente aplicado em varias linguagens de programação. 

**Objetivos de estudo:**
- Compreender o que é um paradigma de programação e qual problema ele resolve
- Entender os fundamentos e a filosofia por trás da POO
- Dominar os 4 pilares: Encapsulamento, Herança, Polimorfismo e Abstração
- Saber identificar quando aplicar POO em um projeto real
- Conhecer as críticas ao uso excessivo do paradigma
- Construir um glossário e prompts reutilizáveis para revisão futura

<br>

---

## 📚 2. Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM:

| # | Fonte | Tipo | Destaques |
|---|-------|------|-----------|
| 1 | [POO – MEC / e-Tec Brasil (PDF)](./pdf/POO%20–%20MEC%20%20e-Tec%20Brasil%20(PDF).pdf) | PDF governamental | Base teórica completa, didático, em português |
| 2 | [POO – Livro Único / Kroton (PDF)](./pdf/POO%20–%20Livro%20Único%20_%20Kroton%20(PDF).pdf) | PDF livro didático | Contexto histórico, classes, objetos, construtores |
| 3 | [POO – Visão Geral / PUC-SP (PDF)](./pdf/POO%20–%20Visão%20Geral%20-%20PUC-SP%20(PDF).pdf) | PDF acadêmico | SOLID, padrões de projeto, história do SIMULA |
| 4 | [POO – FACOM/UFU – Java Completo (PDF)](./pdf/POO%20–%20FACOM-UFU%20–%20Java%20Completo%20(PDF).pdf) | PDF universitário | Pilares com exemplos práticos em código |
| 5 | [FIAP – Guia dos 4 Pilares (artigo web)](https://www.fiap.com.br/radar-tech/post/programacao-orientada-a-objetos-poo-um-guia-completo-sobre-seus-4-pilares-fundamentais-encapsulamento-heranca-polimorfismo-e-abstracao/) | Artigo web | Linguagem acessível, bom para revisão final |

<br>

---

## 🧪 3. Engenharia de Prompts e Cicatrizes

> Cada prompt foi testado no NotebookLM com as fontes acima como base. As notas de troubleshooting registram o que funcionou, o que falhou e como foi corrigido.

---

### Prompt 1 — Configuração do Professor

**Prompt usado:**
```
Sou estudante de desenvolvimento de software e vou estudar o paradigma POO.
Use apenas as fontes deste notebook como base. Você será meu professor e vai
me ensinar esse paradigma, focando em: não dar a resposta de cara, mas me
fazer pensar; explicações simples e precisas; em caso de dúvida, pergunte se
quero mudar a abordagem; em tópicos complexos, aprofunde; periodicamente
pergunte se está sendo um bom professor. Compreendeu? Confirme para eu começar.
```

**Resposta obtida:**

-   Compreendido perfeitamente. Aceito o desafio e estou pronto para ser seu professor nesta jornada pelo paradigma da **Programação Orientada a Objetos (POO)**. Usarei exclusivamente o material fornecido como base para guiar nossos estudos.

    Para começarmos, precisamos entender que a POO não é apenas uma técnica de escrita de código, mas um **paradigma** — ou seja, um modelo, um padrão ou um estilo de se programar para resolver problemas. Diferente de outros estilos onde o foco é apenas o passo a passo das instruções, na POO tentamos aproximar a programação do mundo real.

    As fontes nos ensinam que a POO se baseia na criação de modelos. Um modelo é uma representação simplificada de algo que existe no mundo real (como um objeto, uma pessoa ou um processo), focando no que é importante para o problema que queremos resolver.

    **Aqui vai a sua primeira provocação para pensar**:
    
    Imagine que você precisa criar um sistema para uma pet shop. No mundo real, você vê vários animais. Se você tivesse que criar um "molde" ou uma "especificação" geral para representar qualquer Cachorro nesse sistema, você precisaria identificar:
    -   Quais informações (características) são essenciais para identificar cada cachorro?
    -   Quais ações (comportamentos) esse cachorro pode realizar dentro do seu sistema?
    
    **Tente listar três exemplos para cada uma dessas perguntas**. Não se preocupe com termos técnicos agora, pense na lógica do mundo real aplicada ao software.

    Estou sendo um bom professor até este ponto? Quando você trouxer sua resposta, daremos o próximo passo para transformar esses conceitos em estruturas de programação.

    ---
    <br>

**📝 Nota de troubleshooting:**
>   Nota 7

A IA entendeu:
-   Seu papel como professor
-   Que deve usar somente as fontes fornecidas

Ela ja começou explicando o tema, deu exemplos, deixou um desafio para mim **(mas isso sem eu pedir ate o momento)** e ao final pediu um feedback sobre sua atuação como professor, porem nada anormal em sua resposta.

---

### Prompt 2 — O que é um Paradigma de Programação?

**Prompt usado:**
```
Me explique o que é um Paradigma de Programação, para que serve e qual
problema ele resolve na prática do desenvolvimento de software.
```

**Resposta obtida:**

-    Para entender o que é um **paradigma de programação**, pense primeiro na palavra "estilo" ou "modelo". Se você fosse um arquiteto, usaria o mesmo "estilo" para construir uma casa de madeira e um arranha-céu de vidro? Provavelmente não, pois cada um exige uma forma diferente de pensar e organizar o trabalho.

        Na computação, um paradigma é exatamente isso: um modelo, padrão ou estilo de se **programar**. Ele não é uma linguagem específica, mas sim a maneira de pensar que você utiliza para estruturar a solução de um problema. Cada paradigma propõe uma forma distinta de enxergar e propor uma solução. 

        **Para que serve um paradigma?**

        Ele serve como um guia mental. O paradigma define as "regras do jogo": quais ferramentas você pode usar e como deve organizar suas ideias. Ele ajuda a:
        -   **Organizar o código** de forma lógica e eficiente.
        -   Criar sistemas que sejam **elegantes, eficientes e fáceis de compreender.**
        -   Facilitar a construção de softwares **modulares e reutilizáveis.**
        
        **Qual problema ele resolve na prática?**

        O grande "vilão" que os paradigmas tentam combater é a **complexidade**. Sem um paradigma bem definido, o desenvolvimento de software pode se tornar um caos de instruções difíceis de seguir. Na prática, um bom paradigma resolve:
        
        **1. Dificuldade de manutenção**: Programas sem um padrão claro são difíceis de corrigir ou atualizar.
        
        **2. Falta de escalabilidade**: Ajuda a garantir que o sistema possa crescer sem "quebrar" ou exigir que você refaça tudo do zero.
        
        **3. Rigidez**: Permite que o software seja mais flexível e adaptável a mudanças, o que é essencial já que sistemas reais mudam o tempo todo.

        **Agora, um desafio para você refletir**: Imagine que você tem dois paradigmas famosos: um focado em instruções passo a passo (como uma receita de bolo) e outro focado em objetos que conversam entre si (como pessoas em uma empresa).
        -   Para um sistema muito simples e linear, qual você acha que seria mais rápido?
        -   E para um sistema gigante, como o de um banco, onde as regras mudam toda semana, qual estilo traria mais segurança?
        
        **Estou sendo um bom professor até aqui?** O conceito de "estilo de pensamento" ficou claro ou quer que eu use uma analogia diferente?

    ---
    <br>

**📝 Nota de troubleshooting:**
>   Nota 8

A resposta sobre o o que foi pedido foi boa, direto ao ponto, daria para melhorar no "desafio" fornecido por ela. Ela fica perguntando muito, algo assim:
-   Estou sendo um bom professor até aqui?
-   Estou sendo um bom professor até este ponto?  

Isso está OK, pois assim, caso a pessoa não goste da forma como esta sendo aplicado as explicações, ela pode mudar, `vou manter pois gostei`.

---

### Prompt 3 — POO: Resumo

**Prompt usado:**
```
Sobre o paradigma da POO, me dê um resumo.
```

**Resposta obtida:**

-    **A Programação Orientada a Objetos (POO)** é um paradigma de programação que busca aproximar a escrita de código do mundo real, modelando sistemas como um conjunto de objetos que interagem entre si. Diferente do paradigma procedimental, que foca em instruções passo a passo, a POO organiza o software em torno de dados (atributos) e comportamentos (métodos) que andam juntos.
    
        Para você ter um resumo mental sólido, podemos dividir a POO nestes pontos principais:

        **1. A Base: Classes e Objetos**  
        -   **Classe**: É o "molde" ou a especificação genérica. Ela define quais características e ações um grupo de coisas terá.

        -   **Objeto**: É a materialização ou a instância desse molde. Enquanto "Carro" é a classe, "o seu carro azul" é o objeto concreto.

        **2. Os 4 Pilares Fundamentais** O paradigma se sustenta em quatro pilares que garantem que o sistema seja flexível e fácil de manter:

        -   **Abstração**: Focar apenas no que é essencial para o problema, ignorando detalhes irrelevantes. Se você modela um livro para uma loja, o peso importa; se for para um leitor digital, talvez não.

        -   **Encapsulamento**: Esconder a complexidade interna. Os dados ficam "protegidos" dentro do objeto e só podem ser acessados ou alterados através de métodos específicos, como uma blindagem.

        -   **Herança**: Permite que uma classe nova aproveite características de uma classe já existente. Um "Caminhão" pode herdar características de um "Veículo", evitando repetição de código.

        -   **Polimorfismo**: A capacidade de um mesmo comando ser respondido de formas diferentes. Por exemplo, o comando "mover" faz um pássaro voar e um peixe nadar.

        **3. Origem e Propósito** A POO nasceu na década de 60 com a **linguagem SIMULA**, focada em simulações, e foi popularizada por Alan Kay com o **Smalltalk** nos anos 70. Ela serve para resolver o problema da complexidade, permitindo criar sistemas modulares, reutilizáveis e escaláveis.

        **Para te fazer pensar**: Imagine que você está usando um controle remoto de TV. Você aperta o botão "Volume +" e o som aumenta. Você não precisa saber como o sinal infravermelho é processado ou como o circuito interno da TV altera a voltagem nos alto-falantes.
        
        **Qual dos 4 pilares descritos acima você acha que melhor representa essa experiência de usar o botão sem conhecer o circuito interno? Por quê?**
        
        Estou sendo um bom professor até aqui? A explicação está no ritmo certo para você?

    ---
    <br>

**📝 Nota de troubleshooting:**
>   Nota 10

Resposta clara e objetiva, passou por cada topico do paradigma de forma rapida, deu exemplos facis e uma passada breve na sua historia
---

### Prompt 4 — POO: Aprofundamento com Analogia

**Prompt usado:**
```
Agora sobre POO com mais profundidade no assunto, usando analogia ao mundo real.
```

**Resposta obtida:**

-    Vamos mergulhar mais fundo na anatomia de um objeto e como esses elementos se conectam, usando o mundo real como nosso guia. Na POO, dizemos que um objeto é composto por três características fundamentais: **Estado, Comportamento e Unicidade**. Para entender isso, imagine você e seus colegas de classe. Cada um de vocês é um "objeto" único no mundo (Unicidade), mesmo que tenham o mesmo nome.
    
        **1. Atributos (O que o objeto "sabe" ou "tem")**

        Os atributos representam o estado do objeto. São as características que o definem em um determinado momento.
        -   **Analogia**: Pense em um Smartphone. Ele tem atributos como: `marca`, `modelo`, `nívelDeBateria` e `espaçoDeArmazenamento`.
        -   **Para pensar**: Se o smartphone está com 10% de bateria e você o coloca para carregar, o valor do atributo `nívelDeBateria` muda. O objeto mudou de estado, mas ele continua sendo o mesmo smartphone?.

        **2. Métodos (O que o objeto "faz")**
        
        Os métodos representam o comportamento. São as ações que o objeto pode realizar ou as transformações que ele pode sofrer.

        -   **Analogia**: No mesmo Smartphone, os métodos seriam: `fazerLigação()`, `tirarFoto()` ou `recarregar()`.

        -   **Aprofundando**: Um método muitas vezes altera um atributo. Por exemplo, o método `recarregar()` altera o estado do atributo `nívelDeBateria.`

        **3. A Troca de Mensagens**

        No mundo real, as coisas não funcionam sozinhas; elas interagem. Na POO, os objetos conversam através de mensagens, que nada mais são do que chamadas de métodos.

        -   **Analogia**: Quando você aperta o botão de "Tirar Foto" na tela, você (um objeto Usuário) está enviando uma mensagem para o objeto Câmera dizendo: "execute sua operação de capturar imagem".

        ---
        <br>

        **Desafio para você aprofundar o pensamento**:

        Imagine que estamos modelando um **Sistema Bancário**. Temos dois tipos de conta: **Conta Corrente e Conta Poupança**.

        **1.** Ambas possuem o atributo `saldo. Se eu enviar a mensagem `sacar(100)` para uma **Conta Corrente**, ela pode me permitir ficar com saldo negativo (limite). Se eu enviar a **mesma mensagem** para uma **Conta Poupança**, ela pode negar se o saldo for insuficiente.

        **2. Pergunta**: Como chamamos o pilar da POO que permite que a **mesma mensagem** `(sacar)` resulte em comportamentos diferentes dependendo do tipo de conta?.

        **Estou sendo um bom professor até aqui?** O nível de profundidade está adequado ou quer que eu detalhe mais a estrutura interna das classes?

        ---
        <br>

**📝 Nota de troubleshooting:**
>   Nota 8

Resposta clar e objetiva com o que foi pedido e explos de acordo com o requerido.

---
<br>



### Prompt 5 — Pilar: Encapsulamento

**Prompt usado:**
```
Vamos falar agora sobre seus pilares, começando pelo encapsulamento.
Me explique em detalhes e com analogias simples. Só vamos para o próximo
pilar quando eu pedir — de resto, me fale somente sobre esse pilar!
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

---

### Prompt 5b — Pilar: Herança

**Prompt usado:**
```
Próximo pilar: Herança. Mesma abordagem — detalhes e analogias simples.
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

---

### Prompt 5c — Pilar: Polimorfismo

**Prompt usado:**
```
Próximo pilar: Polimorfismo. Mesma abordagem — detalhes e analogias simples.
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- A resposta ficou abstrata demais? Se pediu exemplo de código, registre aqui. -->

---

### Prompt 5d — Pilar: Abstração

**Prompt usado:**
```
Próximo pilar: Abstração. Mesma abordagem — detalhes e analogias simples.
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

---

### Prompt 6 — Quando Usar POO?

**Prompt usado:**
```
Quando usar POO? Como analiso meu contexto e sei quando aplicá-la?
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

---

### Prompt 7 — Críticas ao Uso Excessivo

**Prompt usado:**
```
Quais são as críticas ao POO e as consequências do seu uso excessivo?
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- Esse prompt tende a gerar respostas interessantes. A IA citou as fontes? Mencionou alternativas como Funcional? -->

---

### Prompt 8 — Glossário

**Prompt usado:**
```
Com base em tudo que estudamos, gere um glossário com os 10 principais
conceitos de POO. Para cada um: nome do conceito, definição curta
(máx. 2 linhas) e um exemplo prático.
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

---

### Prompt 9 — Prompts Reutilizáveis

**Prompt usado:**
```
Agora gere 5 prompts de revisão que eu possa reutilizar no futuro para
revisar POO do zero. Cada prompt deve focar em um aspecto diferente do paradigma.
```

**Resposta obtida:**
<!-- Cole aqui a resposta do NotebookLM -->

**📝 Nota de troubleshooting:**
<!-- -->

<br>

---

## 📖 4. Miniguia de Estudo (Entrega Final)

> Resultado consolidado produzido a partir das sessões no NotebookLM.

---

### 4.1 O que é um Paradigma de Programação?

<!-- Resumo com suas próprias palavras, baseado nas respostas dos Prompts 2 e 3 -->

---

### 4.2 O que é POO?

<!-- Resumo expandido baseado no Prompt 4 -->

---

### 4.3 Os 4 Pilares da POO

#### 🔒 Encapsulamento
<!-- Resumo baseado no Prompt 5 -->

#### 🧬 Herança
<!-- Resumo baseado no Prompt 5b -->

#### 🎭 Polimorfismo
<!-- Resumo baseado no Prompt 5c -->

#### 🌫️ Abstração
<!-- Resumo baseado no Prompt 5d -->

---

### 4.4 Quando Aplicar POO?

<!-- Resumo baseado no Prompt 6 -->

---

### 4.5 Críticas e Limitações

<!-- Resumo baseado no Prompt 7 -->

---

### 4.6 Glossário dos 10 Conceitos-Chave

<!-- Cole aqui o glossário gerado no Prompt 8, formatado como tabela ou lista -->

| Conceito | Definição | Exemplo Prático |
|----------|-----------|-----------------|
| <!-- --> | <!-- --> | <!-- --> |

---

### 4.7 Prompts Reutilizáveis para Revisão Futura

<!-- Cole aqui os 5 prompts gerados no Prompt 9 -->

1. <!-- -->
2. <!-- -->
3. <!-- -->
4. <!-- -->
5. <!-- -->

<br>

---

## 🛠️ Tecnologias e Ferramentas

- [NotebookLM](https://notebooklm.google.com/) — IA de aprendizagem com fontes
- [GitHub](https://github.com/) — Versionamento e portfólio

---

*Projeto desenvolvido como parte do Desafio de Projeto da DIO — Treinando uma IA de Aprendizagem.*