# Projeto - Eleições 2022 (1º turno)

Neste projeto, foram utilizados os resultados do primeiro turno das eleições do ano de 2022.  A base de dados foi extraída do site oficial do TSE ([Resultados - 2022 - Conjunto de dados - Portal de Dados Abertos do TSE](https://dadosabertos.tse.jus.br/dataset/resultados-2022)).

A base de dados bruta possui cerca de 1 milhão de registros (1.048.575), distribuídos em 44 colunas, resultando em um arquivo de aproximadamente 5gb. 

Uma limpeza foi feita, colunas pertinentes à essa análise foram selecionadas, registros duplicados foram tratados e resultou em uma base de dados de cerca de 3mb.

Os dados obtidos a partir desta análise foram comparados com os dados oficiais divulgados pelo TSE e por diversos veículos de comunicação e chegou-se à conclusão de que estão corretos.

Foram utilizados somente dados referentes à votos válidos, portanto, nulos, brancos e abstenções não estão previstas neste estudo.

## 1. Ferramentas utilizadas

- Base de dados oficial do resultado das eleições de 1º turno de 2022
- Python
- Bibliotecas (Pandas, Seaborn, Matplotlib, Scipy)

## 2. Análise dos dados do 1º turno

Em 2022, as eleições no Brasil foram referentes aos cargos: Presidente, Senador, Governador, Dep. Federal e Dep. Estadual.

## 2.1. Deputado Estadual

### a. Quantidade de eleitos por partido
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068002-158bf8a9-9541-46b9-84c8-785b2cf9b4c6.png" width="800px" />
</div>

<br />

### b. Candidatos eleitos mais votados
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068129-641b845a-6c51-4680-a831-fb109839e5d2.png" width="500px" />
</div>

<br />

## 2.2. Deputado Federal

### a. Quantidade de eleitos por partido
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068225-ba922c46-6591-4af2-a576-fb7d27e0a2c1.png" width="800px" />
</div>

<br />

### b. Candidatos eleitos mais votados
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068366-8cba8b65-459a-46c5-9a40-55241c2e2b7e.png" width="500px" />
</div>

<br />

## 2.3. Governador

### a. Quantidade de eleitos por partido
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068524-57992718-f9f9-41c0-a980-573fb8dc1436.png" width="800px" />
</div>
<br />

### b. Candidatos eleitos mais votados
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068797-2cedc93a-e538-4d70-8571-1d11339c4da2.png" width="500px" />
</div>
<br />

## 2.4. Senador

### a. Quantidade de eleitos por partido
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068657-5a1ce0f5-f370-4373-a453-0fe996c0debb.png" width="800px" />
</div>
<br />

### b. Candidatos eleitos mais votados
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197068738-bea87e44-1df9-4402-af50-c7d54f03ecd2.png" width="500px" />
</div>
<br />

## 2.5. Presidente

### a. Percentual de votos no 1º turno
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197069003-e1a4ca35-e0a5-4281-998e-181005e845e0.png" width="800px" />
</div>
<br />

### b. Quantidade de votos no 1º turno
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197069143-0737aa3e-439d-4483-bc21-f8403f9e8ad3.png" width="500px" />
</div>
<br />

## 2.6. Total de eleitos por partido

### a. Eleitos de todos os cargos, no 1º turno
<br />

<div align="center">
<img src="https://user-images.githubusercontent.com/110427400/197069241-08008bf0-2c97-4501-aac2-aa48e00c766f.png" width="800px" />
</div>
