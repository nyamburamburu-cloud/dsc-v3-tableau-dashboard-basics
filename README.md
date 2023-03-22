# Building Dashboards with Tableau

## Introduction
Until now, we have been using Tableau workbooks to get familiar with the Tableau interface. Now we will take your Tableau skills one step further and dive into Tableau dashboards. First, we will get familiar with the Tableau Dashboard Workspace. Then, we will show you how to create a dashboard with Tableau.

## Objectives
You will be able to: 
* Identify and describe dashboard Objects and other elements of a Tableau dashboard workspace
* Use horizontal and vertical containers to create a layout to arrange vizzes and objects on the dashboard
* Add interactive elements to a Tableau dashboard

## Creating a Dashboard
There are a few ways to create a dashboard:
1. Menu Bar: In the menu bar at the top of the interface you will see **Dashboard**. Click on this drop down and select **Dashboard > New Dashboard**.

2. Sheets Tab: To the right of the **New Worksheet** icon, you will find the **New Dashboard** icon.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/dashboard2-new.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

## Format Dashboard Layout with the Device Type Card
One of the benefits of Tableau is that is allows you to easily create visualizations that improve the experience of your end user. In today's business environment, users are often trying to gain insights on the go and like to use mobile devices to interact with dashboards on Tableau.

To facilitate use with mobile devices, Tableau has implemented a **Device Type Card** on the Dashboard pane. Right now, the Default is set to **Phone**, which will limit the maximum width and height of the dashboard.

We also want to consider the experience of desktop users. We can do this by adding another device type to the card. On the Menu bar at the very top of the page, select **Dashboard > Device Layouts > Add Desktop**. 

This option lets you see what your dashboard will look like on different devices, so you can ensure it will be visible. You can even customize the view for each device format. 

If you want to remove a device, you can hover over it on the Dashboard pane and click on the `...` and select **Delete Layout**.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/device-layout.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

## Objects Card
Objects are components that can be incorporated into your dashboard to add additional functionality, customization, and interactivity. The primary objects we will use in this module are **Horizontal Containers** and **Vertical Containers**.

Let's discuss a few of them using the labeled image below.

<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/more-options1.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

1. **Horizontal** - Adds a container to hold objects horizontally
2. **Vertical** - Adds a container to hold objects vertically (more on containers below)
3. **Text** - Adds text boxes in your dashboard to help convey information about your dashboard to the viewer
4. **Image** - Adds images to your dashboard such as a logo
5. **Web Page** - Allows you to embed a web page in your dashboard
6. **Data Story** - Embeds a presentation to add context
7. **Blank** - Adds some blank space
8. **Navigation** - Allows you to create a link to any part of the workbook so the viewer can look closer at some component
9. **Download** - Allows you to embed a button for the viewer to download the viz as a PDF or an image file


**Keep in Mind**: **Ask Data** (10), **Data Story** (11), and **Extension** (12), are not available with Tableau Public. If you would like to research their uses, you can look through the documentation on the <a src="https://www.tableau.com/" target="blank">Tableau Website</a>


### Object Placement
Objects can be placed in the dashboard in one of two manners, either **Tiled** or **Floating**. 

1. **Floating** allows the object to be placed anywhere on the dashboard and can be overlapping any part of the view. 

2. **Tiled** attribute forces the object to share the space with the other objects in the container. 

## Building a Dashboard Layout
By using horizontal and vertical containers in Tableau, you can easily organize your dashboard layout and arrange your sheets to create an effective and visually appealing data presentation.

To add containers:
1. click on the "Insert" menu and select "Horizontal" or "Vertical" container or drag and drop the container from the Objects card to the dashboard canvas.
2. You can adjust the size of the container by dragging the edges or by changing the size values in the "Size" tab of the "Format" menu.
3. To add sheets/vizzes to the container, drag the sheet onto the container.

Repeat steps 1-3 to add more containers and sheets as desired.

You can adjust the layout further by clicking on the "Layout" menu and selecting "Padding," "Gridlines," or "Guides" to help align and organize the elements on the dashboard.

Once you are satisfied with the layout, you can add additional formatting and design elements using the "Format" menu, such as adding a title, adjusting the font, or changing the background color.


## Interactive Elements: Filters
Tableau dashboards can contain interactive elements that allow the end user to alter the view of the data in the dashboard to answer a novel question or perform an **ad hoc analysis**. For example, users can apply **Filters** to view the data that pertains to the segment of the population most relevant to them.

We can apply filters by using the **More Options** menu. You can find this menu by clicking the down arrow on the top right of the viz on your sheet.

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
