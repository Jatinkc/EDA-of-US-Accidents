# opendatasets

`opendatasets` is a Python library for downloading datasets from online sources like [Kaggle](https://www.kaggle.com/datasets) and Google Drive using a simple Python command. 


### Installation

Install the library using `pip`:

```
pip install opendatasets --upgrade
```

### Usage - Downloading a dataset

Datasets can be downloaded within a Jupyter notebook or Python script using the `opendatasets.download` helper function. Here's some sample code for downloading the [US Elections Dataset](https://www.kaggle.com/tunguz/us-elections-dataset):

```
import opendatasets as od
dataset_url = 'https://www.kaggle.com/tunguz/us-elections-dataset'
od.download('https://www.kaggle.com/tunguz/us-elections-dataset')
```

`dataset_url` can also point to a public Google Drive link or a raw file URL.

### Kaggle Credentials

`opendatasets` uses the [Kaggle Official API](https://github.com/Kaggle/kaggle-api) for donwloading dataset from Kaggle.  Follow these steps to find your API credentials:

1. Sign in to  [https://kaggle.com/](https://kaggle.com),  then click on your profile picture on the top right and select "My Account" from the menu.

2. Scroll down to the "API" section and click "Create New API Token". This will download a file `kaggle.json` with the following contents:

```
{"username":"YOUR_KAGGLE_USERNAME","key":"YOUR_KAGGLE_KEY"}
```

3. When you run `opendatsets.download`, you will be asked to enter your username & Kaggle API, which you can get from the file downloaded in step 2.

Note that you need to download the `kaggle.json` file only once. You can also place the `kaggle.json` file in the same directory as the Jupyter notebook, and the credentials will be read automatically.
