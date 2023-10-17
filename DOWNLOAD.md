Dataset **AI4Agriculture Grape Dataset** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/z/8/Zb/ritEmpbr3CuVJsTqgVkMT9a8nU9P6vu02SSzXXelsDxsw3gful2MNAs58y9czJvudWeqCaE2zDcTTlBJ5eey6B0Q8XYR4NF8WzOxGQIp8yJHTBlTn5j4APEG5GvA.tar)

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
