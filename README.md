ONEsite SSO provides a powerful single sign-on solution for your Drupal-powered sites. Extend the capabilities of your site to easily engage with new customers, create a vibrant community around your products, and increase customer conversions.

FEATURES
--------
* Give your users a single, seamless, login for all of your sites.
* Authenticate users via Facebook, Twitter, MySpace, and other OpenID providers.
* Allow your users to link multiple social accounts to their master account.

This module will override the default login and registration forms providing, instead, a link to launch the ONEsite Social Login modal window. This modal will be responsible for authenticating and registering a user on your site.

REQUIREMENTS
------------
A development key is required to interact with any of the ONEsite services. See the installation instructions below for registering with ONEsite.


INSTALLATION
------------
### Step 1: Setting up your ONEsite account
1. [Sign up for an account](http://www.onesite.com/node/ssoSignup) on ONEsite.com.
   You will receive a devkey and an email confirmation.
2. To enable social providers for authentication (Facebook, Twitter, etc…):
	1. You will need to set up your own 'application' on each of the
	   Social Networks you would like to integrate with on your site.
	2. Log in to the [ONEsite control panel](https://admin.onesite.com).
	3. Go to this page: "Plugins" > "Social Integration" > "Settings"
	4. Enable each of the providers you require. Make sure you enter any
	   required API keys or integration info for each provider.
	   

### Step 2: Installing the ONEsite SSO module on your Drupal site
1. Download the module and
   <a href="http://drupal.org/documentation/install/modules-themes/modules-7">install per the usual process</a>.
2. Go to Home > Administration > ONEsite SSO.
3. Paste the ONEsite SSO Devkey you received from creating your ONEsite account and hit "Save". At this point Drupal will connect to the ONEsite servers to discover details about your account and will automatically adjust the other (advanced) settings.
4. Your current Drupal user will now be linked to the admin user on ONEsite. To complete this process you will need to log out of Drupal and log back in using your ONEsite user credentials. You should then be logged in on both ONEsite and your Drupal site.

Visit the [ONEsite Developer Portal](http://developer.onesite.com) for more information about our plugins and SDKs.