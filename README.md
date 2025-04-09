# NL2BASH
# NL2BASH

NL2BASH is a web-based tool that converts natural language instructions into corresponding Bash commands. The application leverages a machine learning model (using [`T5ForConditionalGeneration`](https://huggingface.co/models) and [`RobertaTokenizer`](https://huggingface.co/docs/tokenizers/python/latest/)) from Transformers to generate and execute Bash commands dynamically.

## Features

- **Natural Language Processing:** Convert user instructions into Bash commands.
- **Dynamic Working Directory:** Select the desired working directory for command execution.
- **Command Execution History:** View a log of previously executed commands and outputs.
- **Integrated Interface:** Built with Flask, jQuery, and Bootstrap for a responsive experience.
  
## Project Structure

- **[app.py](c:\Users\saivi\OneDrive\Desktop\Projects\NL2BASH-main\app.py):** Main Flask application that handles routing, model inference, and command execution.
- **[templates/index.html](c:\Users\saivi\OneDrive\Desktop\Projects\NL2BASH-main\templates\index.html):** HTML template for the web interface.
- **[static/style.css](c:\Users\saivi\OneDrive\Desktop\Projects\NL2BASH-main\static\style.css):** Custom CSS styling for the application.
- **[LICENSE](c:\Users\saivi\OneDrive\Desktop\Projects\NL2BASH-main\LICENSE):** Apache License 2.0.

## Installation

1. **Clone the Repository**
   ```sh
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**
   ```sh
   cd NL2BASH-main
   ```

3. **Set Up the Environment**
   - Ensure you have Python 3.8 or later installed.
   - (Optional) Set up a virtual environment:
     ```sh
     python -m venv venv
     source venv/bin/activate # On Windows use: venv\Scripts\activate
     ```

4. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Application**
   ```sh
   python app.py
   ```
   
2. **Access the Web Interface**
   - Open your browser and visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

3. **Generate and Execute Commands**
   - Enter your natural language instruction.
   - Select the desired directory from the dropdown.
   - Click **Generate Command** to view the Bash command.
   - Click **Execute Command** to run the command and view the output.
   - The command and output will be added to the execution history.

## Contribution

Contributions are welcome! Please submit issues or pull requests for improvements and bug fixes.

## License

This project is licensed under the terms of the [Apache License 2.0](c:\Users\saivi\OneDrive\Desktop\Projects\NL2BASH-main\LICENSE).

## Acknowledgments

- Thanks to the developers of [Flask](https://flask.palletsprojects.com/), [PyTorch](https://pytorch.org/), and [Transformers](https://huggingface.co/docs/transformers/index) for the foundational libraries.
- Special mention to the original [JayProngs/NL2BASH](https://huggingface.co/JayProngs/NL2BASH) model.
<p>Authors:
<table>
  <tr>
    <td align="center"><a href="https://github.com/JayProngs"><img src="https://avatars.githubusercontent.com/u/38587156?v=4" width="75px;" alt=""/><br /><sub><b>Jayesh Thakur</b></sub></a></td>
    <td align="center"><a href="https://github.com/saivikasreddy717"><img src="https://avatars.githubusercontent.com/u/143281993?v=4" width="75px;" alt=""/><br /><sub><b>Sai Vikas</b></sub></a></td>
    <td align="center"><a href="https://github.com/aryansharma2k2"><img src="https://avatars.githubusercontent.com/u/118040810?v=4" width="75px;" alt=""/><br /><sub><b>Aryan Sharma</b></sub></a></td>
  </tr>
</table>
