# Online Code Editor Project


## Table of Contents

- [Features](#features)
- [How to Use](#how-to-use)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Project](#running-the-project)
- [Usage](#usage)

## Features

- CodeMirror integration for code editing with syntax highlighting and line numbers.
- Ability to run Python and JavaScript code snippets.
- Real-time display of code output and errors.
- Support for multiple programming languages within the same interface.

## How to Use

1. Open the code editor in your browser.
2. Write Python or JavaScript code in the editor.
3. Click the "Run" button to execute the code.
4. The output or any errors will be displayed in the output area.


## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Before you begin, make sure you have the following software installed on your computer:

- Python: You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository to your local machine using Git:

```bash
git clone https://github.com/inerttila/online-code-editor.git
```

Navigate to the project's directory:

```bash
cd online-code-editor
```

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

On macOS and Linux:

```bash
source venv/bin/activate
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Running the Project

Start the Flask application:

```bash
python server.py
```

Open your web browser and go to http://localhost:5500.

## Usage

You can now use the online code editor to write and execute Python and JavaScript code within your browser.
