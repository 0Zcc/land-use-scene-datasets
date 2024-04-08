# land-use-scene-datasets


-----


We provide a set of urban land use scene classification datasets, which includes sample land use scene classification data from four cities in China, and can be used for urban land use classification studies, especially cross-domain classification studies.

You can [click here](https://drive.google.com/drive/folders/1cjPkFuqMti1yf_q2-4Evps14SmNfapGi?usp=sharing) to get the datasets.

## 1. 数据集详细信息
该数据集的属性信息如下表所示：

|Fuzhou|Quanzhou|Zhengzhou|Wuhan|
|------|-----|---|---|---|
|Sensors|GF-2|GF-7|WorldView|Pléiades|
|Spatial resolution(m) | 0.8 | 0.8 | 0.3 | 0.65|
|Scene size (pixels) | 300x300|300x300|600x600|300x300|
|Residential (samples) | 200 | 400 | 723 | 100|
|Industrial and warehouses|156|227|501|100|
|Commercial|144|128|724|67|
|Transportation |171 | 250 | 600 | 100|
|Water    | 143 | 104 | 384 | 48|
|Green spaceand entertainment | 186|191|387|53|

## 2. 土地利用场景图片示例
下图展示了该数据集的示例图片。

## 3. 数据集文件树

```
filetree
├── /land-use-scene-datasets/
|  ├── /Fz300/
│  │  ├── iamges
│  │  |  ├── Residential
│  │  |  └── Industrial and warehouses
│  │  |  └── Commercial
│  │  |  └── Transportation
│  │  |  └── Water
│  │  |  └── Green spaceand entertainment
|  ├── /Qz300/
│  │  ├── iamges
│  │  |  ├── Residential
│  │  |  └── Industrial and warehouses
│  │  |  └── Commercial
│  │  |  └── Transportation
│  │  |  └── Water
│  │  |  └── Green spaceand entertainment
|  ├── /Zz300/
│  │  ├── iamges
│  │  |  ├── Residential
│  │  |  └── Industrial and warehouses
│  │  |  └── Commercial
│  │  |  └── Transportation
│  │  |  └── Water
│  │  |  └── Green spaceand entertainment
|  ├── /Wh300/
│  │  ├── iamges
│  │  |  ├── Residential
│  │  |  └── Industrial and warehouses
│  │  |  └── Commercial
│  │  |  └── Transportation
│  │  |  └── Water
│  │  |  └── Green spaceand entertainment
