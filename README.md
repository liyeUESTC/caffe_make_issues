# caffe_make_issues
## caffe编译问题汇总


(1)运行python文件训练模型时，会出现“ImportError: No module named _caffe”

问题原因：问题原因是没有编译caffe的python接口，导致运行python代码中涉及到的caffe接口，会报错。


 
- `make clean`

- `make all -j8`   # 编译caffe

- `make pycaffe`  # 编译python接口 

- `make test -j8`  # 测试

- `make runtest -j8`  # 测试
 
