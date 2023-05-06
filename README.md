# python-qrcode-maker

This code allows the user to input text or a link and converts it into a QR code. 

First, it imports the `qrcode` module which provides functionality for generating QR codes. 

Then, the user is prompted to enter the text or link that they want to convert to a QR code using the `input()` function. The input is stored in the `link` variable. 

Next, a `QRCode` instance is created with some default settings, such as the error correction level, box size, and border. The data from the `link` variable is then added to the QR code instance using the `add_data()` method. 

The `make()` method is called to generate the QR code, and the resulting image is stored in the `img` variable. The QR code image is created with a black fill color and gray background color. 

Finally, the image is saved as a PNG file named `qrcode.png` using the `save()` method.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- convert links or text to a QR code.

## Installation

To install this project, follow these steps:
1. Clone the repository to your local machine:
```
git clone https://github.com/devvyyxyz/python-qrcode-maker
```
2. Navigate to the project directory:
```
cd python-qrcode-maker
```
3. Install the project dependencies:
```
pip install -r requirements.txt
```
4. (Optional) If you plan to contribute to the project, you may want to install additional development dependencies. To do so, run:
```
pip install -r requirements-dev.txt
```
5. Set up any required configuration files or environment variables as specified in the project documentation.
6. Run the project:
```
python main.py
```



## Usage

Enter a value when prompted and press enter then navigate to `python-qrcode-maker/qrcode.png`.

## Contributing

Contributions are not being taken.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
