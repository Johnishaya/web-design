# web-design
Hello world!

How is JavaScript different from Java?
The JavaScript programming language, developed by Netscape, Inc., is not part of the Java platform.
JavaScript does not create applets or stand-alone applications. In its most common form, JavaScript resides inside HTML documents, and can provide levels of interactivity to web pages that are not achievable with simple HTML.
Key differences between Java and JavaScript:
•	Java is an OOP programming language while Java Script is an OOP scripting language.
•	Java creates applications that run in a virtual machine or browser while JavaScript code is run on a browser only.
•	Java code needs to be compiled while JavaScript code are all in text.
•	They require different plug-ins.
For additional information about JavaScript, visit Mozilla.org
________________________________________
JavaScript Error javascript.JSException: Unknown name
When loading the webpage an error is displayed:
JavaScript Error javascript.JSException: Unknown name


Possible causes:
1.	JavaScript is not enabled in the browser.
2.	The browser does not support JavaScript technology.
3.	The web page has a JavaScript programming error.
If JavaScript is already enabled in the web browser, then the error message indicates that there is a programming error in the JavaScript code. Contact the webmaster of that site to report the error including:
1.	Error message
2.	Type and version of the browser used
3.	URL of the web page that displayed the error message
4.	Steps to reproduce the error
10 difference between Java and JavaScript for Programmers
Programmers, developers and internet users  have always been confused between Java and JavaScript.  Many people still thinks that JavaScript is part of Java platform, which is not true. In truth, JavaScript has nothing to do with Java, only common thing between them is word "Java", much like in Car andCarpet, or Grape and Grapefruit. JavaScript is a client side scripting language for HTML, developed by Netscape, Inc, while Java is a programming language, developed by Sun Microsystems. James Gosling is Inventor of Java, popularly known as father of Java. While in today's world calling JavaScript just a client side scripting language would not be good, as its now been used in servers also using node.js and people are doing object oriented development in JavaScript, but that was what it was originally developed. There are several difference between Java and JavaScript, from how they are written, compiled and executed. Even capability of Java and JavaScript vary significantly. Java is full feature Object oriented programming language, used in almost everywhere, starting from programming credit card to server side coding. Android uses Java as programming language for creating Android apps, Swing is a Java API used to create desktop applications and Java EE is a Java platform for developing web and enterprise applications. On the other hand JavaScript is primarily used to bring interactivity into web pages, though there are other alternatives like Flash, JavaScript is the most popular one and regaining lots of ground lost earlier with introduction of powerful and easy to use libraries like jQuery and jQuery UI. You can use JavaScript to validate user input, create animation and cool effects in HTML page and can do lot of interactive stuff e.g. reacting on button click, mouse movement, image click etc. In this article, I will share some key differences between Java and JavaScript, mostly from a programmers perspective.


Difference between Java vs JavaScript
Here is my list of key differences between JavaScript and Java as programming languages. I have worked both on them, mainly used Java for all Server Side development, Android and JavaScript for writing client side scripts to do validation, interactivity, animation and ajax calls.
 


1) Execution Environment
First difference between Java and JavaScript is that Java is compiled + interpreted language, Java code is fist compiled into class files containing byte code and than executed by JVM, on the other hand JavaScript code is directly executed by browser. One more difference which comes form this fact is that, Java is run inside JVM and needs JDK or JRE for running, on there other hand JavaScript runs inside browser and almost every modern browser supports JavaScript.




2) Static vs Dynamic Typed language
Another key difference between JavaScript and Java is that, JavaScript is a dynamic typed language, while Java is a statically typed language. Which means, variables are declared with type at compile time, and can only accept values permitted for that type, other hand variables are declared using vary keyword in JavaScript, and can accept different kinds of value e.g. String, numeric and boolean etc. When one variable or value is compared to other using == operator, JavaScript performs type coercion. Though it also provides === operator to perform strict equality check, which checks for type as well. See herefor more differences between == and == operator in JavaScript.




