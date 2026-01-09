# Métricas de Impacto Social: ONG Passos Mágicos

Este projeto consiste em um sistema de métricas desenvolvido para quantificar e ilustrar o impacto social da ONG **Passos Mágicos** na comunidade de Embu-Guaçu. A solução utiliza uma arquitetura de baixo custo baseada em Power BI e processamento de dados em Python, permitindo a análise do desenvolvimento educacional, psicológico e socioeconômico de crianças e jovens assistidos sem a necessidade de investimentos adicionais em infraestrutura.

### Pré-requisitos

Certifique-se de ter Power BI Desktop instalado.

### Instalação

Siga os passos abaixo para configurar o ambiente e acessar os arquivos do projeto:

```bash
#clonar o repositório
git clone https://github.com/jorgeplatero/postech_techchallenge_fase_5.git
cd postech-data-analytics-fase-5-tech-challenge

#criar o ambiente virtual
python -m venv venv
source venv/bin/activate 

#instalar dependências
pip install -r requirements.txt
```

### Como Rodar a Aplicação

Abra o arquivo `.pbix` localizado na pasta principal utilizando o Power BI Desktop.
2.  Caso as fontes de dados (arquivos `.xlsx` e `.csv`) não sejam encontradas, ajuste o caminho das origens no **Power Query** para apontar para a pasta `/data` deste repositório.
3.  Clique em "Atualizar" para popular o modelo associativo com os dados mais recentes.

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **Plataforma BI** | **Power BI** | `-` | Plataforma de BI para desenvolvimento de dashboards |
| **Análise de Dados** | **Pandas** | `2.2.2` | Biblioteca para manipulação de dados |
| **Linguagem** | **Python** | `>=3.11` | Linguagem para desenvolvimento de scripts |

### Fonte de Dados

Os indicadores foram construídos com base em dados cedidos pela ONG Passos Mágicos, informações institucionais e dados demográficos do IBGE. As bases estão disponíveis neste repositório.

### Deploy

O dashboard está disponível via Power BI Service.

Link para o dashboard: https://app.powerbi.com/view?r=eyJrIjoiMTkzNjNlNGEtY2JjYy00OGRmLTgyMzItZDk5NmRlZjI0MDVkIiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9

### Colaboradores

[Mateus Albuquerque](https://github.com/mateus-albuquerque)

[Adrielly Silva](https://github.com/adriellytsilva)

[Victor Reis](https://github.com/VictorReisDev)

[Erica Bassan](https://github.com/EricaBassan)
