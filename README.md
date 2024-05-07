 [comment]: <> (# MSOC-S-IKF)

 <h1 align="center"> MSOC-S-IKF 测试版 (仅供个人学习记录用)
  </h1>


[comment]: <> (  <h2 align="center">PAPER</h2>)
  <h3 align="center">
  <a href="https://ieeexplore.ieee.org/document/10129794">Paper</a> 
  | <a href="https://github.com/zhuqingzhang/MSOC-S-IKF">Original Github Page</a>
  | <a href="https://github.com/arclab-hku/Event_based_VO-VIO-SLAM?tab=readme-ov-file#Dataset-for-stereo-evio">ESVIO Dataset</a>
  </h3>
  <div align="center"></div>


~~~
  cm
  
  #测试Euroc数据集
  roslaunch ov_rimsckf pgeneva_ros_eth.launch

  evo_ape bag ***.bag /cpy_uav/viconros/odometry /envio_nesl/odom -va -p
~~~
