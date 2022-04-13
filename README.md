# Dissertação-Medição georreferenciada de volumes e áreas exteriores com GNSS e LIDAR usando o ATLASCAR2
# Sobre
```
Jorge Silva
Dissertação de Mestrado em Engenharia Mecânica
Laboratório de Automação e Robótica(LAR)
Departamento de Engenharia Mecânica
Universidade de Aveiro
```
# Requesitos

* [ROS (Melodic)](http://wiki.ros.org/noetic/Installation/Ubuntu)

* Gazebo:

```
sudo apt install ros-melodic-gazebo-*
```

* [Creating a workspace for catkin](http://wiki.ros.org/catkin/Tutorials/create_a_workspace)

* Git:

```
sudo apt install git
```

# Setup

Selecionar a pasta catkin_ws/src e correr:

```
git clone https://github.com/jmfs200695/GeorefVolume.git
```
# Rosdep

Para instalar todos os packages necessários execute o seguinte comando:
```
rosdep install --from-paths src --ignore-src -r -y
```

# Run simulation
```
cd catkin_ws
```
```
catkin_make
```
```
source devel/setup.bash
```
```
roslaunch simulation world.launch
```
# Mais informações
[Blog](https://jmfs200695.wixsite.com/tese165)

[My GitHub](https://github.com/jmfs200695)
