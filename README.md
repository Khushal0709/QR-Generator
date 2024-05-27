# QR Code Generator

This is a simple QR Code Generator built using Node.js. The application allows you to generate QR codes for any given text or URL and save them as image files.

## Features

- Generate QR codes for text or URLs
- Save generated QR codes as PNG images
- Simple and easy-to-use interface



## Usage

1. Run the application:

    ```sh
    node index.js
    ```

2. Follow the prompts to enter the text or URL you want to generate a QR code for.

3. The generated QR code will be saved as a PNG image in the `output` directory.

## Examples

### Generating a QR Code for a URL

1. Start the application:

    ```sh
    node index.js
    ```

2. When prompted, enter the URL you want to encode, e.g., `https://www.example.com`.

3. The application will generate the QR code and save it as `output/qrcode.png`.

### Generating a QR Code for Text

1. Start the application:

    ```sh
    node index.js
    ```

2. When prompted, enter the text you want to encode, e.g., `Hello, world!`.

3. The application will generate the QR code and save it as `output/qrcode.png`.

## Dependencies

This project uses the following Node.js modules:

- [qrcode](https://www.npmjs.com/package/qrcode): For generating QR codes.
- [inquirer](https://www.npmjs.com/package/inquirer): For creating interactive command line interfaces.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Submit a pull request.
