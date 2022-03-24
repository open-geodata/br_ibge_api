# IBGE | Serviço Dados

<br>

O IBGE disponibiliza acesso aos dados por meio da [API Serviço Dados](https://servicodados.ibge.gov.br/api/docs).

Essa [API do IBGE](https://servicodados.ibge.gov.br) possibilita baixar os dados diretamente para o _script_. Para baixar as malhas, ou seja, informações geoespaciais, é possivel baixar os dados em três diferentes formatos:
- **_?formato=application/vnd.geo+json_**, para baixar os dados em GeoJson;
- **_?formato=application/json_**, para baixar os dados em TopoJson;
- **_?formato=image/svg+xml_**, para baixar os dados em SVG;

<br>

É possível definir a resolução que, na prática, refere-se ao nível de detalhamento do dado obtido.
- **_?resolucao=0_**, Nenhuma divisão político-administrativa é inserida no interior da malha
- **_?resolucao=1_**, Inclui na malha as macrorregiões. Válido apenas quando a localidade for BR.
- **_?resolucao=2_**, Inclui na malha as Unidades da Federação. Válido apenas quando a localidade for BR ou uma macroregião
- **_?resolucao=3_**, inclui na malha as mesorregiões. Válido apenas quando a localidade for BR, macroregião ou Unidade da Federação
- **_?resolucao=4_**, Inclui na malha as microrregiões. Válido apenas quando a localidade for BR, macroregião, Unidade da Federação ou mesorregião
- **_?resolucao=5_**, inclui na malha os municípios

<br>

E a qualidade.
- **_?qualidade=1_**, pior qualidade;
- **_?qualidade=2_**, razoável qualidade;
- **_?qualidade=3_**, boa qualidade;
- **_?qualidade=4_**, melhor qualidade;

<br>

-----

### *TODO*

1. ...
2. ...
3. ...
