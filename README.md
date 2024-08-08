# Insurance-data-analysis

This dataset contains of insured data, where the Insurance charges are given against the following attributes of the insured: Age, Sex, BMI, Number of Children, Smoker and Region. The attributes are a mix of numeric and categorical variables.


## Age
 Age of primary beneficiary

## Sex 
Insurance contractor gender, female / male

## Bmi
Body mass index, providing an understanding of body, weights that are relatively high or low

## Children
Number of children covered by health insurance / Number of dependents

## Smoker
Smoker / Non - smoker

## Region
The beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

## Charges
Individual medical costs billed by health insurance.

## Setup
### Virtual Environment (VENV) Setup
A virtual environment (venv) allows you to manage separate package installations for different projects, creating an isolated Python environment for each project. This ensures that packages installed for one project do not interfere with those in another.

To create a virtual environment, navigate to your project’s directory and run the following command:

Windows: python -m venv .venv

MacOS/Unix: python3 -m venv .venv

The command will create a virtual environment in a local folder named .venv.

#### Activating the Virtual Environment
Activating the virtual environment sets the environment-specific python and pip executables into your shell’s PATH.

Windows: .\.venv\Scripts\activate

MacOS/Unix: source .venv/bin/activate

#### Deactivating the Virtual Environment
To deactivate the virtual environment and return to the global Python environment, run: deactivate

### Installing Packages with pip
Once your virtual environment is activated, you can install packages using pip. To install the dependencies listed in requirements.txt, use the following commands:

Windows: python -m pip install -r requirements.txt

MacOS/Unix: python3 -m pip install -r requirements.txt
