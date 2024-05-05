# ymsm_midterm2024_bringup_ros

## Usage

### 1. change dir

```bash
cd <workspacce_dir>/src
```

### 2. clone git repo
```bash
git clone https://github.com/miya-tnct/ymsm_controller_ros.git  ymsm_controller && \
git clone https://github.com/miya-tnct/ymsm_midterm2024_bringup_ros.git  ymsm_midterm2024_bringup && \
git clone https://github.com/miya-tnct/ymsm_midterm2024_localizer_ros.git  ymsm_midterm2024_localizer && \
git clone https://github.com/miya-tnct/ymsm_midterm2024_map_server_ros.git  ymsm_midterm2024_map_server && \
git clone https://github.com/miya-tnct/ymsm_midterm2024_planner_ros.git  ymsm_midterm2024_planner && \
git clone https://github.com/miya-tnct/ymsm_midterm2024_pole_finder_ros.git  ymsm_midterm2024_pole_finder
```

### 3. change dir
```bash
cd <workspacce_dir>
```
or

```bash
cd ..
```

### 4. build
```bash
catkin_make
```

### source
```bash
source devel/setup.bash
```

### 5. run
```bash
roslaunch ymsm_midterm2024_bringup.launch bringup param_file:=<your parameter file>
```