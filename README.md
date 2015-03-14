Volume is a Panel Applet that puts a popup volume control in your panel. It is also a Mixer Application. It supports ALSA natively as of version 008. (for OSS and Alsa-OSS compatibility please use Volume-007 or older.)

Requires Python 2.3 and the python alsaaudio module which you can get [http://sourceforge.net/projects/pyalsaaudio here].

![http://rox-volume.googlecode.com/files/volume.png](http://rox-volume.googlecode.com/files/volume.png)

![http://rox-volume.googlecode.com/files/mixer.png](http://rox-volume.googlecode.com/files/mixer.png)

#Releases#

009 (2006-08-06)

  * Theme updates.

008 (2006-01-16)

  * Converted from OSS to ALSA interface.
  * Requires !PyAlsaAudio module.

007 (2005-10-12)

  * Options now editable from the !AppMenu.
  * New Icon

006 (2004-05-22)

  * Input from Cyrille Mars: mouse scroll-wheel on Panel icon changes volume without clicking.
  * Input from Jonatan Liljedahl: option to show a progress bar on the Panel indicating the current volume setting (Options to show/hide the icon and/or progress bar)
  * Italian translation from Yuri Bongiorno.
  * Resizes with the Panel properly.
  * Launch the Mixer from the popup menu

005 (2004-04-20)

  * Figured out how to save/restore the state of the lock/mute/rec checkboxes.
  * I think I have the whole recsrc thing worked out.
  * Made the checkbox labels translatable.

004 (2004-04-18)

  * Factored out the !VolumeControl widget and used in both Volume and Mixer.
  * Lots of configurable things via masks to !VolumeControl()
  * Applet control range is now 0-100 instead of 0-1 and has finer steppings.
  * Applet follows panel orientation now.
  * Separate options for Mixer
  * Option to hide/show each channel (still can't rename them)
  * Option to show values on Mixer sliders like applet does.
  * Translation support

003

  * Wrote a real Mixer app to replace the gnome-volume-control wrapper. UI is a straight rip of gnome-volume-control (for now at least). Needs some polish, but it works.
  * Fixed a small bug reported by Antiphon with Sawfish (popup slider was being positioned wrong)

002

  * Added options dialog and settings for mixer device (e.g. /dev/mixer) and the channel to control (e.g. PCM or Master volume)
  * Changed the popup positioning to always be at the top of the panel and centered (?) on the icon. Still need to handle Left, Right and Top panels.
  * Fixed a small bug in findrox.py.

To Do

  * beep after setting the volume
  * make it pop down when clicking elsewhere, like a menu does and the gnome mixer applet does (anyone know a good way to do this?)

Share and enjoy!
