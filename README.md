## Diagramas de Caso de Uso

# Movimentação do Aluno:

1.	Entrar com Login e Validar: Este caso de uso permite que um aluno entre no sistema utilizando seu login e senha, e valide suas credenciais.

-	Pré-condição: O aluno deve estar registrado no sistema e ter credenciais válidas (login e senha).  
-	Cenário principal:
     -  O aluno acessa a página de login do sistema;
     -  O aluno insere seu login e senha nos campos correspondentes;
     -  O sistema verifica se as credenciais estão válidas;
     -  O sistema autentica o aluno e permite o acesso ao sistema;
     -  O sistema exibe a página principal do aluno.  
-	Pós-condição: O aluno é autenticado no sistema e pode acessar as funcionalidades disponíveis para sua conta.

2.	Verificar dados do perfil: Este caso de uso permite que um aluno visualize seus dados de perfil registrados no sistema.  

-	Pré-condição: O aluno deve estar autenticado no sistema.
-	Cenário principal:
     -  O aluno acessa a página de perfil no sistema;
     -  O sistema recupera os dados de perfil do aluno;
     -  O sistema exibe os dados de perfil do aluno na página.
-	Pós-condição: O aluno visualiza seus dados de perfil no sistema.

3.	Verificar notas: Este caso de uso permite que um aluno consulte suas notas registradas no sistema.

-	Pré-condição: O aluno deve estar autenticado no sistema.
-	Cenário principal:
     -  O aluno acessa a página de notas no sistema;
     -  O sistema recupera as notas do aluno;
     -  O sistema exibe as notas do aluno na página.
-	Pós-condição: O aluno visualiza suas notas no sistema.

4.	Verificar faltas: Este caso de uso permite que um aluno verifique suas faltas registradas no sistema.

-	Pré-condição: O aluno deve estar autenticado no sistema.
-	Cenário principal:
     -  O aluno acessa a página de faltas no sistema;
     -  O sistema recupera as faltas do aluno;
     -  O sistema exibe as faltas do aluno na página.
-	Pós-condição: O aluno visualiza suas faltas no sistema.

5.	Verificar apostilas: Este caso de uso permite que um aluno verifique as apostilas disponíveis no sistema.

-	Pré-condição: O aluno deve estar autenticado no sistema.
-	Cenário principal:
     -  O aluno acessa a página de apostilas no sistema;
     -  O sistema lista as apostilas disponíveis para o aluno;
     -  O aluno seleciona uma apostila para visualização;
     -  O sistema exibe a apostila selecionada na página.
-	Pós-condição: O aluno visualiza a apostila selecionada no sistema.


# Gerenciamento de Professores:

1.   Cadastrar um professor novo: Este caso de uso permite que um membro da Secretaria registre um novo professor no sistema.

-    Pré-condição: O secretário deve estar autenticado no sistema.
-    Cenário principal:
     -  O secretário acessa a página de registro de usuários no sistema;
     -  O secretário escolhe a opção para o registro de professores;
     -  O secretário preenche os dados do novo professor na página;
     -  O sistema insere os dados do novo professor na base de dados.
-    Pós-condição: O secretário visualiza o perfil do professor no sistema.

2. Gerar relatório de professores: Este caso de uso permite que um membro da Secretaria consulte os professores registrados no sistema.

-    Pré-condição: O secretário deve estar autenticado no sistema.
-    Cenário principal:
     - O secretário acessa a página de relatórios no sistema;
     - O secretário localiza e acessa o link do relatório professores cadastrados no sistema;
     - O sistema exibe o relatório de professores na página.
-    Pós-condição: O secretário visualiza o relatório de professores cadastrados no sistema.

# Cadastro de Pessoa Jurídica

Antes que o cadastro de colaboradores terceirizados seja feito, é necessário que os dados da Pessoa Jurídica associada sejam cadastrados. Para isso, o representante da secretaria deve acessar o sistema e inserir as seguintes informações na tela abaixo: nome/razão social, nome fantasia, CNPJ, endereço, bairro/distrito, UF, município, telefone e inscrição estadual. Todos esses campos são de preenchimento obrigatório. Caso haja alguma observacão, o secretário pode inserí-la no campo Informações adicionais. Após o preenchimento das informações, deve-se clicar no botão Próximo (em destaque na imagem abaixo) para que os dados sejam gravados:

![Pessoa Jurídica](Pessoa%20Jurídica.png)

# Cadastro de Colaboradores de Pessoa Jurídica:

1. Cadastrar Colaboradores de Empresa Terceirizada prestadora de serviço de Limpeza na unidade de Ensino: Este caso de uso permite que a Pessoa Jurídica (representante da empresa contratada) cadastre os dados pessoais dos colaboradores, a fim de manter o controle de acesso à Unidade de Ensino.

-   Descrição: Cadastro dos dados pessoais dos colaboradores para manter o controle de acesso à Unidade de Ensino.
-   Pré-Condição: Inclusão de colaboradores na base de dados é feita após o cadastro dos dados de Pessoa Jurídica.
-   Atores: Secretaria e Pessoa Jurídica
-   Prioridade: Essencial

-   Cenário Principal:
    -  A tela de login do sistema Decision é iniciada.
    -  O representante da empresa contratada (Pessoa Jurídica) insere os dados pessoais dos colaboradores.
    -  A secretaria aprova o cadastro dos dados dos colaboradores no sistema.
    -  O sistema Decision insere os dados de cada colaborador na base de dados associada à respectiva pessoa jurídica.

-   Pós-Condição: O sistema possui relacionado cada colaborador com a respectiva empresa à qual faz parte.
