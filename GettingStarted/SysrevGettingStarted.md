<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<link rel="stylesheet" type="text/css" href="https://s3.amazonaws.com/sysrev-blog/GettingStarted/gifplayer.css">
<link rel="stylesheet" type="text/css" href="https://s3.amazonaws.com/sysrev-blog/GettingStarted/sidebar.css">
<script type="text/javascript" src="https://s3.amazonaws.com/sysrev-blog/GettingStarted/jquery.gifplayer.js"></script>

<div class="sidenav">
  <a href="#basic_getting_started">Getting Started</a>
  <a href="#more_detail">More Detail</a>
  <a href="#login">Log in and Invite Friends</a>
  <a href="#import">Import Articles</a>
  <a href="#define_labels">Define Labels</a>
  <a href="#pub_project">Public Projects</a>
  <a href="#demo">Full Demo</a>
</div>

<a name="basic_getting_started"></a>
# Getting Started

1. **Create -** Write a title under "Create a New Project" on [sysrev.com](https://sysrev.com)
<img src="https://imgur.com/40q0fq3.png" style="border: 1px solid black;padding:2px">

2. **Import Data -** Search pubmed, upload pdfs, or upload an endnote file under `Manage -> Sources`
<img src="https://imgur.com/oBwFZhT.png" style="border: 1px solid black;padding:2px">

3. **Add Labels** to extract from your articles under `Manage -> Label Definitions`
<img src="https://imgur.com/MAZUzV7.png" style="border: 1px solid black;padding:2px">

4. **Review** Start reviewing your articles on the `Review` Tab.  
Reviewing articles involves reading articles and assigning your label values to these articles.
Sysrev takes care of the order of review and manages multi-person reviews.
<img src="https://imgur.com/vKZ6rGl.png" style="border: 1px solid black;padding:2px">

5. **Search** through your articles on the `Articles` Tab
<img src="https://imgur.com/ctFWDJb.png" style="border: 1px solid black;padding:2px"> 

6. **Track** the progress of your review on the overview page `Overview` Tab
<img src="https://imgur.com/5Si613T.png" style="border: 1px solid black;padding:2px">

These are the basic steps behind creating a Sysrev review.  Below we'll go into some more detail.

<a name="more_detail"></a>
## More Detail
Let's create a project about honey bees.  At the bottom of this document is a gif showing the full process.

<img class="gif" data-wait="true" data-gif="https://imgur.com/kSuCQeR.gif" src="https://imgur.com/owhJ5xI.png">

<a name="login"></a>
### Log in and invite your friends 
Surely you've done this before.  Your friends can register too after clicking your invite link.  You can find your invite link at `Manage -> Invite Link`. BTW you can join our honey bee review at [sysrev.com/register/a8cbb4cf3f07](https://sysrev.com/register/a8cbb4cf3f07)

### Write the title of your project (Manage -> Settings)
This is also easy, but you should know that you can change your title later if you want.  Once you create a project it is given a unique id.  Our honey bee review got the id 5318.  It shows up in the url for your project eg. https://sysrev.com/p/5318. Because this project is `public` anybody can visit the example project.    

<img class="gif" data-wait="true" data-gif="https://imgur.com/0GhMgEl.gif" src="https://imgur.com/6Aq6P7i.png">


<a name="import"></a>
### Import Articles (Manage -> Sources) 
Ok now things are getting a bit more complex.  For now Sysrev lets you add pubmed articles via search, upload lists of pubmed ids, upload endnote xml files, or upload zip files with loads of pdfs.  

You can add multiple data sources.  You can enable data sources or disable data sources.  Disabled data sources won't show up in reviews.  This can be useful for slowly adding more articles over time.  

You can also delete data sources if you think you messed up.   
<img class="gif" data-wait="true" data-gif="https://imgur.com/CcaMFIF.gif" src="https://imgur.com/iaJWWJm
.png">

In the future Sysrev will offer a banquet of data source options.  Upload json, serve your own database, pick from loads of custom data sources.  We're excited about what is possible here, and invite the community to join us in creating more input data.


<a name="define_labels"></a>
### Define Labels
Sysrev is all about refining existing data.  Assigning labels to documents is one way to do this.  You can create, disable, and delete labels on your project.  You can even do this after the review process has started.  We find that people often realize they want more labels than they originally thought after reviewing some papers.  
<img class="gif" data-wait="true" data-gif="https://imgur.com/uR4ZwFX.gif" src="https://imgur.com/7wJYgx7.png">


##### Label Analysis
After you review papers with binary and categorical labels, the counts of yours (and other) reviewer labels show up on the overview page under **Member Label Counts**.  I labeled some papers about honey bees and discovered a lot of sad bees.   
<img style="margin:auto; display:table;" src="https://imgur.com/i1TCoyw.png">

##### Label Export
You can export all of your reviewer labels in csv format under Manage -> Export -> Export User Answers.
We also have a programming interface for this, but the post for that will come later.  
<img style="margin:auto; display:table;" src="https://imgur.com/qYSEXFn.png">

<a name="pub_project"></a>
### Public Projects
The refinement of data is having a transformative effect on all fields of knowledge.  In academia the number of 'systematic reviews' which involve the refinement of medical literature exceeds 30,000  (see [prospero](https://www.crd.york.ac.uk/prospero/)).  Sadly, most of these reviews result in a publication and no more.  The prospero registry can be seen as a kind of graveyard for data.  

By making your projects public you can give them new life.  Other researchers can download your data, and learn new lessons from all your hours of work.  Eventually we will allow users to clone reviews and use reviews as data sources for other reviews resulting in a ecosystem of systematic review. 

You can make your review "public" - which means that anybody can visit your project by going to the url - by visiting `Manage -> Settings -> Project Visibility`.


<a name="demo"></a>
### Full Demo (1 minute)
<img class="gif" data-wait="true" data-gif="https://imgur.com/jo3bJ8g.gif" src="https://imgur.com/Qmi5RMh.png">

<script>$('.gif').gifplayer();</script>
