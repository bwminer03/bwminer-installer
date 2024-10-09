# bwminer-installer
New script for HiveOS to install newwer drivers for AMD from this repo.

This is a different script to install newer ROCm drivers on HiveOS, by downloading the releases from github. I did not want to use the same install script as hive-os, that way I assure there are no issues.<br />
<font color="red"><b>THIS IS A EXPERIMENTAL RELEASE, DOWNLOADING AND INSTALLING IS FIXED BUT LOOKING FOR TESTERS.</b></font>

<h2><u>How to Use:</u></h2><br />
Current install Method:<br /><br />
First you Must Shutdown Your Rig, and remove USB Drive (if that is how you are running your rig, if not there is another method.)<br />
Using a Second Computer you can download the script, and mount your USB drive to your Operating System. <i>It should show 2 drives mounted one labeled "Hive" and the other is the size of the USB Drive".</i><br /><br />

After you have successfully copied the script to <code>"hive/sbin"</code> it is time to plug your USB Drive back in and power up your miner. After your rig is started we need to exit the miner screen, if you have a miner running. which will then show you the shell. From the shell we will run <code>cd hive/sbin/</code><br /><br />

Next we have to use chmod to allow the file to work so we will run <code> chmod +x bwminer-installer</code> after that we can return back to where we started using <code>cd..</code> twice. after that you should be able to simply run <code>bwminer-installer</code>


<h2>Alternative Methods:</h2><br />

SSH into your rig, then run the same commands.<br />
<code>cd /hive/sbin/</code><br />
<code> wget </code><br />
<i>This will directly download the script to your directory.</i><br />
<code>chmod +x bwminer-installer</code><br />
<code>cd..</code>x2<br />
<code>bwminer-installer</code>

