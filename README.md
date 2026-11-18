# 🌤️ Monitoramento de Temperatura Localizado (Open-Meteo API & Google Sheets)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Open-Meteo](https://img.shields.io/badge/API-Open--Meteo-green.svg)](https://open-meteo.com/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)

Este é um projeto de automação em Python que integra dados de geolocalização armazenados em uma planilha do Google Sheets com a API pública do **Open-Meteo** para obter previsões e condições climáticas em tempo real para múltiplos pontos de interesse.

## 🚀 Funcionalidades

- **Integração com Google Sheets**: Consome dados diretamente de uma planilha pública exportada em formato CSV.
- **Leitura Dinâmica com Pandas**: Varre as coordenadas de latitude e longitude dos locais cadastrados linha por linha.
- **Consumo de API Externa**: Realiza requisições HTTP para a API Open-Meteo utilizando a biblioteca `requests` para obter a temperatura atual do ar (`temperature_2m`).

## 🛠️ Tecnologias Utilizadas

- **[Python](https://www.python.org/)** (Linguagem base)
- **[Pandas](https://pandas.pydata.org/)** (Manipulação e análise de dados)
- **[Requests](https://requests.readthedocs.io/)** (Requisições HTTP à API)
- **[Open-Meteo API](https://open-meteo.com/)** (Serviço meteorológico gratuito)

## 📋 Estrutura da Planilha de Entrada

A planilha lida pelo script deve conter as seguintes colunas obrigatórias:
- `Nome do local`: Nome identificador do ponto de interesse.
- `Latitude`: Coordenada de latitude (ex: `-23.55`).
- `Longitude`: Coordenada de longitude (ex: `-46.63`).

## 🔧 Como Executar

1. Clone este repositório:
   ```bash
 https://github.com/Pamelaaalexandre/Controle-Metereologico.git
