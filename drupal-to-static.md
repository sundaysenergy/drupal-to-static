Dear Client,

I want to give you more background and context to what we have been offering, and what we are proposing for the future.

Shifting to a new site infrastructure can certainly prompt some questions. I think the benefits can be better understood by breaking it down into four sections: Reasons why Drupal may not be the best option now, what we are proposing, what it will look like to you, and the benefits of this new setup.

___

### First, why not Drupal?

Drupal has been a great tool for us, and enabled us to build some really powerful web applications. However, using Drupal for a site like yours is a bit like trying to hang a picture frame with a sledge hammer and railroad spike. Drupal creates "dynamic" sites - dynamic in the sense that each time a person views a page, software on a server rebuilds the page specific to that user at that time.

To accomplish this, we must maintain a large stack of specialized software. Each component requires a significant amount of effort to keep performant and secure. Because Drupal sites are a living thing, they are vulnerable to attack by spammers and hackers. This creates a liability to you as the site owner, and to us as the web host.

Simply stated - for the rates we have been charging, there is no additional allowance for maintaining the software. Sites have been allowed to linger on old software, yielding unpredictable results and potential security breaches.

Consider that our upgrade path to the *newest Drupal 5* is more expensive than converting to a cloud based infrastructure. Also, consider that that is only the latest version of software that is no longer supported. It would be akin to saying, *I've patched my Windows 98 operating system with all of the latest features and bug fixes*. Eventually, it's going to become unreliable or dangerous for both of us.

Upgrading to Drupal 7 requires adapting your old site to a relatively rigid framework, resulting in either a large bill or aesthetic compromises. Furthermore, to avoid similar situations in the future, a more expensive maintenance package must be implemented to ensure that the site is running on the latest software.

Since Drupal is modular, any one of the twenty or so building blocks can be updated or no longer maintained on any given day. This requires constant maintenance, supervision, and re-implementation of given features.

So, why not Drupal? It's a great solution for a site that requires complex permissions, many users with different "roles", and is frequently updated. However, for a smaller site, there are simply better, more appropriately scaled solutions.

___

### What we are proposing

Our answer is a service that takes a folder of text files and images, and dynamically turns this into a website. The website is rebuilt every time the content changes *instead* of every time someone accesses a page. This enables us to make every part of the website static.

In this way, we are able to push the entire site out to a global Content Delivery Network (CDN). This puts your site on dozens of servers across the world instead of a single set of servers. Combined with DNS, the CDN is all that is required to host the website.

We feel like this is an awesome offering, and a great alternative for websites that don't really need Drupal. We are including enterprise DNS (using Dyn.com), a compiler server that turns text files into websites, and we're pushing the entire website to a CDN for $6/mo or $60/yr.

___

### What it will look like to you

There are a few possible scenarios, but we will explain how this will work using most feature-rich option. Rather than logging into a website, you will install a cloud-based application that will allow you to both edit your existing content and create new content.

This will look like any other folder on your computer, except that the content will be available on any device, including computers, iPads, or a smart phone.

Because we are promoting a simplified Markdown editor, you can create and edit content in any editor of your choice. There are many applications, and we are happy to recommend a few options. I will expand on different formats for editing content in the next section.

When you have finished editing or creating your file, you save it just like any other file. What happens next is exciting. The revisions are sent to a repository where *all* of your revisions are stored. From here, your website is reconstructed and published to your hosting company.

This all happens transparently and quickly. That's it. When you log on to another device, your new files will be there waiting for you.

___

### Benefits of the new system

I alluded to some benefits in the above section, but the following is a more complete list:

- Speed. Drupal and other content management systems re-generate each page of a website each time it is visited. Even with the most advanced hardware, it is going to take longer to put a bunch of pieces together than to display an individual page. The new system generates each page only when content is changed. Furthermore, it does this in the background and only serves it to the viewer once it has completely generated. This keeps hosting costs low and performance high.

- Reliability and redundancy. Isolating the generation of content allows us to host your site on a server that does only one thing, and it does it extraordinarily well. All of your site revisions are stored at one of the two largest revision management websites on the Internet and will be available to you, should you need them. 

- Flexibility. You can use any editor, on any device. Want to edit Drupal content on an iPad? It's probably not going to work very well. However, with cloud integration and one of several available editors, you can easily work on the go and have your changes waiting for you on your home computer, in your office, or wherever else you might want to access them.

- Cost. Costs are consistent and features can be added quickly and predictably. The expense to maintain the software that generates your site is eliminated. Also new layouts can easily be produced for the entire site or individual pages. With content management systems, there are two approaches to billing -- pay a lot of money each month to keep things updated, or charge very little but allow software to become old and obsolete so eventually there is a dramatic expense to convert the entire site (or it catastrophically breaks). Under the new system, there won't be any such surprises.

___

### Expense breakdown

Since we are talking about hosting expenses, I'd like to walk through our pricing structure (and how it impacts Drupal hosting).

* DNS hosting is an undervalued service that serves the sole function of pointing your purchased domain names to a server on the internet. There are many free services available, but you get what you pay for. Low cost services often cause problems at the most inconvenient times, and then we get blamed for the outage. "Hey, my website is down. You are hosting my site, fix it." Well, it might be that your domain name isn't properly sending traffic to the right place, or any place. It's just not worth it for us to answer those phone calls and emails for something that isn't our fault and we have no control over. For that reason, we have standardized on using the most reliable DNS service in the industry. It's called Dyn, and is the same one used by sites like Amazon and Twitter. In the 11 years Dyn has been in business, they have not had any downtime. That's a mammoth statement for any web service. We charge $3/mo for this service. Purchasing directly from Dyn, it is $30/mo http://dyn.com/dns/dynect-managed-dns-lite . This is technically an optional service since you could choose to manage your DNS elsewhere, but we would not be able to guarantee your site's availability if you did.

* Our Drupal hosting stack consists of many layers. Firewalls, load balancer, front-end cache, PHP Opt-Code caching, performance optimized versions of PHP, MySQL, and Drupal. Combined with a control panel for managing installations, this sits on redundant servers that use a hybrid of Solid State drives (SSD) and 15K RPM SAS drives.

* Drupal requires constant maintenance. Added features, security fixes, and performance improvements are the norm and happen almost weekly. Site owners very rarely want to be involved with the hassle of creating a development site, putting all the updated code on the development site, testing, and then migrating the live site to the updated code base. For that reason we have started requiring the purchase of a maintenance package that starts at $1/mo per enabled module. Most sites have 10-or-more modules enabled. This prevents us from having to send emails about outdated Drupal installations that need updates for us to be able to continue hosting them.

For hosted sites not using Drupal, we offer these options:

* To keep sites fast, we have the option to push all the site assets that aren't generated dynamically to a global Content Delivery Network. This is for things like images, cascading style sheets, and JavaScript files. It keeps the site load times fast because these files are delivered from a server closest to the website visitor. We charge $6/mo or $60/yr for this service.

* For an additional $6/mo, or $60/year, we have started offering dropbox.com integration. This allows putting your website files into your Dropbox account. You can then edit the files on your computer, and when saved they automatically get synched to your website. Included with the synching of files is the ability to assign actions to Dropbox folders. These can do a variety of things from resizing images to renaming files to be websafe. Our newest feature is the ability to generate a website from a folder of plain text files. Each text file represents a page on the site. These files can contain plaintext, [markdown](), or html code - whichever format you wish to work in.

Other pricing changes...

* Custom domain names are going to cost $13 per year now. This is just a couple dollars more than the right-wing, woman-objectifying GoDaddy service, and provides us easy access to make changes when needed.
