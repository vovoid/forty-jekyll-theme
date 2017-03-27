---
layout: page-inner
title: Documentation - FAQ
permalink: /documentation/faq
---
<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <ul class="actions horizontal">
                <li>
                    <a href="/documentation" class="button">
                        About
                    </a>
                    <a href="/documentation/faq" class="button special">
                        FAQ
                    </a>
                    <a href="/documentation/vsxu-live" class="button">
                        Video - VSXu Live
                    </a>
                    <a href="/documentation/video-tutorials" class="button">
                        Video - Tutorials
                    </a>
                    <a href="/documentation/video-tutorials" class="button">
                        Changelog
                    </a>
                </li>
            </ul>
            
            <header class="major">
                <h1>
                    Frequently Asked Questions about VSXu
                </h1>
            </header>
            <p>
            Click on a question to view the answer.
            </p>
              
              
                      <h2 onclick="$('.question_fullscreen').show()" style="cursor:pointer">
                          Q: How do I run in fullscreen mode?
                      </h2>
                      <div class="question_fullscreen" style="padding-left:20px; display:none">
                          <p>
                            vsxu_player and vsxu_artiste accept command line arguemnts.<br>
                            So, you need to add -f to the command. And optionally -s [width]x[height] for screen resolution<br>
                            Try to use your existing screen resolution, that is always best.<br>
                            When hitting -f VSXu tries to detect your screen resolution but this doesn't always work...<br>
                            <br>
                            Here is an example on how to start VSXu Artiste in Fullscreen Full HD resolution:
                        </p>
                          <pre>vsxu_artiste -s 1920x1080 -f</pre>
                            or
                          <pre>vsxu_player -s 1920x1080 -f</pre>
                        <p>
                           If you run Windows, you can right-click the shortcut in the start menu and edit the command right there.
                            <br>
                            <br>
                            To view all available command line arguments, run this:
                          </p>
                              <pre>vsxu_artiste -h</pre>
                      </div>
              
                      <hr>
              
              
                      <h2 onclick="$('.question_audio').show()" style="cursor:pointer">
                          Q: VSXu is not reacting to sound!
                      </h2>
                      <div class="question_audio" style="padding-left:20px; display:none">
                          <p>
                              This depends on your Operating System.<br>
                            <br>
                        </p>
                            <h2>Windows</h2>
                        <p>
                              If you're on Windows, you have to set the recording settings properly.<br>
                            <br>
                            Why? VSXu works by recording Sound played through the Soundcard.<br>
                            <br>
                              It can be tricky, you have to right-click and show "disabled/hidden devices" to see the device.<br>
                              <br>
                              Try <a href="http://www.sevenforums.com/tutorials/20595-what-u-hear-recording-enable.html"><b>this guide</b></a>
                            - one of our users found this to be quite helpful.<br>
                        </p>
                        <h2>GNU/Linux</h2>
              
                        <p>
                            You should look for a program called <b>pavucontrol</b>.<br>
                            If you're on Ubuntu, you can just search for it in the software center.<br>
                            Or if you prefer command line:<br>
                        </p>
                        <pre>apt-get install pavucontrol</pre>
                        <p>
                            Once installed, you can set the recording settings for individual programs. If you start VSXu first
                            and pavucontrol second, VSXu should show up in pavucontrol and you can then select a sound
                            recording source for it.
                        </p>
                      </div>
              
                      <hr>
              
                      <h2 onclick="$('.question_randomizer').show()" style="cursor:pointer">
                          Q: How do I stop VSXu Player from switching between visuals all the time?
                      </h2>
                      <div class="question_randomizer" style="padding-left:20px; display:none">
                          <p>
                              Easy! Just hit the key "R" on your keyboard.<br>
                            <br>
                              Then if you want it enabled again - hit "R" again.<br>
                              The "R" key toggles the "randomizer" on and off.<br>
                              And... if you press the "F1" key you can see more keyboard shortcuts.<br>
                          </p>
                      </div>
              
              
              <hr>
              
                      <h2 onclick="$('.question_recording').show()" style="cursor:pointer">
                          Q: How do I record the output of VSXu?
                      </h2>
                      <div class="question_recording" style="padding-left:20px; display:none">
                          <h2>It's complicated...</h2>
                          <p>
                              First, you should know that VSXu isn't designed for nor intended as a rendering tool - it's designed
                              to explore and create real time graphics. Please think of it as such, and not a quick shortcut
                              to littering youtube with videos. If anything, such should only be teasers to show off what can
                              really be experienced by running the software "for real" on your own GPU.
                          </p>
                          <p>
                              If your goal is to create video material - we recommend <a href="http://www.blender.org/">Blender</a>.
                              It's probably easier to use, and will get you results quicker.
                          </p>
                          <p>
                              Secondly, Capturing real time graphics is hard on the computer - VSXu is best experienced  running at
                              60 Hz (Frames per second) and often at high resolutions (1080p or higher).
                              This is close to impossible to capture on video.<br>
                              <br>
                              For reference - an i7 with 4x SATA 3 SSD disks in raid can't cope with 1080p @60Hz and barely can do 720p @60Hz.
                          </p>
                          <p>
                              Thus our default stance is "don't" but of course there are situations where you want to post
                              your cool new stuff on youtube or vimeo or [insert random video streaming site here].
                          </p>
                          <h2>Quick list for the impatient</h2>
                          <ul>
                            <li>On windows there is <a href="http://www.fraps.com" target="_blank">FRAPS</a> that a lot of people use and we recommend</li>
                            <li>On GNU/Linux there is <a href="http://recordmydesktop.sourceforge.net/about.php" target="_blank">Recordmydesktop</a>
                                that we have used. Not as easy to use as fraps (need to use command line interface to get it working properly) but
                            still - much recommended.</li>
                            <li>If you can live with low framerate (i.e. you're recording for educational purposes - like we do when
                            we produce VSXu Live - you can use <a href="www.google.com/+/learnmore/hangouts/" target="_blank">Google Hangout</a> which
                            can stream contents of a window live to youtube and you will retain an editable copy afterwards.</li>
                            <li>There are also hardware solutions - the ones at <a href="http://www.avermedia.com/Product/ProductList.aspx?IID=7" target="_blank">Avermedia</a>
                                seems quite useful (we haven't tested them though).</li>
                          </ul>
                      </div>
              
              
              
              
              
              
                      <hr>
              
              
              
              
              
                      <h2 onclick="$('.question_mac').show()" style="cursor:pointer">
                          Q: Why is there no version for Mac OSX?
                      </h2>
                      <div class="question_mac" style="padding-left:20px; display:none">
                          <h2>
                          - Long story short: Because it is not worth it - costs too much effort (and money) to maintain one.<br>
                          </h2>
                          <p>
                            We get this question a lot.<br>
                            <br>
                            First, regardless of OS platform, when releasing software, it has to be tested properly. This is for your
                            sake as a user/customer, and it would be totally pointless - not to mention
                            rude - to deliver untested software. It would most likely crash all the time. This kind of testing
                            needs to be done on many levels, some things pretty regularly - and for that a virtualized environment has saved
                            time and we'd go so far as to say it's necesarry.<br>
                            <br>
              
                            So, in order to properly test VSXu on Windows and GNU/Linux - the same relatively cheap computer can be used (less than $1000). Development
                            can be done in virtualized environments as well. Nightly builds (yes, for Windows also!) take place on GNU/Linux running on very cheap (less than $200) hardware. <br>
                            <br>
                            But when it comes
                            to Apple - the story is vastly different. Let's review some facts.<br>
                          </p>
                          <h2>Apple hardware</h2>
                          <p>
                            Apple hardware is PC hardware. Same parts bought from intel as everyone else.
                            Thus there is no difference in hardware between "Mac and PC". The hardware is the same.
                            <br>
                            VSXu is designed for discrete graphics. That is - "AMD" or "nVidia" graphics chips.<br>
              
                            As of now (January 2016), only the top model of "Mac Book Pro"
                            and the "Mac Pro"  ship with discrete graphics.
                            All other PC:s from Apple ship with Intel HD graphics, including the iMac which used to have discrete graphics.
              
                            But Intel is cheaper, thus more profits for Apple.
              
                            Intel HD Graphics is fine for surfing the web and doing the most basic OpenGL things, but
                            it can not deliver up to our standards - which is running all visuals in VSXu in at least 1080p
                            at 60 frames per second. Also many macs have higher resolutions than that which will mean lower frame rates
                            (down to 10-20) which takes away all the fun from music visualization.
                            <i>So the market simply isn't there.</i>
                          </p>
                          <h2>OSX and its licensing</h2>
                          <p>
                            There are a couple of licensing problems with OSX which complicate things.<br>
                            Its EULA does not allow virtualization on anything other than Apple's own hardware.<br>
                            Thus, we have to go out of our way to buy Apple hardware without discrete graphics to even compile things!
              
                            Again - very different from both Windows and GNU/Linux which do not have these limitations.
                            Hampers development and makes it a big hurdle to even considering supporting OSX.
                          </p>
                          <h2>Conclusion</h2>
                          <p>
                            The development of VSXu is not for-profit so there's really not a budget, and since neither own any computers
                            from Apple (why would one want such limited hardware anyway?)
                            it would cost too much for us to go out of our way just to maintain a Mac version.<br>
                            <br>
                            And on top of everything else, we do not appreciate Apple's arrogance towards developers.
                            <br>
                          </p>
                          <h2>Might we recommend an alternative?</h2>
                          <p>
                              If you want VSXu running, cheaply - get or build a bleeding edge consumer PC with the latest desktop technology that Intel and Nvidia has to offer, and run GNU/Linux on it.<br>
                              <br>
                          </p>
                          <h2>Yet another alternative</h2>
                          <p>
                              Use "boot camp" to dual boot into GNU/Linux or Windows. (If you can live with a mobile-class GPU)
                          </p>
                          <h2>If you still think we should maintain a Mac version</h2>
                          <p>
                            You are always welcome to do just that - the code is Free / Open Source. We probably wont maintain your
                            commits though, you are on your own.
                          </p>
                      </div>
      </div>
  </section>
</div>
