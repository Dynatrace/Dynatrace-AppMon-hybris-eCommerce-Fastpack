<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>hybris eCommerce Fastpack</title>
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
                <h1>hybris eCommerce Fastpack</h1>
    <p>
<a href="attachments_156631071_4_hybris-fastpack-2.0-public.dtp">hybris-fastpack-2.0-public.dtp</a>    </p>
    <div class="section-2"  id="74383375_hybriseCommerceFastpack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/74383375/hybris-performance_management.png" alt="images_community/download/attachments/74383375/hybris-performance_management.png" class="confluence-embedded-image" />
        The dynaTrace FastPack for hybris contains sensors, a template system profile and dashboards for the hybris accelerator eCommerce platform. If you are using dynaTrace UEM you will also get conversion and visitor tagging.    </p>
    </div>
    <div class="section-2"  id="74383375_hybriseCommerceFastpack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">hybris accelerator fastpack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2.1.0, hybris 4.5+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
5.5, 5.6 (fastpack 2.0 only)    </p>
    <p>
6.0 (fastpack 2.1)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Reinhard Brandstaedter    </p>
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
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Community Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Fastpack Download contains:    </p>
<ul class=" "><li class=" ">    <p>
Dashboards (see below)    </p>
</li><li class=" ">    <p>
Template Profile    </p>
</li></ul>    <p>
<a href="attachments_156631071_4_hybris-fastpack-2.0-public.dtp">fastpack 2.0</a> (dynaTrace 5.x)<br/><a href="attachments_174754271_4_hybris-fastpack-2.1.dtp">fastpack 2.1</a> (dynaTrace 6)    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="74383375_hybriseCommerceFastpack-Dashboards"  >
        <h2>Dashboards</h2>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.48.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.48.png" class="" />
            </p>
    <p>
<strong class=" ">Request Balancing</strong><br/>Displays the distribution of requests among webservers and application servers. When you are running a hybris cluster make sure that all requests are equally balanced on both web and application servers. This dashboard also shows the java thread count and CPU utilitzation of individual cluster nodes. Also shown is the busy workers for apache webservers and their transfer rate.    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.26.02.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.26.02.png" class="" />
            </p>
    <p>
<strong class=" ">End User Experience Metrics</strong><br/>End User Performance Overview provides insight on visits, 3rd party content load time and End User Action breakdown.    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.30.29.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.30.29.png" class="" />
            </p>
    <p>
<strong class=" ">Page Impressions and Webrequest Performance</strong>    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.25.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.25.png" class="" />
            </p>
    <p>
<strong class=" ">SOLR Search Engine</strong><br/>Displays the response time and number of SOLR search queries that are made. Also shows the average number of calls to SOLR per transactions (too many unnecessary calls per transaction are usually a hint that there is an architectural problem)    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.28.28.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.28.28.png" class="" />
            </p>
    <p>
<strong class=" ">Java Garbage Collection Health</strong><br/>The Garbage Collection Impact rate on transaction shows how affected transactions are by garbage collection runs. this measure should be as close to 100% as possible, meaning that garbage collection does not negatively affect your users performance. Also shown are individual GC metrics for the hybris application servers.    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.39.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.27.39.png" class="" />
            </p>
    <p>
<strong class=" ">Java Memory Pools</strong><br/>An Overview of the different Java memory pools of you hybris cluster. Helps identifying if your memory sizing is OK and distributed equally (e.g. if single nodes are using more memory due to background jobs)    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.28.12.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-02-06_at_20.28.12.png" class="" />
            </p>
    <p>
<strong class=" ">Database Utilization</strong><br/>Shows how many database statements are beeing issued and the overall time spent for database calls. Also displays the top database statements beeing executed. Long running database statements or too many unnecessary database statements are often a root cause for low performance or slow server side response time.    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-08-22_at_12.46.22.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-08-22_at_12.46.22.png" class="" />
            </p>
    <p>
<strong class=" ">Cron Jobs</strong><br/>Shows the invocations of different cron Jobs and on which node they are executed    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-08-22_at_13.12.34.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-08-22_at_13.12.34.png" class="" />
            </p>
    <p>
<strong class=" ">Web Request Distribution</strong><br/>Shows the serverside response time distribution of all web requests. Color indicators are used for fast requests (green - faster than 1s), slower (yellow - between 1s and 3s), slow (orange between 3s and 5s) and very slow requests (red - slower thatn 5s). This dashboard allows to get a very quick view on how the system is performing or if there are any changes or problems that impact the response time.    </p>
    <p>
            <img src="images_community/download/attachments/74383375/Screen_Shot_2014-08-28_at_12.59.00.png" alt="images_community/download/attachments/74383375/Screen_Shot_2014-08-28_at_12.59.00.png" class="" />
            </p>
    <p>
<strong class=" ">Page Class Performance</strong><br/>Different page handler classes are detected automatically and analyzed. This dashboard lists all detected page classes and displays their average server response time. Also shown is a trending of the last 6 hours, lat day and last 7 days for the average response time and error rate.    </p>
    </div>
    <div class="section-2"  id="74383375_hybriseCommerceFastpack-Installation"  >
        <h2>Installation</h2>
    <p>
Just download and import the FastPack on your dynaTrace Server (see <a href="https://community/display/DOCDT40/Plugin+Management">Plugin Management</a>).<br/>Either configure your hybris agents' name to start with &quot;hybris&quot; so they will be mapped to the system profile contained in the fastpack, or copy the profile to match your application and modify the contained agent groups and mappings.<br/>To use UEM you will need to match your webserver's agent name to the &quot;webserver&quot; agentgroup or adopt accordingly. Also make sure to enable the UEM and webserver sensor in the agent configuration (disabled by default).    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
