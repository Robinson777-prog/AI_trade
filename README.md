# AI_Trade

AI_Trade is an AI-powered trading system designed to simulate hedge fund strategies. This system incorporates multiple agents, each following distinct investment philosophies and strategies to make trading decisions. The project is intended for educational and research purposes only and is not designed for real trading or investment.

## Agents

The system features the following agents, each representing different investment styles:

1. **Ben Graham Agent** - Focuses on value investing, seeking undervalued stocks with a margin of safety.
2. **Bill Ackman Agent** - An activist investor, taking bold positions and advocating for change.
3. **Cathie Wood Agent** - A growth investor who believes in the power of innovation and disruption.
4. **Charlie Munger Agent** - Invests in high-quality businesses at fair prices.
5. **Stanley Druckenmiller Agent** - Macro-focused trader seeking explosive growth opportunities.
6. **Warren Buffett Agent** - A value investor, looking for wonderful companies at fair prices.
7. **Valuation Agent** - Calculates intrinsic value and generates trade signals.
8. **Sentiment Agent** - Analyzes market sentiment for trading decisions.
9. **Fundamentals Agent** - Analyzes fundamental data for decision-making.
10. **Technicals Agent** - Uses technical indicators for generating signals.
11. **Risk Manager** - Monitors and controls risk metrics.
12. **Portfolio Manager** - Finalizes trading decisions and executes orders.

## Disclaimer

This project is for educational purposes only:

- Not intended for real trading or investment.
- No warranties or guarantees are provided.
- Past performance does not guarantee future results.
- The creator assumes no responsibility for financial losses.
- Consult a financial advisor before making investment decisions.

By using this software, you agree to use it solely for learning purposes.

## Table of Contents

- [Setup](#setup)
- [Usage](#usage)
  - [Running the AI Trade System](#running-the-ai-trade-system)
  - [Running the Backtester](#running-the-backtester)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Feature Requests](#feature-requests)
- [License](#license)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Robinson777-prog/AI_trade.git
    cd AI_trade
    ```

2. Install Poetry (if not already installed):

    ```bash
    curl -sSL https://install.python-poetry.org | python3 -
    ```

3. Install dependencies:

    ```bash
    poetry install
    ```

4. Set up your environment variables:

    Copy the example environment file:

    ```bash
    cp .env.example .env
    ```

    Then, set the API keys for:

    - OpenAI API: `OPENAI_API_KEY`
    - Groq API: `GROQ_API_KEY`
    - Financial Datasets API: `FINANCIAL_DATASETS_API_KEY`

## Usage

### Running the AI Trade System

Once setup is complete, you can run the trading simulation system using the following command:

```bash
poetry run python run_simulation.py


Running the Backtester
To simulate historical trades and evaluate past strategies:

bash
Copiar
poetry run python run_backtest.py


------------------------------------------------------------------------------------------------------------------------------------------------------------------
**AI Trade** es un proyecto que utiliza técnicas de inteligencia artificial para realizar análisis y decisiones de trading de manera automatizada. 
El sistema está diseñado para implementar estrategias de trading basadas en modelos de **Machine Learning** y **Deep Learning**, 
utilizando datos históricos del mercado para prever tendencias y optimizar las decisiones de inversión.

## Características

- **Análisis Automatizado**: El sistema puede analizar grandes volúmenes de datos del mercado financiero y generar predicciones sobre la dirección del mercado.
- **Modelos Predictivos**: Utiliza modelos de aprendizaje automático para prever las fluctuaciones del mercado.
- **Estrategias de Trading**: Implementación de estrategias de trading que se ajustan a las predicciones generadas por los modelos.
- **Soporte para Múltiples Activos**: Soporte para operar con diferentes tipos de activos como acciones, criptomonedas, etc.
- **Backtesting**: Capacidad para probar las estrategias utilizando datos históricos y ver cómo habrían funcionado en el pasado.

## Requisitos

Para usar este proyecto, necesitas tener instalados los siguientes programas y librerías:

- **Python** 3.7 o superior
- **Pandas**: Para el análisis de datos.
- **NumPy**: Para cálculos numéricos y operaciones matemáticas.
- **Scikit-learn**: Para el uso de algoritmos de machine learning.
- **Keras/TensorFlow**: Para el entrenamiento de redes neuronales (si usas modelos de Deep Learning).
- **Matplotlib/Seaborn**: Para visualización de datos y resultados.
- **yfinance** o **Alpha Vantage**: Para obtener datos históricos del mercado.
- **Jupyter Notebook**: Para ejecutar y probar los modelos en un entorno interactivo.
