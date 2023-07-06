Dataset **Animals (kapzz)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/5/O/KE/rmUrFVQCChTEmtpm3FFJOY9XAPln5Rl5yZKIy4p7uQ3XqIXwRFgHIwz45YFkb9X6MtQOx7wmteJVw0y2gnsqxEzEz8O7oKtcO5MIjiIAUL5Kzkns8eqcRX2AxPUJ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Animals (kapzz)', dst_path='~/dtools/datasets/Animals (kapzz).tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/graduation-nnzal/animals-kapzz/dataset/2/download/coco)