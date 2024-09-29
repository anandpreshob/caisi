# CAISI
This is the cancer AI screening initiative project

# Description
This is an open-source AI driven cancer screening tool under active development and it is not approved for any treatment. This tool is not FDA or any reulatory body approved so please do not use it for medical diagnosis and concult your doctor for medical advice. Purely intented to be a experimental tool. Looking for volunteers

# Roadmap of Development
## Phase 1:
    1. Convert the input CT or MR image of a patient into 3D nifti format.
    2. Use a full body segmentation tool to break down the input CT/MR into ROIs
    3. Use ROI specific models to run inference for each ROI
    4. Combine the output together for a wholistic scan.
### ROI
ROI can be based on body organ location or specific targeted cancer model

### Model Hunt
    1. Identify research papers with open-source model from multiple research paper proceedings using LLM model engines to identify candidates
    2. Identify initial target areas for the first phase

## Phase 2:
    1. For applications with less data, develop a synthetic data development engine.
    2. Identify a solution to link the data creation with label creation.
    3. Push the model performance higher with synthetic data