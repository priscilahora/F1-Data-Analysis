# 🏎 F1 Data Analysis

Repositório com análises de dados da Fórmula 1 usando Python e FastF1.

## 📂 Projetos

### 1. Análise de degradação de pneus
**Objetivo**: Comparar a degradação de pneus entre pilotos em uma corrida.  
**Ferramentas**: Python, FastF1, Pandas, Matplotlib.
<br/>**Resultados**:  
- Ambos pilotos tiveram desempenho muito próximo com os HARD (diferença de 0.11s no total do stint).
- Isso sugere que a estratégia de conservação de pneus foi equilibrada na corrida.

### 2. Comparação da aceleração e da velocidade nas retas
**Objetivo**: Comparar velocidade máxima e aceleração entre Red Bull (Verstappen) e Mercedes (Hamilton) na reta principal do circuito de Interlagos em 2021.
<br/>**Ferramentas**: Python, FastF1, Pandas, Matplotlib.<br/>
**Resultados**:
- Hamilton atingiu 326.4 km/h vs Verstappen 305.0 km/h (21.4 km/h a mais).
- Padrão observado: Mercedes demonstrou vantagem clara em retas longas, enquanto a Red Bull pode estar otimizada para curvas.

### 3. Análise da Estratégia de Pit Stops
**Objetivo**: Avaliar a eficácia da estratégia de pit stops de Lewis Hamilton durante o GP do Brasil de 2021, observando o impacto nos tempos de volta e na consistência entre stints.
<br/>**Ferramentas**: Python, FastF1, Pandas, Matplotlib.
<br/>**Resultados**:
- Número de paradas: Hamilton realizou 3 pit stops, distribuídos aproximadamente nas voltas 9, 30 e 45.
- Impacto dos pit stops: Cada parada gerou um aumento brusco no tempo de volta. Esse comportamento é esperado, mas o destaque está na queda abrupta nos tempos logo após cada parada, indicando a eficácia do novo composto instalado.

### 4. Comparativo de Telemetria – VER vs HAM (Volta 1)
**Objetivo**: Comparar a volta 1 de Verstappen (VER) e Hamilton (HAM) no GP do Brasil de 2021 com base nos gráficos de velocidade e RPM ao longo da distância.
<br/>**Ferramentas**: Python, FastF1, Pandas, Matplotlib.
<br/>**Resultados**:
- Velocidade Máxima:
VER: atinge cerca de 325 km/h nos trechos finais da reta.
HAM: atinge cerca de 315 km/h, ficando ~10 km/h abaixo de VER.

- Setores de aceleração:
Entre os 500 e 1000 metros, VER ganha vantagem com aceleração mais rápida e maior velocidade de topo (ex: ~270 km/h vs ~240 km/h).
No trecho entre 2500 e 2800 metros, VER também atinge picos mais altos, enquanto HAM sofre quedas mais acentuadas nas frenagens.

- RPM Máximo:
VER: ultrapassa os 11.500 rpm em vários trechos.
HAM: em geral, se mantém abaixo de 11.000 rpm, com destaque para os primeiros 500 metros, onde opera abaixo de 6.000 rpm, sugerindo uma largada mais contida.
