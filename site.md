# Instruction for This Markdown File

Think about someone (perhaps the client) who already knows WordPress taking over the running of the site itself: how do they add new content – as a page or a post? In what category? You may have used a plugin for a calendar of events or something, which needs to be described. Do not recreate WordPress documentation, but clearly explain to the client’s site maintainer how this particular site is organised and can be updated.
_Delete above instructions after finalizing the document._

# Documentation for Site Maintainer

The site is made up of the following categories in hierarchical order.
- Achievements
  - Student's Achievements
- Promotions
- Schedule
- Uncategorized

Contents related to the organization's achievements should be under **Achievements**. The category has one child - **Student's Achievements**, in which contents related to achievements of students, who are learning at Baizonn Learning Center, should be uploaded. Other forms of achievement should be a child of **Achievements**.

Contents related to all types of promotions should be created under **Promotions**. Other types of promotions is not limited to be created as a child of **Achievements**. The same goes for **Schedule** category. 

As for **Uncategorized**, contents which do not fall under any of the above categories, contents which are demo version should be under this category. 

Contents should be created as **post** during the developmental state, not in live site. The agreed contents for live site should be uploaded under their respective page.

## Plugins
Plugins used to Baizonn Learning Center are as follow:
- [Elementor - Version 3.13.0](https://wordpress.com/plugins/elementor)
- [WP Encryption - One Click SSL & Force HTTPS Version 6.0](https://wordpress.org/plugins/wp-letsencrypt-ssl/)
- [Team Section - Version 1.0.7](https://wordpress.org/plugins/team-section/)
- [Smart Slider 3 - Version 3.5.1.14](https://wordpress.org/plugins/smart-slider-3/)
- [WPForm Lite - Version 1.8.1.2](https://wordpress.org/plugins/wpforms-lite/)
- [Timetable and Event Schedule - Version 2.4.9](https://wordpress.org/plugins/mp-timetable/)
- [WP Mail SMTP - Version 3.8.0](https://wordpress.org/plugins/wp-mail-smtp/)

### Elementor Guide
_Assigned to Fred. Delete this sentence after adding the instruction._

### WP Encryption Guide
The WP Encryption plugin creates an SSL certificate for your website, registers it, and checks its domain. It can give advantages for following reasons:
- SEO Advantage: SSL-enabled sites perform better in search results on major search engines like Google than non-SSL sites. increasing the amount of organic visitors to your website.
- Data encryption: Personal information and credit card numbers are securely encrypted during transmission between a server and a visitor on an SSL website.
- Trust: Google Chrome flags non-SSL websites as "insecure," making visitors feel uneasy.
- Authentic: The HTTPS green padlock is a representation of security, trust, and authenticity.


The followings are the steps that needed to perform while installing:
- Using hostgator, we have to create domain and sites that are available with the name (.com).
- After creating succesful domain and sites, need to choose the security function available for further process.
- At the wordpress plugins, we have to install WP Encryption - One Click SSL & Force HTTPS Version 6.0.
- Security fucntions checks from the hostgator allows WP Encryption fully worked on it.


By using WP Encryption plugins, we can use these followings features:
- Generate a free SSL certificate and check the ownership of the domain
- HTTPS provides secure webmail and email.
- Download the created intermediate certificate, key, and SSL certificate files.
- With one click, force HTTPS and enable site-wide HTTPS 301 redirection
- Redirect loop fixes for Cloudflare, StackPath, load balancers, and reverse proxies are part of HTTPS redirection.
- Health page for SSL - Control different SSL & Security features, such as the HSTS stringent transport security Header and HttpOnly secure cookies, among others, and keep track of your SSL score.
- Make sure that crucial security headers like X-XSS-Protection, X-Content-Type-Options, and Referrer-Policy are enabled.
- Enable the fixer for mixed material and unsecure content.
- Prior to the SSL certificate expiration, there is SSL monitoring and automatic email notice.

### WP Mail SMTP Guide
WP SMTP is a WordPress plugin that allows you to configure and send emails through an SMTP server instead of the default PHP mail function. SMTP stands for Simple Mail Transfer Protocol, and it is a protocol used to send and receive emails over the internet.[The official instruction video for setting up WP SMTP is here.](https://youtu.be/A4IClPHbg3k)
WP SMTP plugin provides an easy way to configure the SMTP settings for your WordPress site, including the SMTP server, port, encryption method, authentication, and more. With WP SMTP, you can ensure that your emails are delivered reliably and securely, with improved deliverability and fewer chances of being flagged as spam.
The Steps to set up WP SMTP plugin is as follows :
- Install and activate the WP SMTP plugin from the WordPress plugin repository.
- Go to the WP SMTP plugin settings page by clicking on WP SMTP > Settings in the WordPress dashboard.
- On the settings page, enter your SMTP server details, including the hostname, port number, and encryption method. Your email service provider should be able to provide you with this information. Some common SMTP server providers include Gmail, Yahoo, and Outlook.
- If your SMTP server requires authentication, enter your username and password in the corresponding fields. You may also need to select the authentication method, such as plain text or login.
- If you want to send a test email to ensure that your SMTP settings are working correctly, scroll down to the "Email Test" section and enter your email address. Click the "Send Test Email" button to send a test email.
- If the test email is successful, you will see a confirmation message. If there are any errors, WP SMTP will provide you with details about the error.
- Save your settings by clicking the "Save Settings" button.

### Adding/Editing Teachers' Profile - Team Section Guide
After installing this plugin on the admin panel, it is added into built-in content management tool catalogues. If we add this plugin, it will show the sample team showcase where we can click on it to do simple customization works such as replacing the image/ profile details. This is how site maintainers can update the contents. Moreover, [The official documentation](https://bblockswp.com/docs/team-block/) provides a comprehensive tutorial on how to work with the plugin. Here are design rules that site maintainers should follow:
- Team members' profile pictures should not have rounded-edge for the sake of design consistency when it comes to images.
- The text about teacher's brief should be at most 50 words since long text will lengthen the column, thereby disrupting the design aesthetics.
- Although the sample team showcase provides a feature to add social media links, it should be removed. One potential concern is that providing such links could inadvertently encourage visitors to directly contact the showcased teachers, which could create conflicts of interest with the organization's goals.

It is to note that the design rules may change as specified by the design team.

### Smart Slider 3 Guide
The most capable and user-friendly WordPress plugin for creating sliders, which was never before conceivable, is Smart Slider 3. fully SEO-optimized, responsive, and compatible with any WordPress theme. Without any code, make stunning sliders and tell tales. You can edit the Smart Slider 3 by doing the following steps-

- Log in to your WordPress dashboard, find the Smart Slider 3 on the left side of the screen and click it.
- Pick create new slide.
- Then you can choose what do want in your slide and edit the background on every slide.
- Once you are done click save. Then go to the website and press edit page.
- In the edit page screen you can add the smart slider when you click the [+] on the screen.
- Press browse all then search Smart Slider 3 and click it.
- then press the update button on the top right part of the screen and you can see it on ur website.


### Adding/Editing Forms - WP Form Guide
WPForms is a WordPress plugin that lets you easily build website contact forms. It’s an easy-to-use online form builder for WordPress websites that allows you to create smart forms in minutes without writing any code or hiring a developer. WPForms is full of useful features to help your small business earn more money online.[The official instruction video for setting up WP Form is here.](https://youtu.be/o2nE1P74WxQ) You can connect your forms to tons of popular email marketing services for easy marketing automation. 
Providers include Constant Contact, Mailchimp, Campaign Monitor, MailerLite, and more. With the Elite plan, you can connect your forms to CRMs like ActiveCampaign, HubSpot, and Salesforce. WPForms is an incredibly affordable plugin when you take a look at all the money-making features it offers.
To edit WPForms as a site administrator, you can access plugin-wide settings in WPForms by going to WPForms » Settings in the left WordPress menu. You can edit the wpforms by doing the following steps-
- Log in to your WordPress dashboard and go to the WPForms page.
- Find the form that you want to edit and hover your mouse over it. You will see several options appear, including Edit, Duplicate, Delete, and View.
- Click the Edit button. This will take you to the WPForms editor, where you can make changes to your form.
- You can add or remove form fields by dragging and dropping them from the left-hand side of the screen. You can also customize the field settings by clicking on each field.
- Use the Form Settings tab to customize the form's general settings, such as the form name, description, and confirmation message.
- Use the Notifications tab to customize the email notifications that are sent to you and your users when a form is submitted.
- Use the Confirmations tab to customize the message that users see after they submit a form.
- When you're done making changes, click the Save button to save your changes.

### Adding/Editing Timetable - Timetable and Event Schedule Guide
MotoPress Timetable and Event Schedule is an all-around organizer plugin developed to help you create and manage online schedules for a single or multiple events, customize the appearance of each event, add date, time, description and display all the needed items in a carefully-crafted timetable. It also comes with Upcoming events widget.
- Plugin Demo
- Documentation
- Free Theme
