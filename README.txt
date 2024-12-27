### The README serves as a guide to help you understand the files and folders, and some information about the project.


#### Folder Structuree 

|-- README.txt
`-- src 
    |-- code #Contains all the code                                                                       
    |   |-- drafts #Contains all draft code (can be ignored)								    									
    |   |   |-- EnhancingTransactionMonitoringWithML_v0_1.ipynb
    |   |   |-- EnhancingTransactionMonitoringWithML_v0_2.ipynb
    |   |   |-- EnhancingTransactionMonitoringWithML_v0_3.ipynb
    |   |   `-- EnhancingTransactionMonitoringWithML_v0_4.ipynb
    |   `-- staging #Contains the final code with pdf version of it for better readability
    |       |-- EnhancingTransactionMonitoringWithML_v1.ipynb
    |       `-- EnhancingTransactionMonitoringWithML_v1.pdf
    `-- resources #Contains datasets and presentation
        |-- generated-dataset
        |   |-- pretrain_trusted.csv
        |   `-- pretrain_untrusted.csv
        |-- input-dataset
        |   |-- df_kyc.csv
        |   |-- df_label.csv
        |   `-- df_transactions.csv
        `-- presentation
            `-- Presentation_EnhancingTransactionMonitoringWithML.pdf


#### Note

1. The drafts folder contains several early versions of the code where extensive exploratory data analysis (EDA) was performed, 
such as using .head(), plotting, and other exploratory techniques. (You can ignore this if you want)
2. The staging folder holds a refined and polished notebook, designed to be more linear and easier to follow for readability.
3. For a more user-friendly experience, refer to the PDF version of the V1 notebook located in the staging folder.
4. The generated-dataset folder includes preprocessed datasets that were created before training the models.
5. The presentation folder contains the project presentation, originally created in Google Slides and converted into a PDF format for convenience.