# Especificação do Projeto

## Perfis de Usuários

<table>
<tbody>
<tr align=center>
<th colspan="2"> ATIVISTA AMBIENTAL</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td> 
<td width="600px">Ana, ativista ambiental. 30 anos.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1 - Informações claras sobre dias e locais de coleta seletiva
2 - Instruções sobre descarte de materiais específicos como; eletrônicos, pilhas, óleo, lâmpada. 

2- Encontrar clínicas veterinárias públicas ou de baixo custo em sua localidade. </td>
</tr>
</tbody>
</table>

<table> 
<tbody>
<tr align=center>
<th colspan="2">  MUNÍCIPE </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Bernardo, morador de área de risco. 25 anos. </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1 -  Sistema que permita de maneira rápida  reportar alagamentos, deslizamentos na sua região.
2 - Notificação de áreas afetadas.</td>
</tr>
</tbody>
</table>

<table> 
<tbody>
<tr align=center>
<th colspan="2">  MOTORISTA </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">José, motorista de aplicativo. 46 anos. </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1 - Notificar seus colegas sobre obstáculos e irregularidades no caminho que trafega diariamente, como buracos na pista, entulho, animais no trânsito, etc.
2 - Notificar o poder público sobre as condições acima para que medidas sejam tomadas</td>
</tr>
</tbody>
</table>

<table> 
<tbody>
<tr align=center>
<th colspan="2">  SERVIDOR PÚBLICO </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Ricardo, servidor público do IBAMA. 46 anos. </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1 - Monitorar denúncias e alertas de infrações ambientais feitas pela população, tais como lixo jogado em local impróprio, poluição das vias, animais soltos na pista.</td>
</tr>
</tbody>
</table>

<table> 
<tbody>
<tr align=center>
<th colspan="2">  COMERCIANTE </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Rafaela. Comerciante. 42 anos. </td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1 - Notificar o poder público sobre irregularidades e infrações próximas ao seu ponto comercial como lixo em local impróprio, a fim de que estas sejam resolvidas pelo órgão responsável
2 - Acompanhar o andamento da sua notificação</td>
</tr>
</tbody>
</table>

## Histórias de Usuários


|EU COMO...   | QUERO/PRECISO ...  |PARA ...                 |
|--------------------|---------------------------|----------------------------------|
| Tutor de animais domésticos e não convencionais                | Acessar informações sobre cuidados diários e emergenciais                       | Garantir uma melhor qualidade de vida para o meu pet                              |
| Tutor de animais domésticos e não convencionais                | Acessar localizações de clínicas veterinárias públicas ao meu alcance                       | Garantir atendimento de qualidade sem ter um gasto excessivo                               |
| Tutor de animais domésticos e não convencionais.                 | Acessar informações sobre adaptação de animal adotado.                        | Garantir que a adaptação do pet seja bem-sucedida após a adoção                              |
| Tutor de animais domésticos e não convencionais                | Encontrar dados sobre prevenção de zoonoses                       | Assegurar a proteção contra zoonoses, preservando a saúde tanto do pet quanto das pessoas.                               |
| Estudante na área da saúde                | Levantar informações a respeito de unidades veterinárias públicas em nível nacional                       | Desenvolvimento de pesquisa universitária.                               |
| Estudante na área da saúde.                | Fazer pesquisas sobre especialidade mais procuradas por tutores                       | Incentivo nas especialidades que estão em defasagem de profissionais.                              |
| Estudante na área da saúde.                 | Compartilhar conhecimentos adquiridos nos estudos através de um fórum                       | Compartilhamento de opinião com base em estudos universitários                              |
| Estudante na área da saúde.                 | ..                      | Auxiliar na ampliação de conhecimentos dentro do universo veterinário                              |



## Requisitos do Projeto



### Requisitos Funcionais



|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 | A aplicação deve permitir que o usuário encontre unidades veterinárias públicas e subsidiadas e tenha acesso a informações sobre localizações, contatos e especialidades.   | Alta   | 
| RF-02 | A aplicação deve ter um fórum para que os usuários possam comentar dentro dos tópicos postados                   |Media |
| RF-03 | A aplicação deve ter um fórum para que os usuários possam criar um topico                      | Alta  |
| RF-04 | A aplicação deverá ter botões que direcione o usuário para apps de comunicação como WhatsApp das unidades veterinárias.                  | Alta  |
| RF-05 | A aplicação deverá oferecer uma opção de direcionamento ao usuário para aplicativos de localização, como Google Maps, para as unidades veterinárias.                   | Alta  |
| RF-06 | A aplicação deverá fornecer informações ao usuário sobre cuidados diários com os pets                    |Alta   |
| RF-07 | A aplicação deverá dar dicas e informações sobre a adaptação de um animal adotado.                    |Media   |
| RF-08 | A aplicação deve apresentar um mecanismo para usuários colocarem animais disponíveis para adoção| Baixa   |
| RF-09 | A aplicação deve apresentar um mecanismo para usuários editarem seus perfis | Alta  |
| RF-10 | A aplicação deve apresentar um mecanismo para usuários vizualizarem histórico de animais que disponibilizaram para adoção  | Alta  |



### Requisitos não Funcionais


|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  A aplicação deve ser compatível com os principais navegadores e responsiva a diferentes tamanhos de tela.                 | Alta   | 
| RNF-02 |  A aplicação deve solicitar o consentimento dos usuários antes de coletar seus dados pessoais                   | Alta  |
| RNF-03 |  A aplicação deve apresentar uma interface intuitiva que permita o usuário encontrar dicas diárias e clínicas veterinárias em até quatro cliques                   | Média   |
| RNF-04 | Os botões de comunicação devem estar bem visíveis e devem ser intuitivos, com ícones reconhecíveis para facilitar o uso.                    | Alta  |
| RNF-05 |  A aplicação deve suportar o aumento de números de usuários sem perder qualidade de navegação                   | Alta  |
| RNF-06 | A aplicação deve carregar as páginas em no máximo 5 segundos.                   | Média   |



