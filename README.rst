=======================
theme-jeffmackinnon.com
=======================

The base pelican theme for my site, `jeffmackinnon.com <https://jeffmackinnon.com>`__

There are some variables that you can add to the ``pelicanconf.py`` file that make things look good.

.. code:: python
    
    #
    # JeffTheme variables
    #
    #THEME_COLOUR = 'css-blue' # Leave commented except for the blue option like jmkengineering.com

    ## The search things
    DUCKDUCKGOSEARCHURL = '' # The URL of your site
    ## Sidebar things
    BIO_IMAGE = '' # Make sure that this is in the "images" folder
    ## The Social Things
    SOCIAL_SHARE = True
    SOCIAL_TWITTER = 'jeffmackinnon'
    SOCIAL_GITHUB = 'Jeffmackinnon'
    SOCIAL_LINKEDIN = 'jeffmackinnon'
    SOCIAL_FLICKR = 'jeffmackinnon'
    SOCIAL_MASTODON = 'https://mastodon.social/@jeffmackinnon'
    MICROBLOG = 'microblog' # This isn't used for anything .... yet but I'm thinking of adding a mini-posts for JUST the category here to the sidebar

    #Contact Things
    CONTACT_PHONE_NUM = ''
    CONTACT_EMAIL = ''
    CONTACT_HOME_ADDR = ''
    CONTACT_BUSINESS_ADDR =''


You can copy the entire thing into your ``pelicanconf.py`` file and make the changes for your site. 
