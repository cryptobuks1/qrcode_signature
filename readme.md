# qrcode_signature_ganerator

## Usage

~~~bash
python main.py [-h] [-e PRI_KEY_FILE] [-d PUB_KEY_FILE] {generate,identify}
~~~



## Functions

### 1. generate qrcode

~~~bash
python main.py [-h] [-e PRI_KEY_FILE] [-d PUB_KEY_FILE] generate
~~~

If key files are not provided, the program will use default key.

Then it will ask you to input your message and qrcodify it.



### 2. varify qrcode

~~~bash
python main.py [-h] [-e PRI_KEY_FILE] [-d PUB_KEY_FILE] identify
~~~

If key files are not provided, the program will use default key.

Then you need to scan qrcode with your computer camera, and the program will varify whether your qrcode is valid or not.