# Gerador de Planilhas ODS (toolbox)

- ✅ Recebe Feições como Input para sua execução.
	- ✅ Recebe uma Feição de Polinha como Input (Gleba). A Feição utilizada deve ter um tabela de atributos no padrão necessário contendo colunas especificas
    - Colunas aqui
	- ✅ Recebe uma Feição (Opcional) de Curvas de Nível para cruzar as informações dos pontos obtidos da feição de Gleba para calcular as altitudes correspondente aos pontos.
- ✅ Recebe diversos Inputs de Texto para futuramente preencher a planilhas ODS que será gerada ao final dos procedimentos

# README.md

## Descrição
Este código em Python está relacionado à criação e execução de uma Toolbox no ArcGIS utilizando o módulo `arcpy`. O script define várias classes e funções para gerenciar a Toolbox e seus parâmetros, bem como a execução de um script dentro dela. As principais classes incluem:

- `Constantes`: Responsável por armazenar as constantes do script.
- `DataTypes`: Responsável por guardar todos os tipos de dados necessários para os parâmetros do `arcpy.Parameter`.
- `ParametrosFerramenta`: Responsável pela criação, salvamento e outras funções relacionadas aos parâmetros da Toolbox em execução.
- `Funcoes`: Agrupa as funções utilizadas ao decorrer do código.
- `Logger`: Responsável pelas configurações de log.
- `Resultados`: Responsável por armazenar variáveis em escopos globais e locais.
- `Toolbox`: Representa a própria Toolbox.
- `OdsGenerator`: O script que será executado dentro da Toolbox, com acesso às funções, resultados e registro de log.

### Imagem da Ferramenta
![Ferramenta com inputs Fornecidos](https://github.com/SpatialPyTech/Gerador-de-Planilha-ODS/blob/main/Ferramenta%20Com%20Inputs%20Fornecidos.png)

### Produtos Finais Gerados
![Ferramenta com inputs Fornecidos](https://github.com/SpatialPyTech/Gerador-de-Planilha-ODS/blob/main/Produtos%20Finais%20Gerados.png)

### Planilhas Preenchidas
![Identificacao](https://github.com/SpatialPyTech/Gerador-de-Planilha-ODS/blob/main/Planilha_Identificacao%20Preenchida%20com%20Sucesso.png)

![Perimetro](https://github.com/SpatialPyTech/Gerador-de-Planilha-ODS/blob/main/Planilha_Perimetro%20Preenchida%20com%20Sucesso.png)

## Como Usar
Para usar este código, siga os passos abaixo:

1. Certifique-se de ter o ArcGISPro instalado e configurado em seu ambiente, incluindo a instalação do Python do ArcGIS.

2. Importe a Toolbox no ArcGIS. Isso pode ser feito na interface do ArcGISPro, em seguida basta executar o script `Gerar ODS` dentro da ToolBox.

3. Forneça os Inputs necessário.

4. Execute a Toolbox dentro do ArcGISPro para realizar as operações desejadas.

Lembre-se de que a execução deste código depende inteiramente do ambiente do ArcGISPro, e as funcionalidades específicas serão determinadas pela configuração da Toolbox e pela lógica do script `OdsGenerator`.

## Dependências
Este código depende da biblioteca arcpy, que é uma parte do ArcGIS, um biblioteca que integra funções de sistema de informações geográficas (SIG) desenvolvido pela Esri.


## Autor
Este código foi escrito por `Djalma Filho` e faz parte do projeto Gerador de `Planilhas ODS`.

## Licença
Nossa licença aqui
