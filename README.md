# Projeto Web: Hamburgueria Artesanal Mordida Perfeita 🍔
#Projeto realizado pela aluna Rafaela Toniatto  - R.A:202402781707

## Visão Geral do Projeto 🎯

Este projeto consiste no desenvolvimento de um website para a hamburgueria artesanal fictícia "Mordida Perfeita", localizada na cidade de Campinas. O principal objetivo deste trabalho acadêmico é demonstrar a importância de uma presença online robusta e informativa para bares e lanchonetes. 
Através da criação deste site responsivo e funcional, buscamos evidenciar os benefícios de investir em marketing digital, como:

📌  Interação e Engajamento: Facilitar a comunicação com os clientes e criar um senso de comunidade.  
📌  Atração de Novos Clientes: Aumentar a visibilidade da hamburgueria para um público mais amplo.  
📌  Modernidade e Profissionalismo: Transmitir uma imagem atualizada e confiável do negócio.  
📌  Consciência Ambiental: Promover a sustentabilidade através da disponibilização do cardápio digital via QR Code, reduzindo o consumo de papel.

## Cenário 💭
Podemos imaginar uma hamburgueria com um QR Code nas mesas que dá acesso ao site. Assim, o cliente pode ter acesso ao cardápio e suas atualizações, além de realizar o cadastro e/ou fazer login no site para aproveitar os descontos. Após decidir o pedido, é só solicitá-lo ao atendente e aproveitar a experiência.

##   Paleta de Cores 🎨
 O projeto tem como base a paleta de cores abaixo:


- **Preto:** #000000 (Opacidade: 100%) - Utilizado para fundos de elementos como cabeçalho e rodapé, e para textos primários em algumas seções.
* **Cinza Escuro:** `#212227` (Opacidade: 100%) - Empregado em fundos de elementos de destaque ou como cor de texto secundária.
* **Laranja:** `#FF6700` (Opacidade: 90%) - Cor primária de destaque, utilizada para elementos de navegação, botões e detalhes visuais importantes, com uma leve transparência.
* **Branco:** `#FFFFFF` (Opacidade: 100%) - Usado para textos principais sobre fundos escuros e como cor de fundo para seções específicas.
* **Cinza Médio Escuro:** `#131314` (Opacidade: 95%) - Uma variação de preto com um pouco mais de luminosidade, possivelmente utilizada para sombras ou elementos de interface sutis com alguma transparência.
* **Vermelho Escuro:** `#880404` (Opacidade: 100%) - Uma cor secundária de destaque, potencialmente utilizada para indicar ações importantes, erros ou detalhes específicos.
* **Cinza Claro:** `#CCCCCC` (Opacidade: 100%) - Utilizado para textos secundários, bordas ou elementos de interface com menor ênfase.

## Funcionalidades Implementadas
### Elementos Comuns em Todas as Telas

📌 **Cabeçalho:**
- Fundo: Cor preta ou cinza escuro.
- Logo: No canto superior esquerdo, a logo da hamburgueria "HAMBURGUERIA Mordida Perfeita" estilizada com um hambúrguer dentro de um círculo com borda laranja.
 - Navegação: No canto superior direito, uma barra de navegação horizontal com três links em blocos retangulares laranja:
    * Cardápio
    * Contato
    * Fidelidade

📌 **Rodapé:**

- Fundo: Cor branca ou cinza (a definir).
- Texto de Copyright: Centralizado na parte inferior, uma linha de texto em cor clara indicando "Hamburgueria Mordida Perfeita - Todos os direitos reservados."
 - Ícones de Redes Sociais: No canto inferior direito, um conjunto de quatro ícones brancos em círculos ou quadrados representando plataformas de redes sociais (Facebook, Instagram, Whatsapp e outros).

 ## Funcionalidades Específicas por Tela

 📌  **Tela Principal (Home):**
- Carrossel com imagens dos lanches.

 📌  **Tela de Cardápio:**
- Fotos dos produtos.
- Descrições de preços dos produtos.
- Organização dos itens por categoria (Hambúrguer, Bebidas, Sobremesas) através de GRID ou tabelas/colunas.

 📌  **Tela de Contato:**
- Formulário de contato para dúvidas, sugestões e reservas.
-  Mapa integrado com a localização da hamburgueria em Campinas.
- Campos de Formulário (todos obrigatórios):
        * *Nome:* Campo de texto para o nome do usuário.
        * *Email:* Campo de texto para o endereço de e-mail do usuário.
        * *Telefone:* Campo de texto para o telefone do usuário.
        * *Mensagem:* Campo de texto para a mensagem do usuário.

