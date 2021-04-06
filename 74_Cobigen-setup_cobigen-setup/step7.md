

If there are multiple input elements selected, e.g., Java files, CobiGen will be started in batch mode. For the generation wizard dialog this means, that the generation preview will be constrained to the first selected input element. It does not preview the generation for each element of the selection or of a complex input. The selection of the files to be generated will be generated for each input element analogously afterwards.

Thus the color encoding differs also a little bit:

    - yellow: files, which are configured to be merged.

    - red: files, which are not configured with any merge strategy and thus will be created if the file does not exist or overwritten if the file already exists

    - no color: files, which will be ignored during generation

Initially all possible files to be generated will be selected.

![04-batch-mode-usage.png](./assets/04-batch-mode-usage.png)



