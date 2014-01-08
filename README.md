unity3d-google-site-gadget
==========================

# Description #
This gadget allow you to insert Unity3d webplayer to google services like google site.
This gadget generate the same html content as Unity3d does when you click "build webplayer" by default.
It works with http as well as https protocol.

# Step by Step guide #
* Upload .unity3d build to your site
  * Open your site and in the top right **More** menu select **Manage site**
  *  Select **Attachments** int the left bar
  * Upload your **xxxxxx.unity3d** file here 
  * Save somehwere link to this file
    ![link to unity3d build](https://storage7.static.itmages.ru/i/14/0108/h_1389168347_7568744_39436dd31e.png "link to unity3d build")
* Add unity3d webplayer to your page
  * Create new or open existing page on your google site
  * **Insert -> More gadget ...**
  * In opened window select **Add gadget by URL**
  * Insert following link to the input box
    `https://github.com/nicloay/unity3d-google-site-gadget/releases/download/version_1.0/gadget.xml`
  * Insert link (which you stored before) to the **WebPlayer *.unity3d Url (required)** field
    e.g. in my case `https://sites.google.com/site/nicloay/2DWinterPack.unity3d?attredirects=0&d=1`
  * change **width** and **height** if you need
  * Click **Ok** and save your page.

# Known issues #
Sometime preview doesn't work for the first time when you click on it but if you close preview and open it again, it should show your webplayer.
I havn't faced any problem on the final page, if you will find any problem, please let me know.
