# Group 3 Trading Project

This repository contains our implementation of a trading system using FinRL.

## Getting Started

### Prerequisites
- Git
- Python 3.6 or higher
- Anaconda (recommended)

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/sulaimanabusaleh/group3.git
```

2. Enter the project directory:
```bash
cd group3
```

3. Initialize and update the FinRL submodule:
```bash
git submodule init
git submodule update
```

4. Install required packages:
```bash
pip install -r FinRL/requirements.txt
```

### Project Structure

- `finrl_trading.ipynb`: Main trading notebook
- `step_by_step_backtest.ipynb`: Backtesting implementation
- `train.csv`: Training data
- `trade.csv`: Trading data
- `trained_ppo_model.zip`: Pre-trained model

### Working with Git

To get the latest changes:
```bash
git pull origin master
```

To push your changes:
```bash
git add .
git commit -m "Your commit message"
git push
```
