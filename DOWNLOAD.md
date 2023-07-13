Please visit dataset [homepage](https://zenodo.org/record/5660081#.ZGUTO3bMIuW) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='AI4Agriculture Grape Dataset', dst_path='~/dtools/datasets/AI4Agriculture Grape Dataset.tar')
```
