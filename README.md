# dense_mapping

### Introduction：
Used a monocular camera carried by a drone to establish a map for navigation based on SLAM, and design a trajectory planning algorithm to achieve the optimal trajectory flight of the drone in an indoor scene.

### Contribution：
Achieved depth estimation in monocular SLAM algorithm to generate dense point clouds, utilized OctoMap in ROS to convert point clouds to 3D grid maps that could be used for trajectory planning, solved the problem that sparse point cloud maps could not be used for navigation.

<a href="https://kns.cnki.net/kcms2/article/abstract?v=2arE9-pF_S2W_bYWMQKYUKOFge-euAYWXI-oVfZVH-cmZo6wten5fUBxW4cge_xFCajCZy_ARXVTyLiaaGoF_xtyyiy5vwGZeveP7kerhqE7ckbfoM_vWJTqHp5hw1i50tZYc6bZF_xSqOvWKbYGJlT5Fe1riybfeyUxWeTLG5u6fXOrIHQpLhv2InZkE12d&uniplatform=NZKPT&language=CHS" title="paper">A Voxel Map Reconstruction System of Quadrotor Aircraft Based on Monocular Vision</a> published

<table style="width:100%; border-collapse: collapse;">
  <tr>
    <td style="padding:5px; text-align:center; vertical-align:middle;"><strong>Scene 1</strong><br></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure11.png" alt="图片1" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure12.png" alt="图片2" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure13.png" alt="图片3" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure14.png" alt="图片4" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure15.png" alt="图片5" style="max-width:100%; height:auto;"></td>
    
  </tr>
  <tr>
    <td style="padding:5px; text-align:center; vertical-align:middle;"><strong>Scene 2</strong><br></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure21.png" alt="图片7" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure22.png" alt="图片8" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure23.png" alt="图片9" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure24.png" alt="图片10" style="max-width:100%; height:auto;"></td>
    <td style="padding:5px; text-align:center;"><img src="https://github.com/Burger-Z/Dense_mapping/blob/main/Figures/figure25.png" alt="图片11" style="max-width:100%; height:auto;"></td>
  </tr>
</table>
