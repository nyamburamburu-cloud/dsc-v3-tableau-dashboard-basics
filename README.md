# Building Dashboards with Tableau

## Introduction
Until now, we have been using Tableau workbooks to get familiar with the Tableau interface. Now we will take your Tableau skills one step further and dive into one of the most useful features of Tableau -- __dashboards__. 

First, we will describe the components of Tableau's dashboard workspace. Then, create a few vizzes and learn how to arrange and customize the dashboard to present our data. Next, we will then explore some of the interactive objects and see how they can be used to allow the viewer to ask questions of the data to gain insight.

## Objectives
You will be able to: 
* Identify and describe dashboard Objects and other elements of a Tableau dashboard workspace
* Use horizontal and vertical containers to create a layout to arrange vizzes and objects on the dashboard
* Add interactive elements to a Tableau dashboard

## Creating a Dashboard
There are a few ways to create a dashboard:
1. __The Menu Bar__
In the menu bar at the top of the interface you will see __Dashboard__. Click on this drop down and you will see the options for _Dashboard_. Your first option should be __New Dashboard__, click on this option and you will be taken to a new, blank dashboard.


2. __The Sheets Tab__
To the right of the __New Worksheet icon__, you will find the __New Dashboard__ icon, click on this icon and you will be taken to a new, blank dashboard.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/dashboard2-new.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

## Device Type Card
One of the benefits of Tableau is that is allows you to easily create visualizations that improve the experience of your end user. In today's business environment, users are often trying to gain insights on the go and like to use mobile devices to interact with dashboards on Tableau.

To facilitate use with mobile devices, Tableau has implemented a Device Type Card on the __Dashboard pane__. Right now, the Default is set to Phone, which will limit the maximum width and height of the dashboard.

We also want to consider the experience of desktop users. We can do this by adding another device type to the card. On the Menu bar at the very top of the page, select Dashboard > Device Layouts > Add Desktop. 

This option lets you see what your dashboard will look like on different devices, so you can ensure it will be visible. You can even customize the view for each device format. 

If you want to remove a device, you can hover over it on the Dashboard pane and click on the `...` and select __Delete Layout__.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/device-layout.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

## Objects Card
Objects are components that can be incorporated into your dashboard to add additional functionality, customization, and interactivity. Let's discuss a few of them using the labeled image below.

__Keep in Mind__: __Ask Data__ (10), __Data Story__ (11), and __Extension__ (12), are not available with Tableau Public. If you would like to research their uses, you can look through the documentation on the <a src="https://www.tableau.com/" target="blank">Tableau Website</a>

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/more-options1.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

1. __Horizontal__ - Adds a container to hold objects horizontally
2. __Vertical__ - Adds a container to hold objects vertically (more on containers below)
3. __Text__ - Adds text boxes in your dashboard to help convey information about your dashboard to the viewer
4. __Image__ - Adds images to your dashboard such as a logo
5. __Web Page__ - Allows you to embed a web page in your dashboard
6. __Data Story__ - Embeds a presentation to add context
7. __Blank__ - Adds some blank space
8. __Navigation__ - Allows you to create a link to any part of the workbook so the viewer can look closer at some component
9. __Download__ - Allows you to embed a button for the viewer to download the viz as a PDF or an image file

### Object Placement
Objects can be placed in the dashboard in one of two manners, either __Tiled__ or __Floating__. 

__Floating__ allows the object to be placed anywhere on the dashboard and can be overlapping any part of the view. 

__Tiled__ attribute forces the object to share the space with the other objects in the container. 

If your container has more than one object in it, you will notice that you can determine how the item is placed based on the position you drop it in. Tableau will highlight the position the object will align to as you hover over the container. The same is true for containers as you are adding them to the dashboard.

## Interactive Elements
Tableau dashboards can contain interactive elements that allow the end user to alter the view of the data in the dashboard to answer a novel question or perform an __ad hoc analysis__. For example, users can apply __Filters__ to view the data that pertains to the segment of the population most relevant to them.

We can apply filters by using the __More Options__ menu. You can find this menu by clicking the down arrow on the top right of the viz on your sheet.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/more-options-2.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

In this example, we add a filter for `Sales (SUM)`. In the upper-right corner, there a slider appears that allows the use to toggle the sales amount they wish to filter by.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/slider.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

## Summary
In this lesson, we introduced Tableau's Dashboard workspace and discussed some of the most important functionality, like Device Type and Objects. Then we discussed how you can add interactivity to your dashboards to allow users to ask questions of the data to gain insights. Finally, we discussed how each of these components works together to enhance the end user experience.

In the upcoming lab, we will use this knowledge to build out a Tableau dashboard using the workbook we previously created. 
