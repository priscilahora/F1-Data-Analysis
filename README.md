# 🏎 F1 Data Analysis

Repositório com análises de dados da Fórmula 1 usando Python e FastF1.

## 📂 Projetos

### 1. Análise de Degradação de Pneus
**Objetivo**: Comparar a degradação de pneus entre pilotos em uma corrida.  
**Ferramentas**: Python, FastF1, Pandas, Matplotlib.  
**Resultados**:  
- Ambos pilotos tiveram desempenho muito próximo com os HARD (diferença de 0.11s no total do stint).
- Isso sugere que a estratégia de conservação de pneus foi equilibrada na corrida.

### 2. Comparação da aceleração e da velocidade nas retas
**Objetivo**: Comparar velocidade máxima e aceleração entre Red Bull (Verstappen) e Mercedes (Hamilton) na reta principal do Grand Prix de São Paulo de 2021.
**Ferramentas**: Python, FastF1, Pandas, Matplotlib. 
**Resultados**:
- Hamilton atingiu 326.4 km/h vs Verstappen 305.0 km/h (21.4 km/h a mais).
- Padrão observado: Mercedes demonstrou vantagem clara em retas longas, enquanto a Red Bull pode estar otimizada para curvas.
**Melhoria**: Implementar efeito que do DRS nessa diferença.
