# Apache Stanbol for Drupal

Contains [Apache Stanbol](http://stanbol.apache.org/) pre-configured for use with [Drupal](http://drupal.org).

## Download
You can download the latest package [here](https://github.com/fago/stanbol-for-drupal/archive/master.tar.gz).

## Installation
1. Download the latest [stanbol-for-drupal](https://github.com/fago/stanbol-for-drupal/archive/master.tar.gz) package and extract it.
2. Run java -jar org.apache.stanbol.launchers.stable-0.10.0-SNAPSHOT.jar

That's it. After a few seconds your stanbol instance should be up and running. Access it via http://localhost:8080


## What has been pre-configured?
This packages ships with a few config files that Apache Stanbol picks up automatically. That way, a "drupal" site is added to the entityhub which can be used to index Drupal's content in Stanbol. Next, the default enhancement chain has been pre-configured to link to Drupal's content also. This is done by an EntityHub-Linking engine that has been configured to use the Entithub site of Drupal and is added to the default enhancement chain.
