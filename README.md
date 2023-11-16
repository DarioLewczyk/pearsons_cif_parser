# pearsons_cif_parser
This module allows you to generate individual CIF files with custom names from a Pearson's Crystal Database output with multiple CIFs embedded in it to a folder you choose. 

This module depends on tqdm

* This can be run in a terminal window.
>* If you choose to do it this way, navigate to the directory with the PCD CIFs first then run.
>* The code will prompt you to type a folder name (it could exist already or not)
>* The code will output all CIFS embedded in each of the CIF files you had within the directory to the directory you created.
* If you want to change the filename prototype, you can customize what the code searches for with the dictionary: "pcd_kwargs"
>* The format is: "key", "regular expression to match the value"
