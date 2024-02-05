# FAQ

**What is Focus for?**  

Focus allows you to build your own search tools using a genuine web index. It’s an update of something that we previously called Personal Search, [first released in 2006](https://web.archive.org/web/20060220233451/http://www.mojeek.com/mps). 

From the easy-to-use interface you can:

- choose which sites to search across.
- choose parts of these sites you don’t want to see results from, such as particular subdomains.
- choose sites you don’t want to see results from.
- set up Focus search tools for different types of search tasks.
- save and restore your Mojeek Focus creations, easily moving them to another computer or browser.
- share your Mojeek Focus creations with others.
- use and edit a set of templates provided by both the Mojeek team and other users through this repo.

**How do I submit without a Github account?**  

Github and other similar developer platforms can be very useful for this kind of collaborative work, but we understand that they are not for everyone. If you've created something you really think would be better of shared with others, please get in contact via the [contact page](https://www.mojeek.com/about/contact) or [Community](https://community.mojeek.com/).

**What is Site Clustering and how does it affect Focus?**  

Site Clustering refers to the grouping of results from the same host in order to create a greater variety of websites in results. In a regular Mojeek web search, hosts are clustered; when using Focus, clustering is off by default. You can modify how much or little clustering happens by changing settings in your Focus Dashboard. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/result_clustering.png">

Your Dashboard clustering settings will not be carried across to other users, so please bear this in mind when submitting.

**Can I use Focus like !bangs?**

There is not currently a way to do this through Mojeek, but with both Gecko (Firefox, LibreWolf, Mullvad) and Chromium (Chrome, Brave, Vivaldi) browsers you can add *keywords* for searches, which allow for a key press, or series of key presses, to trigger the use of a specific search engine. You can use this functionality with Focus, and this is how some people have told us they've incorporated Focus engines into their setup. You can also use the *Search bar* option in your [Focus Dashboard](https://www.mojeek.com/focus/dashboard) to have your Focus engines appear on both the homepage and search engine results page in the bar itself. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/focus_search_bar.png">

**Can I use Focus through a search box?**

Yes, the ```?foc=``` parameter means that a Focus can be used as a part of a site-hosted search box, or through the search bar in your browser if you see benefit from that. In order to do this you need to make sure that, as well as ```%s``` to indicate where a query goes in a string, you also add ```&foc=``` and then the name or parameter of the Focus in question, for example ```&foc=Dictionary```. 

**Why 25 sites?**

For the initial release of Focus creations were limited to 25 sites as they need to be stored as a cookie. Uncapping this limit would be difficult, with there being a hard limit of 4096 bytes across browsers, and other problems arising if cookies are extremely long in terms of handling a Focus. This does not mean that this limit is permanent, and if there are sufficient requests then we will look into how this could be addressed to provide more functionality. 

**Can I use Focus just to exclude sites?**

You can do this, it is not really what exclusions are for, but will work that way. Exclusions are really for pulling out a subdomain or similar which is irrelevant i.e. searching across ```example.com``` but not ```developer.example.com```. 

**Why isn't example.com appearing in my Focus? I added it in**

Focus is limited to searching across websites and pages that we currently have in the index, so this probably explains why you're not seeing the site in question, but please do [get in touch](https://www.mojeek.com/about/contact) to troubleshoot further. You can also check yourself by performing a ```site:``` search as [outlined here](https://blog.mojeek.com/2015/03/how-to-submit-your-site-to-mojeek.html).

**Can you crawl it then?**

Mojeek automatically discovers websites during its crawl of the web, for this reason there is currently no way to manually submit a site to Mojeek. If you think there is a glaring omission then please let us know, sometimes there are issues with crawling sites such as robots.txt blocks. 

**Can you add feature X?**

Propose it to us via Issues, the [contact page](https://www.mojeek.com/about/contact) or [Community](https://community.mojeek.com/), let's see! 

**What is unlikely to be accepted?**

Focus creations which are likely to violate our unbiased stance or cause other issues due to their inclusion will not be added into the preset templates. These are tools built by the wider Mojeek community, but when someone looks at the bank of templates without prior knowledge they will think they came from us. We hope that polite discussion here on Github or in the Community will mean that interventions of this nature are few and far between. 
