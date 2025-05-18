# 📚 Seu Narrador Pessoal Powered by Google Gemini (e um toque de Alura!) ✨

<a href="https://colab.research.google.com/github/emerdg/AluraLogica/blob/master/Narrador_Interativo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

---

Cansado de esperar por um RPG mestre que nunca tem horário? Que tal ter um narrador **só pra você**? Este projeto nasceu na [Imersão Dev Google + Alura](https://www.alura.com.br/artigos/imersao-ia), transformando o poderoso [Google Gemini API](https://ai.google.dev/models/gemini) no seu contador de histórias particular.

Ele está pronto para improvisar uma aventura sob medida, baseada nas suas ideias para um narrador carismático, um mundo envolvente e um personagem único! Ou, se a preguiça bater, ele inventa tudo na hora com uma pitada de criatividade. 😉

## ✨ Features Mágicas

*   **Narrador Personalizado:** Defina o humor, gostos e estilo de quem vai te guiar na aventura.
*   **Mundo Sob Medida:** Crie o cenário perfeito, seja ele real ou pura fantasia.
*   **Herói (ou Vilão?) Definido:** Dê vida ao seu personagem com detalhes que importam.
*   **História Interativa:** Jogue e influencie o rumo da narrativa com suas escolhas.
*   **Tecnologia de Ponta:** Tudo isso rodando com a inteligência do Google Gemini e o Agent Development Kit (ADK).
*   **Fácil de Usar:** Feito para rodar diretinho no Google Colab, sem dor de cabeça.

## 🚀 Como Rodar Essa Aventura no Google Colab

Preparar o terreno é super simples, mas requer um passo importante: sua chave da API do Google Gemini. Calma, é rápido!

1.  **Pegue Sua Chave Mágica (API Key):** Se você não tem uma, crie a sua chave da Google Gemini API no [Google AI Studio](https://aistudio.google.com/). É grátis para começar!
2.  **Abra no Colab:** Clique no badge mágico lá no início deste README: <kbd><a href="https://colab.research.google.com/github/emerdg/AluraLogica/blob/master/Narrador_Interativo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a></kbd> Ele abrirá o notebook no Google Colab.
3.  **Guarde o Segredo (Sua API Key):** Dentro do Colab, clique no ícone de uma chave/cadeado na barra lateral esquerda (<kbd>🔑</kbd>). Adicione uma **Nova Chave de Segredo**. O **Nome** do segredo deve ser `GOOGLE_API_KEY` (sim, *exatamente* assim!). No campo **Valor**, cole a sua chave da API que você pegou no passo 1. Não se preocupe, o Colab guarda isso de forma segura e não expõe sua chave no código público.
4.  **Prepare os Motores:** Rode a **primeira célula de código**. Ela instala as bibliotecas necessárias e faz uns ajustes nos bastidores.
5.  **Ajuste os Engajamentos:** Rode a **segunda célula de código**. Essa define as funções e os "agentes" (os assistentes do Gemini) que vão configurar seu narrador, mundo e personagem.
6.  **Comece a Conversa!** Rode a **terceira célula de código**. Ela vai te fazer algumas perguntas para configurar o narrador, o cenário e o seu personagem. Responda com criatividade (ou deixe em branco para ele inventar algo!).
7.  **A História Começa:** Depois das perguntas, o narrador (o Gemini) vai se apresentar e começar a contar a sua história. Digite suas ações ou escolhas quando for sua vez (`SUA VEZ:`).
8.  **O Fim (Temporário):** Para terminar a história a qualquer momento, digite `!FIM` quando for sua vez.

## 🧠 Como Funciona (A Magia por Trás)

Este projeto utiliza o conceito de "Agentes" do Google Agent Development Kit (ADK) em conjunto com os modelos do Google Gemini. Basicamente, temos uma equipe de AIs especialistas:

*   Um agente cuida da **personalidade do Narrador**.
*   Outro agente constrói o **mundo e o estilo da história**.
*   Um terceiro agente define o **Personagem** principal.
*   E o agente principal, o **Narrador**, reúne todas essas informações e interage com você, gerando a narrativa passo a passo.

É como ter uma equipe de roteiristas e um mestre de RPG pessoal, todos eles alimentados pela inteligência artificial!

## 🛠️ Tecnologias Utilizadas

*   Python
*   Google Colab
*   Google Gemini API
*   Google Agent Development Kit (ADK)

## 🚨 Segurança em Primeiro Lugar!

Assim como reforçado no código, este projeto foi desenvolvido com atenção para que o conteúdo gerado (narrador, personagens, história) respeite diretrizes de segurança, evitando temas inapropriados, sexualização, violência excessiva ou representações inadequadas. É para ser uma aventura divertida e segura para todos!

## 🙏 Agradecimentos

Este projeto é fruto do aprendizado na incrível **Imersão Dev Google + Alura**. Um grande obrigado à [Alura](https://www.alura.com.br/) pela didática excelente e ao [Google](https://about.google/) por disponibilizar as ferramentas e o conhecimento sobre a API Gemini!

---

Pronto para a sua próxima aventura literária interativa? 📖✨

## 🆕 Update

*   Com o poder do Gemini, pedi uma ajuda para melhorar a parte visual do projeto. Obrigado Gemini mais uma vez!
