# @bedandbreakfasteu/prettier-config

The Prettier configuration for Bedandbreakfast.eu.

## Usage

1. Install the package:

    ```bash
    yarn add --dev @bedandbreakfasteu/prettier-config@bedandbreakfasteu/prettier-config#1.0.2
    ```

2. Add the following to your `package.json`:

    ```json
    {
        "prettier": "@bedandbreakfasteu/prettier-config"
    }
    ```

    Or use a `.prettierrc.js` if you need to extend it:

    ```js
    module.exports = {
        ...require('@bedandbreakfasteu/prettier-config'),
        semi: false,
    };
    ```
