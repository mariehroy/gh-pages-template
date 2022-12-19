# load_model_essentials
-------------------------

## Model Variable Functions & Checks 

### Fetch Modeling Variables from DF

Retrieves standard modeling variables found in target dataframe and
loads it to the global environment.

getAllVars()

Includes:

 * Control Variables (ex. dichotomous variables)

 * Seasonality Variables

 * Inventory

 * Traffic

 * Campaign Variables (ex. Clicks, Impressions, Spend)

-   Attribution Reference Variables

etc.

### Fetch Modeling Variables and Return Lists

allVarsList()

### Add Winzorized Variables to Env (post winsIQR execution)

#### Please refer to cleaning_and_diagnostics/winsIQR()

addWinVars()

### Verify target DF contains set of fitvariables 

allVarsIn()

### Gather or Reset Predictors

getXv()

### Get Attribution Variables

getAttrVars()

### Create New Dummy Variable 

getDateDummy()

## Get contrast list for all factors

#### Validate numbers of levels and properties

#### Will display only levels actively present in data

getContrasts()

### Identify Missing Contrasts or Contrast Levels 

#### Compare two sets from getContrasts

contrastMatch()

### Get model terms

#### Get List of Predictors

fitTerms()

### Get List of Variables Including Response

fullTerms()

# Model Prep 

### Fetch Previous Model 

#### Including Model Summary and Attribution Metrics 

fetchPreviousM()

### Run Model Variables Prep

modelVarPrep()

#### Includes 

-   Log Transformation

-   Variables Adjustments

-   Time Variables

    addTimeVars()

    addYearTS()

### Additional Dummy Variables

addDummyVars ()

### Decay Variables 

Preps list of variables to decay on provided decay rates vector(s)

prepDecayVars()

### Refolding Data

Refolding and DF adjustments after changes in Selectabilities

foldSelectabilities()

Calls:

-   mergedWideRollup()

-   modelVarPrep()

-   addDummyVars()

-------------------------
