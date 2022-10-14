# ***Generating a multi-resolution network using UMD campus as an example***
## ***How to download a free map file from OpenStreetMap?***
Before the offical introduction, we first introduce a concept called GNMS. General Travel Network Format Specification(GNMS) is a product of Zephyr Foundation, which aims to advance the field through flexible and efficient support, education, guidance, encouragement, and incubation.
In this berif introduction, we will shown you how to generate a multi-resolution network tamplate by what tools, and use other two tools called path4gmns and DLSIM to realize some basic transportation modeling and simulation fuction in this template. To generate a multi-resolution network tamplate, the first tool you need is a python package called OSM2GMNS, which is is an open-source python package which can help users easily convert networks from OpenStreetMap to .csv files with standard GMNS format for visualization, traffic simulation and planning purpose. For more information, please check  [OSM2GMNS](https://github.com/asu-trans-ai-lab/OSM2GMNS). You can either install it via pip :
```python
pip install osm2gmns
```
Or you can install this package inside your python IDIE, take Pycharm as an example (shown as follow), you can go to->Files->Settings->Python interpreter, and you can install any packages in the right-side window. (http://github.com/yourname/your-repository/raw/master/images-folder/1.png)

