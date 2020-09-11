# anemi

This repository contains the source code for the ANEMI3 integrated assessment model of global change. Keys files are described below:

* ANEMI3.mdl - contains model code in text format. Can be opened with a text editor and run with Vensim DSS version 6.3.
* ANEMI3.vdf - contains model code in binary format. Can be opened and run with the Venism Model Reader (https://vensim.com/vensim-model-reader/). Editing with the Vensim Model Reader is not supported

Scenarios used previously with the model are located in the `Scenarios` directory, which contain definitions of model parameters for each scenario.

## Instructions for Running the Model

The ANEMI3 model can be run for free using the Vensim Model Reader. In the software, open `ANEMI3.vdf`. Upon opening, the stock and flow structure of the model will be displayed. To run the model under the default parameter set press "Simulate". After the process is completed, results can be viewed by clicking on a model variable then selecting the "Graph" or "Table" tool. Model constants and lookup tables can be changed by first pressing "Sim Setup" then clicking the "Model Constants" or "Lookup" buttons to alter the default values.
