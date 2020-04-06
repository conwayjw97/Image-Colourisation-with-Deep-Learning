## Manual

### How to Use these Notebooks

Each notebook will contain bold titles above each codeblock to inform the user of what eaech code block does. The titled code blocks which the user will want to edit are:

* **Select your Dataset:** presents the variables that determine which datasets are to be loaded onto the notebook. The user can change these variables to load different datasets.

* **Choose Whether to Train or Load a Model:** contains variables which instruct the notebook to load a pre-trained model from the repository, or to train a model within the notebook. It also lets the user choose whether to save a model that was loaded/trained in the notebook locally, and what filename the saved model should have if the user doesn't wish to use the default naming scheme.

* **Define Training Hyper-Parameters:** if the user wishes to train a model from within the notebook, then they can change the values of these variables to see what effect different hyper-parameter values can have on training.

Every other codeblock contains code to create or use the model, or to output the model's results. These blocks don't require the user to change their contents.

**N.B.** these notebooks originally used Google Drive to save/load models and datsets and worked fine, but for the project submission were changed to use Git to do this, as the repository can be more easily accessed by a third-party. The Git commands in the notebook resulted in being somewhat temperamental however, and sometimes can fail to load certain things first try. If you experience this issue, please try running the code block where it fails multiple times, as it will sometimes succeed after being tried more than once.
