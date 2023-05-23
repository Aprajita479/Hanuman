# Hanuman

This is a Python script that uses the Turtle module to draw shapes based on coordinates and colors specified in a Microsoft Word document.

## Prerequisites

- Python 3.x
- turtle module
- docx module

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install the required dependencies:

   ```bash
   pip install turtle
   pip install python-docx
   ```

## Usage

1. Make sure you have a Microsoft Word document containing the coordinates and colors for the shapes you want to draw. The document should have the extension `.docx`.

2. Replace the `source` variable in the script with the name of your Word document (without the extension):

   ```python
   source = "your_document_name"
   ```

3. Run the script:

   ```bash
   python draw_shapes.py
   ```

4. The turtle window will open in fullscreen mode and start drawing the shapes based on the coordinates and colors specified in the Word document.

## Notes

- The script extracts coordinate and color information from paragraphs in the Word document that match specific patterns using regular expressions. Make sure your document follows the required format for successful extraction.

- The shapes are drawn sequentially, one after another. Each shape is filled with the specified color before moving to the next shape.

- You can adjust the drawing speed by modifying the `tracer` and `speed` functions. Higher values result in faster drawing.

- You can exit the drawing window by closing it manually.

## License

This project is licensed under the [MIT License](LICENSE).
