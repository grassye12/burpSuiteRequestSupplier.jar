# RequestSupplier

A custom Burp Suite extension that sends the request body from the HTTP History tab to a specified local server endpoint: `/some_endpoint` on port `8099`.

## Features

- Send HTTP request bodies directly from Burp's HTTP History tab
- Integrate with local automation tools or scripts
- Easy to install and use as a `.jar` extension
- Was built to work on analyzing GraphQL fields locally/separately
## Installation

1. Download the latest JAR file from the [Releases page](https://github.com/grassye12/burpSuiteRequestSupplier.jar/releases/latest).
2. Open Burp Suite.
3. Go to the **Extender** tab.
4. Click **Add** and select the downloaded `RequestSupplier.jar`.
5. The extension will load and be ready to use.

## Usage

- In the **HTTP History** tab, make sure you have all the necessary requests.
- make sure, local server is propely set up,
- Load the extension and enable it,
- Now, automatically all the request body from those requests will be passed to the local server

## Download

Get the latest `.jar` file here:  
[Download RequestSupplier.jar](https://github.com/grassye12/burpSuiteRequestSupplier.jar/releases/latest)

## License

MIT License

---

Created by [Grassye](https://github.com/grassye12)
