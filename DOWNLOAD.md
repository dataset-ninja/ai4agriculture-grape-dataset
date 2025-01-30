Dataset **AI4Agriculture Grape Dataset** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzEzODVfQUk0QWdyaWN1bHR1cmUgR3JhcGUgRGF0YXNldC9haTRhZ3JpY3VsdHVyZS1ncmFwZS1kYXRhc2V0LURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogInhjVnZPR2c5aW1PbTZpTXlkeHdxQk82UzZ4Vnh3VWg3QjBxK1dOYWJQSDQ9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='AI4Agriculture Grape Dataset', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be downloaded here:

- [ai4agriculture_2020.zip](https://zenodo.org/record/5660081/files/ai4agriculture_2020.zip?download=1)
