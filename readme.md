## Install s3cmd

1. [Download s3 cmd package](http://s3tools.org/download)
2. Unzip the folder
3. `cd` into the unzipped folder and from command line, run `sudo python setup.py install`

## Configure s3cmd

Follow the instructions for configuring s3cmd over at http://s3tools.org/s3cmd

## To sync S3 bucket to a local folder

`s3cmd sync s3://bucket-name ~/Downloads/s3-download-folder-name`

## To package a local folder as an epub

**Note:** If you're using this theme as a framework, you'll need to change the `META-INF-example` folder name to `META-INF` before packaging the epub.

From within the folder, run `zip -r pocket.epub *`