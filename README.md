# classmanager
Um Portal Aluno-Professor construído usando HTML, CSS, Python e Django

Class Manager é um Portal Aluno-Professor onde professores e alunos podem se cadastrar, e os professores podem adicionar alunos em suas turmas.

O Class Manager contém mais recursos, como:
1. Professores podem adicionar ou editar as notas de seus alunos após adicioná-los à turma.
2. Professores também podem escrever avisos que serão enviados a todos os alunos da turma.
3. Professores podem enviar tarefas que serão enviadas a todos os alunos da turma e os alunos podem baixar as tarefas.
4. Os alunos também podem enviar suas tarefas, mas uma vez enviadas, não podem ser alteradas posteriormente.
5. Professores podem ver todas as notas dadas por eles a um aluno através do perfil de notas e podem editá-las, se necessário.
6. Alunos podem ver as notas dadas a eles pelos professores na seção de notas.
7. Alunos podem ver a lista de todos os professores no portal e podem enviar mensagens para qualquer um deles.
8. Professores podem ver todas as mensagens escritas pelos alunos na Caixa de Entrada.
9. O usuário pode procurar qualquer aluno através da opção de busca na parte superior da página da lista de alunos. O mesmo vale para a lista de professores.
10. O usuário pode ver seu perfil através da opção de perfil.
11. O usuário pode adicionar uma foto de perfil e editar seu perfil através da opção de editar perfil.
12. O usuário também pode alterar sua senha, se necessário.

## Capturas de Tela

### Página Inicial

![classmanager](https://user-images.githubusercontent.com/59278577/85334196-73729680-b4f8-11ea-90b6-a42336e1d7dd.PNG)
![classmanager-homepage](https://user-images.githubusercontent.com/59278577/85334362-c2203080-b4f8-11ea-973c-e9ff6b481810.PNG)
![classmanager-homepage1](https://user-images.githubusercontent.com/59278577/85334481-f398fc00-b4f8-11ea-88fc-ba3371076930.PNG)

### Página de Login

![classmanager-loginpage](https://user-images.githubusercontent.com/59278577/85334573-1deab980-b4f9-11ea-86b9-4e1367e78057.PNG)

### Opções Disponíveis para Professores

![classmanager-teacheroptions](https://user-images.githubusercontent.com/59278577/85334843-8cc81280-b4f9-11ea-8162-2ac5756f3884.PNG)

### Opções Disponíveis para Alunos

![classmanager-studentsoptionlist](https://user-images.githubusercontent.com/59278577/85336072-ac603a80-b4fb-11ea-87b5-a942ce294a2b.PNG)

### Página de Perfil
O usuário pode editar seu perfil clicando em Editar perfil.

![classmanager-profilepic](https://user-images.githubusercontent.com/59278577/85335035-f34d3080-b4f9-11ea-9478-bc4632798eef.PNG)

### Notas dadas pelo professor
Aqui, os professores podem ver todas as notas dadas por eles a um aluno específico de sua turma e podem atualizá-las.

![classroom-marksgiven](https://user-images.githubusercontent.com/59278577/85335383-8d14dd80-b4fa-11ea-8257-797c5a0fe52a.PNG)

### Lista de notas obtidas pelo aluno

![classmanager-marksobtained](https://user-images.githubusercontent.com/59278577/85335564-d6fdc380-b4fa-11ea-8219-09d40f96f8e7.PNG)

### Tarefas enviadas pelo professor
Os alunos podem baixar as tarefas enviadas pelo professor e podem enviar seu trabalho também.

![classmanager-assignmentpage](https://user-images.githubusercontent.com/59278577/85335929-6c995300-b4fb-11ea-883d-48ab096dd89a.PNG)

### Envio de tarefas pelos alunos
Os professores podem verificar os envios feitos pelos alunos e podem dar notas para isso.
![classmanager-submissionlist](https://user-images.githubusercontent.com/59278577/85335777-2e039880-b4fb-11ea-8d7d-0edc517ac11e.PNG)

Class Manager usa o conceito de multiusuário do Django, onde alunos e professores são tipos diferentes de usuários e têm funcionalidades diferentes.
Além disso, adicionar recursos como avisos, mensagens, tarefas, adicionar alunos à turma, etc., requer muitos conceitos do Django.
Projetos como o Class Manager são uma ótima escolha para praticar suas habilidades em Django e testar a si mesmo.