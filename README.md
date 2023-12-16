# ESP32_MPU6050_OLED
This is the source code for reading the accelarometer, gyroscope, and temperature sensor data then displaying them on an OLED <br>
The simutation of this sourcode is avaliable at :https://wokwi.com/projects/383981664359646209 <br>
The OLED is based on I2C with the below connection: <br>
### OLED_ESP
This is how the OLED is connected to the ESP32<br>
Make sure to check the address if you want to use I2C
<pre>OLED         ESP32  </pre>
<pre>SDA          21     </pre>
<pre>SCL          22    </pre>
<pre>VCC          VIN    </pre>
<pre>GND          GND    </pre>

### MPU6050_ESP32
If you want to use the I2C bus, then use below the conection as for the address, the librairy will handle it.
<pre>MPU6050       ESP32</pre>
<pre>SDA           21</pre>
<pre>SCL           22</pre>
<pre>VCC          VIN</pre>
<pre>GND          GND</pre>
