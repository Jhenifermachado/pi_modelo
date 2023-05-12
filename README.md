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
(*Nessa parte a equipe deve descrever os requisitos funcionais que serão implementados no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.*)

**5.1 O que são requisitos funcionais?**

Um requisito funcional é uma declaração de como um sistema deve se comportar. Define o que o sistema deve fazer para atender às necessidades ou expectativas do usuário. Os requisitos funcionais podem ser pensados ​como recursos que o usuário detecta.

Os requisitos funcionais são compostos de duas partes:
**função** e **comportamento**. 

- A **função** é o que o sistema **faz**. Por exemplo: *“calcular imposto sobre vendas”*.
- O **comportamento** é **como** o sistema faz. Por exemplo: *“O sistema deve calcular o imposto sobre vendas multiplicando o preço de compra pela alíquota do imposto.”*.

**5.2 Tipos de requisitos funcionais**

Os requisitos funcionais podem ser classificados em:

- Regulamentos de Negócios
- Requisitos de Certificação
- Requisitos de relatório
- Funções Administrativas
- Níveis de autorização
- Rastreamento de auditoria
- Interfaces Externas
- Gestão de dados
- Requisitos Legais e Regulamentares

**5.3 Diretrizes para a elaboração de requisitos funcionais**

Cada requisito funcional precisa ser:

- **Específico** sobre o que o sistema deve fazer.
- **Mensurável** para que você possa dizer se o sistema está fazendo isso
- **Alcançável** dentro do prazo que você definiu
- **Relevante** para seus objetivos de negócios
- **Limitado** no tempo para que você possa
acompanhar o progresso

**5.4 Estrutura do requisito funcional**

Um requisito funcional deve ser estruturado da seguinte forma:

- **Nome do requisito funcional:** descrição do
requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**5.4.1 Nome do requisito funcional**

**R.F. 99 - Nome do requisito funcional:** é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional)
seguida da numeração, para melhor identificação do requisito, acrescido do formato *“Substantivo + onde será feita a ação”*.
Por exemplo: 
- R.F. 01 - Registro de Funcionários
- R.F. 15 - Gerenciamento de consultas
- R.F. 04 - Débito em conta corrente
 
Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números.

**5.4.2 Descrição do requisito funcional**

**Descrição do requisito:** local para descrever a função deste requisito. 

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa.
Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de
usuários. Outro exemplo é algo que faz sentido apenas para um  software, como a própria autenticação.

**5.4.3 Dados necessários**

**Dados necessários:** aqui devem ser colocados os nomes dos dados que serão usados para que esse requisito atenda o que precisa fazer. 

Nas **entradas** e **processos**, em geral, são os dados que serão salvos (seja algo digitado pelo usuário ou captado do sistema, como a hora atual). 

Já nas **saídas**, são os dados que serão exibidos em tela (sejam eles vindos diretamente do banco, ou criados por um cálculo ou busca na sessão do usuário).

**5.4.4 Usuários**

**Usuários:** aqui devem ser colocados os nomes dos usuários que terão acesso a esse requisito, conforme enumerados na descrição do sistema.

**5.4.5 Exemplo de requisito funcional**

- **R.F. 01 - Autenticação de usuário:** tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando
para a página principal de seu perfil de acesso. 
  - **Dados necessários:** login, senha, nível de permissão. 
  - **Usuários:** todos os níveis de usuário.

**5.4.6 Organização dos requisitos funcionais**

As funcionalidades devem ser organizadas em: entradas, processos e saídas.

**Entradas:** São as funcionalidades que alimentarão o software com as informações essenciais para seu uso. 
 
**Exemplos de entradas:**
- “**Registro de usuário**” (para permitir depois seu acesso ao software).
- “**Registro de paciente**” (que seria útil caso nosso software fosse ppara uma clínica, evitando registrar várias vezes os mesmos dados da pessoa a cada consulta e viabilizando um histórico de seus
atendimentos).

**Processos:** Em geral, englobam toda ação que executa cálculos, processamentos de tomada de decisão ou transforma dados em novos dados. 

**Exemplos de processos:**
- “**Autenticação de usuário**”, que usará os dados de “**Registro de usuário**” em sua execução.
- “**Agendamento de consulta**”, que usará dados do “**Registro de paciente**” e talvez do “**Registro de funcionário**” em sua execução.

**Saídas:** São os relatórios, gráficos, impressões, etc., que utilizarem os dados do software para gerar informações pertinentes ao
negócio, mas sem intenção de alterá-los, apenas permitindo sua visualização e filtragem. 

**Exemplos de saídas:**
- “Relatório de consultas por paciente”.
- Relatório de vendas”. 
- “Log de usuários autenticados”.

Todos esses podem ser consideradas saídas, pois usam informações de entradas e processos de modo a mostrar informações relevantes ao
negócio. Lembre-se que, diferentemente das entradas e processos, aqui os dados necessários devem ser os que a tela exibirá.

**5.4.7 Exemplo de organização dos requisitos funcionais**

(_A seguir, um exemplo de organização de requisitos funcionais, com entradas, processos e saídas._)

**Entradas:**

- **R.F. 01 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 02 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Processamento:**

- **R.F. 03 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 04 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Saídas:**

- **R.F. 05 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 06 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

# 6. Requisitos não funcionais

