# NOTIONPY
NOTIONPY uses notion api to add data to dataset



## Quickstart
Note:
Need the latest version of NOTIONPY requires Python 3.5 or greater.
- Get your token from [notion my-integrations](https://www.notion.so/my-integrations)
- Create the dataset in notion, and share the current dataset with my-integration 
<img src="https://github.com/wuchangsheng951/NOTIONPY/blob/main/share_example_invite.png" width="440">


## install
```
pip install nopynotion
```

## Usage

```
from nopynotion import NOPY
#initialize the NOPY instance
no = NOPY(token,datasetID)

# update the value
no.add_col_value({'iou':'33',"Name":'hul2u','data':'233s2'})

```
