Press `C` and `W/A/S/D/Q/E`to rotate.  
Press `R` to rotate camera and recording, screenshots are saved in record file dirctory.  
![r](img/r.gif)  
Change attribution in [scene.py](scene.py)  
`LOOK_AT` is the target you look at when you are pressing `C` to rotate or recording.  
`INTERVAL_TIME` is the interval time between two frames when recording.  

Use [gif_generater.py](gif_generater.py) to generate your record result.
![gif](img/mario.gif)


# Mario Theme
![mario](img/mario.jpg)
# a 24 years old student
![inm](img/inm.jpg)
# Saint Diana(unfinished)
Inspired By [Dina](https://t.bilibili.com/520981951078003843?tab=2)
![dina](img/diana.jpg)

# <a name="title">Taichi Voxel Challenge</a>

<p align="center">
<img src="demo.jpg" width="75%"></img>
</p>

> Figure: result of `python3 example6.py`. Please replace the image above (`demo.jpg`) with yours, so that other people can immediately see your results :-)

We invite you to create your voxel artwork, by putting your [Taichi](https://github.com/taichi-dev/taichi) code in `main.py`!

Rules:

+ You can only import two modules: `taichi` (`pip` installation guide below) and `scene.py` (in the repo).
+ The code in `main.py` cannot exceed 99 lines. Each line cannot exceed 120 characters.

The available APIs are:

+ `scene = Scene(voxel_edges, exposure)`
+ `scene.set_voxel(voxel_id, material, color)`
+ `material, color = scene.get_voxel(voxel_id)`
+ `scene.set_floor(height, color)`
+ `scene.set_directional_light(dir, noise, color)`
+ `scene.set_background_color(color)`

Remember to call `scene.finish()` at last.

**Taichi Lang documentation:** https://docs.taichi-lang.org/

**Modifying files other than `main.py` is not allowed.**


## Installation

Make sure your `pip` is up-to-date:

```bash
pip3 install pip --upgrade
```

Assume you have a Python 3 environment, simply run:

```bash
pip3 install -r requirements.txt
```

to install the dependencies of the voxel renderer.

## Quickstart

```sh
python3 example1.py  # example2/3/.../7/8.py
```

Mouse and keyboard interface:

+ Drag with your left mouse button to rotate the camera.
+ Press `W/A/S/D/Q/E` to move the camera.
+ Press `P` to save a screenshot.

## More examples

<a href="https://github.com/raybobo/taichi-voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/city.jpg" width="45%"></img></a>  <a href="https://github.com/victoriacity/voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/city2.jpg" width="45%"></img></a> 
<a href="https://github.com/yuanming-hu/voxel-art"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/tree2.jpg" width="45%"></img></a> <a href="https://github.com/neozhaoliang/voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/desktop.jpg" width="45%"></img></a> 
<a href="https://github.com/maajor/maajor-voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/earring_girl.jpg" width="45%"></img></a>  <a href="https://github.com/rexwangcc/taichi-voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/pika.jpg" width="45%"></img></a> 
<a href="https://github.com/houkensjtu/qbao_voxel_art"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/yinyang.jpg" width="45%"></img></a>  <a href="https://github.com/ltt1598/voxel-challenge"><img src="https://github.com/taichi-dev/public_files/blob/master/voxel-challenge/lang.jpg" width="45%"></img></a> 

## Show your artwork 

Please put your artwork at the beginning of this README file. Replacing the `demo.jpg` file with your creation will do the job.
