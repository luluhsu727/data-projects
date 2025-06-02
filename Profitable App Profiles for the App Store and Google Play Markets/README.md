# Profitable App Profiles for the App Store and Google Play Markets

## Introduction
* A company builds Android and iOS mobile apps that are available on Google Play and in the App Store. All apps built are **free** to download and install for English-speaking audience. The main source of revenue of A company consists of **in-app ads**. This means the more users who see and engage with the ads, the better.

* The aim of the project is to analyse data to help the developers understand what type of apps are likely to attract more users.

## Data source and description
* Two datasets are used in this project. One from GooglePlay whilst the other from AppleStore. 
* Link to download the GooglePlay data here: [Link](https://www.kaggle.com/datasets/lava18/google-play-store-apps). You can also find data documentation to help you understand waht each column describes 
* Link to download the AppleStore data here:[Link](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps). You can also find data documentation to help you understand waht each column describes

## Data details 
**googleplaystore.csv**

|Column|Description|
|------|-----------|
|App|Application name|
|Category|Category the app belongs to|
|Rating|Overall user rating of the app (as when scraped)|
|Reviews|Number of user reviews for the app (as when scraped)|
|Size|Size of the app (as when scraped)|
|Installs|Number of user downloads/installs for the app (as when scraped)|
|Type|Paid or Free|
|Price|Price of the app (as when scraped)|
|Content Rating|Age group the app is targeted at - Children / Mature 21+ / Adult|
|Genres|An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Famil|
|Last Updated|Date when the app was last updated on Play Store (as when scraped)|
|Current Ver|Current version of the app available on Play Store (as when scraped)|
|Android Ver|Min required Android version (as when scraped)|

**Mobile App Store**

|Column|Description|
|------|-----------|
|id|App ID|
|track_name|App Name|
|size_bytes|Size (in Bytes)|
|currency|Currency Type|
|price|Price amount|
|rating_count_tot|User Rating counts (for all version)|
|rating_count_ver|User Rating counts (for current version)|
|user_rating|Average User Rating value (for all version)|
|user_rating_ver|Average User Rating value (for current version)|
|ver|Latest version code|
|cont_rating|Content Rating|
|prime_genre|Primary Genre|
|sup_devices.num|Number of supporting devices|
|ipadSc_urls.num|Number of screenshots showed for display|
|lang.num|Number of supported languages|
|vpp_lic|Vpp Device Based Licensing Enabled|
