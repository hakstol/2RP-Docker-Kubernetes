<h1 align="center">2RP-Docker-Kubernetes 🌐</h1>

<h4></h4>

<h3>Escopo - Task 2</h3>

<p>Esse teste tem como finalidade avaliar o nível de conhecimento do candidato em relação as ferramentas Docker e Kubernetes, tal como se ele possui conhecimento de linguagem de programação.</p>

<h2>Tarefas:</h2>
<ol>1. Criar uma aplicação que fique exibindo o valor de uma variável de ambiente do sistema operacional de 20 em 20 segundos, o nome da variável deve ser "TWORPTEST" e o valor desta variável deve ser "true100%".</ol>
<ol>2. Criar um container usando docker ou outro orquestrador de containers similar.</ol>
<ol>3. Opcional: fazer o upload da imagem construída para um container registry de preferência. Observação: o valor da variável deve ser exibido no log do container</ol>
<ol>4. Opcional: Instanciar um cluster kubernetes local usando Minikube, K3D ou similar para criação e testes dos manifestos.</ol>
<ol>5. Criar manifestos kubernetes incluindo os tipos deployment, service, secret. O deployment deve rodar a imagem docker construida nas etapas anteriores e na secret deve ser adicionado a variável esperada pela aplicação e passada para o container como variável de ambiente.</ol>
<ol>6. Bônus (opcional): Fazer um script bash que percorre os namespaces e coleta a secret de cada deployment para comparar se o valor da secret do deployment está sendo exibida no log do container que está rodando a aplicação. Se o valor da secret estiver sendo exibida retornar uma mensagem informando que o container tem um problema de segurança.</ol>

<h2>Observações:</h2>
<ul>• O código precisa ser autoral, cópia de códigos prontos da internet serão desconsiderados</ul>
<ul>• A não realização de qualquer etapa apenas reduz a nota final, porém nenhuma das atividades propostas é passível de eliminação direta. O teste é para indicação do nível de conhecimento nas ferramentas e capacidade de lidar com novas tecnologias, então realize o máximo de atividades que conseguir</ul>
