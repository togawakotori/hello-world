--------------------------
**留言板**

**置頂**: 完結撒花  

2018/04/15: 發佈Cannon

2018/04/12：發佈了基於列的Matrix Multiplication版本

2018/04/12: https://stackoverflow.com/questions/5104847/mpi-bcast-a-dynamic-2d-array

2018/04/10: 編譯含靜態鏈接庫的文件
          
            mpicc -c MyMPI.c
            ar -rc MyMPI.a MyMPI.o
            mpicc matrix.c -o matrix ./MyMPI.a

2018/04/08: 如何進行矩陣乘法？

2018/04/08: **特報** Octave竟然出了圖形界面

2018/04/06: 發佈了過濾2,3,5,7倍數的程序(prime7b.c)。

2018/04/05: 完成另一種方法編寫去除偶數的方法(prime2b.c)

2018/04/03: **特報** Juno + Mircosoft Azure Network: 擺脫電腦 在IPAD上運行JUPYTER NOTEBOOK

2018/04/02: 修正了Comm_size==1时的严重bug; 发布了过滤2、3、5倍数的版本(prime5.c)

2018/??/??: 如何建立免密的SSH Connection: 首先在两台电脑上建立名字一样的用户, 然后交换生成的公钥到对方authorized_keys中.

------------------------------

Sharing a Folder

          gedit /etc/exports
          
          /mirror \*(rw,sync)

-------------------------------

How to compile?

          mpicc \*.c -o \*

          mpiexec -n 16 ./*


------------------------------

Principe de cpi.c:

Intergrate(4/(1+x^2),x,0,1)==pi

------------------------------
More Details:

http://blog.csdn.net/bendanban/article/details/9136755

http://blog.sina.cn/dpool/blog/s/blog_4e8bda0c0102vqfx.html