3) Support of Closures
JavaScript supports closures, in form of anonymous function. In simple words, you can pass a function as an argument to another function. Java doesn't treat method as first class citizen and only way to simulate closure is by using anonymous class. By the  way Java 8 has brought real closure support in Java in form oflambda expression and this has made things much easier. It's very easy to write expressive code without much clutter in Java 8.




4) OOP
Java is an Object Oriented Programming language, and though JavaScript also supports class and object, it's more like an object oriented  scripting language. It's much easier to structure code of large enterprise application in Java then JavaScript. Java provides packages to group related class together, provides much better deployment control using JAR, WAR and EAR as well.




5) Right Once Run Anywhere
Java uses byte code to achieve platform independence, JavaScript directly runs on browser, but code written in JavaScript is subject to browser compatibility issue i.e. certain code which work in Mozilla Firefox, may not work in Internet Explorer 7 or 8. This is because of browse based implementation of JavaScript. This was really bad until jQuery comes. Its a JavaScript library which helps to free web developers from this browser compatibility issues. This is why I prefer to write code using jQuery rather than using plain old JavaScript code, even if its as simple as calling getElementById() orgetElementByName() methods to retrieve DOM elements.




7) Block vs Function based Scoping
Java mainly uses block based scoping i.e. a variable goes out of scope as soon as control comes out of the block, unless until its not a instance or class variable. On the other hand JavaScript mainly uses function based scoping, a variable is accessible in the function they are declared. If you have a global variable and local variable with same name, local will take precedence in JavaScript.




8) Constructors
Java has concept of constructors, which has some special properties e.g. constructor chaining and ensuring that super class constructor runs before sub class, on the other hand JavaScript constructors are just another function. There is no special rules for constructors in JavaScript e.g. they cannot have return type or their name must be same as class.




9) NullPointerException
JavaScript is much more forgiving than Java, you don't have NullPointerException in JavaScript, your variable can accept different kinds of data because of JavaScript is dynamically typed language.




10) Applicability
Last but not the least, JavaScript has it's own space, sitting cozy along with HTML and CSS in Web development, while Java is everywhere. Though both has good number of open source libraries to kick start development, but jQuery has certainly brings JavaScript on fore front.


That's all on difference between Java and JavaScript language. As I said, they are totally different language, one is a general purpose programming language, while other is scripting language for HTML. Though you can do lot of fancy stuffs using JavaScript, you still don't have features like multithreading, as compared to Java. By the way JavaScript was originally named as Livescrpit, may be due to the fact that it makes your HTML pages live, and programming world would certainly be free of this confusion, had Netscape hadn't renamed LiveScript as JavaScript.
You might like:
•	How to remove duplicates elements from ArrayList in Java
•	10 Articles Every Programmer Must Read
•	Top 30 Java Phone Interview Questions Answers for Freshers, 1 to 2 Years Experienced
•	How to find middle element of LinkedList in Java in one pass
Posted by Javin Paul   
Email This BlogThis! Share to Twitter Share to Facebook 
Labels: HTML and JavaScript , interview questions , java
7 comments :
oops said...
This post gives me a feeling that its pretty out of date.
Javascript has broken beyond the boundaries of browser and a lot of things mentioned are no more applicable with the advent of nodeJS. (Ex: 5 states that JavaScript directly runs on browser).
Makes me feel that you tried Javascript, did not like and this a page about why one should stick to Java and Javascript only belongs to browser.
March 23, 2015 at 10:18 AM
Anonymous said...
Dude its 2015 not 2005.
March 24, 2015 at 12:34 PM
Nimnio said...
@oops, you did not read the entire post. You missed "While in today's world calling JavaScript just a client side scripting language would not be good, as its now been used in servers also using node.js and people are doing object oriented development in JavaScript, but that was what it was originally developed."

I believe this article was written for those who truly do not know what the difference is between Javascript and Java. Javascript developers are probably surprised that those people exist, but they do. I have an equally fun time explaining what "Java EE" is compared to Java.
March 27, 2015 at 12:14 PM
Anonymous said...
> almost every modern browser supports JavaScript.
*All* modern browsers support JS.

> JavaScript supports closures, in form of anonymous function. 
Anonymous functions have nothing to do with closures. Any function can have a closure.

