# 🎮 E-Play Games - Advanced Redux & Game Catalog

Uma plataforma de catálogo de jogos de alta performance desenvolvida com **React**, utilizando o **Redux Toolkit** para gerenciamento de estado global e **Styled Components** para uma interface personalizada e responsiva. O projeto foca na organização de dados complexos e na experiência do usuário em um ambiente de e-commerce.

---

# 📝 Resumo (Resume)
Neste projeto, implementei uma arquitetura robusta onde o estado da aplicação (carrinho e filtros) é centralizado via **Redux**. A tipagem com **TypeScript** foi levada a um nível mais profundo, definindo a estrutura de objetos de jogos que incluem múltiplas plataformas e categorias. A estilização utiliza o poder das **Templates Literals** do JS para injetar um esquema de cores centralizado em todo o CSS global, facilitando futuras manutenções e trocas de temas.



## 🚀 Tecnologias e Ferramentas (Tech Stack)

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)](https://styled-components.com/)

## 📋 Funcionalidades em Destaque
* **Configuração de Store Profissional:** Uso de `configuraStore` para desacoplar a criação da store da inicialização da aplicação, seguindo as melhores práticas de Redux.
* **Modelagem de Dados (Game Interface):** Tipagem complexa que suporta arrays de plataformas, diferenciação entre preço antigo e atual, e categorização automática.
* **Tematização Centralizada:** Objeto `cores` exportável que alimenta o `GlobalStyle`, garantindo que toda a aplicação (fontes e fundos) mude instantaneamente ao alterar uma única variável.
* **Layout Fluido & Adaptativo:** Uso de seletores de container com Media Queries aninhadas para garantir que o catálogo de jogos seja visualmente impactante em monitores e dispositivos móveis.
* **Injeção de Provedor (Provider):** Envolvimento da aplicação no nível raiz para garantir que todos os subcomponentes (`Header`, `Produtos`) tenham acesso imediato ao estado global sem prop drilling.
* **Design System (Roboto & Colors):** Escolha estratégica de fontes e paleta de cores escura (Dark Mode) focada no público gamer.



---

# 👨‍💻 Sobre mim (About Me)
Olá, meu nome é **Kaio**, tenho 22 anos. Como meu foco principal é a transição para o **Back-End com Python**, este projeto de jogos me ensinou a lidar com objetos JSON de alta complexidade. No back-end, projetamos estruturas de dados (schemas) que o front-end consome; entender como o TypeScript valida essas estruturas me permite criar APIs muito mais seguras e fáceis de integrar com qualquer interface moderna.

### Entre em contato (Contact me)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=61DAFB)](https://linkedin.com/in/kaio-grativol-baldo-071a74150/)
[![Instagram](https://img.shields.io/badge/Instagram-000?style=for-the-badge&logo=instagram&logoColor=61DAFB)](https://www.instagram.com/kaiull__/)
[![GitHub](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github&logoColor=61DAFB)](https://github.com/SeuUsuarioAqui)

---
*Projeto desenvolvido para consolidar o uso avançado de Redux Toolkit e tipagem estrita no ecossistema React.*
