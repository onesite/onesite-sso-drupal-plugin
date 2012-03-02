ONEsite SSO provides a powerful single sign-on solution for your Drupal-powered sites. Extend the capabilities of your site to easily engage with new customers, create a vibrant community around your products, and increase customer conversions.

FEATURES
--------
* Give your users a single, seamless, login for all of your sites.
* Authenticate users via Facebook, Twitter, MySpace, and other OpenID providers.
* Allow your users to link multiple social accounts to their master account.

This module will override the default login and registration forms providing, instead, a link to launch the ONEsite Social Login modal window. This modal will be responsible for authenticating and registering a user on your site.

REQUIREMENTS
------------
A development key is required to interact with any of the ONEsite services. You can register for a development key at [http://www.onesite.com/node/ssoSignup)](http://www.onesite.com/node/ssoSignup).


INSTALLATION
------------
### Step 1: Setting up your ONEsite account
1. <a href="http://www.onesite.com/">Contact ONEsite</a> to create an account.
   You will receive a devkey.
2. For social integration:
	1. You will need to set up your own 'applications' on each of the
	   Social Networks you would like to integrate with on your site.
	2. Log in to the ONEsite control panel.
	3. Go to this page: "Social Integration" > "Settings"
	4. Enable each of the providers you require. Make sure you enter any
	   required API keys or integration info for each provider.
	   

### Step 2: Installing the ONEsite SSO module on your Drupal site
1. Download the module and
   <a href="http://drupal.org/documentation/install/modules-themes/modules-7">install per the usual process</a>.
2. Go to Home > Administration > ONEsite SSO.
3. Paste the ONEsite SSO Devkey you received from creating your ONEsite account and hit "Save".

At this point Drupal will connect to the ONEsite servers to discover details about your account and will automatically adjust the other (advanced) settings.
