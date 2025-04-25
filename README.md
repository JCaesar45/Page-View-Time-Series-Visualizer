```markdown
# Sea Level Predictor

This project predicts sea level rise using historical data from 1880 to 2014. It uses the `epa-sea-level.csv` dataset, which contains the global average sea level change over time, to fit two lines of best fit and predict future sea level changes up to 2050.

## Project Overview

- **Dataset**: The data comes from the U.S. Environmental Protection Agency (EPA) and includes the global average sea level change from 1880-2014.
- **Goal**: Create a visualization that shows the historical sea level change and predictions for future sea levels using linear regression models.

## Features

- **Scatter plot** of the historical sea level data.
- **Line of Best Fit** from 1880–2050.
- **Line of Best Fit** from 2000–2050 (projecting future rise using recent trends).
- **Predictions** for sea level rise by 2050.

## Setup

### Prerequisites

To run this project, you need the following:

- Python 3.x
- Pandas
- Matplotlib
- SciPy

### Installing Dependencies

You can install the required dependencies using pip:

```bash
pip install pandas matplotlib scipy
```

### Running the Script

To run the project, simply execute the `sea_level_predictor.py` file. This will generate a plot and save it as an image.

```bash
python sea_level_predictor.py
```

The plot will be saved as `sea_level_plot.png` in the project directory.

### Testing

There are unit tests available in the `test_module.py` file. The tests are imported into `main.py`, which is used to test the functionality of the plot creation.

To run the tests, use the following:

```bash
python main.py
```

### Files

- `sea_level_predictor.py`: Contains the code to generate the plot and perform the linear regression.
- `main.py`: Used to run and test the code.
- `test_module.py`: Contains unit tests to validate the implementation.
- `epa-sea-level.csv`: The dataset with historical sea level data.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

```

This README provides everything from setup instructions to usage and testing. Let me know if you want to modify any part of it!