Requisitos não funcionais (**RNFs**) são as restrições impostas a um sistema que definem seus atributos de qualidade.

Eles geralmente são indicados por adjetivos como **segurança**, **desempenho** e **escalabilidade**.

**6.1 Categorias de requisitos não funcionais**

Os requisitos não funcionais são importantes porque ajudam a garantir que o sistema atenda às necessidades do usuário.

Os Requisitos Não Funcionais explicam as limitações e restrições do sistema a ser projetado. **Esses requisitos não têm nenhum
impacto na funcionalidade do aplicativo.** Além disso, existe uma prática comum de subclassificar os requisitos não funcionais em várias categorias:

- Interface de Usuário
- Confiabilidade
- Segurança
- Atuação
- Manutenção

Os requisitos não funcionais podem ser divididos em duas categorias:

1. **Atributos de qualidade:** Estas são as características do sistema que determinam sua qualidade geral. Exemplos de atributos de qualidade incluem segurança, desempenho e usabilidade.
2. **Restrições:** Estas são as limitações impostas ao sistema.
Exemplos de restrições incluem tempo, recursos e ambiente.

**6.2 Vantagens dos requisitos não funcionais**

Os requisitos não funcionais ajudam a garantir que o sistema seja:

1. Adaptado às necessidades do usuário.
2. Adequado à finalidade.
3. Escalável, seguro e confiável.
4. Fácil de usar e manter.

**6.3 Exemplos de requisitos não funcionais**

Aqui estão alguns exemplos de requisitos não funcionais:
1. **Segurança**: O sistema deve ser protegido contra acesso não
autorizado.
2. **Atuação**: O sistema deve ser capaz de lidar com o número necessário
de usuários sem qualquer degradação no desempenho.
3. **Escalabilidade**: O sistema deve ser capaz de aumentar ou diminuir
conforme necessário.
4. **Disponibilidade**: O sistema deve estar disponível quando necessário.
5. **Manutenção**: O sistema deve ser fácil de manter e atualizar.
6. **Portabilidade**: O sistema deve ser capaz de rodar em diferentes
plataformas com alterações mínimas.
7. **Confiabilidade**: O sistema deve ser confiável e atender aos requisitos
do usuário.
8. **Usabilidade**: O sistema deve ser fácil de usar e entender.
9. **Compatibilidade**: O sistema deve ser compatível com outros sistemas.
10. **Conformidade**: O sistema deve cumprir todas as leis e regulamentos
aplicáveis.

**6.4 Exemplo de organização dos requisitos não funcionais**

(_A seguir, um exemplo de organização de requisitos não funcionais._)

**Requisitos não funcionais:**

- **R.N.F. 01 - Nome do requisito não funcional:** descrição do requisito. 
- **R.N.F. 02 - Nome do requisito não funcional:** descrição do requisito.

**Exemplos de requisitos não funcionais:**


**Sistema de Padaria**:
- R.N.F. 01 - Navegador homologado: O sistema deverá ser homologado somente para o navegador Google Chrome.
- R.N.F. 02 - Processador: É recomendado para o sistema  no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.
- R.N.F. 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de Ram para melhor performance.
- R.N.F. 04 - Arquitetura: A arquitetura que será utilizada para criação do sistema será Rest.
- R.N.F. 05 - Conexão com banco de dados: Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.
- R.N.F. 06- Banco de dados: O sistema será implementado com o banco de dados MySQL.
- R.N.F. 07 - Implementação: O sistema deverá ser desenvolvido com linguagem Java, Javascript,  HTML5, CSS3 e JQuery.
- R.N.F. 08 - Segurança: Ficará a critério do responsável do estabelecimento a segurança dos acessos ao sistema, tendo consciência das pessoas que possua permissão para acesso.
- R.N.F. 09 - Ambiente de Desenvolvimento Integrado (IDE): Para criação do sistema, será utilizado  Eclipse.
- R.N.F. 10 - Disponibilidade: O sistema irá atender 99% do tempo de uso, somente ocorreria problemas de cadastro, remoção, inserção ou alteração em casos de falta de rede ou energia.
- R.N.F. 11 - Legais: O sistema deve atender às exigências da LGPD (Leis Gerais da Proteção de Dados).

**Sistema de Ordem de Serviço:**
- R.N.F. 01 - Navegadores homologados: o sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox. 
- R.N.F. 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o CSS3 e o HTML5, além das bibliotecas de jQuery e Javascript.
- R.N.F. 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Java.
- R.N.F. 04- Interoperabilidade: O banco de dados será o Mysql, com a linguagem SQL de banco, sendo todo produzido através do mysql Workbench .
- R.N.F. 05- Forma de uso do software: O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.
- R.N.F. 06- Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados.
- R.N.F. 07- Autenticação: Para realizar o acesso ao sistema é necessário ter um usuário de autenticação criado pelo administrador, além da possibilidade de solicitar um envio de redefinição de senha.
- R.N.F. 08- Web Server: O servidor web utilizado será o Apache Tomcat, nas versões mais atualizadas.
R.N.F. 08- Níveis de segurança: O software terá diferentes tipos de acesso para cada tipo de login, tendo as permissões ideais a função de cada um.

**6.6 Conclusão**

Requisitos não funcionais são essenciais para qualquer sistema. Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.

É importante considerar cuidadosamente todos os requisitos não funcionais antes de projetar e desenvolver um sistema.
Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.
