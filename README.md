# User Status and Opportune Moment Dataset
This is a dataset about the opportuness of a smartphone user's status for interventions. In a one-week in-the-wild user study, 11 pairs of smartphone users used an app, called MyButler [1], in which each user can specify and share their current status with their partner. Their partner could choose whether to send a notification for their mobile instant message or not based on the shared status. 

## `mybutler_dataset.csv`
- `Status`: the current status set by each user (`Participant ID`)
- `Participant ID`: the user who set the current status (`Status`)
- `Date Time (Hour)`: the hour of the day (0-23) when the `Action` was selected by the partner
- `Action`: the action ('alert_now' or 'dont_alert') selected by the user's partner 

## References
[1] Hyunsung Cho, Jinyoung Oh, Juho Kim, and Sung-Ju Lee. 2020. I Share, You Care: Private Status Sharing and Sender-Controlled Notifications in Mobile Instant Messaging. <i>Proc. ACM Hum.-Comput. Interact.</i> 4, CSCW1, Article 034 (May 2020), 25 pages. DOI:https://doi.org/10.1145/3392839
