
## Usage

### TypeScript

```javascript
const OpenAPIClientAxios = require('openapi-client-axios').default

const definition = 'https://github.com/allengrant/shopify_openapi/raw/master/shopify_openapi.yaml'
let api = new OpenAPIClientAxios({ definition })
api = await api.init()
```

### Python

```bash
# Generate the Python Client
openapi-python-client generate --url https://github.com/allengrant/shopify_openapi/raw/master/shopify_openapi.yaml
cd shopify-admin-api-client
```

```python
from shopify_admin_api_client import Client

client = Client(base_url="https://example.myshopify.com")
```

## Contributing

[fork]: https://github.com/USER/REPO/fork
[pr]: https://github.com/USER/REPO/compare
[style]: https://github.com/styleguide/ruby
[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

## Contributions to the OpenAPI descriptions

**We don't currently accept pull requests that directly modify the description artifacts found in this repository.** If you have feedback on the descriptions or have found a mismatch between the behavior that is described in this repo and the runtime behavior of the API, please open an issue.

## Contributions to other files in the repository

We will gladly accept pull requests for contributions to other files in this repository.

### Submitting a pull request

0. [Fork][fork] and clone the repository
0. Create a new branch: `git checkout -b my-branch-name`
0. Make your change
0. Push to your fork and [submit a pull request][pr]
0. Pat your self on the back and wait for your pull request to be reviewed and merged.

## Bugs

If you find a bug, open an issue. We're actively maintaining this. We understand that Shopify's documentation doesn't always line up exactly with its behavior. That's why this spec is so important. We're documenting how the API really works.

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
