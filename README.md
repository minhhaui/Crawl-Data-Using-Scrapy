# Crawl-Data
Using Scrapy FrameWork crawl question in StackOverFlow

# INSTALL DEPENDENCY
   
   pip install scrapy
   
   Start project:
  
      scrapy startproject stack

# Tree Project:

  crawl-data/
    scrapy.cfg            # deploy configuration file

    stack/                # project's Python module, you'll import your code from here
        __init__.py

        items.py          # project items definition file

        middlewares.py    # project middlewares file

        pipelines.py      # project pipelines file

        settings.py       # project settings file

        spiders/          # a directory where you'll later put your spiders
            __init__.py
            stack_spiders.py
 
 # Run crawler:
  
          scrapy crawl "name"
          -----
          scrapy crawl stack



