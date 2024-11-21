# Análise de Portfólio e Fronteira Eficiente de Markowitz

Este projeto implementa uma análise de portfólio baseada na teoria de Markowitz, utilizando dados de ações brasileiras para calcular retornos, riscos e correlações, além de simular portfólios otimizados.

## 📊 **Descrição do Projeto**
A análise é realizada com base nos preços ajustados de 6 ações da B3 entre 2015 e 2023:
- **BBAS3.SA** (Banco do Brasil)
- **CMIG4.SA** (Cemig)
- **ARZZ3.SA** (Arezzo)
- **MRVE3.SA** (MRV Engenharia)
- **GGBR4.SA** (Gerdau)
- **TOTS3.SA** (TOTVS)

O objetivo é criar portfólios eficientes, minimizando o risco para um dado retorno esperado ou maximizando o retorno para um dado nível de risco.

---

## 🚀 **Principais Funcionalidades**
1. **Coleta de Dados**: Busca preços históricos das ações utilizando a biblioteca `yfinance`.
2. **Análise Estatística**:
   - Retorno acumulado e anualizado.
   - Volatilidade (risco) anualizada.
   - Correlação entre ativos.
3. **Construção de Portfólios**:
   - Simulação de combinações de pesos.
   - Identificação da alocação com menor volatilidade.
4. **Visualização Gráfica**:
   - Comparação de preços normalizados.
   - Gráfico da Fronteira Eficiente.
   - Gráfico de `drawdown` (quedas máximas em relação ao pico).

---

## 📈 **Resultados**
### Estatísticas por Ativo
| Ativo      | Retorno Anualizado | Volatilidade Anualizada |
|------------|--------------------|-------------------------|
| ARZZ3.SA   | 13,65%            | 40,23%                 |
| BBAS3.SA   | 17,18%            | 42,24%                 |
| CMIG4.SA   | 12,33%            | 42,69%                 |
| GGBR4.SA   | 16,96%            | 46,67%                 |
| MRVE3.SA   | 10,74%            | 45,63%                 |
| TOTS3.SA   | 14,04%            | 38,63%                 |

### Portfólios
- **PORT1 (50% GGBR4, 50% MRVE3)**:
  - Retorno: 14,42%.
  - Volatilidade: 30,95%.

---

## 📂 **Como Executar**
1. Clone este repositório:
   ```bash
   git clone https://github.com/gianmalfate/markowitz-portfolio.git
2. Instale as dependências necessárias:
    ```bash
    pip install numpy pandas matplotlib seaborn yfinance
3. Abra o notebook e execute as células:
    ```bash
    jupyter notebook Trabalho_1_Fronteira_eficiente_de_Markowitz.ipynb

🛠 Tecnologias Utilizadas
- Python
- Bibliotecas:
    - `numpy`
    - `pandas`
    - `matplotlib`
    - `seaborn`
    - `yfinance`

📧 Contato

Para dúvidas ou sugestões, entre em contato:
- Email: gianmalfate@gmail.com
- LinkedIn: Giancarlo Malfate Caprino
