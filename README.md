# PlayStation WebKit Analyzer

## Link
[PWA](https://seregonwar.github.io/PWA/)

## Description

PlayStation WebKit Analyzer is a tool designed to analyze WebKit browser information on PlayStation devices. This project collects data such as WebKit version, media capabilities, known vulnerabilities, and more. Currently, vulnerability research is minimal; I am working on integrating a database that aggregates numerous exploits, such as exploitdb. Therefore, the current findings may not be very accurate due to the limited amount of available data.

## Features

- Analysis of WebKit browser information
- Checking WebKit vulnerabilities
- Support testing for Fetch, XMLHttpRequest, and WebSocket
- Browser permission checks
- SSL/TLS security testing
- Cache directive verification
- Analysis of localStorage and sessionStorage
- Media capabilities
- File system access
- DOM and JavaScript API fuzzing
- Event brute force and API combinations
- UserAgent spoofing

## Usage

1. Open the link in the "Link" section of this `README.md` file in your browser.
2. Click the "Inspect" button to access a modified version that allows the use of all tools. The tools will not work if you skip this step! You must be on the "about:blank" page.
3. Use the various buttons to perform specific tests:
    - **Analyze WebKit**: Starts the WebKit browser analysis.
    - **Download Analysis**: Downloads the analysis results in JSON format.
    - **Inspect**: The "Inspect" button has no function. You need to click on the toolbox at the bottom right to inspect and use the browser console.
    - **View Page Source**: View the page's source code.
    - **Trigger DevTools**: Forces the opening of developer tools. After clicking "Inspect", they will automatically be enabled.
    - **Fuzz DOM**: Performs DOM fuzzing. This may freeze the page; do not click on other elements during the process.
    - **Bruteforce Events**: Performs brute force on events.
    - **Test WebSocket**: Tests WebSocket support.
    - **Spoof UserAgent**: Modifies the browser's UserAgent. This function is very useful for simulating a different UserAgent.

## Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss what you would like to change. Make sure to update tests as necessary.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- **Seregonwar** - [GitHub](https://github.com/SeregonWar) | [Twitter](https://x.com/SeregonWar)

## Acknowledgements

- Thanks to the [Eruda](https://github.com/liriliri/eruda) project from which I derived the DevConsole.

# **Disclaimer**
This project was developed in support of another, namely the [overflow](https://github.com/seregonwar/Overflow) project, in all likelihood, given the fact that the project in this repository is more complete I will migrate the functions of the overflow project into this one, this will not affect the development of either project since both projects are compatible. This is not an exploit but aims to find flaws in the console's WebKit by analyzing the packages it works with and running active code directly on the browser seeing the effects in real time, so the software works on any browser and you can also test it on your computer or any console you want without a usable devtools.
