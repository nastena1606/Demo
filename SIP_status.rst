VoIP network performance statistics
***********************************
==========
SIP status
==========
You can view statistics about the SIP services you provide for the past 24 hours. This helps you to detect changes in your network (e.g. a burst of registrations) and respond to them accordingly.

The statistics includes information about calls and registrations. There are four metrics:

• the number of active calls;
• the number of calls per second;
• the number of registered UAs;
• the number of registrations per second.


They are available as the **SIP status** widget on the **Dashboard** page. 

![SIP_status_main](https://user-images.githubusercontent.com/60600800/73686237-48fe7900-46d0-11ea-823b-bb879f41896d.png)"

To measure statistics, enable the **Metrics.StorageEnabled** option on the Configuration server. The measurement frequency is 15 minutes. The date and time of the last measurements are shown at the top of the widget.

The SIP status widget has both collapsed and extended views. In the **collapsed** view, only the last measured data is shown. 
 
![SIP_status_collapsed](https://user-images.githubusercontent.com/60600800/73686310-67fd0b00-46d0-11ea-9b40-7a81ff8f0be3.png)


The **extended** view also includes charts where you can see statistics for an exact timestamp during the last 24 hours. There are two charts: the left-hand one shows statistics for calls and the right-hand chart – for registrations.

![SIP_status_extend](https://user-images.githubusercontent.com/60600800/73686327-6f241900-46d0-11ea-9bd6-b445ccc332d0.png)


The figures below the charts show the metrics’ values for an exact timestamp. The timestamp is placed between the charts. When you highlight a specific time on one of the charts, the same time is highlighted on the second chart and the values below the charts change. 
   




