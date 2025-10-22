# Substituicao_nuvens

Repositório associado ao projeto **FAPESP 2024/13710-0**, desenvolvido no âmbito do grupo **MAPEAR UNESP – IGCE/UNESP Rio Claro**.

Este repositório contém:
- Scripts em Python e Jupyter Notebook para substituição de nuvens em imagens de satélite;
- Relatório Final FAPESP;
- Artigo submetido ao SBSR (Simpósio Brasileiro de Sensoriamento Remoto).

## Informações do projeto
**Pesquisador Responsável:** Prof. Dr. Danilo Marques de Magalhães  
**Bolsista:** Helena Zotelli  
**Número do Processo FAPESP:** 2024/13710-0  
**Período de vigência:** 01/10/2024 – 30/09/2025  

## Descrição técnica
O script realiza a **substituição de pixels nublados** em séries temporais de imagens Landsat-8, gerando composições contínuas para o cálculo de NDVI e análise da cobertura vegetal. As etapas incluem:
1. Máscara de nuvens e sombras;  
2. Substituição de pixels mascarados;  
3. Cálculo de NDVI;  
4. Reclassificação da cobertura da terra.  

