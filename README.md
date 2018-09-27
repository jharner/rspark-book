## rspark-tutorial

`rspark-tutorial` provides content illustrating the use of `rspark`, a Docker-based computing environment. `rspark` runs R, RStudio, PostgreSQL, Hadoop, Hive, and Spark in containers on your local computer (or optionally on AWS). The content covers a range of topics including many aspects of the `tidyverse`, machine learning using Spark, etc.

This tutorial is meant to run in conjunction with `rspark-docker`, which contains images of the `rspark` components. The steps for installing and launching the `rspark-docker` containers is given here:  

[https://github.com/jharner/rspark-docker](https://github.com/jharner/rspark-docker)  

To get access to the tutorial content within `rsaprk-docker`, do the following within the [rspark-tutorial](https://github.com/jharner/rspark-tutorial) repo:

1. Click on the `Clone or download` green button and then click on the `Open in Decktop` button. Alternately, you can click on the `Download Zip` button, but this does not provide a local `git` repo.  

2. Click on the `Files` tab in RStudio and then click the `Upload` menu item. Navigate to a zipped version of `rspark-tutorial` and upload. (This step assumes you are running and logged into the RStudio container.)  

3. Execute the `.Rmd` files in the various modules/sections to generate R notebooks of R markdown files.

Note: If you have `git` installed, you can issue the following command in a terminal to clone `rspark-tutorial`:  

`git clone https://github.com/jharner/rspark-tutorial.git`

If you have cloned `rspark-tutorial`, you will be able to pull updates by issuing the following command:

`git pull origin master`

If you want an excellent Git GUI, then download and install: [Sourcetree](https://www.sourcetreeapp.com).





