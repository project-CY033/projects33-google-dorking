# GoogleDoc

GoogleDoc is a simple tool for performing Google dorking on a specified target domain. 

## Features

- GUI for easy use
- Multiple Google dork queries
- Help option for command-line usage

## Usage

1. **Running the Tool:**
    - Run the `GoogleDoc` executable.
    - Enter the target domain and click "Start Google Dorking".

2. **Command-line Options:**
    - Run `GoogleDoc --help` to see the help message.

## Building from Source

To build the executable from the source, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Musharraf33/projects33-google-dorking.git
    cd googledoc
    ```
 
2. Run the following command to install requirements:
```sh
   pip install -r requirements.txt
   ```
3. Install `pyinstaller`:
    ```sh
    pip install pyinstaller
    ```

4. Run:
    ```sh
     python googledoc.py
    ```

5. The executable will be available in the `dist` directory.

## Important Notes

- Ensure you have permission to perform Google dorking on the specified target.
- This tool is intended for educational and authorized security testing purposes only. Unauthorized use is illegal and unethical.
- Before start Dorking open firfox or any browser.


## License

This project is licensed under the MIT License.
