# Coin Counter JavaScript Application

This JavaScript application calculates the exact amount of change needed in quarters, dimes, nickels, and pennies for a given dollar amount.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
  - [coinCounterRecursive](#coinCounterRecursive)
  - [coinCounterClosure](#coinCounterClosure)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>


2. **Install dependencies:**


    ```bash  

    npm install


    ```

3. **Usage:**
To use the coin counter application, integrate the coinCounterRecursive and coinCounterClosure functions into your JavaScript projects.

Example of usage:
```bash
    const { coinCounterRecursive, coinCounterClosure } = require('./coinCounter');

    const amount = 4.99;

    // Using coinCounterRecursive
    const changeRecursive = coinCounterRecursive(amount);
    console.log(`Change for $${amount.toFixed(2)} using coinCounterRecursive:`);
    console.log(changeRecursive);

    // Using coinCounterClosure
    const changeClosure = coinCounterClosure(amount);
    console.log(`Change for $${amount.toFixed(2)} using coinCounterClosure:`);
    console.log(changeClosure);

```
