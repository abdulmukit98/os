# os
edu key <br>
YJDNW-RX2PQ-HH77B-KVM6X-YDWWB 


### bash command shortcut 
    /home/abdul/.bashrc
    alias gnome-open='xdg-open'
    this will define xdg-open as gnome-open

    add cd Desktop, it will goto desktop at terminal start

### after linux
    gnome-tweek-tool
    dash to dock (gnome-shell-extension)
    audacious
    vol shortcut
    preload
    gparted
    sublime text
    octave
    krita
    filezilla
    indicator-stickynotes
    bleachbit
    tlp
    thermald
    gimp
    pdftk

### powershell alias
    get-alias  >  list of alias 
    create powershell profile
        New-Item –Path $Profile –Type File –Force
    New-Alias abc ls
    cd e:
    function edge ([string]$arg1) 
    {
        cd 'C:\Program Files (x86)\Microsoft\Edge\Application\/'
        .\msedge.exe $arg1
        cd e:
    }
    
### powershell if-else

	#with parameter
	function audacious([string]$arg1)
	{
		if($arg1)
		{
			& 'C:\Program Files (x86)\Audacious\bin\audacious.exe' $arg1
		}
		else
		{
			& 'C:\Program Files (x86)\Audacious\bin\audacious.exe' 'E:\Music\'
		}
	}


### after windows
* vol shortcut<br>
* [mixer ding remove](https://www.youtube.com/watch?v=TC5q4vRplCs)<br>
* [files can safely be deleted](https://thegeekpage.com/files-can-safely-delete-windows-10-save-space/#:~:text=It%20is%20completely%20safe%20delete%20the%20contents%20of,keyboard.%20A%20dialog%20box%20will%20ask%20for%20permission.)<br>
* [update download loc](https://www.technig.com/delete-windows-10-update-files/#:~:text=1%20Open%20your%20File%20Explorer%20%28%20This%20PC,files%20and%20temporary%20files.%20...%20More%20items...%20)<br>
* [halt update](https://www.youtube.com/watch?v=QmtGJ5UhlME)<br>
* evince<br>
* mp3 juices<br>
* z-library<br>
* flaticon<br>
* malwarebits<br>
* [camtasia](https://drive.google.com/drive/folders/1YFHrhBFyOHRx-qcuxdN46YYASGmXjHHz)<br>
* [realtek](https://drive.google.com/drive/folders/1YFHrhBFyOHRx-qcuxdN46YYASGmXjHHz)<br>
  [process](https://youtu.be/Sy3rH0s3-Ek)<br>
* nomacs<br>
* Foxit <br>
* edge default Bing 

### mojave file icon
    yaru-> org.gnome.Nautilus.png
    256*256 for list icons
    48*48 for dock icons
    nothing else needed
    
    move custom pack to /usr/share/icons
    not /home/.icons
    else it show little bit mistake

### exclusive task
* [ubuntu freez](https://askubuntu.com/questions/4408/what-should-i-do-when-ubuntu-freezes)
* [tryshift uninstallation](https://support.tryshift.com/kb/article/194-how-to-uninstall-shift/)
* extract-deb


### alsamixer 
for both headphone and speaker active <br>
* [initialize](https://itectec.com/ubuntu/ubuntu-how-to-switch-between-headphones-and-speakers-without-unplugging-headphones/)<br>
* [alsa property](https://wiki.ubuntu.com/Audio/Alsamixer)
* press m for mute/unmute
* pulseaudio -k (kill)
* pulseaudio --start

###  pdftk
	pdftk   file1.pdf   file2.pdf   file3.pdf    cat output newfile.pdf
	pdftk A=first.pdf B=second.pdf cat A1-5 B1 A6-end output out.pdf

### create powershell profile
	new-item -path $profile -type file -force


https://www.microsoft.com/en-us/p/app/9p2b8mcsvpln <br>
