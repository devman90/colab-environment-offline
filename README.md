# colab-environment-offline
For offline install for colab environment(python3.7)

Some packages are not included in this repository because of the file size issues.
(Refer below descriptions.)

You should download these large files from pypi manually.

842M torch-1.10.0-cp37-cp37m-manylinux1_x86_64.whl
467M tensorflow-2.7.0-cp37-cp37m-manylinux2010_x86_64.whl
249M mkl-2019.0-py2.py3-none-manylinux1_x86_64.whl
137M xgboost-0.90-py2.py3-none-manylinux1_x86_64.whl

You can install the packages by this command.
`pip install --no-index --find-links=./packages -r requirements.txt`

