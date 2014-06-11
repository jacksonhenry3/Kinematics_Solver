<p>
	Kinematics area a simple section of Neutonian mechanics covered in high school. It essential involves figuring out which of 4 equations to apply in which order based on what information you need and what information you have about the motion of an object. The four equations are 
</p>
<table style="width:80%; margin:20px auto;text-align:center;">
	<tr>
		<td>
			d = v<sub>i</sub> t + <sup>1</sup>/<sub>2</sub> a t<sup>2</sup>
		</td>
		<td>
			v<sub>f</sub><sup>2</sup> = v<sub>i</sub><sup>2</sup> + 2 a d
		</td>
	</tr>
	<tr>
		<td>
			v<sub>f</sub> = v<sub>i</sub> + a t
		</td>
		<td>
			d = (v<sub>f</sub> + v<sub>i</sub>) <sup>1</sup>/<sub>2</sub> t
		</td>
	</tr>
</table>
<p>
	where d is distance, t is time, v<sub>i</sub> is the initial velocity, v<sub>f</sub> is the final velocity and a is the acceleration. This program brute forces the problems. I manually solved every equation for every variable and input the symbolic solution. After that when the user inputs the known variables it essential check what equations are applicable to solve for the desired variable and then calculates it using the general solution i found.
</p>
you can read more about kinematics <a href = 'http://www.physicsclassroom.com/class/1DKin/Lesson-6/Kinematic-Equations'>here</a>
<hr>
written in <a href = 'https://www.python.org/'>Python</a> 2.7.3<br>

Dependencies:
	<ul>
		<li>
			<a href = 'http://www.wxpython.org/'>wxPython</a>
		</li>
	</ul>