> It's much easier to structure code of large enterprise application in Java then JavaScript
How? You have one module per file, same thing both languages.

> JavaScript directly runs on browser, but code written in JavaScript is subject to browser compatibility issue i.e. certain code which work in Mozilla Firefox, may not work in Internet Explorer 7 or 8
You are confusing JavaScript the language and the Document Object Model.

> If you have a global variable and local variable with same name, local will take precedence in JavaScript.
Variable shadowing works exactly the same in Java as it does in JavaScript.

> JavaScript is much more forgiving than Java, you don't have NullPointerException in JavaScript
Although JavaScript doesn't have NPE's, the circumstances where you would get an NPE will produce an error. It's simply not called NullPointerException, it's otherwise the same thing.

> JavaScript has it's own space, sitting cozy along with HTML and CSS in Web development, while Java is everywhere.
I have a phone that has an OS where the apps are written in JS. You can program robots with JS. You can program watches with JS.

> By the way JavaScript was originally named as Livescrpit, may be due to the fact that it makes your HTML pages live
Netscape also originally had a server side LiveScript environment, so I'd say your guess is wrong.
April 2, 2015 at 4:30 PM
Anonymous said...
As someone who just learned JS for fun this is a great article with some great discussion points afterwards. Thanks for helping to bring things into perspective guys!
July 15, 2015 at 5:33 PM
subodh garg said...
I found this post outdated and misleading. With the advent of Node.js, JavaScript is now everywhere(front-end, back-end and even mobile development). 
Don't believe me! Go and explore: "MEAN stack" for web development and Ionic/Cordova frameworks for hybrid app development.

P.S. @Javarevisited, Sorry for some harsh feedback here. I am a great fan of your blog and your Java teachings. I myself has learned a lot from your posts. Thank you for these posts. They are really helpful but for this post particularly, I found it quite misleading. Finally, we all are learners in this vast ocean of knowledge ;)
April 13, 2016 at 3:46 AM


