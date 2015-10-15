# VIP Big Data and Learning Analytics

### Evaluating MOOCDB for Coursera Data - [Main Docs](http://moocdbdocs.readthedocs.org/en/latest/)

#### Evaluation Notes
* The Piping scripts provided combines the data - [Anonymized Forum, Anonymized General, Hash Mapping] provided by coursera for a particula course into a Target database of our choosing.
* 

#### Database Schema Visualized 
- Moocdb Core and Schema (Moocdb Clean) : is used by all transformation tasks; Import once and use many times [1, 2]. 
- Target (Moocdb Output) : Data after transformations are put into this database for future analysis [3].

1. [moocdb_clean](https://github.com/4ni1/vip/blob/master/schema/moocdb_clean.pdf)
2. [moocdb_core](https://github.com/4ni1/vip/blob/master/schema/moocdb_core.pdf)
3. [moocdb_output](https://github.com/4ni1/vip/blob/master/schema/moocdb_output.pdf)

#### References
1. [Developing Standards and Systems for MOOC Data Science](http://arxiv.org/pdf/1406.2015.pdf)
2. [Case Study on edX Circuits and Electronics](http://groups.csail.mit.edu/EVO-DesignOpt/groupWebSite/uploads/Site/MoocshopCamera.pdf)
3. [Mooc VIZ: Large Scale Open Access Collaborative Data Analytics Platform for MOOCs.](http://francky.me/doc/NIPS2013_education-workshop_MoocViz.pdf)
4. [Mooc Images](http://francky.me/doc/MOOCEnImages2013.pdf)
5. [Moodb Presentation](http://www.slideshare.net/srecko/moo-cdb)
6. [MoocDB, DiscourseDB, DataShop](http://cra.org/wp-content/uploads/2015/08/koedinger.pdf)



