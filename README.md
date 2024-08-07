# Upload FASTA Files to Nextclade.org

This tutorial will guide you through the steps to upload your FASTA files for outbreak analysis on [Nextclade.org](https://clades.nextstrain.org/).

## Step 1: Prepare Your FASTA Files

Ensure that your FASTA files are ready for upload. The file format should be `.fasta` and should contain the sequence data for the outbreaks you want to analyze.

## Step 2: Visit Nextclade.org

Go to [Nextclade.org](https://clades.nextstrain.org/) in your web browser.

## Step 3: Navigate to the Upload Section

On the Nextclade homepage, you will see an option to upload your files. This is typically labeled as "Drag and drop your sequence file(s) here" or similar.

## Step 4: Drag and Drop Your FASTA Files

1. Open the folder on your computer where your FASTA files are stored.
2. Select the FASTA files you want to upload.
3. Drag the selected files and drop them onto the upload area on the Nextclade webpage.

![Drag and Drop](figs/Screenshot%202024-08-06%20at%207.47.18 PM.png)

## Step 5: Wait for the Upload to Complete

Nextclade will start processing the files as soon as you drop them. You will see a progress bar or indicator showing the upload status. Wait until the upload is complete.

## Step 6: Review and Analyze Your Data

Once the upload is complete, Nextclade will process your sequences and provide you with the analysis results. You can review various details such as clades, mutations, and quality assessments.

## Step 7: Download the Results metadata

After the analysis is complete, you can download the results. Look for the download options on the results page to save the data to your computer. Download either the csv or tsv format. 
![Metadata](figs/Screenshot%202024-08-06%20at%207.49.14 PM.png)

# Step 8: Download the phylogenetic tree
In the same menu, look for the newick options on the results page to save the phylogenetic tree
![tree](figs/Screenshot%202024-08-06%20at%207.52.42 PM.png)

# Additional Tips

- Ensure that your internet connection is stable during the upload process.
- If you encounter any issues, refer to the [Nextclade documentation](https://docs.nextstrain.org/projects/nextclade/en/stable/user/nextclade-web.html) for troubleshooting tips.

That's it! You've successfully uploaded and analyzed your FASTA files using Nextclade.org.


# How to Combine Tree and Metadata from Nextclade and Upload to Microreact

This guide will walk you through the steps to combine your phylogenetic tree and metadata from Nextclade and upload them to Microreact for visualization.

## Step 1: Generate and Download Data from Nextclade

1. **Upload your FASTA files to Nextclade**:
    - Follow the previous guide on [how to upload FASTA files to Nextclade.org](#how-to-upload-fasta-files-to-nextcladeorg).

2. **Generate the Tree and Download Results**:
    - After processing your sequences on Nextclade, download the following files:
      - **Tree file (Newick format, `.nwk`)**
      - **Metadata file (CSV format, `.csv`)**

## Step 2: Prepare Files for Microreact

Ensure that your metadata file and tree file are ready for upload. The metadata file should be a CSV with columns that correspond to the node labels in your tree file.

## Step 3: Visit Microreact.org

Go to [Microreact.org](https://microreact.org/) in your web browser.

## Step 4: Create a New Project

1. On the Microreact homepage, click on the **Create** button.
2. Select **Create a new project** from the dropdown menu.

## Step 5: Upload Your Tree File

1. In the **Create a new project** interface, locate the **Tree** section.
2. Click on **Choose file** and upload your tree file (`.nwk`).

## Step 6: Upload Your Metadata File

1. In the same interface, locate the **Metadata** section.
2. Click on **Choose file** and upload your metadata file (`.csv`).

## Step 7: Review and Configure Your Project

1. After uploading both files, Microreact will process the data and create a visualization.
2. Review the visualization to ensure the tree and metadata are correctly integrated.
3. You can configure various settings such as labels, colors, and layouts to better visualize your data.

## Step 8: Save and Share Your Project

1. Once you are satisfied with the visualization, click on **Save**.
2. You will be provided with a unique URL that you can use to access and share your Microreact project.

## Additional Tips

- Ensure that the node labels in your tree file match the identifiers in your metadata file.
- Refer to the [Microreact documentation](https://docs.microreact.org/) for additional customization options and troubleshooting tips.

That's it! You've successfully combined your tree and metadata from Nextclade and uploaded them to Microreact for visualization.
