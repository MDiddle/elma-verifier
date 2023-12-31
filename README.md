# ELMA-verifier

This Python module allows users to verify whether an organization number is valid and is set up to receive invoices through the EHF format.

## Installation
To install the `elma-verifier` package, simply use `pip`:

```bash
pip install elma-verifier
```

## Usage
Here's how you can use the elma-verifier:

```python
from elma_verifier import verifier
result = verify.verify_org_number("YOUR_ORG_NUMBER_HERE")
print(result)  # Returns True if organization number is registered to receive EHF invoices, otherwise False
```

## Issues & Contributions
If you come across any issues or would like to contribute to the improvement of this package, please open an issue or submit a pull request.

## Acknowledgements and Dependencies

- **Selenium**: This package uses [Selenium](https://www.selenium.dev/) which is licensed under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).

## License
This package is distributed under the MIT License.

Copyright 2023 Mathias S. Mjømen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


