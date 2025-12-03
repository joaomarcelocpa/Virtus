<div align="center">
  <img src="documentação/imagens/logo-virtus.png" alt="Virtus Logo" height="200"/>
</div>

## 📋 Descrição
Sistema de moeda estudantil desenvolvido no Laboratório de Desenvolvimento de Software, que permite a gestão de moedas de bonificação virtuais entre alunos e professores em ambiente acadêmico.

Virtus implementa um sistema de economia interna para instituições de ensino, onde professores podem distribuir moedas virtuais aos alunos como recompensa por participação, desempenho acadêmico e outras atividades. Os alunos podem acumular e trocar essas moedas por benefícios e vantagens oferecidas pela instituição ou empresas parceiras.

## 🚀 Acesso ao Sistema

O sistema **Virtus** está disponível online e pode ser acessado através do link:

**[https://virtus-psi.vercel.app/](https://virtus-psi.vercel.app/)**

### Deploy e Hospedagem

O projeto foi implantado utilizando as seguintes plataformas:

- **Frontend:** Hospedado na [Vercel](https://vercel.com/), garantindo deploy automatizado, alta performance e disponibilidade global através de CDN.
- **Backend:** Hospedado no [Render](https://render.com/), proporcionando uma infraestrutura confiável para a API REST e integração com o banco de dados PostgreSQL.

## 🏗️ Arquitetura do Sistema

O **Virtus** foi desenvolvido com base na arquitetura **MVC (Model-View-Controller)**, que separa claramente as responsabilidades da aplicação, garantindo melhor organização, escalabilidade e manutenção do código.

- **Model (Modelo):** Responsável pela lógica de negócio, regras e comunicação com o banco de dados.
- **View (Visão):** Camada de interface que exibe as informações ao usuário de forma amigável.
- **Controller (Controlador):** Atua como intermediário entre a View e o Model, processando requisições e controlando o fluxo da aplicação.

Além disso, adotamos o uso de **DTOs (Data Transfer Objects)** para otimizar a transferência de dados entre as camadas da aplicação. Essa prática aumenta a segurança, evitando a exposição desnecessária de entidades, e melhora a performance na comunicação entre back-end e front-end.

No front-end, foi utilizado o **App Router do Next.js**, que permite uma estrutura de rotas moderna e eficiente, com renderização híbrida (SSR e SSG), facilitando a criação de páginas dinâmicas e otimizadas para SEO.

---

## 🧩 Tecnologias Utilizadas

| Logo                                                                           | Tecnologia | Descrição |
|--------------------------------------------------------------------------------|-------------|-----------|
| <img src="documentação/imagens/spring.png" alt="Spring Boot" height="40"/>     | **Spring Boot** | Framework Java utilizado no back-end, responsável pela API REST, autenticação e integração com o banco de dados. |
| <img src="documentação/imagens/nextjs.png" alt="Next.js" height="40"/>         | **Next.js** | Framework React moderno usado no front-end, oferecendo renderização híbrida e excelente experiência do usuário. |
| <img src="documentação/imagens/postgreesql.png" alt="PostgreSQL" height="40"/> | **PostgreSQL** | Banco de dados relacional usado para armazenar e gerenciar as informações de alunos, professores e moedas. |

## 📚 Documentação

### Diagrama de Casos de Uso
![Diagrama de Casos de Uso](documentação/diagramas/Diagrama%20de%20Casos%20de%20Uso.jpeg)

### Diagrama de Classes
![Diagrama de Classes](documentação/diagramas/Diagrama%20de%20Classes.png)

### Diagrama de Componentes
![Diagrama de Componentes](documentação/diagramas/Diagrama%20de%20Componentes.png)

### Diagrama de Entidade e Relacionamento
![Diagrama de Entidade e Relacionamento](documentação/diagramas/Diagrama%20de%20Entidade%20e%20Relacionamento.jpeg)

### Diagrama do Modelo Relacional
![Diagrama do Modelo Relacional](documentação/diagramas/Diagrama%20do%20Modelo%20Relacional.png)

### Diagramas de Sequência

#### Cadastro de Vantagem
![Diagrama de Sequência 1](documentação/diagramas/Diagrama%20de%20Sequência%201.jpeg)

#### Listagem de Vantagens
![Diagrama de Sequência 2](documentação/diagramas/Diagrama%20de%20Sequência%202.jpeg)

### Diagramas de Comunicação

#### Envio de Moedas
![Diagrama de Comunicacao 1](documentação/diagramas/Diagrama%20de%20Comunicacao%201.png)

#### Troca de Vantagens
![Diagrama de Comunicacao 2](documentação/diagramas/Diagrama%20de%20Comunicacao%202.png)


### Histórias de Usuário
 [`Histórias de Usuário.pdf`](documentação/diagramas/Histórias%20de%20Usuário.pdf)

### Script do Banco de Dados PostgreSQL
[`script-postgresql.pdf`](documentação/scripts/script-postgresql.sql)

### Apresentação do Projeto - Primeira Versão
[`Apresentação Virtus.pdf`](documentação/apresentações/Apresentação%20Virtus.pdf)






## 👥 Equipe
Projeto desenvolvido pelos alunos:
- Bernardo de Resende Marcelino
- Flávio de Souza Júnior
- João Marcelo Carvalho Pereira Araújo
- Miguel Figueiredo Diniz
