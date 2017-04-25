---
id: 8
title: HTPC setup
date: 2010-04-03T18:52:52+00:00
author: admin
layout: post
category:
  - coding
tags:
  - HTPC
  - Mac
  - MacMini
  - Plex
  - TV
---
My <a title="nan" href="http://www.flickr.com/photos/8397489@N04/3869887134/" target="_blank">nan</a> had a PVR before I did. This quickly spurred my &#8211; impulse buy &#8211; instincts, and our house soon owned a <a title="TopfieldPVR" href="http://www.itopfield.com.au/product-detail.asp?idx=145" target="_blank">Topfield PVR</a>.  Over time the inability to export, the flakiness of the timer recording, the guide and corrupted recordings wore down the gloss of digital TV.  Of course having possums re-arrange our aerial to face directly away from the tower didn&#8217;t help.

Whilst on holidays in Amsterdam, we were out at a friends house for dinner. After being suitably wowed by a 6 year old&#8217;s hovering helicopter, the hosts HTPC setup was introduced.

I saw <a title="Plex" href="http://www.plexapp.com/" target="_blank">plex</a> and I was sold. On our return I visited my friendly <a title="Mac1" href="http://www.mac1.com.au/pages/index.php" target="_blank">Mac1</a> store and took the plunge into replacing our familiar &#8211; but sub optimal &#8211; TV setup.  Now our media (music, photo&#8217;s, online content, movies, TV) are presented via a sleek form factor <a title="MacMini" href="http://www.apple.com/au/macmini/" target="_blank">mac mini</a>, through [plex](http://www.plexapp.com/ "Plex") or <a title="eyeTV" href="http://www.elgato.com" target="_blank">eyeTV</a>, with nothing but a simple, minimalistic, <a title="appleRemote" href="http://en.wikipedia.org/wiki/Apple_Remote" target="_blank">apple remote</a> to drive the whole shebang.

<div id='gallery-1' class='gallery galleryid-8 gallery-columns-3 gallery-size-thumbnail'>
  <dl class='gallery-item'>
    <dt class='gallery-icon landscape'>
      <a href='http://adamrumbold.com/?attachment_id=23'><img width="150" height="150" src="http://adamrumbold.com/wp-content/uploads/2010/04/screen-150x150.jpg" class="attachment-thumbnail size-thumbnail" alt="" aria-describedby="gallery-1-23" /></a>
    </dt>
    
    <dd class='wp-caption-text gallery-caption' id='gallery-1-23'>
      Plex TV media library
    </dd>
  </dl>
  
  <dl class='gallery-item'>
    <dt class='gallery-icon landscape'>
      <a href='http://adamrumbold.com/?attachment_id=25'><img width="150" height="150" src="http://adamrumbold.com/wp-content/uploads/2010/04/screenMusic-150x150.jpg" class="attachment-thumbnail size-thumbnail" alt="" aria-describedby="gallery-1-25" /></a>
    </dt>
    
    <dd class='wp-caption-text gallery-caption' id='gallery-1-25'>
      Plex iTunes media library
    </dd>
  </dl>
  
  <dl class='gallery-item'>
    <dt class='gallery-icon landscape'>
      <a href='http://adamrumbold.com/?attachment_id=26'><img width="150" height="150" src="http://adamrumbold.com/wp-content/uploads/2010/04/screenEyeTV-150x150.jpg" class="attachment-thumbnail size-thumbnail" alt="" aria-describedby="gallery-1-26" /></a>
    </dt>
    
    <dd class='wp-caption-text gallery-caption' id='gallery-1-26'>
      EyeTV on screen display
    </dd>
  </dl>
  
  <br style="clear: both" />
</div>

The main benefits:

  * TV commercials are <a title="commercial skip" href="http://code.google.com/p/etv-comskip/" target="_blank">automatically detected</a> (mostly) and skipped upon playback
  * TV Shows and Movies get their metadata populated for slick browsing and storage (<a title="PlexMedia" href="http://www.plexapp.com/images/imgMov2001-w900.jpg" target="_self">eg</a>).  Recorded TV/movies (or for that matter ripped content) have any crap stripped out before becoming part of our Plex based media library (which is only going to get <a title="AlexandriaPlex" href="http://elan.plexapp.com/2010/03/24/the-road-to-alexandria-part-1-introduction/" target="_blank">better</a>)
  * Recordings can be scheduled from anywhere in the house via one of our iPhones without affecting anyone&#8217;s viewing. If the downstairs TV is too loud and I&#8217;m in bed \*I\* can turn it down. If we are out and forgot to record something there&#8217;s an eyeTV _<a title="eyeTVApp" href="http://www.elgato.com/elgato/na/mainmenu/products/software/EyeTV-app.en.html" target="_blank">app</a> for that_
  * 6 buttons on the apple remote is enough to do (almost) everything. Anything too difficult can be handled by VNC or SSH
  * Music can be played, or photo&#8217;s browsed, from my iMac in the study. Handy given the iMac is my workhorse for Aperture and iTunes.

It took some time but it now passes the &#8216;girl friend&#8217; test &#8211; especially after our reception was fixed.

The key elements of the technical setup are:

  * <a title="Plex" href="http://plexapp.com" target="_blank">Plex</a> &#8211; a **free** fork of XBMC, pretty and functional UI, nice integration with the Mac
  * The Apple Remote doesn&#8217;t help without <a title="RemoteBuddy" href="http://www.iospirit.com/products/remotebuddy/" target="_blank">RemoteBuddy</a> to glue all the actions together. RemoteBuddy, through it&#8217;s intuitive menu, gives you: access into almost all applications, options within applications, system preferences, sleep/shutdown, system volume etc.
  * A 2Tb external hard drive tucked away to store all the TV Shows and Movies we are slowly amassing.
  * The elgato <a title="EyeTVDiversity" href="http://www.elgato.com/elgato/int/mainmenu/products/tuner/diversity08/product1.en.html" target="_blank">eyeTV diversity</a> &#8211; HD dual tuner
  * An &#8216;application&#8217; link from Plex back to eyeTV.  Generally holding the menu button on the remote takes you to RemoteBuddy&#8217;s application menu &#8211; from which you can do anything &#8211; but Plex uses the held menu button for it&#8217;s context menu.
  * An <a title="iceTV" href="http://www.icetv.com.au/" target="_blank">iceTV</a> subscription for the on screen display TV guide (whilst costly &#8211; it does contain all the EPG data &#8211; something our PVR often missed)
  * ..and small things &#8211; like auto login and auto start of applications

Best of all, the setup will continue to evolve and improve as PLEX, eyeTV and ancillary bits are updated.  Already there are a number of great plugins &#8211; TED, XKCD, flickr, YouTube <a title="PlexPlugIns" href="http://elan.plexapp.com/category/plug-ins/" target="_blank">etc</a>.

Of course it&#8217;s not all smooth sailing:

  * the cursor sometimes gets moved into the top right of screen forcing the menu bar to display,
  * the eyeTV schedules can&#8217;t easily (without a keyboard/mouse) be extended to cater for shows running over,
  * reduced remote buttons &#8211; can lead to multiple presses for common tasks

But overall, I&#8217;m chuffed, and have the slick aluminium apple remote arriving next week (ony $25 on ebay!).  It&#8217;s even prompted me to sort our my album art and metadata within my iTunes library