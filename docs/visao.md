# Documento de Visão

## Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| - | - | - | - |


## 1. Objetivo do projeto

Diante da crescente descentralização de sistemas no setor automotivo brasileiro, o **Oktano** surge como a solução unificadora para o fluxo completo de gestão de oficinas mecânicas e auto centers. O objetivo é centralizar em uma única plataforma SaaS moderna todas as operações essenciais — desde ordens de serviço, controle de estoque e financeiro até emissão de NF-e e relatórios analíticos —, otimizando a produtividade, reduzindo erros manuais e garantindo escalabilidade para negócios de todos os tamanhos em todo o Brasil.

Com foco no mercado local, o Oktano atua em duas frentes principais: **a mecânica**, que facilita a comunicação fluida entre cliente e oficina ao controlar serviços, orçamentos e histórico de veículos; e **a financeira**, dedicada à gestão eficiente de estoque, pagamentos e faturamento. Essa abordagem integrada assegura consistência no fluxo de usabilidade, proporcionando conforto operacional, maior rendimento financeiro e segurança total para donos de oficinas e suas equipes.

## 2. Descrição do problema

| **Categoria**       | **Descrição**                                                                                     |  
|----------------------|---------------------------------------------------------------------------------------------------|  
| **Problema**         | Descentralização e desorganização do fluxo de operações em oficinas automotivas com uso de ferramentas fragmentadas (WhatsApp, planilhas, folhas impressas) ampliam ruídos na comunicação e praticidade profissional. |  
| **Afeta**            | Mecânicos, auxiliares-administrativos, equipe financeira.                 |  
| **Impacta**          | Aumenta o estresse dos profissionais, gera retrabalho, falhas operacionais e riscos à qualidade do atendimento. |  
| **Solução**          | Sistema eficiente que centraliza as princpais funcionalidades do atendimento automotivos (registro de serviços, pagamento, estoque) em um único ambiente, avisos automáticos e interface intuitiva. |  

## 3. Descrição dos usuários

| **Nome** | **Descrição** | **Responsabilidade** |  
|----------|---------------|----------------------|
| **Administrador** | Perfil responsável pela gestão do Oktano | - Gerencia oficinas; 
| **Gerente** | Agente responsável por manter o perfil da oficina | - Gerencia funcionários; <br> - Emissão de relatórios; <br>
| **Funcionário** | Ator responsável pelas operações dentro da Oficina, seja pela gestão dos serviços, ou pelo estoque | - Gerencia clientes; <br> - Gerencia veículos <br> - Gerencia estoque <br> - Gerencia notas fiscais <br> 

## 4. Descrição do ambiente dos usuários

A plataforma será usada em duas circustâncias. Para controle corporativo total no caso do administrador do sistema, e na visão das oficinas para sua própria gestão. Os funcionários terão acesso à aproximadamente 80% das funcionalidades por meio de desktop ou notebooks localizados nos setores administrativos das oficinas. 

Portanto, por se tratar de uma plataforma de viés corporativo, os usuários necessitam de um sistema que comporte acesso estável e de uso prolongado. Seja em seus próprios espaços de trabalho, até a possibilidade de atuar remotamente via tablet ou laptop.

## 5. Principais necessidades dos usuários

Os funcionários necessitam de ferramentas robustas e integradas para garantir o funcionamento contínuo dos serviços. Entre suas principais necessidades estão um fluxo de ponta a ponta, sem ter que utilizar recursos externos para realizar suas operações, tais como: criação, edição e visualização integrada dos clientes, veículos, etc; transparência nas movimentações do estoque, como peças, débito e crédito. 

Além disso, é essencial o acompanhamento em tempo real do banco de dados da oficina, transações, serviços feitos, bem como o acesso a relatórios gerenciais e indicadores que auxiliam em decisões estratégicas. Por fim, as oficinas precisam de uma única ferramenta integrada, colaborativa, eficiente e clara para melhor desempenho em suas funções básicas.

## 7. Visão geral do produto

A plataforma Oktano tem como objetivo ser uma solução digital que unifica as principais funcionalidades no atendimento automotivo. Com foco em otimizar a rotina dos funcionários, gerenciar e ter um acesso rápido as informações cruciais das oficinas, promovendo transparência de suas informações e recursos para gerencia de clientes, serviços e estoque.

A plataforma é composta por 3 módulos distintos, voltados aos seguintes perfis de usuários: Administrador, oficina e seus funcionários. Cada módulo contempla funcionalidades específicas, mas todos se integram para garantir fluidez, confiabilidade e alinhamento das operações.

Para o Administrador, o sistema disponibiliza ferramentas de governança e administração de acessos, permitindo-o acessos estatísticos e controle sobre todas as oficinas cadastradas na plataforma mantendo a confiabilidade, privacidade dos usuários e a segurança de seus dados.

Para o gerente, o sistema oferece controle total restrito a própria oficina, como: controle de despesas, histórico de estoque e emissões fiscais, além de acesso aos seus relatórios mensais.

