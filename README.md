# drupal-logger
## Event logging and content versioning module for drupal
drupal-logger is a project undertaken by fundamental research group at IIT,Bombay which focuses on  advancing the event log module in drupal which was developed earlier by Cipix Internet.
This module logs specific events. The events are saved in the database and can
be viewed on the page admin/reports/events. Furthermore, a views integration is
provided in which you can relate for instance a node to its events. You could
use this to display the total number of views, or the number of times that the
node has been modified and by which users.

Currently, the following events are supported3333333:
* User authentication (login/logout/request password)
* Node operations (CRUD)
* User operations (CRUD)
* Menu operations (custom menu's and menu items CUD operations)
* Taxonomy operations (vocabulary and term CUD operations)


drupal-logger empowers the users to more advanced features based on the core event log module. Apart from the above features, four new features have been added:
Namely,

* Clear log messages button
* Ability to log to a file instead of a database.
* Backup event_log database content.
* Notify Illegal access to authorized user.

Since data visualization is imperative and indispensable to business and data analytics, drupal-logger comes with four pellucid visualizations.
Namely,

* Log Data Visualization
* Log data Visualization User
  

