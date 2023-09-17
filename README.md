
# Google Colab File Downloader

This is a simple Python script for Google Colab that allows users to input a remote URL and download a file to their Google Drive.

## Usage

1. **Mount Google Drive:**
   - Run the first cell to mount your Google Drive. This will allow you to interact with your Drive from within the Colab environment.

2. **Input Remote URL:**
   - After mounting your Drive, the program will prompt you to enter the URL of the file you want to download. Make sure it's a direct download link.

3. **Download to Google Drive:**
   - The script will use `wget` to download the file to your Google Drive in the specified directory (`/content/drive/MyDrive/Backup/`).

4. **Optional: Perform Loop:**
   - The script also includes a loop for demonstration purposes. You can replace the loop with your own code if needed.


## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or suggestions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
