## Data

**Feature naming**
    - `[stage].[parameter_type].[parameter_name]` (Example: rougher.input.feed_ag)
    - Possible values for `[stage]`:
        - `rougher` — (raw ore) flotation
        - `primary_cleaner` — primary cleaning
        - `secondary_cleaner` — secondary cleaning
        - `final` — final features
    - Possible values for `[parameter_type]`:
        - `input` — raw material parameters
        - `output` — product parameters
        - `state` — parameters that characterize the current state of processing
        - `calculation` — calculation features

**Target**
    - `rougher.output.recovery` — amount removed from rough concentrate.
    - `final.output.recovery` — final withdrawal amount of concentrate.

## Goal

Prepare a prototype machine learning model that predicts the amount of pure gold extracted from gold ore based on data about extraction and purification processes. The model should optimize production and eliminate unprofitable parameters.

## Libraries used:
* pandas
* scikit-learn
* matplotlib