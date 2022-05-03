# @bedandbreakfasteu/prettier-config

The Prettier configuration for Bedandbreakfast.eu.

##Usage

1. Make sure `@bedandbreakfasteu/prettier-config` is available in your project.

2. Add the following to your `package.json`:

    ```json
    {
        "prettier": "@bedandbreakfasteu/prettier-config"
    }
    ```

    If you don't want to use `package.json`, use a `.prettierrc.json` that exports a string:

    ```json
    "@bedandbreakfasteu/prettier-config"
    ```

    Or if you need to extend this config use a `.prettierrc.js`:

    ```js
    module.exports = {
        ...require('@bedandbreakfasteu/prettier-config'),
        semi: false,
    };
    ```

3. Install the prettier plugin in your IDE and enable `format on save` for auto formatting.
