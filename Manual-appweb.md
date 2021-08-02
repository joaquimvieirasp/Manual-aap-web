# <a name="index"></a> Índice

* 1 [Introdução](#intro) 

* 2 [Airspace](#airSpace)

* 2.1 [Inicio](#homeAirspace)

* 2.2 [Principais Comandos](mainCommands)
  
* 3 [Flight Plans](#flightPlans)

* 3.1 [Inicio](#homeFlightplans)

* 4 [Scenarios](#scenarios)

* 4.1 [Inicio](#homeScenarios)

* 5 [Simulation](#simulation)

* 5.1 [Inicio](#homeSimulation)

* 6 [Analysis](#analysis)
  
* 6.1 [Inicio](#homeAnalysis)

* 7 [Comandos Básicos](#basicCommands)

# <a name="intro"></a> 1.Introdução


A demonstração da Plataforma de análise de espaço aéreo, segue 5 etapas como mostra a [Figura 1.1](#figViewHome), começando pelo **_Airpace_**.

<figure id="figViewHome">
	<img src="Figuras-aapweb/view_home.png" alt="Visualização da Home" title="Visualização da Home" width="800">
	<figcaption>Fig. 1.1: Visualização da Home. </figcaption>
</figure>

# <a name="airspace"></a> 2. Airspace

**Objetivo**: Visualização e criação de novos elementos do espaço aéreo, esses elementos poderão ser utilizados posteriormente para a criação de cenários de simulação (**sem regras**), para navegar no Airspace, basta clicar em **ir para a página inicial**, no canto superior direito da página, como mostra a [Figura 2.1](#figViewBotton)

<figure id="figViewBotton">
	<img src="Figuras-aapweb/view_botton_airspace.png" alt="Visualização Airspace" title="Visualização Airspace" width="800">
	<figcaption>Fig. 2.1: Visualização Air Space. </figcaption>
</figure>

### <a name="homeAirspace"></a> 2.1. Home AirSpace

Ao entrar na página inicial do **Airspace**, será exibido um painel de navegação para a _visualização_ e a _adição_ de novos elementos do espaço áereo:

<figure id="figviewAirSpaceDetais">
	<img src="Figuras-aapweb/view_airspace_details.png" alt="Visualização da Home" title="Visualização da Home" width="800">
	<figcaption>Fig. 2.1.1.a: Visualização da Home Airspace. </figcaption>
</figure>

#### <a name="aixm"></a> AIXM

Este botão exibi a versão e data do arquivo AIXM, conforme a figura:

#### <a name="aixmchange"></a> Change AIXM


Este botão permite selecionar outro arquivo AIXM, conforme a figura:

<figure id="figviewChangeaixm">
	<img src="Figuras-aapweb/view_changeaixm_details.png" alt="Visualização da Change AIXM" title="Visualização dA Change AIXM" width="800">
	<figcaption>Fig. 2.1.1.b: Visualização da Change AIXM. </figcaption>
</figure>

#### <a name="joinview"></a> Join View


Este botão permite inserir todos os elementos (**_airports, navaids, fixs, airways, sectors, sid, star_**) para a visualização no mesmo mapa:

<figure id="figviewJoinview">
	<img src="Figuras-aapweb/view_joinview_details.png" alt="Visualização da joinview" title="Visualização da joinview" width="800">
	<figcaption>Fig. 2.1.1.c: Visualização da Join View. </figcaption>
</figure>

#### <a name="airports"></a> Airports


Este botão permite a busca e visualização de um aeroporto, e com o botão NEW é possível incluir um novo aeroporto inserindo as informações que serão solicitadas como (**_id, name, lat, lon, type, max rwy lenght, country code e elevation_**), após o preenchimento o usuário pode finalizar a criação do elemento clicando em Submit

<figure id="figviewairport">
	<img src="Figuras-aapweb/view_airport_details.png" alt="Visualização do airport" title="Visualização do airport" width="800">
	<figcaption>Fig. 2.1.1.d: Visualização do Airport. </figcaption>
</figure>

#### <a name="navaids"></a> Navaids


Este botão permite a visualização no mapa de dispositivo visual ou eletrônico que forneça informações de orientação ponto a ponto ou dados de posição para aeronaves em vôo, e com o botão NEW é possível inserir novo dispositivo inserindo os dados que serão solicitados (**_type, lat, lon, elevation, freq, var id desc_**), após o preenchimento o usuário pode finalizar a criação do elemento clicando em Submit

<figure id="figviewNavaids">
	<img src="Figuras-aapweb/view_navaids_details.png" alt="Visualização da navaids" title="Visualização da navaids" width="800">
	<figcaption>Fig. 2.1.1.e: Visualização do Navaids. </figcaption>
</figure>

#### <a name="fixs"></a> Fixs
 

<figure id="figviewFixs">
	<img src="Figuras-aapweb/view_fixs_details.png" alt="Visualização da Fixs" title="Visualização da Fixs" width="800">
	<figcaption>Fig. 2.1.1.f: Visualização da Fixs. </figcaption>
</figure>

#### <a name="airways"></a> Airways

#### <a name="sectors"></a> Sectors

Este botão possibilita a visualização de áreas de controle do espaço aéreo no mapa, e com o botão NEW é possível inserir novas áreas inserindo as informações que serão solicitadas **name, type, uppre limit(fl), lower limit(fl)**, após o preenchimento o usuário pode finalizar a criação do elemento clicando em Submit

<figure id="figviewSectors">
	<img src="Figuras-aapweb/view_sectors_details.png" alt="Visualização da sectors" title="Visualização da sectors" width="800">
	<figcaption>Fig. 2.1.1.g: Visualização dos Sectors. </figcaption>
</figure>

#### <a name="sidstar"></a> Sid e Star
 
<figure id="figviewStar">
	<img src="Figuras-aapweb/view_star_details.png" alt="Visualização da star" title="Visualização da star" width="800">
	<figcaption>Fig. 2.1.1.h: Visualização da Star. </figcaption>
</figure>


# <a name="FlightPlans"></a> 3. Fligt Plans

### <a name="homeFlightplans"></a> 3.1. Home Flight Plans

**Objetivo** do **Fligt Plans** é criar, editar e deletar planos de vôo que podem ser utilizados posteriormente para criação de cenários de simulação, para mudar o arquivo que lista os vôos, clique no botão **CHANGE RPL**, ou visualizar os planos de vôo existentes conforme a figura:


### Principais Comandos

a. Ao clicar em um dos elementos da lista, a rota de vôo do elemento será exibida no mapa.

b. Mudar o RPL (Change RPL) - Arquivo que lista os vôos.

c. Selecionar o botão Create/Edit Flight, que redireciona o usuário á página de criação e edição de vôos.

d. O botão "Home" permite o redirecionamento á página inicial dos Planos de Vôo.

e. O campo "Search" permite a busca dos vôos (não só pelo **ID** do vôo, como também suas caracteristicas).

f. Na tabela de vôos, na coluna de Actions, o ícone de "caneta" permite a edição do vôo, e o ícone de "lixeira", a sua exclusão.

g. Ao clicar no ícone de caneta, serão abertos alguns campos para preenchimento. Após, o botão **Submit** permitirá o salvamento dos dados.

h. O batão "New Item" permite a adição de um novo vôo.

### Demonstração dos Principais Comandos:


<figure id="figViewFlightPlans">
	<img src="Figuras-aapweb/view_fligtPlans_details.png" alt="Visualização FlightPlan" title="Visualização FlightPlan" width="800">
	<figcaption>Fig. 3.1.a: Visualização Flight Plans. </figcaption>
</figure>

***

Para criar ou editar um plano de vôo, clique no botão **create / edit flight** como mostra a [Figura 3.1.a](#figViewFlightPlans) onde será exibido um menu com os planos de vôo cadastrados ou criar ou novo item como mostra a [Figura 3.1.b](#figViewcreate)


<figure id="figViewCreate">
	<img src="Figuras-aapweb/view_createPlans.png" alt="Visualização CreatePlans" title="Visualização CreatePlans" width="800">
	<figcaption>Fig. 3.1.b: Visualização Flight Plans. </figcaption>
</figure>

***


Para criar um novo plano de vôo, clique no botão **new item** e em seguida preencha as informações que serão solicitadas e finalize clicando em **save**, como mostra a [Figura 3.1.c](#figViewNewIten)


<figure id="figViewNewIten">
	<img src="Figuras-aapweb/view_newitem.png" alt="Visualização NewIten" title="Visualização NewIten" width="800">
	<figcaption>Fig. 3.1.c: Visualização New Iten. </figcaption>
</figure>


# <a name="scenarios"></a> 4. Scenarios


<figure id="figViewBotton">
	<img src="Figuras-aapweb/view_botton_scenarios.png" alt="Visualização Scenarios" title="Visualização Scenarios" width="800">
	<figcaption>Fig. 4.1: Visualização Scenarios. </figcaption>
</figure>

### <a name="homeScenarios"></a> 4.1. Home Scenarios

**Objetivo**: Criação de cenários de vôo.

### Principais Comandos

a. Preencher os dados necessários para a criação de um cenário.

b. Conforme o preenchiomento dos campos, o cenário vai sendo exibido no mapa ao lado.

c. O botão "View and Submit Scenario" ao final da página, permite a visualização e envio do cenário criado.

d. O botão "Clear Fields" permite que o usuário limpe os campos dados.

### Demonstração dos Principais Comandos:



# <a name="simulation"></a> 5. Simulation


<figure id="figViewBotton">
	<img src="Figuras-aapweb/view_botton_simulation.png" alt="Visualização Simulation" title="Visualização Simulation" width="800">
	<figcaption>Fig. 5.1: Visualização Simulation. </figcaption>
</figure>

### <a name="homeSimulation"></a> 5.1. Home Simulation

**Objetivo** executar a  simulação dos planos de vôo.

### Principais Comandos

a. Selecionar um cenário da lista de cenários.

b. Na lista de baixo, é possível selecionar o(s) elemento(s) do espaço aéreo que deseja visualizar nete cenário.

c. O botão "Select" inicia a simulação do cenário selecionado.

	1. A simulação será iniciada, e os aviões aparecerão no mapa, em movimento.No canto inferior esquerdo, estão as opções de "Renomear", "Finalizar", "Resumi/Pausar", e "Acelerar" a simulação, respectivamente.
	2. No canto superior direito, está o campo para seleção de elementos a serem exibidos no mapa.
	3. As três barras do canto superior esquerdo, abrem uma barra lateral para redirecionamento à outras páginas do Projeto Bluesky.

# <a name="analysis"></a> 6. Analysis

comparar um cenario de voo com outro cenário

<figure id="figViewBotton">
	<img src="Figuras-aapweb/view_botton_analysis.png" alt="Visualização Analysis" title="Visualização Analysis" width="800">
	<figcaption>Fig. 6.1: Visualização Analysis. </figcaption>
</figure>

### <a name="homeAnalysis"></a> 6.1. Home Analysis


