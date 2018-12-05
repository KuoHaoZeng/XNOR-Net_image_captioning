## Warning
It's an ongoing project. The result isn't good right now.

## Usage 


#### 1. Clone the repositories
```bash
$ git clone https://github.com/pdollar/coco.git
$ cd coco/PythonAPI/
$ make
$ python setup.py build
$ python setup.py install
$ cd ../../
$ git clone https://github.com/yunjey/pytorch-tutorial.git
$ cd pytorch-tutorial/tutorials/03-advanced/image_captioning/
```

#### 2. Download the dataset

```bash
$ pip install -r requirements.txt
$ chmod +x download.sh
$ ./download.sh
```

#### 3. Preprocessing

```bash
$ python build_vocab.py   
$ python resize.py
```

#### 4. Train the model

```bash
$ python train_bin.py    
```

#### 5. Test the model 

```bash
$ python sample_bin.py --image='png/example.png'
```

<br>

## TODO

- [ ] ONNX implementation
- [ ] TVM implementation

<br>

## Acknowledge
Specially thank [Yunjey Choi](https://github.com/yunjey) for making the [image captioning tutorial](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning) for PyTorch public. Also thank [jiecaoyu](https://github.com/jiecaoyu) for making the [XNOR-Net](https://github.com/jiecaoyu/XNOR-Net-PyTorch) for PyTorch public.
