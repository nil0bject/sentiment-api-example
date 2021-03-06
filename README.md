## 3scale Example Sentiment API

This is the top level README file which provides an index to the versions available. Check out the version that interests you here: 

 * Version 0: Original Sentiment API example, using Sinatra <a href="version_0/README.md">[README]</a>.

 * Version 1: First video example using GRAPE, 3scale and Heroku <a href="version_1/README.md">[README]</a>.

 * Version 1: Second video example adding proper sentiment analysis and API Analytics <a href="version_2/README.md">[README]</a>.

The API is meant to serve an example of how you can easily create an API, and how you can use the free 3scale platform to control, manage and monitor the operations of the API so that you only have to do the fun part.

The original sentiment values are taken from the dataset AFINN-111.txt from [Technical University of Denmark](http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010).

##Notes

 * From Version 1 onwards the code can be run on Heroku but to facilitate this config.ru, procfile etc. need to be in the top level directory. This is done using symlinks. If you want to run a specific version locally simply change to that directory. If you want to run a version on Heroku, update the symlinks to point to the right directory and then run.