# Install
```
cd autodistill-florence-2
pip3 install -e .
python3 setup.py build
python3 setup.py install

# ImportError: cannot import name 'EncoderDecoderCache' from 'transformers' (/usr/local/lib/python3.10/dist-packages/transformers/__init__.py)
pip install peft==0.10.0
```
