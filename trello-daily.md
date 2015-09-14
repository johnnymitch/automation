# How to setup and test a daily Trello feed (via Zapier)

![](http://jmitch.me/github/trello.jpg)

## Setup
- Open Zapier: https://zapier.com
- Trigger App = **Trello**
- Action App = **Trello**
- Trigger = **New Notification**
- Action = **Create new card**
- Accounts = **Choose your own account**
- Fiter = **Data Card Due** + **Exists**
- Board = **Your board** (e.g. "John - Daily")
- List = **Your list** (e.g. "To do")
- Name = **Data Card Name** > {{5233331__data__card__name}}
- Description = **Data Text** & **Data Card URL** > {{5232994__data__text}} and {{5233573__data__card__url}}
- Member = **Yourself** (e.g. "John Mitchell")
- Due Date = **Date + 24h** > {{5232994__date}} +24h
- URL Attachments = **Data Card URL** > {{5233573__data__card__url}}

## Testing
- Open Trello: https://trello.com
- Create a new card on any board you're added to on Trello
- Add yourself as a member on the card you just created
- Add a due date to the card you just created (make the due date tomorrow, 1 min away from the current time). E.g. if it's 14.09.2015 / 3pm, set the due date to 15.09.2015 / 3.01pm. This will trigger the date activity notification in one-minute.
- Wait until you get a notification from Trello saying the task is due (within 30 seconds)
- Go to Zapier and manually run the task (click the down arrow on the task then click run)
- Head over to your daily list board, and your task will be there :-)

## Further reading
- https://zapier.com/help/trello/
- https://zapier.com/help/advanced-tips/
