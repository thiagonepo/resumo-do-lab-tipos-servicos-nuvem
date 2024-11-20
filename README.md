# resumo-do-lab-tipos-servicos-nuvem

Este repositório contém um resumo das lições adquiridas durante o desenvolvimento do LAB na DIO.

## 🚀 Resumo sobre os Tipos de Serviços em Nuvem

A computação em nuvem oferece uma variedade de serviços que permitem que empresas e indivíduos armazenem e processem dados de forma flexível e escalável, sem a necessidade de servidores físicos. Os principais modelos de serviço são:

- **Software como Serviço (SaaS):** Permite o uso de aplicativos via navegador, sem a necessidade de gerenciar a infraestrutura subjacente. Exemplos incluem Google Docs e Microsoft 365.
  - **Vantagens:** Facilidade de uso, baixo custo e atualizações automáticas.

- **Plataforma como Serviço (PaaS):** Oferece uma plataforma para o desenvolvimento e implantação de aplicativos, permitindo que os desenvolvedores se concentrem apenas no software. Exemplos: Google App Engine e AWS Elastic Beanstalk.
  - **Vantagens:** Agilidade no desenvolvimento e foco em aplicativos, sem a preocupação com a infraestrutura.

- **Infraestrutura como Serviço (IaaS):** Oferece recursos virtualizados, como servidores e armazenamento. Exemplos: Amazon EC2 e Google Compute Engine.
  - **Vantagens:** Flexibilidade e controle sobre a infraestrutura.

Além desses modelos, existem a **nuvem pública** (compartilhada por vários usuários), a **nuvem privada** (dedicada a uma única organização) e a **nuvem híbrida** (uma combinação das duas). A escolha do serviço ideal depende do orçamento, controle desejado e da complexidade do aplicativo.

## 🚀 Resumo sobre o Modelo de Responsabilidade Compartilhada

O **modelo de responsabilidade compartilhada** é fundamental na computação em nuvem, no qual as responsabilidades pela segurança e gestão dos serviços são divididas entre o provedor e o cliente. A divisão varia conforme o tipo de serviço utilizado (SaaS, PaaS ou IaaS):

- **Software como Serviço (SaaS):**  
   - **Provedor de nuvem:** Gerencia toda a infraestrutura, incluindo segurança de aplicativos, servidores, redes e armazenamento.
   - **Cliente:** Gerencia o acesso aos dados, define permissões e controla a autenticação.

- **Plataforma como Serviço (PaaS):**  
   - **Provedor de nuvem:** Cuida da infraestrutura subjacente, como servidores e redes.
   - **Cliente:** Responsável pelo gerenciamento e segurança do código e dos aplicativos criados.

- **Infraestrutura como Serviço (IaaS):**  
   - **Provedor de nuvem:** Responsável pela infraestrutura física, como servidores e armazenamento.
   - **Cliente:** Gerencia o sistema operacional, as redes virtuais e a segurança dos dados.

### Exemplo de divisão de responsabilidades:
- **Provedor de nuvem:** Responsável pela segurança física dos data centers, controle de hardware e manutenção da infraestrutura.
- **Cliente:** Gerencia a configuração segura dos serviços, identidades, acessos e proteção de dados.
