# FRM/CRM Credit Risk Models

## Overview

This repository contains implementations and documentation for Credit Risk Models, specifically focusing on Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD). These models are essential components of Financial Risk Management (FRM) and Credit Risk Management (CRM).

## Table of Contents

- [Models](#models)
  - [Probability of Default (PD)](#probability-of-default-pd)
  - [Loss Given Default (LGD)](#loss-given-default-lgd)
  - [Exposure at Default (EAD)](#exposure-at-default-ead)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Models

### Probability of Default (PD)

- **Description:** PD measures the likelihood that a borrower will default within a given timeframe. It is a crucial component in credit risk assessment.
- **Usage:**
  ```python
  from models.pd_model import calculate_pd

  # Input variables (e.g., financial ratios, credit history)
  input_data = {...}

  # Calculate PD
  pd = calculate_pd(input_data)
  ```

### Loss Given Default (LGD)

- **Description:** LGD represents the potential loss incurred by a lender in the event of a borrower's default. It is the proportion of exposure not recovered.
- **Usage:**
  ```python
  from models.lgd_model import calculate_lgd

  # Input variables (e.g., collateral value, recovery rates)
  input_data = {...}

  # Calculate LGD
  lgd = calculate_lgd(input_data)
  ```

### Exposure at Default (EAD)

- **Description:** EAD estimates the potential loss a lender may face if a borrower defaults at a specific point in the future.
- **Usage:**
  ```python
  from models.ead_model import calculate_ead

  # Input variables (e.g., outstanding balance, credit conversion factor)
  input_data = {...}

  # Calculate EAD
  ead = calculate_ead(input_data)
  ```

## Usage

1. Clone the repository: `git clone https://github.com/black82hat/FRM-CRM.git`
2. Navigate to the repository: `cd FRM-CRM`


## Contributing

Contributions are welcome! If you have improvements or additional models, feel free to open an issue or submit a pull request.

Creator : [Lakshaya Maleti](https://www.linkedin.com/in/lakshaya-maleti-9b600a113/)

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to customize this README according to your specific implementation details and structure. Ensure that you replace placeholder text such as `yourusername` with your actual username or organization name.