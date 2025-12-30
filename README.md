🏥 Prontuário Médico
📖 O que é este projeto?

Este projeto é um Prontuário Médico Web, desenvolvido para auxiliar médicos e clínicas no gerenciamento de pacientes, consultas e informações médicas, de forma centralizada, digital e organizada.

A aplicação tem como objetivo substituir processos manuais, facilitando o acesso ao histórico clínico dos pacientes e melhorando a eficiência no atendimento médico.

🧑‍⚕️ Finalidade

Organizar dados médicos de pacientes

Centralizar informações clínicas em um único sistema

Facilitar o controle de consultas e prontuários

Apoiar o dia a dia de médicos e secretárias

🛠️ Tecnologias Utilizadas
Front-end

HTML

CSS

JavaScript

Back-end

Python

Django

⚙️ Funcionalidades

Todas as funcionalidades da aplicação estão documentadas detalhadamente no documento abaixo:

📄 Documentação de Funcionalidades do Prontuário Médico
👉 https://docs.google.com/document/d/1SF1U4m3K-staia9yr9XtHj449TbteS8yPry3e6XJRsQ/edit?tab=t.0#heading=h.m3g3sdv6n1dr

Este documento descreve:

Funcionalidades do sistema

Regras e fluxos principais

Comportamentos esperados da aplicação

Tecnologias 

Este projeto utiliza:

Front-end desenvolvido em HTML, CSS e JavaScript

Back-end desenvolvido em Django

A documentação externa serve como referência principal para entendimento completo das funcionalidades do sistema.

1 Pagina: Login

E-mail:
Senha: (olhinho para visualizar a senha)

Opção de esqueceu senha
Criar Conta

2 Pagina: Criar Conta
Primeiro Nome
Ultimo Nome
Email
Senha
Confirmar senha
Criar Conta

3 pagina ESQUECEU SENHA
Quadrado perguntando e-mail(caso o email estiver no banco de dados, manda um codigo de verificação) (Caso não, da erro e indica que e-mail nunca foi cadastrado)

4 pagina COLOCAR CODIGO DE VERIFICAÇÃO 
Quadradinho pedindo o codigo de verificação 

5 pagina REDEFINIR SENHA
Pede nova sonha
Confirmar nova senha
Botao ALTERAR SENHA ( já redireciona o usuario para a pagina de login)

6 Pagina: Menu

Side Bar com as opções :
Pacientes 
Novos Pacientes 
Agenda

No Meio da pagina 

Um quadradinho para último paciente (Nome e CPF do paciente)
(Veria em relação a agenda, último paciente onde o médico confirmou atendimento)
Clicando nesse quadradinho já iria para o perfil do paciente 

Outro quadrinho apontando para o próximo paciente (Caso ele seja um paciente sem registro no sistema ou seja novo, Uma mensagem “Primeira vez do paciente NOME PACIENTE) (Caso tenha registro dele um quadradinho com o Nome e o cpf dele abaixo)
Clicando nesse quadradinho ja iria para o perfil do paciente 

Final da pagina poderia ter atalhos 

7 Pagina  Criar perfil de Novo Paciente
Informações sobre Pessoa
Nome completo 
CPF
Número de telefone 
Idade
Sexo
CRIAR PERFIL

8 Pagina PESQUISA INTELIGENTE DE PACIENTE

Estará organizado em ordem alfabética todos os paciente mas em cima terá uma barra de pesquisa inteligente para facilitar a busca do perfil do paciente 
Será colunas com o Nome da pessoa e o CPF dela embaixo.
Se redireciona para o perfil do paciente indicado 
Caso não encontre nenhuma devera aparecer na tela “Nenhum paciente com esse nome foi registrado “

9 PAGINA Perfil do Paciente 
No topo da tela tera um icone caso seja masculino de um menino e casa seja feminino um icone de uma menina, ao lado as informações sobre o Paciente 
Nome completo
Cpf
Sexo
Número de celular.
Peso/Altura/IMC
Botão para editar e excluir 
Uma side bar com algumas opções 
“Adicionar informações” - colocar alergias e etc
“Evolução” - ficar a opção das ultimas consultas do paciente e o que foi relatado e passado para o medico ver.Data do atendimento solicitações de exame/tratamento e conduta e etc(ficar disponível tanto a receita passado quanto observações feitas pelo medico,prescrição e etc).
“Nova Consulta” - Pronto para criar a prescrição da proxima consulta 

Pagina 10 informações completas
Esteticamente sem muita firula, side bar normal com todas as informações separadas de acordo com a necessidade 

Pagina 11 - “Evolução”
Podendo visualizar exatamente o que foi comentado nas ultimas consultas 
Opções em botões com as datas das consultas previas. Organizando em quadrantes(Divididas em categorias) colocando as informações que o medico indicou. Caso seja a primeira consulta do paciente aparecer “Primeira consulta “


Pagina 12 - “Nova Consulta “
Dividir em categorias com espaço com caixa de texto.
Ver viabilidade de colocar atalhos inteligentes para remédios/ problemas frequentes e etc.

————————

Pagina 12+1 - Agenda

Todos os horários por um dia ( começa tal hora e termina tal hora)
Setas para avançar um dia e seta para voltar um dia
Um botão para você poder avançar meses ou para um dia específico.
Um botão de mais para adicionar um horário 
Cores diferentes (bloquinhos)

14 pagina ou mini pagina -
Criação de um agendamento 
Nome 
CPF
Dia e horário 
Criar agendamento 
