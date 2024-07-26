# GNSS-Denied Geolocalization of UAVs Day and Night Using Terrain-Weighted Constraint Optimization
![UAV_IMG](https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/GIF.gif)
Unmanned Aerial Vehicles (UAVs) are increasingly being used across various industries, from agriculture to the military. To perform these complex tasks, UAVs rely on GNSS for positioning and navigation. However, GNSS is susceptible to spoofing and environmental interference, making it crucial for UAVs to infer their position during GNSS denial. 
We have developed a visual positioning system that combines image matching, visual odometry, and terrain constraints. This system utilizes publicly available satellite maps and DEM data from the internet, does not require altimeters or IMUs, is immune to signal interference, does not require loop closure correction, and does not accumulate errors, allowing for re-localization after positioning failure.
Furthermore, the system is adaptable to terrain variations, image tilt and rotation, changes in altitude, and complex flight paths. It does not require the camera to be oriented strictly downward and exhibits robustness to seasonal and lighting changes. We used data from 20 complex scenarios, including plains, hilly terrain, and urban and rural areas, with multiple flight paths, viewpoints, seasonal weather conditions, and thermal infrared variations, to thoroughly validate the system's robustness and accuracy. Experimental results indicate that our system successfully achieved high-altitude, long-distance, large-scale, and high-precision GNSS-denied positioning during both day and night under pure visual conditions. The positioning accuracy is comparable to GPS, making it a strong complement to GNSS in GNSS-denied scenarios.
***
The video of our experimental results is as follows: 
<table>
      <tr>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(a).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(b).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(c).png" ></td> 
            <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(d).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(e).png" ></td> 
      </tr >
      <tr >
	    <td><a href="https://www.bilibili.com/video/BV1kxeDeoE8S/">bilibili</a></td>
	    <td><a href="https://youtu.be/XvOESC_gK2A">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1yHeDe8Ei5/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1yHeDe8ESg/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1E4421S7zN/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1j4421S7aA/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
	</tr>
      <table>
      <tr>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(f).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(g).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(h).png" ></td> 
            <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(i).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(j).png" ></td> 
      </tr >
      <tr >
	    <td><a href="https://www.bilibili.com/video/BV1cS421d7C5/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1RZ421N7Pw/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1Yw4m1k7ex/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1AM4m117c2/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV18x4y147kb/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
	</tr>
        <table>
      <tr>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(k).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(l).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(m).png" ></td> 
            <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(n).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(o).png" ></td>
      </tr >
      <tr >
	    <td><a href="https://www.bilibili.com/video/BV1Hn4y1f7Mc/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV19y411i7z7/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1ar421K7ik/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV151421t79s/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1BS421X7Jy/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
	</tr>
        <table>
      <tr>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(p).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(q).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(r).png" ></td> 
            <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(s).png" ></td>
	    <td colspan="2"><img src="https://github.com/YFS90/GNSS-Denied-UAV-Geolocalization/blob/main/Img/fig9(t).png" ></td>
      </tr >
      <tr >
	    <td><a href="https://www.bilibili.com/video/BV1AW421R7iw/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1XH4y1c7kw/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV1K142187NU/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV13b421J7m8/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
            <td><a href="https://www.bilibili.com/video/BV19f421v7Ni/">bilibili</a></td>
	    <td><a href="https://www.bilibili.com">YouTube</a></td>
	</tr>
</table>


