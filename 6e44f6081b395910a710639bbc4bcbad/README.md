## Leave Management App

# This is Scoped Application built using ServiceNow App Engine Studio.
# #BuildWithAES

**App Features:**
1. App lets user create leave request.
2. Approval link is shared on MS Teams channel.
3. Mananger can then approve the leave request.
4. Leave Balance is updated.

**Steps**
1. Import Github Repo in your Servicenow Instance.
2. Create a group and Role >> "x_492126_leave_m_0.LM User".
3. Add user to the group to access this app records.
4. Navigate to  Menu "Leave Request" and create new request.
5. Click on "Request" button. (Approval is triggered to manager)
6. Message is sent on MS teams channel with approval link.
7. After the approval Leave Request status is updated to approved.
8. Leave Balance is updated.

***Stay Tuned for the UI experience in next version***

**Note:**
Please update Webhook URL in the Flow to send notification to correct Teams Channel.\
Do activate following flows.
1. Flow: "Leave Approval MS Teams Notification".
2. Flow: "Leave Management Flow".