Read more: http://javarevisited.blogspot.com/2015/03/10-difference-between-java-and-javascript-programming.html#ixzz4Og6N33YG
•	
Post a comment
•	Email Article
•	Print Article
•	  Share Articles 
Java vs. JavaScript: Similarities and Differences
By Joe Burns
So... what is the difference between Java and JavaScript anyway?
They are both similar and quite different depending on how you look at them. First their lineage:
Java is an Object Oriented Programming (OOP) language created by James Gosling of Sun Microsystems. JavaScript is a scripting language that was created by the fine people at Netscape and was originally known as LiveScript. JavaScript is a (very) distant cousin of Java in that it is also an OOP language. Many of their programming structures are similar. However, JavaScript contains a much smaller and simpler set of commands than does Java. It is easier for the average weekend warrior to understand. 
You may be wondering what OOP means by now. Object Oriented Programming is a relatively new concept, whereas the sum of the parts of a program make up the whole. Think of it this way: you are building a model car. You build the engine first. It can stand alone. It is an engine and everyone can see it's an engine. Next you build the body. It can also stand alone. Finally, you build the interior including the seats, steering wheel, and whatnot. Each, by itself is a object. But it is not a fully functioning car until all the pieces are put together. The sum of the objects (parts) make up the whole.
Continuing with the model car example, when you built the engine, you didn't use any of the parts that would later build the seats (a 350 four-barrel engine with a seat belt sticking out if the piston would look pretty silly). The point is that all the parts that made up the engine were of a certain class of parts. They all went together. Ditto with the body and then the interior.
The point is that in these languages, you build objects out of classes of commands to create the whole. Understand the terminology? Good. Moving along...
Java and JavaScript are Still Two Different Animals
Now let's talk about how Java and JavaScript differ. The main difference is that Java can stand on its own while JavaScript must (primarily) be placed inside an HTML document to function. Java is a much larger and more complicated language that creates "standalone" applications. A Java "applet" (so-called because it is a little application) is a fully contained program. JavaScript is text that is fed into a browser that can interpret it and then it is enacted by the browser--although today's web apps are starting to blur the line between traditional desktop applications and those which are created using the traditional web technologies: JavaScript, HTML and CSS.
Another major difference is how the language is presented to the end user (that's you when you're surfing). Java must be compiled into what is known as a "machine language" before it can be run on the Web. Basically what happens is after the programmer writes the Java program and checks it for errors, he or she hands the text over to another computer program that changes the text code into a smaller language. That smaller language is formatted so that it is seen by the computer as a set program with definite beginning and ending points. Nothing can be added to it and nothing can be subtracted without destroying the program.
JavaScript is text-based. You write it to an HTML document and it is run through a browser. You can alter it after it runs and run it again and again. Once the Java is compiled, it is set. Sure, you can go back to the original text and alter it, but then you need to compile again.
Java applets run independent of the HTML document that is calling for them (and Java is also what runs many appliances and mobile devices, and does not require a web browser). Sure, they appear on the page, but the HTML document did little more than call for the application and place it. If the programmer allows it, oftentimes parameters can be set by the HTML document. This includes the background color of the applet of the type of text it displays, etc. The delivery of the applet is done through a download. The HTML document calls for the application, it downloads to the user's cache, and waits to run. JavaScript is wholly reliant on the browser to understand it and make it come to life.
The Benefits of JavaScript
In my opinion, JavaScript's main benefit is that it can be understood by the common human. It is much easier and more robust than Java. It allows for fast creation of web page events. Many JavaScript commands are what are known as Event Handlers: They can be embedded right into existing HTML commands. JavaScript is a little more forgiving than Java. It allows more freedom in the creation of objects. Java is very rigid and requires all items to be denoted and spelled out. JavaScript allows you to call on an item that already exists, like the status bar or the browser itself, and play with just that part. JavaScript is geared to web pages. Java is geared toward where it is needed most at the time.
Both will create great web page events. Both can offer interaction between the user and your Web page. But they are not created equally by any means.
So to answer the question of which to use where... use whichever fits your needs. That sounds like a cop-out answer, but remember that the applets and JavaScript are most often offered on the Net as fully functioning items. You simply grab them from the Net and use them on your page (provided you are given permission). There are many, many sites out there that do nothing more than hand out applets or JavaScript. Gamelan.com is a good one for applets. Take a look at javascripts.com for over 2300 free JavaScript scripts. The HTML Goodies Appletand JavaScript Tutorials will teach you how to implement these items on your pages. They will not teach you to write the languages, but rather instruct you on placing functioning applets and JavaScript scripts on your Web pages. It is a good introduction to the formats. Once you know how to get these pups on your pages, you'll understand more about their structures and can then more easily attempt to learn the language and create functioning JavaScripts or applets yourself.
If you feel you're already at the point where you'd like to learn to write JavaScript, stop by theHTML Goodies 30-Day JavaScript Primer Series. I wrote it with a wonderful co-author, Andree Growney. We think you'll like it.
Enjoy!

