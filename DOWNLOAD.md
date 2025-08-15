Dataset **Supervisely HRDA Plants Demo** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjgxMV9TdXBlcnZpc2VseSBIUkRBIFBsYW50cyBEZW1vL3N1cGVydmlzZWx5LWhyZGEtcGxhbnRzLWRlbW8tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiVVlBTCtvUkZnSjV6KzlkV2R2eVF4Tm1zYUtLNUg5RjEwSHloNFJLdWE0UT0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22supervisely-hrda-plants-demo-DatasetNinja.tar%22)

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