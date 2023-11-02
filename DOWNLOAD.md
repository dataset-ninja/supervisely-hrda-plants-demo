Dataset **Supervisely HRDA Plants Demo** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/N/5/XT/YgkEtGPZNJnoIWu9uSyX8AIGSwehXw8mjmsLOZpuuyz0maz9ScklR7RIQyvY7K75IZ7kNJWBR7maap4eBzcorviJr7irJS5Jt7XZZRaU2D8nrmuB2z9w7IuIAKCu.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Supervisely HRDA Plants Demo', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://supervisely.com/blog/train-a-model-with-62-labeled-images-hrda-semi-supervised/).