ChroniCal
=========

Part of our mission on the Chronline team is teaching students about web development. We have created this assignment because we believe the only way to learn how to write code is to write code. If you complete this assignment, you will understand the fundamentals of web development and have created a real web application. Furthermore, we may integrate your code into the main Chronicle repository since we want to add this feature anyway.

The project is to create a calendar app similar to Google calendar. The user should be able to create different calendars that contain a collection of scheduled events. The events should be displayed in a typical calendar layout. You can design it however you want and are encouraged to add additional features (like integrating the Duke events API).

To help you learn about Rails development, we recommend the Michael Hartl [Rails tutorial](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book). For that reason, we have set out a guide of how to build this application as you go through the tutorial. Below you will find a list of each chapter and 1) what you should now know and 2) the next pieces of the application that you should build. If you complete the exercises after each chapter, you will have a functional calendar by the end.

## Rails tutorial chapter by chapter

### Chapter 1

This section will familiarize you with the Rails environment and tools you will need. We introduced text editors, terminals, and git in our talk on tooling. As Hartl describes in this section, these truly are invaluable tools for any programmer. As a side note, if you have a Windows computer, we highly recommend working on this project in a Linux virtual machine. You can download [VirtualBox](https://www.virtualbox.org/), and install [Ubuntu](http://www.ubuntu.com/) on the guest machine.

### Chapter 2

This is the extent of what we covered during the Sunday session on Rails. You will learn how to scaffold out a *very* basic Rails application and deploy it with Heroku. Once you complete this chapter you will understand just how easy it is to launch your own website with Rails.

### Chapter 3

In this chapter, you will start writing the calendar application. The goal is to put up a static home page. Hartl also discusses the benefits of test driven development. This is worth reading though I don't recommend going through the Advanced Setup section right now. Instead of completing his exercises, simply create a home page that states what this application will do. This is your chance to play around with HTML if you are not yet familiar with it. Try using header tags (`<h1>`, `<h2>`, etc.) and paragraph tags. Since we have not added any CSS yet, the page will be mostly unstyled.

### Chapter 4

In this chapter, Hartl runs through some basics of Ruby and the syntax. We covered most of this in on of the sessions, but if you are not familiar with Ruby, I recommend reading through this chapter and completing exercises 1-4 that he describes in section 4.6.

### Chapter 5

Here we begin writing CSS using [Bootstrap](http://getbootstrap.com/2.3.2/) as a base. To stay consistent with the tutorial, I recommend using Bootstrap 2 rather than the more recent version, Bootstrap 3. Hartl also shows how to make your homepage appear at the root path (/) in Listing 5.35. You should follow along in making a header with the logo, but not the footer. Hartl creates Help and About pages that you do not need to, so anywhere he makes links to them you can omit. You should still follow the instructions in section 5.4 in setting up routes for user login and sign up. We will need this later on.

After reading through this chapter, we know enough about Ruby, HTML, CSS, and Rails to make a simple monthly calendar in HTML. See if you can create a homepage that looks like the screenshot below. Show the current month with today's date highlighted.
