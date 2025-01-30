Dataset **Supervisely HRDA Plants Demo** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MTFfU3VwZXJ2aXNlbHkgSFJEQSBQbGFudHMgRGVtby9zdXBlcnZpc2VseS1ocmRhLXBsYW50cy1kZW1vLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIm12MjFaWDZoN0p2YzhpN2JlM3MwOUxkMkNtSkYyRU9yZTFBcFNEemZXY2c9In0=)

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