📌  **Tela de Agradecimento Pós Envio do Formulário:**
- Frase de agradecimento centralizada na tela.
- Imagens de Hambúrgueres (Background): Em segundo plano, com uma opacidade redduzida ou como uma sobreposição sutil.

 📌  **Tela de Programa de Fidelidade (Opções):**
-  Frase Centralizada: "Faça parte do nosso programa de fidelidade".
-  Opções Interativas: Abaixo do título, dois blocos retangulares semitransparentes sobrepostos às imagens de hambúrgueres em segundo plano, oferecendo duas opções principais:
   
       *     Coluna Esquerda (Cadasro):*
        *    *Título:* Cadastro (implícito).
            * *Campos de Formulário:*
                * *Nome:* Campo de texto para o nome do usuário.
                * *Email:* Campo de texto para o endereço de e-mail do usuário.
                * *Senha:* Campo de texto para o usuário inserir uma senha.
            * *Botão:* "Cadastrar".
    
        Coluna Direita (Login):*
        * *Título:* Entrar / Login (implícito).
        * *Campos de Formulário:*
            * *Email:* Campo de texto para o endereço de e-mail do usuário.
            * *Senha:* Campo de texto para o usuário inserir sua senha.
        * *Botão:* "Entrar".

📌  **Tela de Programa de Fidelidade (Usuário Logado - Opções):**
- Frase Centralizada: "Olá XXX, O que deseja ver?".
- Opções Interativas: Abaixo do título, dois blocos retangulares semitransparentes sobrepostos às imagens de hambúrgueres em segundo plano, oferecendo duas opções principais:
     * Bloco Esquerdo: Contém a palavra "Cadastro".
     * Bloco Direito: Contém a palavra "Promoções".
- Botão de Sair.
- Imagens de Hambúrgueres (Background): Em segundo plano, com uma opacidade reduzida ou como uma sobreposição sutil.

📌  **Tela de Programa de Fidelidade (Alterar Cadastro):**
- Título Principal:* Centralizado na parte superior da seção laranja, a frase "Olá XXX, vamos atualizar seu cadastro?".
- Formulário de Atualização:* Abaixo do título, um formulário com os seguintes campos:
        * *Nome:* Um campo de texto pré-preenchido com o nome atual do usuário.
        * *Email:* Um campo de texto pré-preenchido com o email atual do usuário.
        * *Senha:* Um campo de texto para o usuário inserir sua nova senha (ou a senha atual para confirmar a atualização).
- Botão de Ação (Atualizar): Abaixo dos campos do formulário, botão retangular com a palavra "Atualizar".
- Opção de Excluir Cadastro: Abaixo do botão "Atualizar", a pergunta "Deseja excluir seu cadastro?"
- Botão de Sair.
- Imagens de Hambúrgueres (Background): Em segundo plano, com uma opacidade reduzida ou como uma sobreposição sutil.

📌  **Tela de Programa de Fidelidade (Promoções):**
- Frase: "Olá XXX, veja algumas promoções:".
- Blocos de Promoções: Abaixo do título, dois blocos retangulares semitransparentes sobrepostos às imagens de hambúrgueres em segundo plano, apresentando as promoções:
    * *Bloco Esquerdo (Cupom Aniversário):*
    * *Título:* "CUPOM ANIVERSÁRIO:".
    * *Descrição:* "No dia do seu aniversário, seu lanche é na FAIXA! Apresente seu documento na hora do pagamento e aproveite!" :) em letras claras.
- *Bloco Direito (Outros Cupons):* Apresenta uma lista de outros cupons ou promoções:
    * *Título:* "CUPOM PRIMEIRA COMPRA:".
    * *Título:* "CUPOM COMPRA ACIMA DE R$200,00:" seguido da palavra "COMPROVAZ”.
    * *Título:* "CUPOM 10% EM ABRIL: 10ABRIL".
- Botão Sair.
- Imagens de Hambúrgueres (Background): Em segundo plano, com uma opacidade reduzida ou como uma sobreposição sutil.

## Proposta de Design - [Figma](https://www.figma.com/proto/OTzb9PPUapjwhWF3Ev2H1J/Projeto-Web---Hamburgueria?node-id=1-721&starting-point-node-id=1%3A721&t=VgpMOJC1PZXyoI9Q-1) 
   <div align="center">
      <img src="/design/design_telas.png" alt="Telas no geral">  
   </div>
   <br>
   
> [!IMPORTANT]
> O projeto ainda está sendo amadurecido, podendo sofrer alterações no design e funcionalidades das telas!
  
