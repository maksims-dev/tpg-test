# Environments

- Create a shopify.theme.toml file
- minimal settings:
    ```
    [environments.development]
    store = "<store-name>"
    ignore = ["config/settings_data.json"]
    ```

# Start working

using Shopify CLI:
- shopify theme dev -e development