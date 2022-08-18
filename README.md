# ceph-benchmark

How to run

```
sudo yum install librados2-devel
sudo g++ -std=c++11 -g -c ceph-client.cpp -o ceph-client.o
sudo g++ -std=c++11 -g ceph-client.o -lrados -o ceph-client
sudo ./ceph-client >> test.log
```
