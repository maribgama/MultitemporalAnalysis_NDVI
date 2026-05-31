# Monitoramento Dinâmico de Mata Seca com Google Earth Engine e Python

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-API-4285F4?style=flat&logo=google&logoColor=white)](https://earthengine.google.com/)
[![GIS](https://img.shields.io/badge/GIS-Cartography-589632?style=flat)](https://qgis.org/)

Este repositório é parte do meu **Trabalho de Conclusão de Curso (TCC) em Geografia na Universidade de Brasília (UnB)**. Ele demonstra o desenvolvimento de um pipeline automatizado em Python para o monitoramento e mapeamento fenológico de um fragmento crítico de **Mata Seca Semidecídua** no Parque Distrital do Gama, DF.
Utilizei computação em nuvem e sensoriamento remoto para analisar as respostas deste ecossistema único frente à sazonalidade severa do bioma Cerrado.

---

## 🎯 Objetivo Central do Projeto

O objetivo principal deste projeto foi desenvolver e validar uma metodologia automatizada para monitorar e visualizar a dinâmica de NDVI em um fragmento florestal remanescente, servindo como uma ferramenta de baixo custo e alta precisão para a gestão ambiental local e a pesquisa científica.

Para isso, estabeleci objetivos técnicos secundários:
1.  Acessar e processar séries históricas massivas de imagens dos satélites Sentinel-2 (MSI) sem a necessidade de hardware robusto local.
2.  Automatizar o processo cartográfico de geração de pranchas comparativas multitemporais.
3.  Gerar produtos com boa resolução prontos para compor relatórios executivos ou publicações acadêmicas.

---

## 🚀 Metodologia

| Categoria | Tecnologias e Ferramentas | Funcionalidades Demonstradas |
| :--- | :--- | :--- |
| **Ciência de Dados** | Python (Jupyter), NumPy, Pandas, Matplotlib | Manipulação de matrizes, processamento multitemporal, visualização customizada. |
| **Sensoriamento Remoto** | Google Earth Engine (API Python), Sentinel-2 MSI | Cloud Computing, cálculo de NDVI nativo, calibração radiométrica, QA60 cloud bitmasking. |
| **GIS & Cartografia** | geemap, Matplotlib, Cartographic layout, UnB Research | Detecção dinâmica de ROI, crop automatizado, escala métrica e norte customizados, 300 DPI output. |

---

## 📂 Visualização dos Resultados

Abaixo estão os produtos finais gerados pelo código, prontos para entrarem direto no documento do TCC.

### Prancha Cartográfica Multitemporal
<img width="2617" height="3216" alt="prancha_ndvi_3anos_final" src="https://github.com/user-attachments/assets/66f85155-3937-4e23-8aa7-c278d7807f60" />
*Prancha sintética comparando a Estação Seca e a Estação Chuvosa nos anos-chave de 2016, 2020 e 2025.*

### Gráfico Histórico de Sazonalidade (2015-2025)
<img width="2767" height="1540" alt="grafico_sazonalidade_ndvi_final" src="https://github.com/user-attachments/assets/87b88d23-46ff-4517-8425-dcf47f271440" />
*Gráfico de linhas gerado mostrando a dinâmica de NDVI média ao longo dos anos, com destaque para a queda característica durante a estação seca (caducifólia).*
