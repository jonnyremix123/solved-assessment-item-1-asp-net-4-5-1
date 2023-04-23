Download Link: https://assignmentchef.com/product/solved-assessment-item-1-asp-net-4-5-1
<br>
This assessment item relates to the course learning outcome numbers 1 and 2.More specifically, the objective of this assignment is for students to:

• Develop a dynamic Internet application with a consistent look and feel for business using anintegrated suite of software tools.

IntroductionYou are required to develop the Aussie Stamp Place website using ASP.NET 4.5.1 and C#. You mustdevelop the web pages according to the specifications given in this document. This means that you mustprovide the functionality specified, produce the layout specified and use the data and images provided on thecourse website. This document is a specification that you are required to implement.Overview of website to be developedYour website must:• Use a master page and content pages throughout• Define and use a consistent theme throughout• Use a web.sitemap and related navigation controlsYou are also required to:• submit a brief Word document as discussed below.You are required to develop the following pages:Web Page DescriptionDefault.aspx The home page.Pages/Default.aspx Descriptor for top level menu itemPages/animals.aspx Header and table of Australian native animal stamps, each stamphas a name, price, number in stock, last update time and an image.Pages/flowers.aspx Header and table of Australian native flower stamps, each stamphas a name, price, number in stock, last update time and an image.Pages/peace.aspx Header and table of Peace and Victory stamps, each stamp has aname, price, number in stock, last update time and an image.Pages/zoological.aspx Header and table of Australian zoological stamps, each stamp has aname, price, number in stock, last update time and an image.About/Default.aspx The default About pageAbout/About.aspx Brief information about the website.About/ContactUs.aspx A contact us page with contact information.Page 2 of 9You must also create the Web.sitemap and Masterpage.master files, as well as make appropriate editsto the web.config file.These requirements are discussed in more detail below.Provided materials – starter kitTo get you started, an assignment starter kit is available on the course Moodle web site. This starter kitcontains:• The Images directory containing all the images required for the assignment• The App_Themes directory containing resources and files required for themesWebsite structureThe files in your website should be structured in the following way:Web.sitemapYou must construct your web.sitemap to achieve the following menu hierarchy:The menu items above must map to the following content pages:Menu item Content pageHome ~/Default.aspxStamp Catalogs ~/Pages/Default.aspxStamp Catalogs -&gt; Zoological Stamps ~/Pages/zoological.aspxStamp Catalogs -&gt; Peace Stamps ~/Pages/peace.aspxStamp Catalogs -&gt; Flower Stamps ~/Pages/flowers.aspxStamp Catalogs -&gt; Animal Stamps ~/Pages/animals.aspxAbout ~/About/Default.aspxAbout -&gt; Contact Us ~/About/ContactUs.aspxAbout-&gt; About Us ~/About/About.aspxAussieStampPlacePageszoological.aspxpeace.aspxflowers.aspxanimals.aspx

