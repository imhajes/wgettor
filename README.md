#### WGETTOR

###### A torsocks DDOS tool for Debian Linux Distros:   python + wget + tor

Requirements:
 <ul>
  <li>Debian Linux Distro</li>
  <li>python3</li>
  <li>netstat/net-tools</li>
  <li>tor/torsocks</li>
</ul>

usage:
<pre>
  <code>
python wgettor.py -t &lt;target URL or IP&gt; -n &lt;number of requests to make on target&gt;
sudo python -t https://somesite.com -n 5000
  </code>
</pre>

Ensure that tor is running as a service on local host at 127.0.0.1:9050
prior to running.
<br>
You can replace or add user-agents inside the set_user_agents() method
<br><br>
<img src="https://github.com/rootVIII/wgettor/blob/master/web_server_log_screenshot.png" alt="example1" height="675" width="950"><hr>
<br><br>
This was developed on Ubuntu 16.04.4 LTS.
<hr>
<b>Author: James Loye Colley  09JUN2019</b>
