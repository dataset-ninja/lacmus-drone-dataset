Dataset **LADD: Lacmus Drone Dataset** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/bfujyz8lmibrms7p8n87e/ladd-lacmus-drone-dataset-DatasetNinja.tar?rlkey=az60mbn0ynq43xm5dn8v8pgon&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='LADD: Lacmus Drone Dataset', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/mersico/lacmus-drone-dataset-ladd-v40/download?datasetVersionNumber=3).