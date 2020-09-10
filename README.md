## Volkscocoapi
### Known Issues
- this repo is based on pycocotools, so the inputs have to follow COCO format.
- pred format: [{'image_id': XX, 'bbox': [x, y, w, h], 'score': X, 'category_id': X }, ...]
- target format: {'info': {},
                  'licenses': [],
                  'images': [
                     {'file_name': X,
                      'height': X,
                      'width': X,
                      'id': X
                     },
                     ...
                  ],
                  'annotations':[
                     {'segmentation': [],
                      'area': X,
                      'iscrowd': 0 or 1,
                      'image_id': X,
                      'bbox': [x, y w, h],
                      'category_id': X,
                      'id': X,
                      },
                      ...
                  ],
                  'categories':[
                     {'id': X,
                      'name': X,
                      'supercategory': X,
                     },
                     ...
                  ]
                 }

## Installation
Currently, you could install by run
```shell
pip install "git+"

```

## Contact

This repository is currently maintained by Chenhao Wang ([@C-H-Wong](http://github.com/C-H-Wong))

## Credits
We got and modified much code from [cocoapi](https://github.com/cocodataset/cocoapi), thanks to [COCO](https://github.com/cocodataset).
