# Markdown Tutorial
### Author - James Kirkland
### The purpose of this tutorial is to show anyone how to create an HTML webpage.
### The target audience for this tutorial is anyone not familiar with coding or information systems.


## This tutorial will cover:
- Creating a new HTML Page
- Page Structure
- Tag Usage
- Adding Text
- Adding Images
- Adding Links
- Hosting and Publishing

### Creating a new HTML Page
![notepad graphic](https://static.makeuseof.com/wp-content/uploads/2013/05/notepad.png)
![expression graphic](https://davescomputertips.com/wp-content/uploads/2015/05/01ew4.jpg)

Creating a new HTML page begins with selecting an editor. This can be most any text editor, for example, Notepad is a free tool that is great for getting familiar with writing in HTML. Likewise, there are more complex editors with further capabilites than a basic text editor. Microsoft Expression Studio 4 is one example of one of these editors and this particular program allows users to connect to their host site and publish pages from within the application. For our purposes, I would recommend beginning with Notepad.
### Page Structure

![HTML Structure Graphic](https://i1.wp.com/qatechhub.com/wp-content/uploads/2016/09/BasicHtmlStructure.png?resize=540%2C360)

As you can see from the graphic above, HTML pages begin with the DOCTYPE tag. This specifies the document type associated with the code that we are writing and determines how the document is parsed. Next is the html tag which encapsulates the rest of the code and declares the page as an HTML page. This tag must be closed using </html> at the end of your code. Inside the HTML tags will be the header, title and body which are the meat and potatoes of the HTML page you will be creating. The header tag basically specifies the top of the page and usually contains a title which is created using the <title> tag. Below the header is the body of the page. Using the <body> tag, you can add text, images, links and so much more to your HTML page.
  
### Tag Usage

![Tag Chart](https://cdn-images-1.medium.com/max/1600/0*eU6H-gxRpslRHfNT.jpg)

The chart above shows just a few key tags used in creating HTML pages. It is important to understand how to use these tags in order to format your page in a way that is clean, engaging and easy to follow!
### Adding Text

Open the Notepad Program on your computer, and create a new blank document.
It is always a good idea to set your main tags before your start to add content to the page. To begin, we need to set the DOCTYPE to HTML using the <!DOCTYPE html> tag at the top of the page. Next, on the line below add your <html> tag and make sure to close it with a </html> tag below it. Now you can add the rest of your tags in between the <html> tags, here you will add the header, title and body as shown in the page structure graphic above. Remember to close your tags!
  
Once this is done, we are ready to add content to our new HTML page. We need something to call our page now, add a title of your choosing between the title tags enclosed in the header of your HTML page. For example: <head><title> HTML TUTORIAL </title></head>. This does not display title text on the actual page but it does give users something to search for your page by in various search engines such as Google or Bing.

Now that that is done we are ready to add some content to our page using the <body> tags we set up initially. Between the opening and closing body tags is where your text and images will go. To add text to your HTML page you will need to use the paragraph tags denoted by <p> and </p>
  
  -Example <body><p> This is example text for my new HTML page! </p></body>
  
 As you can see, adding text is fairly easy. Next we need to format our text in a way that serves the purpose of the page and is easy for users to read. Looking at the tag chart above you will see various formatting tags. Let's try a few of them out.
 
 -Example <body><p><b><u> This is example text for my new HTML page! </u></b></p></body>
 
 In the example above you can see that i inserted two tags around my text. Doing so should result in your page displaying the following:
  
  _**This is example text for my new HTML page!**_
  
 Here we have formatted our text to be both bold and italicized. This is useful for creating separation between titles and paragraph text in documents. If you created a page wher the text looked completely the same it would most likely be bland and difficult for users to follow. Formatting tags allow us to add a little style and structure to our HTML pages!
 
 [Check out w3schools awesome complete list of HTML tags and tutorials](https://www.w3schools.com/tags/default.asp)
 
### Adding Images

Images can be added to your HTML page using the Image source tag. Let's try adding an image in the example below.

Using the image tag shown in the chart above, fill in the quotes with the url of the image you would like to add to your page, doing show should result in something like this.
-Example <img src="http://1.bp.blogspot.com/-LElg66bdQRA/T3v3KRxrI4I/AAAAAAAABuw/zGM13l1fwjE/s1600/Mountain+Sunrise+Wallpapers+1.jpg">
### Adding Links

Links can be added to your page using the "a href=" tag. The url for the link you wish to add should be inserted after the equals sign within the opening tag. In between your opening and closing link tags is where you will need to add the Text that your hyperlink will be attached to. 
### Hosting and Publishing

Once you have completed your HTML page to your liking, it is time to publish the page for the world to see! This can be done using either an editor with built in publishing functionality or a content managment service of your choosing. Publishing is done using FTP or File Tranfer Protocol which allows you to connect to your host site and transfer files.  As previously mentioned, , all you need to do is connect to your the domain that you will be using and add the new HTML page that you have just created.

![publish page graphic](https://th.bing.com/th/id/OIP.tbVvMhkhL9wMmpaUlqHOSQHaE6?pid=Api&rs=1)

**Congratulations, you just created and published your first HTML page!**
