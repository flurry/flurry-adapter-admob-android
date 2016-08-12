Flurry Android Adapter for AdMob and DFP
========================================

### Adapter version 6.4.2 - Updated 2016-08-12

This adapter enables mediation of Flurry ads via the Google Ads SDK for 
[DoubleClick for Publishers](https://developers.google.com/mobile-ads-sdk/docs/dfp/android/mediation-networks) or 
[AdMob](https://firebase.google.com/docs/admob/android/mediation-networks).

### Installation

Download the [library jar](flurryAdapter.jar) file and import it into your project.

This library also requires the 
[Flurry Ads SDK for Android](https://developer.yahoo.com/flurry/docs/integrateflurry/android/), which needs to
be included in your project.


### Mediate Flurry Ads through AdMob or DFP

To integrate Flurry as a mediated network in your AdMob/DFP ad serving, three initial steps are necessary:

1. Integrate Flurry SDK and Flurry adapter for DFP and AdMob into your app.
2. Configure Flurry's Adspace(s). 
3. Configure AdMob to mediate Flurry.

To learn more about these steps, read the Yahoo Developer Network documentation for 
[AdMob](https://developer.yahoo.com/flurry/docs/publisher/mediation/admob/android/) or 
[DFP](https://developer.yahoo.com/flurry/docs/publisher/mediation/dfp/android/).

Changelog
---------

### Version 6.4.2 - 2016-08-12
* Supports Google ads v2 mediation APIs
