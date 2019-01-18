# FlickrBulkProcessor
If you decided to quit Flickr, and had already download the zip files (their archive), this [notebook](https://jupyter.org/) attempts to extract the zip files, and organize your photos the way how you did it in Flickr. Note that comments, and tags are not processed in this notebook.

Sure, you can expand it to perform as such.

## Instructions
* Login to your Flickr account, and "download your data" per their instructions. This process may take a few days. When they are ready to give you your data, links will appear in your Settings.

* Download all zip files into a folder, where you will perform your "work". These are big zip files and can sometimes get corrupted. It may help if you do this in the cloud (i.e. if you have a VM somewhere) rather than your PC especially if your internet connection is slow. Also, blindly extracting the files (i.e. the pictures) will work just fine, except that they are not organized per album. Go figure!

* Once all the files are in one folder, download/clone/copy and paste the notebook file [Process Flickr Data.ipynb](Process%20Flickr%20 Data.ipynb) into your work folder as well.

* At this time of writing, the code is designed to handle the data structure described in the json files. That may change...
