# PDF Table Extractor

This Python script extracts tables from PDF files using the Camelot library and provides data visualization capabilities using Pandas and Seaborn.

## Features

- Extract tables from user-provided PDF files
- Process and clean extracted data
- Visualize table data using Seaborn

## Requirements

To run this script, you need to have Python installed on your system along with the following libraries:

- Camelot-py
- Pandas
- Seaborn

You can install these libraries using pip:

```
pip install camelot-py pandas seaborn
```

Note: Camelot-py requires Ghostscript to be installed on your system. Please refer to the [Camelot documentation](https://camelot-py.readthedocs.io/en/master/user/install.html#install) for installation instructions specific to your operating system.

## Usage

1. Place the script in your desired directory.
2. Run the script using Python:

```
python Table_Extractor.py
```

3. When prompted, enter the path to your PDF file.
4. The script will extract tables from the PDF, process the data, and generate visualizations.

## How it works

1. **PDF Table Extraction**: The script uses Camelot to extract tables from the provided PDF file. Camelot is particularly good at extracting tables from PDFs, even when they're complex or poorly formatted.

2. **Data Processing**: After extraction, the script uses Pandas to process and clean the data. This may include operations like removing empty rows, converting data types, or reorganizing the data structure.

3. **Data Visualization**: Finally, the script utilizes Seaborn to create visualizations of the extracted data. These visualizations can help users quickly understand the content and structure of the extracted tables.

## Customization

You can modify the script to change how tables are extracted, processed, or visualized. Refer to the documentation of Camelot, Pandas, and Seaborn for more advanced usage and customization options.

## Troubleshooting

If you encounter any issues:

- Ensure all required libraries are correctly installed.
- Check that the PDF file path is correct and the file is accessible.
- Verify that Ghostscript is properly installed on your system.

## Contributing

Contributions to improve the script or this documentation are welcome. Please feel free to submit a pull request or open an issue on GitHub.

## License

The license under which this script is released, e.g., MIT.
