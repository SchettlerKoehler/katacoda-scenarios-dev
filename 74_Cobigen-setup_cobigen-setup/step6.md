# Usage

In this step we will learn about the types of modes for usage of CobiGen.

CobiGen has two different generation modes depending on the input selected for generation. 
    1. Simple mode
    2. Batch mode



    Selecting the menu entry Generate​ the generation wizard will be opened.The left side of the wizard shows all available increments, which can be selected to be generated. Increments are a container like concept encompassing multiple files to be generated, which should result in a semantically closed generation output. On the right side of the wizard all files are shown, which might be effected by the generation - dependent on the increment selection of files on the left side. The type of modification of each file will be encoded into following color scheme if the files are selected for generation:

    - green: files, which are currently non-existent in the file system. These files will be created during generation

    - yellow: files, which are currently existent in the file system and which are configured to be merged with generated contents.

    - red: files, which are currently existent in the file system. These files will be overwritten if manually selected.

    - no color: files, which are currently existent in the file system. Additionally files, which were unselected and thus will be ignored during generation.

![03-simple-mode-usage.png](./assets/03-simple-mode-usage.png)



