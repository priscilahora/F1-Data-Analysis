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
**Objetivo**: Analisar diferenças de desempenho entre VER e HAM ao longo da volta inicial com base em velocidade e rotação do motor.
<br>**Ferramentas**: Python, FastF1, Pandas, Matplotlib.
<br/>**Resultados**:
- Velocidade Máxima:
Ambos atingem picos similares (~320–325 km/h), mas HAM alcança a velocidade máxima um pouco antes (~4200 m), com curva de aceleração mais suave.
ER demora mais para atingir esse pico, indicando aceleração mais progressiva.

- Setores de vantagem de VER:
Entre 1000 e 1800 metros, VER mostra velocidades maiores em praticamente todos os trechos (~10–20 km/h acima), especialmente em curvas, o que sugere melhor tração ou confiança em frenagens tardias.
No setor entre 2500 e 2800 m, VER mantém velocidade mais constante nas mudanças de direção, enquanto HAM sofre quedas bruscas.

- RPM:
HAM atinge picos de até 13.000 rpm logo no início (~0–300 m), enquanto VER se mantém abaixo de 12.500 rpm por quase toda a volta.
VER apresenta RPM mais estável após 500 m, o que pode indicar uma pilotagem mais eficiente em trocas de marcha.
