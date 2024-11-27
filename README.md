<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
I've set up osTicket and it's ready for us to customize the system.
Let's start by creating roles for the help desk. Go to the Admin panel, click Agents, then click Roles. We'll make a role called Supreme Admin.
To create the role, click "Add new role" and type in the name. You can choose what each role is allowed to do. For our Supreme Admin role, we'll turn on all permissions since this will be the highest-level role. Keep in mind that regular help desk agents will have more limited access to the system.
</p>

![image](https://github.com/user-attachments/assets/c727a0f2-65b2-4f9c-bb09-4ca7b2794ae2)




</p>
<br />
<p>
</p>
<p>
To create a new department, click the "Departments" button in the agents tab. Every agent needs to be placed in a department that matches their job role. For example, we'll make a "System Administrators" department for our top-level admins. Once you create a department, you can set up other important features like response times, department managers, and email settings.
</p>
<br />
<p>
  
![image](https://github.com/user-attachments/assets/9406294a-c282-4076-8ea8-bee02a6cd6db)


</p>
<p>
Let's create a new team after setting up a department. Teams are groups of agents from different departments working together. You can pick your best agents from various areas to form a specialized team. For instance, if you have a specific product, you can create a team of experts who know that product well. To create a team, simply go to the Teams section under Agents. You'll notice there's already a Level I support team - we'll add another one called Online Banking.
</p>
<br />
<p>
  
![image](https://github.com/user-attachments/assets/7471f720-0774-4be7-ba3a-6cca4b6da79d)

</p>
<p>
With our new team set up, we'll create a setting to allow anyone to create tickets. Navigate to Admin Panel → Settings → User Settings.

</p>
<br />

![image](https://github.com/user-attachments/assets/81f5c9ab-104f-4f39-adbc-fc0c238462fe)


</p>
<p>
 Let's create Agents—the helpdesk employees who solve tickets. Each Agent is assigned to a primary department with a specific role for handling that department's tickets. Agents can also access other departments and have different roles within each one. You can manage all Agent permissions, access levels, and team assignments in the Agents tab.
</p>
<br />

![image](https://github.com/user-attachments/assets/a0e4d7bb-2c1e-4c39-830f-4b0fed3c80d7)


</p>
<p>
After creating agents, we will set up users. Users are customers who create tickets when they need help. Each user is identified by their email address. To create a user, navigate to Agent Panel > Users > User Directory > Add New. 
</p>
<br />

![image](https://github.com/user-attachments/assets/d9b70ca4-06e9-4d2c-b149-aeacb6648b19)


</p>
<p>
SLA Plans specify the timeframe within which the help desk must resolve a specific ticket. To create SLA Plans, navigate to Admin Panel->Manage->SLA Plans. Each SLA operates on a schedule that includes a grace period. For example, SEV-A runs on a 24/7 schedule with a one-hour grace period.
</p>
<br />

![image](https://github.com/user-attachments/assets/934daeb7-065b-444a-85e7-05e9398823f8)


</p>
<p>
Help topics help users categorize their tickets. In the example below we can create a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking.  
</p>
<br />

![image](https://github.com/user-attachments/assets/5528bed2-46d6-4479-b1f9-6da6fad62a3d)


</p>
<p>
