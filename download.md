---
layout: page
title: Download
permalink: /download
main_menu: yes
---
<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h1>Download VSXu</h1>
            </header>
            <p>
            Current Version: {{ site.current_version }} Released {{ site.current_version_date }}
            </p>
            <ul class="actions horizontal">
                <li><a href="#" class="button" 
                onClick="
                    document.getElementById('download_windows').style.display = 'block'; 
                    document.getElementById('download_linux').style.display = 'none';
                    document.getElementById('download_source').style.display = 'none';
                    document.getElementById('paypal').style.display = 'none';
                "
                >Windows</a></li>
                <li><a href="#" class="button" 
                onClick="
                    document.getElementById('download_windows').style.display = 'none'; 
                    document.getElementById('download_linux').style.display = 'block';
                    document.getElementById('download_source').style.display = 'none';
                    document.getElementById('paypal').style.display = 'none';
                "
                >GNU/Linux</a></li>
                
                <li><a href="#" class="button" 
                onClick="
                    document.getElementById('download_windows').style.display = 'none'; 
                    document.getElementById('download_linux').style.display = 'none';
                    document.getElementById('download_source').style.display = 'block';
                    document.getElementById('paypal').style.display = 'block';
                "
                >Source Code</a></li>

            </ul>
        
            <p id="download_windows" style="display:none">
                <a href="#" onClick="document.getElementById('paypal').style.display = 'block';">Installer for Windows (64-bit)</a><br/>
                Contains VSXu Artiste and VSXu Player
            </p>
            
            <p id="download_linux" style="display:none">
                <a href="#" onClick="document.getElementById('paypal').style.display = 'block';">AppImage for GNU/Linux (64-bit)</a><br/>
                Contains VSXu Artiste, VSXu Player and Server.<br>
                <br>
                To run, set execution flag on the file and just run it. Most desktop environments understand this type of file
                so if you put it on your Desktop for instance - you can usually just double click it.
            </p>

            <p id="download_source" style="display:none">
                VSXu is written in C++ and hosted on GitHub.  
                <a href="https://github.com/vovoid/vsxu" target="_blank">Go to github (new window)</a><br>
                <br>
                VSXu is CMake-based.<br>
                This means you can use any editor, but in terms of IDE's we recommend either QtCreator or Visual Studio.<br>
                See the INSTALL file for more information.
            </p>

            <div style="display:none" id="paypal">
                <h2>Thanks for downloading!</h2>
                <h3>Donate / Follow</h3>
                <table>
                <tr>
                <td style="width:50%;">
                    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                        <input type="hidden" name="cmd" value="_s-xclick">
                        <input type="hidden" name="hosted_button_id" value="M8F8R67LFC3M2">
                        <input type="hidden" name="on0" value="Yes! I want to">
                        <select name="os0">
                            <option value="Donate Casual">Donate Casual $3,00 USD</option>
                            <option value="Donate Fair">Donate Fair $5,00 USD</option>
                            <option value="Donate Cute">Donate Cute $10,00 USD</option>
                            <option value="Donate Great">Donate Great $15,00 USD</option>
                            <option value="Donate Sweet">Donate Sweet $20,00 USD</option>
                            <option value="Donate Wow">Donate Wow $30,00 USD</option>
                            <option value="Donate Super">Donate Awesome $50,00 USD</option>
                            <option value="Donate Awesome">Donate Super Awesome $100,00 USD</option>
                        </select>
                        <input type="hidden" name="currency_code" value="USD">
                        <br>
                        <input type="image" src="https://www.paypalobjects.com/en_US/SE/i/btn/btn_paynowCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
                        <img alt="" border="0" src="https://www.paypalobjects.com/sv_SE/i/scr/pixel.gif" width="1" height="1">
                    </form>
                </td>
                <td style="width:50%">
                    <iframe id="twitter-widget-0" scrolling="no" frameborder="0" allowtransparency="true" class="twitter-follow-button twitter-follow-button-rendered" title="Twitter Follow Button" src="http://platform.twitter.com/widgets/follow_button.89bd237a86eeb0e8b1de842a4b88b09b.en.html#dnt=false&amp;id=twitter-widget-0&amp;lang=en&amp;screen_name=VSXu&amp;show_count=true&amp;show_screen_name=true&amp;size=l&amp;time=1490522543370" style="position: static; visibility: visible; width: 216px; height: 28px;" data-screen-name="VSXu"></iframe>
                    <br>
                    <br>
                    <iframe src="http://www.facebook.com/plugins/like.php?href=https%3A%2F%2Fwww.facebook.com%2Fpages%2FVovoid-VSXu%2F129044247131992&amp;send=false&amp;layout=standard&amp;width=450&amp;show_faces=false&amp;action=like&amp;colorscheme=dark&amp;font&amp;height=35" style="border:none;height:30px;width:100%"></iframe>
                 </td>
                 </tr>
                 </table>
            </div>
        </div>
    </section>
</div>
