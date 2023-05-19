# Projeto Integrador - Modelo
**Projeto Bola na Rede.**


Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Equipe:
- [Essari](github.com/aluno1)
- [Jhenifer](github.com/jhenimf)
- [Eduardo](.com/)
  
Links do projeto:
(*Coloque aqui os links para a documentação do projeto e os repositórios e plubicação do backend e frontend.*)
-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   Backend: [Repositório](github.com/marcoandre/pi-backend) e [Publicação](https://pi-backend.herokuapp.com/)
-   Frontend[Repositório](github.com/marcoandre/pi-frontend) e [Publicação](https://pi-frontend.herokuapp.com/)


# 1. Desenvolvimento

**1.1.1 Ponto de Vendas (PDV)**

**Gerenciamento de vendas para uma loja de time**

A nossa cliente, Simone, tem uma loja no centro chamada Bola na Rede e, devido a qualidade de suas camisas, ela está crescendo rapidamente. Recentemente, ela contratou mais funcionários para atendimento, caixa, vendedor, etc.
Assim, atualmente, ela consegue concentrar seus esforços para melhorar a gestão da loja. Para isso, ela quer abrir sua loja online para ter mais desempenho em suas vendas. Como sua intenção
é melhorar o desempenho da loja, é muito importante que ela consiga ter
controle, como por exemplo, de vendas e do estoque.


# 2. Situação Problema

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")


Compra de estoque: A loja deve adquirir um estoque de camisas de time de diversos tamanhos e modelos, direto com o fornecedor ou através de distribuidores.

Organização do espaço: É importante que a loja organize o espaço de forma atraente e funcional, com expositores que facilitem a visualização dos produtos e prateleiras organizadas por tamanho e time. A loja também pode decorar o espaço com elementos relacionados ao esporte e aos times, para criar um ambiente temático.

Atendimento ao cliente: Os funcionários da loja devem estar disponíveis para ajudar os clientes a encontrar o que estão procurando, responder a perguntas sobre os produtos e oferecer sugestões. É importante que os funcionários tenham conhecimento sobre os times e jogadores, para poderem auxiliar os clientes na escolha das camisas.

Venda e pagamento: Quando o cliente escolhe uma camisa, o funcionário deve informar o preço e o método de pagamento disponível (dinheiro, cartão de crédito, etc). O cliente realiza o pagamento e recebe a camisa, que pode ser entregue em uma sacola ou embalagem.

Controle de estoque e reposição: É importante que a loja tenha um controle de estoque para saber quando é necessário repor os produtos. Assim, é possível manter a variedade de modelos e tamanhos para atender a demanda dos clientes.

Manutenção e limpeza: A loja deve manter o espaço limpo e organizado, e as camisas devem ser mantidas em boas condições para a venda. É importante também cuidar da manutenção dos equipamentos e da segurança do espaço.

-  A nossa cliente Simone fez um orçamento e chegou a conclusão de que é preciso contratar 10 funcionários para o melhor atendimento.Sendo assim,2 serão para a limpeza da loja,2 para o caixa,3 para o atendimento e 3 para abastecer o estoque.

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas:

**Introdução**: 

A loja Bola na Rede localizada no centro de Joinville, foi inaugurada no dia 10 de setembro de 2018, o seu objetivo é vender camisas personalizadas e oficias do time de cada cliente. A dona se chama Simone, ela contratou depois de um ano de funcionamento, alguns funcionarios para ajudar.  
  
  **Situação-problema**:
  
  Uma possível situação problema da loja seria a falta de variedade de produtos em estoque. Se a loja não tiver uma boa gestão de estoque ou não acompanhar as tendências do mercado de camisas de time, pode acabar oferecendo poucas opções para seus clientes. Isso pode levar a uma diminuição das vendas e uma perda de competitividade em relação a outras lojas de camisas de time. Além disso, a falta de variedade pode desestimular a fidelização de clientes, que podem acabar buscando outras lojas com mais opções de produtos.
  
  **Conclusão**:
   Para solucionar essa situação, a loja poderia investir em uma gestão de estoque mais eficiente e em pesquisas de mercado para identificar as tendências de camisas de time mais procuradas pelos clientes. Também poderia buscar parcerias com fornecedores para garantir o acesso a uma variedade maior de produtos.

# 3. Descrição da proposta

 Nosso site pretende a melhoria das compras de camisas, ajudando a melhorar o estoque e deixar mais organizado, garantindo o conforto do cliente que pode encomendar seu produto da sua casa.
-   **Os níveis de usuário do sistema**. Todos os funcionarios e clientes terão acesso a pagina de vendas, mas apenas os funcionarios terão acesso para a pagina do estoque .
-   **O que poderá ser feito no software**. Vendas de camisas.
-   **Se houver mais de um nível de usuário**, Terá o usuário para clientes e um para os funcionarios.


# 4. Regras de negócio

- RN01- Para fazer pedidos no site o usuario deve estar cadastrado
- RN02- Caso um lote de camisa tenha pelo menos 10 camisetas com defeito, pedir devolução na fabrica
- RN03- Pagamento disponivel em pix, cartao de debito ou credito.
- RN04- No pagamento via cartao de credito, parcelar em meses pares até 6.
- RN05- Todos os pedidos devem ser contabilizados em uma planilha automaticamente. 
- RN06- A cada 100 pedidos, deve se enviar automaticamente um email para o admin.
- RN07- Garantia de 3 meses em todos os produtos da loja.
- RN08- Troca apenas com eitqueta no prazo de 30 dias.

# 5. Requisitos funcionais

RF01 - Registro de Usuário:

- Descrição do requisito: 
Permitir que os usuários se cadastrem na loja online fornecendo informações como nome, endereço, e-mail e senha.
- Dados necessários: Nome, endereço, e-mail, senha.
Usuários: Todos os usuários.

RF02 - Busca de Camisas por Time:

- Descrição do requisito: Permitir aos usuários pesquisar e visualizar camisas de times por meio de uma busca no sistema.
- Dados necessários: Time do camisa.
- Usuários: Todos os usuários.
 
 RF03 - Adicionar Camisa ao Carrinho de Compras:

- Descrição do requisito: Permitir aos usuários adicionar camisas ao carrinho de compras.
- Dados necessários: ID da camisa, quantidade desejada.
Usuários: Todos os usuários.

RF04 - Processamento de Pagamento:

- Descrição do requisito: Processar o pagamento das camisas selecionadas pelos usuários.
- Dados necessários: Detalhes do pagamento (número do cartão de crédito, data de validade, código de segurança).
- Usuários: Todos os usuários.

RF05 - Atualização de Estoque:

- Descrição do requisito: Atualizar o estoque de camisas disponíveis após uma compra ser concluída.
- Dados necessários: ID da camisa, quantidade comprada.
- Usuários: Administradores.

RF06 - Confirmação de Compra:

- escrição do requisito: Exibir aos usuários uma confirmação de compra após o processamento bem-sucedido do pagamento.
- Dados necessários: Detalhes da compra (camisas compradas, total, data e hora da compra).
- Usuários: Todos os usuários.
- 
RF07 - Recibo de Compra:

- Descrição do requisito: Gerar um recibo de compra que pode ser baixado ou enviado por e-mail para os usuários.
- Dados necessários: Detalhes da compra (camisas compradas, total, data e hora da compra, informações de entrega).
- Usuários: Todos os usuários.




 




# 6. Requisitos não funcionais

**6.1 Categorias de requisitos não funcionais**

- Interface de Usuário
- Confiabilidade
- Segurança
- Desempenho
- Manutenção

**6.2 Vantagens dos requisitos não funcionais**

Os requisitos não funcionais ajudam a garantir que o sistema seja:

1. Adaptado às necessidades do usuário.
2. Adequado à finalidade.
3. Escalável, seguro e confiável.
4. Fácil de usar e manter.


**Requisitos não funcionais:**

- R.N.F. 01 - Interface de Usuário: O sistema deve possuir uma interface intuitiva e fácil de usar, permitindo aos usuários navegar e comprar camisas de times de forma eficiente.

- R.N.F. 02 - Confiabilidade: O sistema deve ser confiável, garantindo que as transações sejam processadas corretamente e que as informações dos clientes sejam protegidas.

- R.N.F. 03 - Segurança: O sistema deve ser protegido contra acesso não autorizado, utilizando medidas de criptografia, autenticação e controle de acesso adequados.
  
- R.N.F. 04 - Desempenho: O sistema deve ser capaz de lidar com um grande número de usuários simultaneamente, sem comprometer a velocidade de resposta e a experiência do usuário.
  
- R.N.F. 05 - Manutenção: O sistema deve ser fácil de manter e atualizar, permitindo a adição de novos produtos, atualização de preços e gerenciamento de estoque de forma eficiente.

Especificação dos requisitos não funcionais:
- R.N.F. 01 - Interface de Usuário: O sistema deve possuir um design responsivo, adaptando-se a diferentes dispositivos (desktop, tablets e smartphones) para uma experiência consistente em todas as plataformas.
- R.N.F. 02 - Confiabilidade: O sistema deve garantir a integridade dos dados do cliente, evitando perdas ou corrupção de informações.
- R.N.F. 03 - Segurança: O sistema deve utilizar criptografia SSL/TLS para garantir a segurança das transações e proteção dos dados sensíveis dos clientes.
- R.N.F. 04 - Desempenho: O sistema deve ter um tempo de resposta rápido, permitindo aos usuários navegar e efetuar compras sem atrasos significativos.
- R.N.F. 05 - Manutenção: O sistema deve ser modular e fácil de atualizar, permitindo a adição de novos produtos e alterações nos preços de forma ágil.

Arquitetura e tecnologias:

- Utilize uma arquitetura de aplicação web, como o modelo Cliente-Servidor.
- Para o desenvolvimento do front-end, utilize HTML5, CSS3 e JavaScript, aplicando princípios de design responsivo.
- Para o back-end, utilize uma linguagem de programação como Python ou Node.js, juntamente com um framework web, como Django ou Express.js.
- Utilize um banco de dados relacional, como MySQL ou PostgreSQL, para armazenar as informações dos produtos e dos usuários.
Implemente medidas de segurança, como autenticação de usuários, controle de acesso e proteção contra ataques, utilizando bibliotecas e frameworks adequados.
- Implementação dos requisitos não funcionais:

- Desenvolva a interface de usuário com um design atraente e responsivo, permitindo a navegação intuitiva e a visualização dos produtos de forma clara.
- Implemente medidas de segurança, como criptografia SSL/TLS,