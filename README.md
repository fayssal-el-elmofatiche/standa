---
title: Stock Analysis Dashboard - *standa*
emoji: 📈
colorFrom: gray
colorTo: green
sdk: docker
pinned: false
license: mit
---
![Stock Analysis Dashboard](standa.png)

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

A live demo can be found at https://huggingface.co/spaces/felmofatiche/standa

# standa - *St*ock *An*alysis *Da*shboard

## Introduction
Welcome to the Stock Analysis Dashboard, an open-source project designed for interactive stock data visualization and analysis. This dashboard is built using [Panel](https://panel.holoviz.org/), [Cufflinks](https://github.com/santosjorge/cufflinks), and [Plotly](https://plotly.com/python/), providing a dynamic and user-friendly interface for exploring stock market trends and metrics.

## Features
- Interactive charts and graphs using Plotly and cufflinks
- Customizable technical analysis charts
- Historical data comparison
- Forecasting

## Installation
To set up the Stock Analysis Dashboard, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/fayssalelmofatiche/standa.git
```

2. Navigate to the project directory:

```bash
cd standa
```

3. Install required packages

```bash
poetry install
```

## Usage
To run the dashboard:

```bash
panel serve standa.ipynb --show --autoreload
```

## Contributing

Contributions to the Stock Analysis Dashboard are welcome! Please read our CONTRIBUTING.md for guidelines on how to contribute.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
Acknowledgements

- Panel for the web app framework
- Cufflinks and Plotly for data visualization
- The open-source community for continuous support

## Disclaimer

*standa* is for informational purposes only and does not constitute financial advice.


