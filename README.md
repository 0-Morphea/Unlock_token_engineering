# Unlock_token_engineering
Token unlock engineering tool, aim to manage depletion test &amp; forecast price impact
# Interactive Token Unlock Schedule with Market Depth Provisioning

This Streamlit app provides an interactive tool for modeling token unlock schedules with market depth provisioning and dynamic pricing. The app includes features such as stochastic price simulation, dynamic market depth modeling, and ROI visualization.

## Features
- **User Inputs**: Adjust maximum supply, token price, bear market parameters, vesting schedules, and more.
- **Price Models**: Supports constant price and stochastic price (Black-Scholes model).
- **Dynamic Market Depth**: Simulate market depth over time and visualize overflow.
- **Vesting Schedule**: Customize token vesting schedules for multiple categories.
- **Bear Market Periods**: Define periods of increased sell pressure.
- **ROI Calculation**: Calculate and visualize ROI evolution over time.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## How to Use

1. Launch the app and use the sidebar to input tokenomics parameters:
   - Maximum supply
   - Initial token price
   - Vesting schedules
   - Bear market periods

2. Select a price model (constant or stochastic).
3. Visualize token unlock schedules, ROI evolution, and market depth overflow.
4. Adjust parameters dynamically to see their impact in real-time.

## File Structure

```
|-- app.py              # Main application code
|-- requirements.txt    # Python dependencies
|-- readme.md           # Project documentation
```

## Dependencies
The app uses the following Python libraries:
- `streamlit`: For building the interactive web app.
- `numpy`: For numerical computations.
- `pandas`: For data manipulation.
- `matplotlib`: For plotting graphs.

## Contributions
Feel free to submit issues or pull requests if you have ideas for improving the app.

## License
This project is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License. See the LICENSE file for details.
