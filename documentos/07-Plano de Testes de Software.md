# Plano de Testes de Software

Os testes funcionais a serem realizados na aplicação são descritos a seguir. 

|Caso de Teste    | CT-1 - Verificar o funcionamento da página meu perfil|
|:---|:---|
| Requisitos Associados | RF-09 A aplicação deve apresentar um mecanismo para usuários editarem seus perfis |
| Objetivo do Teste | Verificar se o usuario está habilitado a fazer edição de dados da sua conta, Como Foto, email, Senha, Número de Telefone, Data de nascimento.|
| Passos | 1-Fazer login na página  <br>  2- Acessar a área "Meu Perfil"  <br> 3- Interagir com os Botões de editar |
| Critérios de êxito | Todas os ambientes editáveis devem permanecer salvos ao trocar de pagina ou recarregar a página|
| Responsável por elaborar do caso de Teste | Nicholas |
 

|Caso de Teste    | CT-2 - Verificar o funcionamento da criação de tópicos no fórum|
|:---|:---|
| Requisitos Associados | RF-3 A aplicação deve ter um fórum para que os usuários possam criar um topico |
| Objetivo do Teste | Verificar se o usuário consegue criar e postar um novo tópico no fórum.|
| Passos | 1- Acessar a área "Fórum" <br> 2- Clicar em "começar" para abrir o modal de preenchimento do forumulário <br> 3- Clicar em "publicar" e verificar se foi publicado.|
| Critérios de êxito | Tópico criado disponivel na página de Fórum.|
| Responsável por elaborar do caso de Teste | Rafael  |

 |Caso de Teste    | CT-3 - Verificar o funcionamento da criação de comentários nos tópicos postados no fórum|
|:---|:---|
| Requisitos Associados | RF-2 A aplicação deve ter um fórum para que os usuários possam comentar dentro dos tópicos postados|
| Objetivo do Teste | Verificar se o usuário consegue inserir comentários em tópicos de fórum.|
| Passos | 1- Acessar a área "Fórum" <br> 2- Em um tópico postado, clicar em "comentar" para abrir o modal de preenchimento do forumulário <br> 3- Clicar em "comentar" e verificar se o comentário foi publicado. |
| Critérios de êxito | Comentário publicado no tópico na página de Fórum.  |
| Responsável por elaborar do caso de Teste | Rafael |

 |Caso de Teste    | CT-4 - Verificar o funcionamento da página de Adoção |
|:---|:---|
| Requisitos Associados | RF-8 - A aplicação deve apresentar um mecanismo para usuários colocarem animais disponíveis para adoção	|
| Objetivo do Teste | Verificar se o usuário logado consegue cadastrar um animal para adoção. |
| Passos | 1- Acessar a página de Adoção <br> 2- Clicar no botão "Cadastrar Animal" e verificar se a janela para preenchimento dos dados do animal abre normamente <br> 3- Preencher os dados do animal, incluindo um upload de uma foto e clicar em cadastrar <br> 4- Verificar se o animal cadastrado apareceu na lista de animais disponíveis para a adoção e se os botões de "Editar" e "Excluir" estão habilitados|
| Critérios de êxito | Animal cadastrado na página de Adoção  |
| Responsável por elaborar do caso de Teste | Lucas |

 |Caso de Teste    | CT-5 - Verifcar a interação com o conteúdo |
|:---|:---|
| Requisitos Associados | RF-6 A aplicação deverá fornecer informações ao usuário sobre cuidados diários com os pets |
| Objetivo do Teste | Verificar se o usuario consegue interagir com algum dos tópicos pré estabelecidos|
| Passos | 1-Acessar página home <br> 2-Passar o mouse por cima do item "Meu Pet" <br> 3-Clicar em "Cães" e terá acesso  |
| Critérios de êxito | Ao clicar no Título, o usuario terá acesso ao conteúdo |
| Responsável por elaborar do caso de Teste | Nicholas |

 |Caso de Teste    | CT-6 - Verificar o funcionamento do direcionamento ao Whatsapp|
|:---|:---|
| Requisitos Associados | RF-04 A aplicação deverá ter botões que direcione o usuário para apps de comunicação como WhatsApp e E-mail, com as unidades veterinárias |
| Objetivo do Teste |Analisar o direcionamento realizado pela api do Whatsapp com os números das unidades veterinárias. |
| Passos | 1-Acessar página SOS Pet<br>2-Selecionar uma Unidade.<br>3-Clicar no botão do Whatsapp e entrar na conversa.<br>|
| Critérios de êxito | Ser direcionado corretamente ao Whatsapp da Unidade |
| Responsável por elaborar do caso de Teste | Danielle |


 |Caso de Teste    | CT-7 - Verificar funcionamento da Api do Google Maps |
|:---|:---|
| Requisitos Associados | RF-05 A aplicação deverá oferecer uma opção de direcionamento ao usuário para aplicativos de localização, como Google Maps, para as unidades veterinárias.  |
| Objetivo do Teste | Verificar o funcionamento da Api e retorno da localização da Unidade |
| Passos | 1-Acessar página SOS Pet<br>2-Selecionar uma Unidade.<br>3-Entrar no mapa que consta na Unidade e verificar o endereço que é retornado na mesma e onde se encontra o pin da localização.<br>|
| Critérios de êxito | Retorno correto da localização da Unidade  |
| Responsável por elaborar do caso de Teste | Danielle |

 
