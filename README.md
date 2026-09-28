  Hobbify - Gestão de Hobbies

O **Hobbify** é uma plataforma simplificada desenvolvida para auxiliar na organização e acompanhamento de atividades pessoais e hobbies (como treinos, leitura, culinária e coleções).

#  Funcionalidades do MVP
-  Perfil do Usuário
-  Cadastro de Hobbies com metas semanais
-  Registro de atividades realizadas
-  Acompanhamento de progresso básico

#  Tecnologias Utilizadas
- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **Controle de Versão:** Git / GitHub
- **Gestão de Projeto:** Metodologia Ágil / Kanban

- https://github.com/gabrielricci-creator


# AULA 2 - CONCEPÇÃO: DO PROBLEMA AO MVP

## 1. Pesquisa e Definição de Personas

### Persona 1: Lucas Andrade
- **Idade:** 24 anos
- **Ocupação:** Estudante universitário e estagiário
- **Perfil e Dificuldades:** Possui uma rotina corrida e pouco tempo livre. Deseja manter hábitos como leitura diária e exercícios físicos, mas esquece com frequência de praticar ou perde o controle de quantas vezes realizou a atividade durante a semana.
- **Objetivo no Hobbify:** Registrar rapidamente uma atividade realizada e visualizar o seu progresso acumulado na semana de forma simples e direta.

---

## 2. Definindo o MVP (Produto Mínimo Viável)
O MVP do Hobbify foca exclusivamente na gestão essencial de hábitos e hobbies, permitindo cadastro, registro de execução e acompanhamento visual sem complexidades desnecessárias.

---

## 3. User Stories do MVP

### US01 - Tela Inicial e Boas-Vindas
- **História:** Como usuário, quero ver uma tela inicial personalizada com meu nome e mensagem de boas-vindas para ter uma experiência agradável ao abrir o aplicativo.
- **Critério de Aceite:** A tela principal deve exibir o nome do usuário cadastrado e um cabeçalho simples de navegação.

### US02 - Cadastro de Novo Hobby
- **História:** Como usuário, quero cadastrar um novo hobby especificando o nome, categoria e meta semanal de vezes para organizar meus objetivos.
- **Critério de Aceite:** O formulário deve aceitar o nome do hobby, categoria (ex: Esporte, Leitura, Arte) e meta semanal numérica, adicionando o item à lista.

### US03 - Visualização de Cartões de Hobbies
- **História:** Como usuário, quero visualizar meus hobbies em formato de cartões na tela para acompanhar o status de cada um.
- **Critério de Aceite:** Cada cartão deve exibir o nome, a categoria, o total de sessões concluídas e a meta semanal definida.

### US04 - Registro de Atividade Realizada
- **História:** Como usuário, quero clicar em um botão no cartão do hobby para registrar que concluí uma sessão hoje.
- **Critério de Aceite:** Ao clicar no botão "+1 Sessão", a contagem da semana deve ser incrementada instantaneamente na tela.

### US05 - Exclusão de Hobby
- **História:** Como usuário, quero ter a opção de remover um hobby cadastrado para manter minha lista limpa e atualizada.
- **Critério de Aceite:** O cartão do hobby deve possuir um botão de exclusão que remove o item da tela após confirmação do usuário.
