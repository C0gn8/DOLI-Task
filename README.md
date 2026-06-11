# DOLI Task

The DOLI Task is a computerized experimental task designed to investigate metaphoric language processing and cognitive constraint in clinical and non-clinical populations. Further information about the experiment is available on https://www.olidnejad.com

**Version 5.2** is the latest stable working release and is recommended for all new research use.

Version 3.1. was the initial prototype. It did not allocate stimuli lists correctly.

Version 5.1 corrected the issues of 3.1. and also moved away from a desktop GUI approach using Tkinter to a web-based presentation using Streamlit. It still contained an error, thought to be fixed, where distractor items were front-loaded ahead of main items instead of interleaved into the main item set. 

Version 5.2. is the version recommended for data collection. 

## Running the Task

From the project directory, run:

```bash
streamlit run DOLI_V5.2.py
```

Or download all files and run the batch file.

The task will open automatically in your web browser.

Results are saved in .csv format in the /data folder of the GitHub Codespace. Cloning the repository is recommended if you wish to store data on the Codespace.

## Licence

This project is released under **CC0 1.0 (Public Domain Dedication)**.

## Citation

If you use the DOLI Task in research, please cite:

Delgaram-Nejad, O., et al. (2022). *A Tutorial on Norming Linguistic Stimuli for Clinical Populations*. Applied Corpus Linguistics.
