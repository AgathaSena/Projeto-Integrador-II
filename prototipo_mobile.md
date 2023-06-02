# Diagrama de Componentes 

Segue abaixo a representação do Diagrama de Componentes:

<img width="611" alt="Diagrama de Componentes" src="https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/bb9d8fe0-2eb8-4683-aae5-ea441e653f3a">

O diagrama é composto por três componentes principais: 

1. Aplicativo móvel: O aplicativo móvel se comunica com o servidor de backend para enviar comandos de alimentação e receber informações sobre os animais de estimação.
2. Servidor/ cliente MQTT: Componente responsável por estabelecer a conexão com o servidor MQTT, enviar mensagens para os tópicos relevantes e receber mensagens dos tópicos assinados. 
3. Alimentador automático: O alimentador automático, por sua vez, recebe os comandos do servidor e executa a alimentação programada. Esse componete possui uma câmera embutida para monitoramento dos animais de estimação e um áudio embutido para possíveis interações com eles. Além de poder incluir motores, sensores e outros componentes físicos relacionados.


# Tela inicial
A tela inicial é responsável por permitir a interação do usuários com as funcionalidade do aplicativo e consequentemente o controle do alimentador. No primeiro acesso será solicitado ao que ele escolha uma forma segura de se cadastrar no aplicativo. Isso poderá ser realizado de três formas, com o seu email google, com seu login do facebook ou com o seu email pessoal.
![tela-inicial](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/654e6c76-67c9-476b-8160-7b9a339945ad)


# Tela de cadastro

A tela de cadastro é a tela acessada após a escolha do método de entrada no app.
Essa tela solicita algumas informações que permitiram fornecer ao usuário maior segurança e um perfil personalizado. Os dados pedidos são: Nome, email, senha e a confirmação da senha.

![tela-cadastro](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/ad7faf73-8157-44ed-913b-783e2483f26f)


# Tela de login
Após o cadastro ter sido concluído, será liberado para o usuário a tela de login. Essa tela, efetivamente permiti ao usuário realizar sua interação com o aplicativo utilizando uma maneira confiável e segura. Nessa tela será pedido o Nome utilizado no cadastro e a senha para acesso.

![tela-login](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/7ca1b770-6483-4c25-b01f-4d97fa66a8d5)


# Menu

O menu apresenta de forma direta e visual todas as opções principais que podem ser acessadas pelo usuário. Entre elas estão: agendar rotinas, registro comportamental, notificações, acessar câmera, histórico e configurações.
- Agendar rotinas: Permitir que o usuário crie rotinas de forma personalizada de acordo coma as necessidades dele e do seu pet.
- Registro comportamental: Apresenta um registro compilado dos dados coletados ao longos de um determinado período referente ao comoprtamento do pet.
- Notificações: Fornecem um resumo rápido das ações ocorridas em tempo real.
- Acessar câmera: Fornece acesso a câmera presente no alimentador para visualização em tempo real.
- Histórico: Armazena de forma organizada e estruturada as todas as informações coletadas como notificações para serem acessadas quando necessário.
- Configurações: Apresenta ao usuário opções de personalização do seu perfil no aplicativo, além de permitir a adição de novos participantes.

![menu](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/573e0e0a-e5c6-4c50-8c66-d7f551a3b5d8)

# Agendar rotinas

A tela de agendar rotinas, faz exatamente o que seu nome propõe. Essa opção fornece ao usuário a possibilidade de agendar tarefas, como o horário da alimentação, a quantidade, os dias da semana. A personalização dessa atividades permiti que o usuário tenha uma automatização de atividades antes manuais.

![agendar-rotinas](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/fe32dba8-a218-4a9e-a45e-d531b965155f)

# Registro Comportamental 

O registro comportamental apresenta as informações de tudo que ocorreu ao longo de um período realacionado as atividades/rotinas aplicadas ao pet. O registro comportamental considera para suas análises tanto ações reais, programas pelo usuário como também aquelas ações espontâneas realizadas pelo pet, como por exemplo o horário que bebeu água, ou os horários que ele foi tentar se alimentar. A coleta e análise desses dados podem fornecer um padrão diário do pet para seu tutor que pode ser usado para inferências importantes sobre a saudade dele.

![registro-maio](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/0ef32672-fa22-4396-91e2-a63147b68816)
![registro-fevereiro](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/145e8f12-bc5c-443e-af8e-78d97305fc93)

# Notificações
Notificações das ações realizadas pelo pet em tempo real. Essa opção fornece de forma resumida informações importantes com o objetivo de manter o tutor informado.

![notificacoes](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/ecc3c7b0-2698-45f8-a477-7ba54a102603)


# Histórico
A tela de histórico apresenta todas as ações realizadas ao longo de um periódo de tempo selecionado pelo tutor. As atividade e ações realizadas são apresentadas de forma detalhada e estruturada contendo informações mais específicas sobre tais ações.

![historico](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/7f7ac9fe-6d83-4a87-9169-3b76acdd3562)


# Vídeos do Histórico
Apresenta uma galeria dos vídeos salvos pelo tutor/usuário contendo datas e horários.

![vídeos](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/5c201e19-dc1c-48c5-96d3-8e9252c23b3e)

Um exemplo de como ficaria a apresentação do vídeo, mostrando o seu pet.
## Vídeo V03 12/05 - Histórico
![video-1205](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/63efe7b5-586e-442d-bb46-4eadcc86e4b2)

## Vídeo V01 10/05 - Histórico
![video-1005](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/11ed66eb-09f8-4ab7-a75c-1ebf3a025d9e)

# Alimentação e água
Informações que ficaram guardadas das notificações 
![alimentacao](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/fab1adb6-5289-4d79-9b74-31d634b9a499)

# Alimentação e água
Informações mais detalhadas 
![alimentacao2](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/81e15e9b-2c59-49ef-9c91-e5dc56103ebb)

# Câmera
Permite o controle e acesso da câmera presente no alimentador ao vivo.
![camera](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/21163b99-3ccd-428b-9674-f2763ba4bbe2)

# Configurações
Apresenta as opções que podem ser personalizadas pelo usuário.
![configuracoes](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/cbd2d507-b873-4be1-ab30-d5e682f8c7ab)

# Tela do Usuário/ Perfil
Tela de perfil, onde conseguimos ver as informações do usuário.
![perfil](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/00e7dcd3-8b6d-4342-8aea-743b8cf8a87c)

# Configurações do Usuário
Ainda fazendo parte da tela de perfil, onde conseguimos alterar as informações do usuário.
![config.-usuario](https://github.com/AgathaSena/Projeto-Integrador-II/assets/79552519/86024a20-45b0-41fe-8b52-00eea6f21426)






