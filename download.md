---
layout: page
title: Download
permalink: /download
---
<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h1>Download VSXu</h1>
            </header>
            <ul class="actions horizontal">
                <li><a href="#" class="button" 
                onClick="document.getElementById('download_windows').style.display = 'block'; document.getElementById('download_linux').style.display = 'none';"
                >Windows</a></li>
                <li><a href="#" class="button" 
                onClick="document.getElementById('download_linux').style.display = 'block'; document.getElementById('download_linux').style.display = 'none';"
                >GNU/Linux</a></li>
            </ul>
        
            <p id="download_windows" style="display:none">
                <a href="#" onClick="document.getElementById('paypal').style.display = 'block';">Download for Windows 64-bit</a><br/>
                Contains VSXu Artiste and VSXu Player
            </p>
            
            <p id="download_linux" style="display:none">
                <a href="#" onClick="document.getElementById('paypal').style.display = 'block';">Download for GNU/Linux 64-bit</a><br/>
                Contains VSXu Artiste, VSXu Player and Server
            </p>
            <div style="display:none" id="paypal">
                <h2>Thanks for downloading!</h2>
                <h3>Please consider donating</h3>
                <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                    <input type="hidden" name="cmd" value="_s-xclick">
                    <input type="hidden" name="hosted_button_id" value="M8F8R67LFC3M2">
                    <input type="hidden" name="on0" value="Yes! I want to">
                    <table>
                      <tbody>
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
                        </td></tr>
                    </tbody></table>
                    <input type="hidden" name="currency_code" value="USD">
                    <input type="image" src="https://www.paypalobjects.com/en_US/SE/i/btn/btn_paynowCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
                    <img alt="" border="0" src="https://www.paypalobjects.com/sv_SE/i/scr/pixel.gif" width="1" height="1">
                </form>
            </div>
        </div>
    </section>
</div>
