# Image Scraper Project

This project is a simple image scraper that uses the Selenium library to retrieve a given number of images based on a provided search term. It's a helpful tool for collecting images from various sources on the web.

## Getting Started

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.8

### Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies by running the following command in your terminal:
   ```
   pip install -r requirements.txt
   ```

### Usage

1. Open `main.py` in a code editor.
2. Modify the `search_term` variable to the desired search term.
3. Set the `num_images` variable to the number of images you want to scrape.
4. Ensure you have the correct path to the `chromedriver.exe` specified in the `DRIVER_PATH` variable.
5. Run the script using `python main.py`.

The script will initiate a web browser, perform the image search, and download the specified number of images to the designated directory.

### Example

```
# Modify these variables according to your preferences
search_term = "landscape"
num_images = 10
DRIVER_PATH = r'D:\Data Science-D drive\imagescrapper_sc-main\chromedriver.exe'

# Rest of the script...
```
## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.


