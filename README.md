# JavaScript-Meteor-CMS

Every program starts from data, data defines everything. So please start from VO (see lib/vos).
The main trick in data binding. I use https://viewmodel.org + VO. And there is no business logic in view. 
View just signalize that something is happen and all magic and data processing is made inside "commands".
Special tool for "commands" - Comman and Q-deferred.
Then see \client\views\components\menu