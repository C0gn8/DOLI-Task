# DOLI Task

The DOLI Task is a computerized experimental task designed to investigate metaphoric language processing and cognitive constraint in clinical and non-clinical populations. Further information about the experiment is available at https://www.olidnejad.com.

**Version 5.2** is the latest stable working release and is recommended for all new research use.

## Version History

### Version 3.1

The initial prototype release. This version contained an error in stimulus list allocation.

### Version 5.1

Corrected the stimulus allocation issues present in Version 3.1 and migrated the task from a Tkinter desktop GUI to a Streamlit web-based interface. This version still contained an error whereby distractor items were presented as a front-loaded block rather than being interleaved with the main stimulus items.

### Version 5.2

Corrects the distractor presentation issue and is the recommended version for data collection.

## Running the Task

From the project directory, run:

```bash
streamlit run DOLI_V5.2.py
```

Alternatively, download all files and run the included batch file.

The task will open automatically in your web browser.

Results are saved in CSV format in the `/data` folder. Users intending to collect data are encouraged to clone the repository rather than relying on temporary GitHub Codespaces storage.

## Licence

This project is released under **CC0 1.0 (Public Domain Dedication)**.

## Citation

If you use the DOLI Task in research, please cite:

Delgaram-Nejad, O., et al. (2022). *A Tutorial on Norming Linguistic Stimuli for Clinical Populations*. Applied Corpus Linguistics.
