CrossFTP Client
-----------------
CrossFTP Client is an excellent FTP client. CrossFTP Pro is a FTP client supporting FTPS, FXP, WebDav, Sun Cloud Storage and Amazon S3. CrossFTP uses a two-pane interface so that the novice user can master in minutes. 

Official website: http://www.crossftp.com
Copyright (C) 2005-2010 CrossFTP Software

System Requirements:
-----------------
Java Runtime Environment 1.5.0 (JRE) or later is required. JRE 1.6 is recommended, you can download it at http://www.java.com

Mac OS X users: your OS already comes with a Java runtime so you are ready.

CrossFTP Client and Server installation guide: 
-----------------
 - System requirement: Sun java 1.5+
 - This guide contains how to run CrossFTP through a), Java Web Start, b), Command line, c), Web browser, d), Deployment CrossFTP in your Web Server.
 - For the normal end users, it is recommend to run CrossFTP through a) Java Web Start.

a) Java Web Start
  1), Run CrossFTP client:
      Double click on crossftp.jnlp, and CrossFTP client will automatically be downloaded and installed.
  2), Run CrossFTP server:
      Double click on crossftpserver.jnlp, and CrossFTP server will automatically be downloaded and installed.

That's all for normal end users. Advanced users can read the followings for advanced installations.

b) Command line
  1), For windows user:
      Please go to the CrossFTP directory first. 
      i), To run the CrossFTP Client:
          >run_client.bat

      ii), To run the CrossFTP Server:
          >run_server.bat

  2) For Mac/Linux/Unix user:
     Please go to the CrossFTP directory first.
     i), To run the CrossFTP Client:
        >chmod +x run_client.sh
        >./run_client.sh

     ii), To runt the CrossFTP Server:
        >chmod +x run_server.sh
        >./run_server.sh

CrossFTP client's command line parameter usage: start_client.sh [-layoutMode
      layoutMode] [-n] [-protocol protocol] [-host host] [-proxyHost proxyHost]
      [-user user] [-proxyUser proxyUser] [-port port] [-h] [-account account]
      [-proxyDomain proxyDomain] [-load queue_file] [-jnlp_server
      jnlp_server_url] [-showToolbar showToolbar] [-showMenu showMenu]
      [-remotePath remotePath] [-passive passive] [-pass pass] [-proxyPass
      proxyPass] [-key key] [-jnlp_client jnlp_client_url] [-proxyPort
      proxyPort] [-proxyType proxyType]
-account,--account <account>                   FTP account name in FTP
                                               protocol, or the Windows Domain name in WebDav protocol
-h,--help                                      Show command line options
-host,--host <host>                            FTP host name
-jnlp_client,--jnlp_client <jnlp_client_url>   Client's jnlp
-jnlp_server,--jnlp_server <jnlp_server_url>   Server's jnlp
-key,--key <key>                               License Key
-layoutMode,--layoutMode <layoutMode>          Layout mode of the
                                               application (full or mini)
-load,--load <queue_file>                      [Pro only] Load the queue
                                               file and start transfer
-n,--no_restore                                Do not show queue restore
                                               dialog
-pass,--pass <pass>                            FTP password
-passive,--passive <passive>                   FTP Passive mode (true or
                                               false)
-port,--port <port>                            FTP port
-protocol,--protocol <protocol>                Protocol type (FTP,
                                               FTPS/Implicit, FTPS/SSL, FTPS/TLS, SFTP/SSH, WebDav, WebDav/HTTPS, S3, or
                                               S3/HTTPS)
-proxyDomain,--proxyDomain <proxyDomain>       HTTP proxy's Windows
                                               domain
-proxyHost,--proxyHost <proxyHost>             Proxy host
-proxyPass,--proxyPass <proxyPass>             Proxy password
-proxyPort,--proxyPort <proxyPort>             Proxy port
-proxyType,--proxyType <proxyType>             Proxy type (HTTP, SOCK4,
                                               SOCK5, FTP_OPEN, FTP_SITE)
-proxyUser,--proxyUser <proxyUser>             Proxy user
-remotePath,--remotePath <remotePath>          Remote path
-showMenu,--showMenu <showMenu>                Display menu or not(true
                                               or false)
-showToolbar,--showToolbar <showToolbar>       Display toolbar or
                                               not(true or false)
-user,--user <user>                            FTP user name


c) Web Browser (CrossFTP client only)
Open web.htm in your favorite web browser, and CrossFTP will launch just inside your web browser as a Java Applet.

d) Deploy CrossFTP in your internal web server:
If you want to establish an Intranet Java Web Start/Applet environment for CrossFTP Client and Server:
  1), Please extract this installation package on your Intranet's http server. Let's say the extracted directory's http path is "pathToYourCrossFTPRoot"
  2), Modify the crossftp.jnlp file, change the original base URL address in line: codebase="http://www.crossftp.com/" to the crossftp.jnlp's base URL on your http server. For example, codebase="pathToYourCrossFTPRoot"
  3), Modify the crossftpserver.jnlp file in the same way as crossftp.jnlp
  4), Congratulations! Now you can Java Web Start CrossFTP at http://yourSite/pathToYourServerRoot/crossftp.jnlp, or visit the Web CrossFTP at http://yourSite/pathToYourCrossFTPRoot/web.htm
  5), If you want to customize Web CrossFTP Pro for your customers, such as the initial FTP site, proxy, key, etc., please use our Web Wizard to customize the CrossFTP client at: http://www.crossftp.com/webWizard.htm
  6), If you want to customize Java Web Start JNLP for the CrossFTP Pro, please send email to support@crossftp.com to get more helps.
