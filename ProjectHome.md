<img src='http://rudix.org/images/rudix.png' align='right'>

Rudix is a collection of pre-built Unix software delivered as packages for Mac OS X (10.8, 10.7 and 10.6). <b>This site is the repository for Mac OS X 10.7 (Lion).</b>

To bootstrap Rudix, open Terminal.app and type:<br>
<pre><code>curl -O https://raw.github.com/rudix-mac/package-manager/master/rudix.py
sudo python rudix.py install rudix
</code></pre>

You will be probably asked for administrator password.<br>
<br>
Now you can use Rudix package manager to install other packages.<br>
<pre><code>sudo rudix install pip
Downloading rudix.googlecode.com/files/pip-1.1-0.pkg
######################################################################## 100,0%
installer: Package name is pip 1.1
installer: Installing at base path /
installer: The install was successful.
All done
</code></pre>

<pre><code>sudo rudix remove pip
Forgot package 'org.rudix.pkg.pip' on '/'.
</code></pre>

For more information, please visit <a href='http://rudix.org/'>Rudix main site</a>.