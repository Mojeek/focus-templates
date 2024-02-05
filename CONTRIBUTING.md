# Focus Contributing Guide

To submit a Focus you can either open an Issue, for whcih there will be a set of boxes to fill out, or you can submit a Pull Request. If you are submitting a Pull Request then please look at the [focus folder](https://github.com/PrivacyDingus/focus-templates/blob/main/focus) which contains ```.focus``` file formats as a reference guide.

### The following items will be required in order to submit a Focus:
- a suggested name for the Focus, we will not be able to use the same name twice
- a suggested description for the Focus i.e. *Dictionary search, Tech Blogs, No Pinterest*
- a set of inclusions, sites that will be included in the Focus
- any exclusions (optional) which might be specific subdomains i.e. search ```.twitter.com``` but not ```ads.twitter.com```
- a link to, or attachment of, an icon - preferably an svg file

## Criteria for Acceptance
In order to be a candidate for the global Mojeek Focus Template Library, a Focus must:
- not replicate like-for-like the functionality of a Focus already in the library
- have a unique name i.e. not be given the same title as a pre-existing Focus template
- have a name and description which are clear and not misleading, or representing a value judgement i.e. a search across Apple properties called *Crap technology*
- not search across x-rated adult content
- not offer functionality which would violate Mojeek's unbiased stance i.e. if a search is created for an election, it should encompass all relevant parties OR if a search is specifically to only look at 'left-wing' news, this must be called out in the title and description.

**This list is not necessarily comprehensive, and will be revisited as the Library grows.** 

## Creating a Focus
Before submitting a Focus, you'll need to create one, and make sure that it does what you want it to do. To do this you'll need to visit your [Focus Dashboard](https://www.mojeek.com/focus/dashboard) and click the *Create new* button.

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/focus_dashboard.png">

You will then be asked to name your Focus, please choose something that is clear, descriptive, and that relates to the purpose that your Focus will have. You can go back and edit this at any time, so if your idea is not quite *there* yet, you can give it a placeholder name. Just remember to edit this before submitting. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/focus_name.png">

In the *Sites to Search* box you enter in all the sites the Focus is intended to search across, one per line up to a limit of 25 in the *Dashboard*. 

You can add any of the following:
Subdomain: ```www.example.com```
Domain: ```.example.com```

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/sites_to_search.png">

In the *Exceptions* box you put sites which the Focus should exclude. This step mainly exists to allow you to exclude subdomains from a Focus, so if you have ```.example.com``` included, but you want to not search across pages from ```developers.example.com``` then this subdomain would go in this box. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/exceptions.png">

Once you're happy with your Focus, press *Save* to return to the Dashboard.

## Testing a Focus
In order to check the utility and functionality of your newly-created Focus, we'd suggest testing it out a bit before submitting. If you have questions or things that don't seem quite right, you can get in touch via our [Contact Page](https://www.mojeek.com/about/contact), [Community](https://community.mojeek.com/), or by submitting an Issue. 

## Submitting a Focus
Once created a Focus lives in your Dashboard; by clicking near the Focus' Name you can expand its box.

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/completed_focus.png">

You then click the button labelled *Backup this Focus*; this tool can also be used to backup your creations if you use other browsers, or regularly clear cookies. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/backup.png">

Your created Focus contains most of the information needed for submitting it here between ```{``` and ```}```   

- The ```" "``` is your title 
- The items after ```i=``` are your inclusions
- The items after ```&e=``` are your exclusions (if you have none then this will not be featured)

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/backup_highlighted.png">

This text can now be used to raise an Issue to submit your Focus, you can find the currently-available templates in the [focus folder](https://github.com/PrivacyDingus/focus-templates/blob/main/focus), here is an example:
  
```# title: Dictionary```  
```# description: Dictionary search```  
```# author: Mojeek```  
```# icon: dictionary```  
  
```i=dictionary.com```  
```i=thefreedictionary.com```  
```i=urbandictionary.com```  
```i=vocabulary.com```  
```i=merriam-webster.com```  
```i=synonym.com```  
```i=thesaurus.com```  

## Icons
A Focus Template will display like the ones below, and so your submission is easier to add if it has an icon with it. 

<img src="https://github.com/PrivacyDingus/focus-templates/blob/main/assets/default_templates.png">

These icons are best as single-colour 16x16 svg files, if this is not possible then please get in touch via our [Contact Page](https://www.mojeek.com/about/contact), [Community](https://community.mojeek.com/) or flag this in your Issue. You can also use websites like [svgrepo](https://www.svgrepo.com/) to find commercial-friendly and royalty free icons, use the *monochrome* search option to take out icons which might display badly when added to the templates. 

If the Focus you're creating would suit an icon that is already in this repo, then grab the name of it from the [icons folder](https://github.com/PrivacyDingus/focus-templates/blob/main/icons) and use that when you submit your issue.

## Editing a Focus
Through using a template you might find a way that it could be improved, through a better description and title, or through adding in more inclusions or exclusions. For example, if your usage of a template consistently returned an irrelevant subdomain, then you might want to help out by proposing a change which excludes this. 

**If you are doing this through an Issue** please use the Issue template for editing a Focus.  
**If you are doing this through a Pull Request** please directly edit the ```.focus``` file in the [focus folder](https://github.com/PrivacyDingus/focus-templates/blob/main/focus).

As with submissions, not all edits will be actioned when it comes to templates. Please be clear in your reasoning as to why the change would improve the user experience of the Focus in question. 