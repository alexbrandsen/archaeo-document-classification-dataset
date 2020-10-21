# archaeo-labelling-gold-standard

This repo contains a test set of 100 Dutch archaeological excavation reports, and their corrected metadata labels for subjects and time periods.

We also include labels for the train set, but unfortunately as the files are not all open access, we only provide a link to the metadata, which does include a link to the PDF file if available.

## Folders and Files

The [test](test) folder contains [test_sitetypes.csv](test_sitetypes.csv) and [test_timeperiods.csv](test_timeperiods.csv) which contain the labels per file for site types and time periods respectively. These are comma separated CSV files, labels are separated by |. 

In the [test/files](test/files) folder are all the documents from the test set as .txt files. 

---

The [train](train) folder contains the labels and links to metadata (including PDF link where available) for time periods and site types for the entire dataset. We've included files for just the top level categories (main) and for all categories, including subcategories (all). 

## Codes

The codes used are from the Archeologisch Basisregister (ABR). Wherever the code xxx is used, this means there is no information / the label is unknown. This can mean either no label can be assigned, or the metadata field was left empty by accident.


## Acknowledgements

This dataset was created by Alex Brandsen and Martin Koole.

## License

All files in this repository are licensed under a GNU GPLv3 License.
