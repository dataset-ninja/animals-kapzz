Dataset **Animals (kapzz)** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/C/v/f7/Ti7Mt9KS7FYSIXOey6Zo4bZiAqJRZysYO3jvN2NoRXn4OEFDpgsMORR8fJya7tqW0pmPT23j55b0Cnyd1SN9IpAZn5JFbtGa7wlExEOhJGEmEWqmZlhSVd7TVLay.tar)

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