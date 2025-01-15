# Credit Card Flag Validator

This project is a simple JavaScript application that identifies the flag of a credit card based on its number. It supports various card types including Visa, MasterCard, American Express, Discover, and Diners Club.

## Project Structure

```
credit-card-flag-validator
├── src
│   ├── index.js          # Entry point of the application
│   └── utils
│       └── validator.js  # Contains the card flag validation logic
├── package.json          # npm configuration file
└── README.md             # Project documentation
```

## Installation

To get started with the Credit Card Flag Validator, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd credit-card-flag-validator
npm install
```

## Usage

To use the credit card flag validator, run the following command:

```bash
node src/index.js
```

This will execute the application and test various credit card numbers to identify their flags.

## Examples

The application will output the following examples:

- `4111111111111111` -> Visa
- `5111111111111111` -> MasterCard
- `341111111111111`  -> American Express
- `6011111111111111` -> Discover
- `30011111111111`   -> Diners Club

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or additional features.
