Em construção
# Algebra-Linear-com-Python
**_Aplicações dos tópicos aprendidos na disciplina Álgebra Linear usando a linguagem de progamação Python._**

#### Começando
Essas instruções terão como finalidade mostrar-lhes como baixar e usar os códigos do repositório em suas máquinas, visando compilar e
editar para diversas finalidades.

#### Pré-requisitos
É interessante que o usuário tenho instalado todo o ambiente de trabalho Python instalado em sua máquina.Caso não seja viável a instalação 
do Python em sua máquina, não se preocupe. Há outra forma pela qual é possível acessar os progamas do repositório. Vamos apresentar o 
Google Colab Notebook mais adiante e como é possível usá-lo para baixar o progama e executá-lo através do seu navegador Google Chrome.

#### Instalando

###### Baixando o ambiente de trabalho Python em sua máquina.

Veja o vídeo abaixo para instalar devidamente o Python em sua máquina(disponível para Windows, Linux e Mac).

- [Instalando o Python3 e o IDLE](https://www.youtube.com/watch?v=VuKvR1J2LQE)

Após todos os procedimentos do vídeo terem sido realizandos, abra o prompt de comando da sua máquina e digite os seguintes comandos
para importar todas as bibliotecas usadas nos progamas do repositório:

1. **_pip install numpy_**
2. **_pip install matplotlib_**
3. **_pip install scipy_**
4. **_pip install jupyter_** ou **_pip install jupyter lab_**
5. **_pip install sympy_**
6. **_pip install imageio_**
7. **_pip install ipywidgets_**

Após importar todas as bibliotecas acima você terá todo os requisitos necessários para compilar os progamas apresentados no repositório.

###### Usando o Google Colab Notebook

Como foi dito acima, outra opção razoável é usar o Google Colab Notebook. Vale salientar que por mais completo que seja essa instrumento
de trabalho da Google, ele não possuí todas as bibliotecas disponíveis acima. Entretanto, você pode verificar qual célula não compilará,
um dos erros possíveis é a não disponibilidade da biblioteca no servidor. Para contornar tal fato, crie uma nova célula de código(CODE)
e digite **_pip install [ ]_**, na qual [ ] será o nome da biblioteca a ser importada. Veja o vídeo abaixo para ter uma ideia de como
utilizar o Google Colab Notebook.


- [Get started with Google Colaboratory](https://www.youtube.com/watch?v=inN8seMm7UI)

#### Compilando

Vamos agora aprender a compilar todos os progamas do repositório dado que todos os passos acima estão satisfeitos. O arquivo .ipynb 
utilizando é um forte instrumento para se utilizar quando deseja-se estudar tópicos de progamação voltados para algum assunto 
didático. No nosso repositório, usamos tal instrumento para trazer aplicações da disciplina de Álgebra Linear computacionalmente.
Muito além de ser algo complementar no aprendizado, é também um ótimo começo para quem deseja aprender a linguagem de progamação 
Python, dado que é uma linguagem com aplas funcionalidades para diversas áreas de trabalho.

###### Como usar os notebooks

Os arquivos com extensão .ipynb são chamados de notebooks. Um notebook é composto por células, essas que obedecem as normas vigentes de
boa prática de progamação: a ideia da progamação sequencial. Uma célula pode ser de dois tipos: célula de código(Code) ou célula de 
texto(Markdown). As células de texto elas são independentes entre sí em um viés computacional, pois a execução da mesma não vai 
interferir nas células de código. Sobre o víes do aluno, é interessante para o seu entendimento que a leitura das mesma seja feito
sequencialmente, dado que alguns notebooks desenvolvidos anteriormente ajudam no entendimentos das desenvolvidas posteriormente. As
células de código, como foi dito acima, obedecem a idea da progamação sequencial. Desse modo, é fundamental que:
 > **TODAS AS CÉLULAS SEJAM EXECUTADAS, DO INÍCIO AO FIM, DADO QUE AS CÉLULAS POSTERIORES SÃO DEPENDENTES DAS CÉLULAS ANTERIORES**
 Caso contrário, erros de compilação surgirão, interrompendo o funcionamento do progama.
 
 ###### Abrindo um notebook
 
 Para quem optou por instalar na sua máquina o ambiente de trabalho do Python, pode seguir as seguintes instruções para abrir um 
 notebook em sua máquina:
 
 1. Abra o prompt de comando;
 2. Digite **_jupyter notebook_** caso tenha optado pelo métod de instalação **_pip install jupyter_** ou digite **_jupyter lab_** 
 caso tenha optado pela opção de intalação **_pip install jupyter lab_**;
 > Jupyter Notebook tem o mesmo funcionamento do Jupyter Lab, a única diferença é que o segundo é uma versão do aplicativo mais recente que o primeiro.
 3. Após ter feito isso, o será criado no seh prompt de comando uma espécie de servidor local e o aplicativo será aberto em seu browser
 padrão;
 > **NÃO FECHE O SEU PROMPT DE COMANDO ENQUANTO ESTIVER USANDO O JUPYTER NOTEBOOK OU JUPYTER LAB, CASO CONTRÁRIO, O KERNEL DO APLICATIVO SERÁ ENCERRADO JUNTO.**
 4. Caso você queira criar um novo notebook, clique na opção "New Launcher". Dentro do progama:
  - Ícone do disquete("Save the notebook contents and create checkpoint"): salva o seu progama(Ctrl + S);
  - Ícone de +("Insert a cell below"): Insere uma célula no seu notebook;
  - Ícone de tessoura("Cut the selected cells"): corta alguma célula selecionada do seu progama;
  - Ícone de copiar("Copy the selected cells"): cópia uma célula do seu progama;
  - Ícone da prancheta("Paste cells from the clipboard"): cola a célula copiada;
  - Ícone de dar play("Run the selected cells and advance"): compila a célula selecionada;
  - Ícone de parar("Interrupt the Kernel"): Interrompe a compilação da célula em processo;
  - Ícone de reiniciar("Restart the Kernel"): Reinicia a compilação da célula em processo;
  - Opção Markdown: Transforma a célula selecionada em uma célula de texto;
  - Opção Code: Transforma a célula selecionada em uma célula de código;
 5. Caso você queira criar uma pasta, clique na opção "New folder";
 6. Caso você queira adicionar um novo arquivo .ipynb do seu computador, clique na opção "Upload Files";
 
 Para quem optou usar o Google Colab Notebook, pode seguir as seguintes instruções para executar um notebook em um servidor pelo
 Google Browser.
 
 1. Logo de início, aparecerá uma janela com diversas opções, nela você pode fazer os seguintes passos:
  - Na aba "Examples", temos uma série de progamas .ipynb fornecidos pelo Google para familizarizar o usuário com o aplicativo;
  - Na aba "Recent", é possível ver os progamas .ipynb acessados recentemente;
  - Na aba "Google Drive", você verá todos os seus progamas criados
  > Todos os progamas criados no Google Colab Notebook são salvo no Google Drive vinculado a conta do usuário.
  - Na aba "Git Hub", pode-se copiar a URL do repositório que tem uma extensão .ipynb e usá-lo para abrir o progama do Git Hub no 
    Google Colab Notebook de forma direta.
    > **PARA USUÁRIOS DO GOOGLE COLAB NOTEBOOK, ESSA SERÁ A FORMA DE ACESSAR OS PROGAMAS DO NOSSO REPOSITÓRIO**
  - Na aba é "Upload" você pode adicionar um progama .ipynb do seu computador diretamente no Google Colab Notebook.
 2. Na opção "New Python3 Notebook" você conseguirá criar um novo notebook.
  - Na
 