Make a Comment
•	Miss Anonymoussaid on February 8, 2016 at 12:01 pm
I need a lot more similarities about Java and Javascript. I'm writing a compare and contrast school article, and my scores are really low just because I don't have enough similarities.
Reply
•	Kirk Roystersaid on January 6, 2016 at 4:20 pm
Are we programmers, or are we people delivering value to others? If the latter, then it's a matter of delivering a robust, reliable solution that aligns to an organization's mission and priorities. Javascript enabled me to do exactly this, and didn't have to put up with the programmer egos that show their face in these comments. So everyone, wake up and realize that we work for someone other than the person in the mirror.
Reply
•	Dorkosaid on June 26, 2015 at 1:17 am
Javascript is a butchered down Java for the web, that fact it relates to programming at all is a joke. In fact any scripting language oop or not is not comparable with an actual programming language. Unless you see writing your next operating system in ASP chances are you won't be doing much beyond web. This is why I hate DSL languages "they ultimately suck" and teach folks the wrong way of doing things. Want to learn real programming start with either C or Java not Javascript.
Reply
•	Jasonsaid on November 6, 2015 at 11:54 pm
You are so wrong. Javascript is NOT "butchered" Java, in fact the 2 languages have nothing in common apart from their common style ancestor, C. People (like you) think they are somehow related based on nothing more than their name. Research the history of the name "Javascript", it's a crap name and was derived from "Java" for no valid reason.
Reply
•	ANONsaid on October 30, 2015 at 9:00 pm
So what would you like to consider a programming language. PHP ? Ruby on Rails ? Python ? (or HTML ? lol jk)
Reply
•	Anonymoussaid on August 7, 2015 at 12:02 pm
lmfao, leave it to javafags to defend their awful language. I can agree with you on C stuff, but java is just downright terrible
Reply
•	Arthor Wrightsaid on June 18, 2015 at 10:14 am
Finally, I found explanations of Java and Javascript that I, a common mortal, can understand!
Reply
•	Mauriciosaid on June 3, 2015 at 3:04 am
Dissapointed with this concern because I can not use a bioinformatic App call Dali in WIn8, MacYossemite or Ubuntu14
Reply
•	Anonymoussaid on April 10, 2015 at 5:50 pm
JavaScript is definitely the better one in my opinion. Easier to use and people to learn. Although Java does have more capabilities, many would never be called by the average aspiring programmer.
Reply
•	Bartsaid on October 28, 2014 at 1:15 pm
"Another major difference is how the language is presented to the end user (that's you when you're surfing)." I read "that's you when you're suffering", thinking of Java applets.
Reply
•	Prajwal Msaid on October 15, 2014 at 10:12 am
The text was very useful,comprehensive and resourceful.Analogies and simple language proved very easy to understand even a person who is very much away from computer knowledge.
Reply
•	Mr.Rightsaid on June 18, 2015 at 4:05 pm
Well, OOP makes use of separate objects (i.e. piece of compiled programmes) that each do independent separate functions. (e.g.C++) whereas scripting makes use of text base instructions that are readily understood by the browsers. So, it is safe to say that Javascript is primarily web focused programming language.
Reply
•	Nikhilsaid on October 13, 2014 at 10:01 am
Excellent article Joe. Short and precise. The differences in Java and JavaScript aptly spelled out.Great explanation and examples used.
Reply
•	Srinivas Raj.Gsaid on September 3, 2014 at 1:49 am
It's Really understandable and Good sentences between Java and JavaScript....! Really its good.
Reply
•	sumysaid on April 3, 2014 at 4:08 am
thanks to solve my query,vnice & understandable explanation......
Reply
•	Confusedsaid on March 28, 2014 at 6:59 am
Very poor explanation of Object Oriented Programming (OOP). You begin in a clear manner, but let your metaphor overtake your explanation
Reply
•	Ivansaid on March 22, 2014 at 8:36 am
Very nice explanation you've got. Cleared my mind. Thanks!
Reply
•	ACHUTHANKUTTY Csaid on March 14, 2014 at 12:17 am
I am very much thankful to you. Really I was in confusion whether I can enable Javascript if I buy a new android mobile which doesn't have java.
Reply
•	Pankssaid on March 5, 2014 at 3:37 am
Hi I wanna be learn a javascript but i am not a programming background. so how to i start a learn. Direct learn javascript ya first learn c & c++ then join javascript...please suggest me urgent... Regards Panks
Reply
•	faysal ahmedsaid on April 18, 2014 at 3:00 am
to learn javascript no need to learn c,c++. You can direct learn javascript. JavaScript is an OOP scripting language while c,c++ only programming language. if you want to learn a programming language then i suggest to you learn java. Because it's an oop language which helps to learn javascript. ok!
Reply
•	sumysaid on April 3, 2014 at 4:12 am
hi,no need to do c,c++.as uknow javascriptlanguage isjust like a text,u have to write in a html code.
Reply
•	Noobiesaid on April 2, 2014 at 11:05 am
Use Code Academy, I just started (no coding background) and find it very easy to understand!
Reply
•	Yacoub Seynisaid on March 24, 2014 at 5:07 pm
No, you do not need to learn C or C++ before learning JavaScript.