Já os funcionários contam com um ambiente centralizado, com acesso total às suas estatísticas como profissional. Além disso, acesso ao fluxo completo de atendimento, desde o cadastro dos clientes e seus veículos, até a emissão de nota fiscal no final do atendimento. 

O sistema também contempla funcionalidades de personalização e automação, como notificações inteligentes e atualização automática no estoque via nota fiscal, além de relatórios e indicadores de desempenho. A combinação desses elementos garante uma gestão moderna, colaborativa e humanizada das oficinas, reduzindo descentralização e promovendo eficiência operacional.

## 8. Requisitos Funcionais

| **Código** | **Ator** | **Nome** | **Descrição** | **Prioridade** |     
|------------|---------------|----------------------|------------|------------|
| **RF01** | Gerente | Gerencia de funcionários | O gerente tem acesso ao controle de funcionários na sua oficina.  | Alta |
| **RF02** | Funcionário | Registro de clientes/veículos | Os funcionários podem manter o registro de clientes na oficina, incluindo seus veículos. | Alta |
| **RF03** | Gerente/Funcionário | Listagem de Serviços | Os gerentes e funcionários podem ter acesso a uma listagem de serviços associados à oficina. | Alta |
| **RF04** | Funcionário | Emissão de nota fiscal | Os funcionários devem emitir nota fiscal a cada serviço concluído. | Alta |
| **RF05** | Gerente/Funcionário | Estoque | A oficina e seus funcionários devem ter acesso ao seu estoque para conclusão dos serviços disponíveis. | Alta |
| **RF06** | Sistema/Gerente | Notificações do estoque | O sistema notifica o gerente sobre atualizações no estoque. | Alto |
| **RF07** | Administrador | Listagem de Oficinas | Os administradores do Oktano devem ter acesso a uma lista dos perfis das oficinas cadastradas. | Alta |
| **RF08** | Funcionário | Manter ordem de serviço | Os funcionários devem abrir e manter a ordem de determinado serviço a ser realizado na oficina. | Alta |
| **RF09** | Sistema | Dashboard interativo | O sistema deve possuir um dashboard que constantemente é atualizado conforme os dados da oficina em questão. | Médio |
| **RF10** | Gerente/Funcionário | Perfis de Usuário | Os usuários podem ter acesso a sua página de perfil. | Baixo |


## 9. Requisitos não-funcionais

| **Código** | **Nome** | **Descrição** | **Categoria** |  **Classificação** |     
|------------|---------------|----------------------|------------|------------|
| RNF01   | Responsividade                | O sistema deve ser totalmente responsivo, garantindo usabilidade adequada em dispositivos móveis, tablets e desktops.                                 | Usabilidade       | Obrigatório    |
| RNF02   | Interface Intuitiva           | A interface deve ser simples, direta e de fácil compreensão para minimizar curva de aprendizado.                                                      | Usabilidade       | Obrigatório    |
| RNF03   | Proteção de Dados Sensíveis   | Dados pessoais, usuários e de serviços devem ser armazenados e transmitidos de forma segura, seguindo práticas de segurança modernas, como criptografia e autenticação.| Segurança         | Obrigatório    |
| RNF04   | Padronização de Ambiente      | O sistema deve ser dockerizado para padronizar o ambiente de desenvolvimento, testes e produção corporativa.                                                      | Infraestrutura    | Obrigatório    |
| RNF05   | Compatibilidade Cross-Browser | O sistema deve funcionar corretamente nos navegadores mais utilizados (Chrome, Firefox, Edge, Safari).                                                | Usabilidade       | Obrigatório    |
| RNF06   | Mensagens de Erro padronizadas   | O sistema deve apresentar mensagens de erro claras e orientadas ao usuário, sem exibir informações técnicas como stacktraces. Exemplo: "Erro ao salvar ordem de serviço. Tente novamente ou contate o suporte." | Usabilidade       | Obrigatório    |

## 10. Stack de Tecnologias

| Categoria             | Tecnologia      | Descrição  |
|------------------------|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Backend**            | Python           | Linguagem principal escolhida por sua produtividade, performance, eficiencia e potencial de evolução do sistema no mercado corporativo, sendo base para o framework utilizado. |
| **Framework Backend**  | Django Rest Framework    | Framework web performático, corporativo e com ferramentas eficientes que ajudarão a garantir segurança e fácil manutenção. |
| **Banco de Dados**     | PostgreSQL     | Banco de dados relacional robusto, selecionado para lidar com grandes volumes de dados, transações críticas e escalabilidade futura. |
| **Frontend**           | Angular        | framework voltada à criação de interfaces dinâmicas, responsivas e integração com o backend, escolhido por sua robustez e boa arquitetura.|
| **Infraestrutura**     | Docker         | Plataforma de conteinerização utilizada para padronizar ambientes, isolar dependências e facilitar o desenvolvimento, testes e deploys consistentes no futuro. |