## Data

#### models/

Contains the architecture and weights of the trained models that were used for the evaluations shown on the report. You can check manual.md within the src/ folder to learn how to load these models into the notebooks yourself.

#### datasets/

Contains the ShapeSet, Face images, and Imagenette datasets used to evaluate our models. Cifar-10 is not included here, as it is downloaded inside the notebooks through the use of dedicated Tensorflow function calls.

All datasets used in this project respect the appropriate licencing: 

* Cifar-10 is an MIT licenced dataset: https://github.com/wichtounet/cifar-10

* Face images was reused from the MIT licenced project: https://github.com/2014mchidamb/DeepColorization

* Imagenette is an Apache 2.0 licenced dataset: https://github.com/fastai/imagenette

* ShapeSet was made specifically for use on this project.

* If you involved human subjects in any form, you will require ethical permission.
    * Keep records of all items related to ethics in `data/ethics`. There are templates for scripts, guidance provided.
    * **You must have scanned PDFs of signed checklists in this folder**, or PDFs of ethics confirmations from other sources
    * Ensure you remain GDPR compliant. In general:
        * Never collect personally identifiable information if at all possible. 
        * Pseudonymise identifiers for subjects. 
        * Use coarse demographic values unless you need specific information (for example, if you need age ranges, collect ranges, not specific ages)
        * Ensure you have explicit consent for the storage and use of data from human subjects
        * DO NOT STORE PERSONALLY IDENTIFIABLE INFORMATION ON REMOTE SERVERS (no Dropbox, Github, etc.)

* Keep a written description of the data, what is contained, and how it was captured in `data/readme.md`
* Record all raw data as an immutable store. **Never modify captured data.** 
    * Keep this under `data/raw`
    * This could be logs, questionnaire responses, computation results

* Write scripts to produced processed data from these (e.g. tidy dataframes, excel sheets, csv files, HDF5 files, sqlite databases)
* Write scripts that process these into results, visualisations, tables that you include in your project.
* If you use Jupyter/RStudio notebooks, place these in `data/notebooks` and name them carefully (not "Untitled1", "Untitled2").

