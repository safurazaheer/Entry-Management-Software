# Entry-Management-Software
## Problem statement:

We need an application, which can capture the Name, email address, phone no of the visitor and same information also needs to be captured for the host on the front end. At the back end, once the user enters the information in the form, the backend should store.

## Solution:
We have created a single admin which can add Host, whenver any visitor comes to visit a host, he/she can choose the host whom they wants to meet.After the visitor fills the form, the host will recieve the email and sms regarding the details of the visitor.

We created an application, which capture the Name, email address, phone no of the visitor and
same information is also captured for the host on the front end.
At the back end, once the user enters the information in the form, the backend stores all of
the information with time stamp of the entry.
This triggers an email and an SMS to the host informing him of the details of the visitor.
When the visitor leaves, an email/sms is sent to the visitor which includes:
1. Name
2. Phone
3. Check-in time,
4. Check-out time,
5. Host name
6. Address visited.

## Example:
Visitor Details:
Name - Anant Sharma
Email - a.sharma@xyz.com
Phone - 9999999999
Checkin Time - 9:00 AM IST
Checkout Time - 4:00 PM IST
Host Details:
Name - Vishesh Singh
Email - vs@xyz.com
Phone - 000000000
Once Anant checks in and enters his details in the application, Vishesh should get an email and
an SMS stating the visitor details.
After the meeting or visit is over, and Anant checks out at 4:00 PM, Anant should get an emails
stating his visit details :

1. Name
2. Phone
3. Check-in time,
4. Check-out time,
5. Host name
6. Address visited.

## Requirement:
EMAIL_HOST_USER = 'example@gmail.com'

[Link](https://myaccount.google.com/security)
In the given Link, in the less secure App section, turn it on.
![GitHub Logo](/images/Google.png)
## Visitor Form
![GitHub Logo](/images/Visitor_form.png)
## List Of Visitors
![GitHub Logo](/images/list_of_visitor.png)
## Host Form
![GitHub Logo](/images/Create_host.png)
## List Of Hosts
![GitHub Logo](/images/listhost.png)

## SMS screenshot:
![GitHub Logo](/images/msg_screenshot.jpeg)
## Email Screenshot:
![GitHub Logo](/images/gmail.png)
