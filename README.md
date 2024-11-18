---
description: >-
  Este é um trabalho solicitado pela Prof. Kadidja para a matéria "Projeto de
  Linguagens de Programação" do 8º semestre de Ciência da Computação do Centro
  Universitário do Distrito Federal.
---

# DevOrbit

Integrantes:

* Pedro Henrique da Rocha Soares - [GitHub](https://github.com/peterspbr)
* Wesley Lopes Ferreira Santos - [GitHub](https://github.com/Lupescoder)
* Guilherme Coelho - [GitHub](https://github.com/)
* Diego Lohan - [GitHub](https://github.com/diegolohan14)

#### 1. Introdução

O **DevOrbit** é uma plataforma convergente, em que integra funcionalidades de blog e fórum em um ecossistema auto-sustentável, projetado para promover a inteligência coletiva dentro da instituição. Operando sob um modelo de governança colaborativa, os discentes desempenham um papel central na curadoria do conteúdo, garantindo a acurácia e relevância das informações por meio de um sistema de votação meritocrático. A estrutura do **DevOrbit** permite a iteração contínua dos posts, onde os alunos, além de poderem endossar os conteúdos mais valiosos, também são habilitados a realizar contribuições e modificações, garantindo um fluxo orgânico de conhecimento em múltiplas frentes temáticas.

O site foi construído usando as seguintes ferramentas:

* **Frameworks**: Laravel + Vue;
* **Linguagens de programação**: PHP, Javascript;
* **Banco de dados**: MariaDB.

#### 2. Pré-requisitos

Para contribuir no desenvolvimento ou instalar o site localmente, é necessário ter:

* `PHP >= 8`
* `MySQL >= 8`
* `Node.js >= 18.16.0`

Acesse o GitHub do nosso projeto:

* **GitHub**: [https://github.com/peterspbr/devorbit](https://github.com/peterspbr/devorbit).

Para instalar e começar a usar, basta rodar os seguintes comandos no terminal:

```
git clone https://github.com/peterspbr/devorbit.git
cd devorbit
composer install
npm install pinia
php artisan migrate
composer run dev
```

#### 3. Como começar:

Para iniciar sua imersão no DevOrbit, é necessário realizar o processo de cadastramento, fornecendo um nome e RGM devidamente válidos. Apenas após essa autenticação inicial será possível desbloquear o acesso à plataforma, assegurando a integridade do sistema e garantindo uma experiência exclusiva e personalizada.

#### 4. Estrutura do Site

1. **Página Inicial**: Introdução ao site, com opções para login e cadastro.
2. **Login e Registro**: Cadastro e login do usuário.
3. **Perfil**: Área restrita onde o usuário pode acessar suas informações.
4. **Página Principal**: Plataforma convergente, integrando funcionalidades de blog e fórum.

#### 5. Funcionalidades Principais

* **Autenticação de Usuário**: Login e registro com opções de recuperação de senha.
* **Portal**: O portal garante a integração com os demais projetos dos estudantes do curso.
* **Github**: Acesso ao código fonte do projeto com direito a fazer seu próprio deploy em seu ambiente.
* **Área do Aluno**: Acesse a área do aluno da UDF.
* **Blog**: Criação e interação de posts entre os usuários.

#### 6. Suporte e Manutenção

Para questões técnicas, entre em contato com o suporte por meio da página de contato do site ou enviando e-mail para [m4sh1lo@protonmail.com](mailto:m4sh1lo@protonmail.com).

**Atualizações**:

* Atualizações de segurança e manutenção ocorrem mensalmente.
* Sugestões de novas funcionalidades são bem-vindas e podem ser enviadas para o e-mail do suporte.
