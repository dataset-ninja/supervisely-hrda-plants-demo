Please visit dataset [homepage](https://www.ipb.uni-bonn.de/data/sugarbeets2016/) to download the data. 

Afterward, you have the option to download it in the universal [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format) by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Supervisely HRDA Plants Demo', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.