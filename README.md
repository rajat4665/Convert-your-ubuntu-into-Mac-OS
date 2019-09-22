<img class="alignnone size-full wp-image-163" src="https://getpython.files.wordpress.com/2019/09/maxresdefault.jpg" alt="maxresdefault.jpg" width="1280" height="720" />

Hi readers, are you guys using ubuntu? , have you guys bored by using the same user interface ? then this post for you. In this post I am gonna show you how you can coustomise your ubuntu interface in just few steps and make it like Mac os. So without wating anymore time let's dive in.
<h3>Step 1: Dwonload all required files form this <a href="https://drive.google.com/file/d/1ObDZn6e-4Zrv1CRJZR4MC3RzF2oPQ4ze/view" target="_blank" rel="noopener">link</a></h3>
<h3>Step 2: Install gnome tweak tool by the following command</h3>
<pre>sudo apt-get install -y gnome-tweak-tool</pre>
<h3>step 3: Install chrome gnome shell by this command</h3>
<pre>sudo apt-get install -y chrome-gnome-shell</pre>
<h3>Step 4: open firefox/chrome and go to this website "https://extensions.gnome.org/"</h3>
Here search user-theme in gnome extention click on that and see toggle on-off button , turn it On and a popup appear for install extention click on install

<img class="alignnone size-full wp-image-156" src="https://getpython.files.wordpress.com/2019/09/screenshot-from-2019-09-23-03-49-42.png" alt="Screenshot from 2019-09-23 03-49-42" width="1295" height="448" />
<h3>Step 5: Extract all files that you download from step1</h3>
<ol>
	<li>Now go to your home and press ctl+h to display hidden folders</li>
	<li>Now create a folder name .icons in this directory and paste two folder in the ,icons folder ( folder 1 name = "El_Capitan_CursorsMODNew" folder 2 name = "MacOSX" )</li>
	<li>Now create a folder name .theme in your home directory and paste folder named "Sierra-light"</li>
</ol>
<h3>Step 6: Now use tweak for real action!!!</h3>
<ol>
	<li>First open tweak from apps and I recommed you to take a screenshots off default settigs in the case of restore it will help us.</li>
	<li>now go to application section uder theme click on it and you will see a dropdown at the bottom click on sierra-light and it will change User interface immedeately.</li>
	<li>simmilarlly go to Cursor , icon, shell setion select El_Capitan_CursorsMODNew, MacOSX respectively and Sierra-light</li>
</ol>
<h3>Step 7: Now time to tweak shell theme</h3>
<ul>
	<li>Extract  this file XO.for.Dash.to.PANEL.tar.xz
<ul>
	<li>go to the fonts folder move all Fonts in to this directory ~/.local/share/fonts if this directory not exists than create new one</li>
</ul>
</li>
	<li>Extarct  this file XO.for.Dash.to.DOCK.tar.xz
<ul>
	<li>open this dirctory open it again and copy directory name gnome-shell</li>
	<li>now paste this directory in .themes/MacOS_HS folder</li>
	<li>now copy activities.svg file from /.themes/Sierra-light/gnome-shell/assets/activities.svg and paste into this directory/.themes/MacOS_HS/gnome-shell/assets</li>
	<li>copy this css " i have copied this from .themes/Sierra-light/gnome-shell/gnome-shell.css" and paste it in
/.themes/MacOS_HS/gnome-shell/gnome-shell.css
<ul>
	<li>#this is css copy and paste as mentioned</li>
	<li>#panel #panelActivities.panel-button > * {
background-image: url("assets/activities.svg");
background-position: center top;
width: 24px;
height: 24px;
background-color: transparent !important;
background-gradient-direction: none !important;
border: none;
color: transparent;
}</li>
</ul>
</li>
</ul>
</li>
</ul>
<h3>Step 8: Now time to enable dash to doc and blur effect to Gnome shell</h3>
go to "https://extensions.gnome.org" and search "Dash to Dock", when it will open click on On toggle button it will install ASAP

<img class="alignnone size-full wp-image-159" src="https://getpython.files.wordpress.com/2019/09/screenshot-from-2019-09-23-04-11-27.png" alt="Screenshot from 2019-09-23 04-11-27" width="1205" height="452" />

go to "https://extensions.gnome.org" and search Blyr

when it will open click on On toggle button it will install ASAP

<img class="alignnone size-full wp-image-160" src="https://getpython.files.wordpress.com/2019/09/screenshot-from-2019-09-23-04-14-14.png" alt="Screenshot from 2019-09-23 04-14-14" width="1197" height="408" />
<h3></h3>
<h3>Step 9:Now open XO.for.Dash.to.DOCK this directory and perform some commands</h3>
"XO.for.Dash.to.DOCK/DOCK Settings/Gnome Version 3.30 - 3.32.md" open it and run all command in your terminal one by one.
<h3>Step 10: Time to work on lock screen</h3>
Go to this link "https://www.gnome-look.org/p/1207015/" and go to its files setcion download files according to your Unbuntu version
and extract it.

now open this folder and locate install.sh file , now open terminal here and paste two following commands.
<ul>
	<li>sudo chmod +x install.sh</li>
	<li>./install.sh</li>
</ul>
now go to the folder where have extracted "HighSierra-wallpapers" this folder , now open it right click on wallpaper which you want to set as background.
<ul>
	<li>now right click on in and select set as wallpaper</li>
	<li>now again right click on same image and you will see script option in this menu click on and select setAsWallpaper option.</li>
</ul>
<h3>Step 11: customise top bar</h3>
<ul>
	<li>go to this link "https://extensions.gnome.org/extension/104/netspeed/" and turn it ON.</li>
	<li>open tweak and go to the top bar , here enable battery percentage</li>
</ul>
<img class="alignnone size-full wp-image-161" src="https://getpython.files.wordpress.com/2019/09/screenshot-from-2019-09-23-04-23-11.png" alt="Screenshot from 2019-09-23 04-23-11" width="1203" height="406" />
<h3>Step 12: Configure fonts settings</h3>
make cahnges as mentioned in this screenshots

<img class="alignnone size-full wp-image-162" src="https://getpython.files.wordpress.com/2019/09/screenshot-from-2019-09-23-04-26-03.png" alt="Screenshot from 2019-09-23 04-26-03" width="1360" height="531" />
<h1></h1>
<h1>I Hope you guys have followed all the steps and it worked for you, thankyou for reading this article</h1>
 
