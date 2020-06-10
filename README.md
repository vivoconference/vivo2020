# VIVO 2020 Conference website

## About the conference

The 11th annual VIVO Conference will be held on-line June 16-17.  To join the organizing committee, please see [the conference task force page](https://wiki.lyrasis.org/display/VIVO/VIVO+Conference+2020+Task+Force) in the VIVO wiki.

## About the site

This site is built using [Zeppelin](https://github.com/gdg-x/zeppelin) a Jekyll framework.  To work on the site you will 
need Ruby, gem, and Jekyll installed.  See https://jekyllrb.com/.

## OpenReview

The conference has been using [OpenReview](http://openreview.net) to manage submissions, reviews, and acceptance.  
Data from OpenReview can be mined using 
python and [their API](https://openreview-py.readthedocs.io/en/latest/#)

## Local hosting

Clone this repository and edit `_config.yml` to run locally.  You will need to change the baseurl to `""` and url to `""`. All site Urls should be relative and resolve appropriately. 

Use

    bundle exec jekyll serve
    
to start a local copy of the site running at `localhost:4000`

If you have modified `_config.yml` to run locally, be sure to restore the url values in any commit so the site will run remotely.  baseurl should be set to `/vivo2020` and url should be set to `http://vivoconference.org`
