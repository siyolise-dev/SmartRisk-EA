# SmartRisk-EA

A custom MQL5 Expert Advisor built for MetaTrader 5 that calculates optimal lot sizes based on account balance and fixed-risk percentage. 

## Features
- **Dynamic Lot Sizing:** Automatically calculates lot sizes based on 1% risk.
- **Risk Management:** Prevents over-leveraging by accounting for stop-loss distance.
- **Safety:** Includes a high-volatility safety override.

## Usage
1. Compile the script in your MetaEditor.
2. Drag onto your preferred currency pair chart.
3. Adjust `RiskPercent` in the input settings as needed.

## License
Distributed under the MIT License.
