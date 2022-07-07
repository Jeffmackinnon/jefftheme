=======================
theme-jeffmackinnon.com
=======================


The base pelican theme for my site, `jeffmackinnon.com <https://jeffmackinnon.com>`__

There are some variables that you can add to the ``pelicanconf.py`` file that make things look good.

.. code:: python

    #
    # Theme variables
    #
    ## The search things
    DUCKDUCKGOSEARCHURL = 'Your URL'
    BIO_IMAGE = 'image' # Make sure that this is in the "images" folder
    ## The Social Things
    SOCIAL_TWITTER = 'jeffmackinnon'
    SOCIAL_GITHUB = 'jeffmackinnon'
    SOCIAL_LINKEDIN = 'jeffmackinnon'
    SOCIAL_MASTODON = 'https://bluenoser.me/@Jeff'

    #SOCIAL_FLICKR = ''
    #MICROBLOG = ''
    CONTACT_PHONE_NUM = '+# (###) ###-####'
    CONTACT_EMAIL = 'name@url.tld'
    #CONTACT_HOME_ADDR = ''
    #CONTACT_BUSINESS_ADDR =''

    THEME_COLOUR = 'css-blue' # There are only 2 colours right now, pink and blue. Pink is Default
    SITELICENSE = '' # Change to what you want.
    #
    #Frontpage customization
    #
    TAGLINEHEAD = 'This is a header'
    TAGLINE = 'This is the tagline'
    CORNERSTONE_CONTENT = True # If true add the html you want in include/cornerstone.html
    NEWSLETTER = '' # Put the HTML or JS from your provider here.
    INCLUDECATEGORY = True # This includes the Category in the article list
    MOREBUTTON = True #This adds the "MORE" to the article list

    # That's all folks


You can copy the entire thing into your ``pelicanconf.py`` file and make the changes for your site. 
