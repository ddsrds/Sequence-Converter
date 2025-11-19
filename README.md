# 🧬 Sequence Converter - [Nucleotide to Protein]

This script aims to reformat genetic sequence files (such as .fasta or .txt files) as follows:

- Preserves the original header (line starting with '>').

- Converts all subsequent lines of the sequence into a protein sequence, facilitating sequence processing by other programs.

# 📁 Steps to use the script

1. Save the script and the sequence file
- Create a new folder in your Google Drive.

- Save this script inside that folder.

- Save the sequence file, i.e., the file you want to convert, in the same folder as the script.

- Important: Rename the sequence file to "sequence.txt".

#2. Open the script in Google Colab

- Right-click on the script file (e.g., sequence_formatter.ipynb) and select "Open with > Google Colab".

- Colab will open in a new browser tab with the script content loaded.

#3. Edit File Paths

In the second code block, you will find two important lines at the beginning:

input = '/content/drive/MyDrive/CreatedFolderName/sequence.txt'

output = '/content/drive/MyDrive/CreatedFolderName/output.txt'

- Change the path in the input variable to reflect the exact location where you saved the file in your Drive (sequence.txt).

- Change the path in the output variable to the location where you want to save the output file (output.txt).

#4. Allowing Access to Google Drive

For the script to access files saved in your Google Drive, you need to connect Google Colab to your Drive account. Follow the steps below:

- With the script open in Google Colab, use the command "CTRL + F9" to execute the code for all blocks.

- Colab will request permission to access your Google Drive.

- After logging in, a screen will appear requesting authorization to access the files in your Google Drive. - Click the option to authorize access and your Google Drive will be mounted in the Colab environment.

#5. Verify the output file.

- Access the folder where the files are located in your Google Drive.

- The newly converted file should appear as: output.txt

- If it doesn't appear immediately, refresh the Drive page a few times, as Google Drive may take a few seconds to display files created by Colab scripts.

#6. Possible Errors

- The script does not modify the genetic data, it only converts the sequence format. However, to avoid errors, make sure:

- You are connected to a Wi-Fi network.

- The original filename must be exactly sequence.txt.

- The paths in the script are correct.

- If you encounter more errors, try restarting your browser or computer.
