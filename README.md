<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
We will go through example tickets commonly worked in a real-world enterprise setting.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Example Ticket 1</h3>
<p>
This tutorial continues after the post-installation configuration.
  https://github.com/JackieG8803/Post-Installation-Configuration
</p>
<p> First, we will come to our osTicket Support Center landing page. Here end users can submit tickets for issues they come across.
</p>

![1](https://github.com/user-attachments/assets/467e4d41-7010-4616-ac30-ffabe8fff72e)


<p>
In our agent portal as "John," and example ticket we created is titled "entire mobile/online banking system is down"</p>
<p>Our example end user, James, comments that the employees in his department are unable to access the banking portal.</p>

![2](https://github.com/user-attachments/assets/8e180480-edd8-4b93-b8bd-ca66945dfec0)

<p>We might consider assigning this ticket to the Sev-A level as it may have a significant impact to the business, causing the company to lose thousands of dollars as each hour passes unresolved.
</p>
<p>Help desk agents should regularly keep a stream of communication with the internal IT team assigned to the same ticket, and with the end-user.</p>

![3](https://github.com/user-attachments/assets/92f60672-f60b-434e-bfcd-ead540fd4ccb)

<p>As help desk agent "John," we make the necessary updates to the ticket communicating the severity of the issue and assigning the ticket to the appropriate SLA. </p>

![4](https://github.com/user-attachments/assets/1db78198-86b5-47a9-a8ff-63e5ebe54fc9)

<p>With a Sev-A ticket, this might get elevated to a tier 2 or tier 3 support team to handle these high-severity cases.</p>
<br />

<h3>Example Ticket 2</h3>
<p>Let's work another example ticket. We can submit a ticket as "James Doe" who describes an issue with many employees in the Accounting department who cannot open Adobe software. Depending on the urgency - perhaps accountants need to access and print crucial invoices and contracts.</p>

![5](https://github.com/user-attachments/assets/aeda7117-fc67-451a-82f4-e602fd56ed01)


<p>
As agent "Jane Doe," in our agent panel we can see the ticket submitted. 
</p>

![6](https://github.com/user-attachments/assets/a38fe1a7-0f68-426d-98e7-08d8f5e1f3a7)

<p>We might communicate with James directly, ask questions to get to the root of the issue, and diagnose possible issues and identify troubleshooting solutions.</p>
<p>Through our communication with James, we might learn that there was a recent OS update that only affected several people in the department.</p>

![7](https://github.com/user-attachments/assets/8b967886-5cd4-4eb3-8b7e-172e137ee092)

<p>Again, keeping an open line of communication is key to providing excellent customer service and keeping the service team informed of the situation.</p>

![8](https://github.com/user-attachments/assets/d71c0dcc-ee73-46f3-8494-f22ee8ba20d5)

<p>Sometimes, there may be conflicting software affecting another software from working properly. However, if all of the workstations and users are managed centrally, likely every user in the same department and role will have the same access controls and software installed.</p>
<p>Other times, it may be a simple system restart to the affected computers; an uninstall and reinstall of the software; or software needing an update/patch.</p>

![9](https://github.com/user-attachments/assets/00bcff06-6fa1-421b-9368-641500331898)
![10](https://github.com/user-attachments/assets/d062454a-cd2e-4d5a-b014-86748241154a)

<h3>Example Ticket 3</h3>
<p>In this example, a ticket may come up with a device not working. Sometimes these tickets will be pretty vague and so we need to diagnose the main issue.</p>

![11](https://github.com/user-attachments/assets/042d5ce6-3557-43a3-a300-8abf8c8a2952)
![12](https://github.com/user-attachments/assets/733d79d4-703e-4012-837c-caa8160e077c)

<p>Through asking more questions, we may diagnose the problem to a faulty charger and reissue a new charger.</p>
<p>Sometimes, the issue might be with the power outlet itself, the laptop, or the charger. We might test the outlet if it works with other devices. Test the charger if it works with other laptops.</p>
<p>Other times, it may be hardware failure such as the motherboard, RAM, or hard drive; overheating; corrupted BIOS settings; power button malfunction; liquid damage, etc.</p>

![13](https://github.com/user-attachments/assets/a61b04c5-f3d1-4321-b288-ab5a86010e3d)

<p>Often we may work a ticket and another issue arises. Here, the CFO indicates that the new charger worked but found a corrupted file. Perhaps he was working on something and the laptop shut off without the file being saved or backed up.</p>
<p>From within the current ticket, we can create a chained ticket to address this new issue. Some SLAs or company policies may inform agents on how to go about these situations, but for our example, we will create a chained ticket.</p>
<p>Chained tickets help support SLA management (help track overall resolution times), maintains context of ticket issues (preserves history and context of original problem), improves efficiency (support agents can quickly access previous solutions and actions taken, potentially speeding up the resolution process).</p>

![14](https://github.com/user-attachments/assets/c7bfbc5c-5cb9-4bdd-a395-3bd3b8ddf415)
![15](https://github.com/user-attachments/assets/ff97bf99-3a6a-47ec-a9b2-478186658b84)
![16](https://github.com/user-attachments/assets/e597b368-56e7-4818-ab62-2fbfd4f64799)
![17](https://github.com/user-attachments/assets/b0345494-282f-44cc-8075-f82b5610ed77)


<p>Again, we want to ask questions and get to the root of the issue, such as:</p>
- What specific error message are you experiencing?
- When did you first notice the issue?
- Have you made any changes to your system, such as software updates or installations?
- Can you open the file on another device or computer?
- Recent power outages?
- What application are you using to open the file?

![18](https://github.com/user-attachments/assets/0b05a4f6-4034-4d3b-9e39-c72340b8de25)

<p>We learn that the file was an Excel spreadsheet the CFO was working on when his system unexpectedly shutdown. A potential solution may be to retrieve a backup of the file: </p>

![19](https://github.com/user-attachments/assets/e1f6a087-4bdb-48cf-86e2-f988c7ebf62b)
![20](https://github.com/user-attachments/assets/49a0d865-ade5-4607-9503-62d576f54e1f)


In conclusion, working with example tickets provides valuable hands-on experience in managing the ticket lifecycle from intake to resolution. As helpdesk professionals, it is important to:
- Utilize specialized groups in streamlining ticket assignments and resolution through organized team structures
- Maintain clear communication, keeping end-users informed throughout the ticket lifecycle to enhance satisfaction
- Regularly analyze ticket data, identifying trends and areas for improvement to optimize your helpdesk operations.

<p>Best of luck with your IT journey!</p>
