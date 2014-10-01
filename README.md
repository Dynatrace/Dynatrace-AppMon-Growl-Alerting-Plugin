<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Growl Alerting Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Growl Alerting Plugin</h1>
    <div class="section-2"  id="123634699_GrowlAlertingPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/123634699/icon.png" alt="images_community/download/attachments/123634699/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
This plugin allows <strong class=" ">sending dynaTrace incidents to Growl over the network</strong>.<br/>Growl Action plugin works with :    </p>
<ul class=" "><li class=" ">    <p>
Growl on Mac (http:/www.growl.info)    </p>
</li><li class=" ">    <p>
<a href="http://www.growlforwindows.com/gfw/">Growl on Windows</a>    </p>
</li><li class=" ">    <p>
<a href="http://mattn.github.io/growl-for-linux/">Growl on Linux</a>    </p>
</li><li class=" ">    <p>
<a href="http://snarl.fullphat.net/">Snarl on Windows</a>    </p>
</li></ul>    <p>
NB: from Growl you can even forward notifications to:    </p>
<ul class=" "><li class=" ">    <p>
<a href="http://blog.growlforwindows.com/2010/10/toasty-notifications-for-windows-phone.html">Toasty on Windows Phone</a>    </p>
</li><li class=" ">    <p>
<a href="http://www.prowlapp.com/">Prowl on  iOS</a>    </p>
</li><li class=" ">    <p>
<a href="https://play.google.com/store/apps/details?id=com.growlforandroid.client&amp;hl=en">Growl on Android</a>    </p>
</li></ul>    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Growl Alerting Plugin</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
5+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Laurent Izac (laurent.izac@compuware.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Plugin binary : <a href="attachments_123896085_1_com.dynatrace.diagnostics.plugins.growl_1.0.1.jar">com.dynatrace.diagnostics.plugins.growl_1.0.1.jar</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="123634699_GrowlAlertingPlugin-Installation"  >
        <h2>Installation</h2>
<ul class=" "><li class=" ">    <p>
On the dynaTrace server side, import the plugin jar file and activate the plugin (see <a href="https://community/display/DOCDT55/Plugin+Management">Plugin Management</a>).    </p>
</li></ul>    <p>
            <img src="images_community/download/attachments/123634699/dt_growl_plugin_install.png" alt="images_community/download/attachments/123634699/dt_growl_plugin_install.png" class="confluence-embedded-image" />
            </p>
<ul class=" "><li class=" ">    <p>
Then, you need to add the Growl Action Plugin in the 'Extended Actions' of each of the incidents you want to generate Growl alerts for.    </p>
</li></ul>    <p>
            <img src="images_community/download/attachments/123634699/dt_growl_plugin_config.png" alt="images_community/download/attachments/123634699/dt_growl_plugin_config.png" class="confluence-embedded-image" />
            </p>
    </div>
    <div class="section-2"  id="123634699_GrowlAlertingPlugin-Usage"  >
        <h2>Usage</h2>
    <p>
In Growl's settings, you can configure how you want to display different severities:    </p>
    <p>
            <img src="images_community/download/attachments/123634699/growl_application_settings.png" alt="images_community/download/attachments/123634699/growl_application_settings.png" class="confluence-embedded-image" />
            </p>
    <p>
Sample notifications (click to enlarge):<br/>            <img src="images_community/download/attachments/123634699/live_toasts.png" alt="images_community/download/attachments/123634699/live_toasts.png" class="" />
            </p>
    <p>
            <img src="images_community/download/attachments/123634699/sample_notifications_using_iphone_style.png" alt="images_community/download/attachments/123634699/sample_notifications_using_iphone_style.png" class="" />
            </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
