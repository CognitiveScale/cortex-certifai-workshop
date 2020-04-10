# Accelerate AI/ML Workflows in Hybrid Cloud with Red Hat OpenShift Kubernetes Platform and CognitiveScale Cortex Certifai

https://odsc.com/speakers/accelerate-ai-ml-workflows-in-hybrid-cloud-with-red-hat-openshift-kubernetes-platform-and-cognitivescale-certifai/


# Prerequisites

1) Download the Certifai toolkit - https://www.cognitivescale.com/download-certifai/
2) Python 3.6 (We will use 3.6 so everyone is at the same level)
3) Conda is installed
4) Windows users must use PowerShell and have access to the folder where the toolkit was unzipped.

# Install the Certifai Toolkit

1) Set your context to the toolkit folder where you unzipped the contents of the Certifai Toolkit .zip during the download process.

`cd <path-to-folder-where-toolkit-was-unzipped>`

2) Create a Python 3.6 virtual environment.

`conda create -n certifai-odsc python=3.6`

3) Activate the newly created environment.

`conda activate certifai-odsc`

4) (To enable the use of Jupyter notebooks) Install the base requirements.

`pip install -r requirements.txt`

5) Install the CERTIFAI packages

# For Mac or Linux

`pip install packages/all/*``
`pip install packages/python3.6/*``

# For Windows PowerShell

`Get-ChildItem .\packages\all\*.zip | ForEach-Object -Process { pip install $_ }``
`Get-ChildItem .\packages\python3.6\*.zip | ForEach-Object -Process { pip install $_ }``

6) Verify that the Certifai CLI and client libraries are installed successfully.

`certifai -h`


# Workshop 1

## Explore Sample Reports provided with the Certifai Toolkit:

`certifai console examples/reports`

# Workshop 2

## In a terminal or PowerShell window set your context to the Certifai Toolkit notebooks directory

`cd examples/notebooks`

`jupyter notebook`

## Follow instructor how to run your own Certifai Scans