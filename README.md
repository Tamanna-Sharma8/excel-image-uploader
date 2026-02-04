
# Excel Image Uploader

Excel Image Uploader is a utility that allows users to upload Excel files containing image data or image URLs, process them, and download or store images automatically.

This tool is useful for bulk product uploads, catalog processing, and image extraction workflows in e-commerce or data-processing systems.

## Features

- Upload Excel files containing image data or URLs
- Extract image links from Excel sheets
- Download and store images automatically
- Supports bulk image processing
- API-based integration support
- Error handling for invalid or missing data

## Use Cases

- E-commerce product image import
- Bulk catalog processing
- Image metadata extraction
- Automated image download pipelines

## Project Structure

```

excel-image-uploader/
│
├── app/                # Backend application
├── uploads/            # Uploaded Excel files
├── downloads/          # Downloaded images
├── requirements.txt    # Dependencies
└── README.md

````

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/excel-image-uploader.git
cd excel-image-uploader
````

Create a virtual environment (recommended):

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the server:

```bash
python app.py
```

or

```bash
python -m app
```

Server will run locally and accept file uploads.

## API Usage (Example)

Upload an Excel file:

```
POST /upload
```

Form data:

```
file: <excel file>
```

The API processes the file and downloads/extracts images accordingly.

## Known Issues

* Large files may take longer to process.
* Invalid image URLs are skipped.

## Future Improvements

* Progress tracking UI
* Parallel image downloads
* Admin dashboard
* Cloud storage integration

## Contribution

Pull requests and suggestions are welcome.

## License

This project is open-source and available under the MIT License.
=================
final requirements added