default.aspxMasterPage.MasterWeb.configWeb.sitemapImagesApp_ThemesHomeStamp CatalogsAbout Animal StampsFlower StampsZoological StampsPeace StampsContact UsAbout UsPage 3 of 9Master pageYour master page must achieve the following layout:HeaderThe header must contain the logo. The actual logo displayed will depend on the theme. Your Colourtheme uses your own design of a logo or you can use the supplied logo.jpg. The Monochrome themeuses logo.jpg and found with the supplied Stylesheet.css file in the starter kit.NavThe Nav should contain a SiteMapPath control. Note:• The control must obtain its menu items from the Web.sitemap file; menu items should not be hardcoded into the SiteMapPath control.• Your control should not show the top (Home) node.AsideThe aside should:• display a DropDownList for choosing the theme.• use a TreeView to show a site menu. The Home menu should not appear twice.The aside will also be used in assignment 2 for providing a login area.FooterThe footer contains two divisions – the copyright and lastupdate divisions. The copyrightdivision should contain a copyright symbol, your name and the current year, along with the image copyrightstatement. The lastupdate division should contain the date that the website was last updated. You mayhard code this date.ThemesThe appearance of the website will be controlled by the use of themes. Two themes shall be supported. Thefirst is the Monochrome theme and consists of a copy of the Stylesheet.css style sheet supplied inthe starter kit and renamed Monochrome.css. The supplied logo, logo.jpg, is found in the starter kits/Images folder. The second theme is a Colour theme you have to define yourself. You can re-use theHeaderContentFooterAsideNavPage 4 of 9logo.jpg file for the header image. You should modify the supplied stylesheet.css file. Start byrenaming it Colour.css and then modify it to achieve your new style.Content pagesThe appearance and required functionality of the content pages are described below.Home pageThe default home page should appear as follows to a user when viewed with the Monochrome theme:Stamp CatalogsThe default Stamp Catalogs page must appear as follows. Note that for brevity, only the main content area isshown.Page 5 of 9Stamp Catalogs – Zoological StampsThe Zoological Stamps page must appear as follows. Note that for brevity, only the main content area isshown.Note that:• A table layout is used.• The Name, Price, # in stock and Last update fields must be as shown and the last cellshould contain the image of the stamp.Page 6 of 9Stamp Catalogs – Peace StampsThe Peace Stamps page must appear as follows. Note that for brevity, only the main content area is shown.As before a table layout is used with the Name, Price, # in stock and Last update fields and the lastcell should contain the image of the stamp.Stamp Catalogs – Australian Flower StampsThe Australian Flower Stamps page must appear as follows. Note that for brevity, only the main contentarea is shown. As before a table layout is used with the Name, Price, # in stock and Last updatefields and the last cell should contain the image of the stamp.Page 7 of 9Stamp Catalogs – Australian Native Animals StampsThe Australian Native Animals Stamps page must appear as follows. Note that for brevity, only the maincontent area is shown. As before a table layout is used with the Name, Price, # in stock and Lastupdate fields and the last cell should contain the image of the stamp.ThemesThe appearance of the website will be controlled by the use of themes. Two themes shall be supported. Thefirst is the Colour theme and consists of the ColourStyle.css style sheet and the logo in thelogo.jpg file. The second theme is the Monochrome theme and is implemented using the logogrey.jpglogo and the MonochromeStyle.css style sheet.AboutThe default About page must appear as shown.Page 8 of 9The Contact us page must appear as shown.The About us page must appear as shown.Word documentYou are to prepare a brief Word document. Your document should:• Include an appropriate title page.• List the features you successfully implemented, there is no need to describe them.• List the features you were unable to successfully implement; you should describe the problem in afew sentences and also briefly describe anything you attempted to get it to work. Your approach toidentifying and attempting to fix these bugs may gain you some partial credit for those features youwere unable to implement.• A description of any additional functionality you believe would be useful to add to this Website.Explain what the features are and how they would help to improve the Website.• Discuss any moral or legal issues that may arise in running a business based on the idea behind thisweb site.• References (if any) listed using the Harvard Referencing Style.SubmissionYou are required to submit your assignment electronically via the Moodle course website. You mustcombine the following files together in a .ZIP or .RAR archive:• The directory containing your ASP.NET website.• Your Word documentThe resulting archive file should be submitted on the course website. Please note that you should use yourstudent number as the name for the archive file you upload to the Moodle website.Image copyrightsImportant note to students: The images supplied on the course Website for this assignment are only to beused in preparing the solution for this assignment. Use of these images for any other purpose is strictlyprohibited in accordance with the copyright laws.Page 9 of 9Assessment criteriaAssignmentComponent Criteria Marks TotalMaster page – general– Layout and general themes as required– Header contains logo– Footer is correct1.5Master page –Navigation– Web.sitemap correct– In Nav site map tool correctly used– In aside drop down list used to select theme and the treeview works asrequired2Stamp Catalog pages– Default page correct– The required fields are on all 4 catalog pages and are correct– Images are present and work correctly on all pages– Tables display correctly on all pages5About pages – The default about and the contact us and about us pages display andhave the correct information 0.5Theme– The theme drop down list is displayed– Toggling the theme selection updates the display correctly on allpages– A colour style (theme) independently created3Word document– Lists complete and incomplete stages and describes steps taken tocomplete functionality (if applicable)– Discussion of ethical or legal issues– Suggestions for new functionality3PenaltiesTotal 15Comments:Lecturer’s Signature Date: