=== ActiveCampaign - The autonomous marketing platform ===
Contributors: activecampaign
Tags: activecampaign, marketing automation, email marketing, AI agent, business growth
Requires at least: 2.0
Requires PHP: 5.4
Tested up to: 6.8
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add ActiveCampaign contact forms and live chat to any post, page, or sidebar. Also enable ActiveCampaign site tracking for your WordPress blog.

== Description ==

ActiveCampaign is the autonomous marketing platform built to transform how marketers, agencies, and business owners work. Use Active Intelligence to power goal-aware automations and orchestrate personalized experiences across email, SMS, and WhatsApp. Effortlessly integrate with 1000+ apps, uncover deep performance insights, and optimize your workflows so you win every day.

* <strong>Autonomous marketing</strong>
Built on the foundation of marketing automation, fuel your marketing strategy and customer journeys with AI-driven execution, optimization, and insight at every step.
* <strong>AI agents</strong>
Run entire marketing campaigns through simple prompts, backed by Active Intelligence.
* <strong>Cross-channel marketing</strong>
Reach prospects and customers wherever they are, with email, SMS, WhatsApp, and more.
* <strong>On-brand, personalized content</strong>
Creative tools that deliver professional, conversion-ready designs for email and landing pages.
* <strong>CRM</strong>
Track, manage, and automate your sales process.
* <strong>1000+ apps & integrations</strong>
Connect ActiveCampaign to your favorite tools.


<strong>WooCommerce + ActiveCampaign</strong>
Turn on ActiveCampaign [site tracking](https://help.activecampaign.com/hc/en-us/articles/9127994708636-Use-ActiveCampaign-Site-Tracking-with-WordPress) in just a few clicks.
Seamlessly add ActiveCampaign forms to your WordPress website.

Learn more: [How to use the ActiveCampaign WordPress Plugin](https://help.activecampaign.com/hc/en-us/articles/222475388-Use-the-ActiveCampaign-WordPress-plugin)


== Screenshots ==

1. Active Intelligence Workspace
2. Form Builder
3. Automation Builder
4. Settings page for ActiveCampaign plugin
5. Configuring your form settings
6. AI Brand Kit
7. Active Intelligence
8. Cross-channel marketing
9. Deals CRM


== Installation ==

This section describes how to install the plugin and get it working. Please see [our additional help documentation](http://www.activecampaign.com/help/integrating-subscription-forms-with-wordpress/) for more detailed information.

1. Upload the entire "activecampaign" zip file to the Plugins section of WordPress, or "Add New" plugin and search for "activecampaign."
2. Visit the Settings > ActiveCampaign section in WordPress.
3. Fill in your ActiveCampaign connection details, then hit Update.
4. Configure your forms:
    - Using Classic Editor? Choose which subscription forms to use in the widget and associated CSS settings for each, then hit Update Settings again. You can also copy your shortcodes from this section.
    - Using the Gutenberg Block Editor? All your forms and CSS options will be available in AC Forms block.
    - Using shortcodes? The `[activecampaign form=ID css=1]` shortcode will display a form anywhere on your site where shortcode syntax is supported. Toggle shortcode parameters `css=1` or `css=0` to override the plugin setting's "Use ActiveCampaign's form CSS" value.
5. Embed multiple forms onto a single page!
6. Enable site tracking to have page visits tracked to ActiveCampaign.

== Frequently Asked Questions ==

= How do I create ActiveCampaign subscription forms to use in WordPress? =

You need to be using [ActiveCampaign email marketing platform](http://www.activecampaign.com/) to use this widget. Create new subscription forms in the platform by going to the "Integration" section, then they will be available through this plugin.

= How does this plugin differ from copying and pasting the subscription form onto my site manually? =

This plugin makes it much easier to do without requiring you to know which theme (or core WordPress) files to modify. Also, copying and pasting HTML into WordPress can often cause odd display issues (depending on your WordPress theme).

= What happens after someone submits the subscription form on my WordPress site? =

The same thing that would happen if they submitted it from another site: it redirects back to the ActiveCampaign confirmation message, or a custom URL if you have that set up for the subscription form in ActiveCampaign (modify your forms under the "Integration" section).

If you enable the "Ajax" option of the plugin settings, you can have the form submitted without the page reloading (so the viewer never leaves the page).

= Can my form require an opt-in email confirmation be sent? =

Yes, you would just make sure that your form settings (in ActiveCampaign) have the Opt-in confirmation setting checked.

= I get a "Connection failed" message. What does this mean? =

Please make sure that your login information is correct, and that you have at least one Integration form already created in the ActiveCampaign system.

= Can ActiveCampaign send transactional emails for my WordPress site? =

With [ActiveCampaign Postmark](https://postmarkapp.com/?utm_source=activecampaign&utm_medium=referral&utm_campaign=activecampaign_wordpress) — that’s ActiveCampaign’s transactional email provider — you can make sure your transactional emails (including password reset emails, form notifications, or account setup emails) are getting delivered, every time. With WordPress’ default mailer, crucial transactional emails often end up in the spam folder or aren’t delivered at all. With Postmark, deliverability issues are a thing of the past. [Learn more about Postmark for WordPress →](https://wordpress.org/plugins/postmark-approved-wordpress-plugin)

= How can I report security bugs?

You can report security bugs through ActiveCampaign's security disclosure form here: [Report a security vulnerability.](https://www.activecampaign.com/security/report-an-issue)



== Changelog ==
= 8.1.21 =
* Update plugin branding

= 8.1.20 =
* Update description of plugin to reflect current ActiveCampaign features

= 8.1.19 =
* Update description of plugin to reflect current ActiveCampaign features

= 8.1.18 =
* Update supported versions of WordPress

= 8.1.17 =
* Security fix to address XSS vulnerability with API URL and API Key verification

= 8.1.16 =
* Verifying 6.5 compatibility, updated listing

= 8.1.15 =
* Security fix to address SSRF vulnerability with API URL verification and wp_safe_remote_get
* Removing unreachable deprecated curl code

= 8.1.14 =
* Fixing shortcode CSS display in Form Preview

= 8.1.13 =
* Verifying 6.3.1 compatibility, updated listing

= 8.1.12 =
* Security fix to address XSS vulnerability

= 8.1.11 =
* Removing obsolete Javascript

= 8.1.10 =
* Verifying 6.0 compatibility, updated listing

= 8.1.9 =
* Updated authentication for internal API requests

= 8.1.8 =
* Updated listing

= 8.1.7 =
* Updated listing

= 8.1.6 =
* Improving credential check to fix permissions bug
* Fixing non-inline form previews in block editor
* Removing unnecessary Google Font loads on no-style embeds
* Updating Plugin description

= 8.1.5 =
* Updating Readme with up to date screenshots and better descriptions
* Updating Plugin Settings with clearer descriptions of form and shortcode use cases
* Fixing block editor CSS class input on dynamic div output
* Fixing display of Site Tracking settings without forms
* Site Tracking JS migrated to vgo() from pgo()
* Fixing bug with Tracking ID fetch
* Adding admin notice stack for future plugin updates

= 8.1.4 =
* Rolling back settings page form/css deprecations. We have improved testing workflows moving forward.

= 8.1.3 =
* Hotfix for Default CSS option deprecation
* Moving from global assignment to block/shortcode assignment
* Allowing fallback for existing blocks without CSS setting

= 8.1.2 =
* Simplifying plugin settings options
* Dropping 'Global' CSS option for block, defaulting to 'Use ActiveCampaign CSS'
* Converting to Dynamic Block pattern

= 8.1.1 =
* Improved error handling on expired credentials and misconfigurations
* Shortening Block widget name to 'AC Forms'

= 8.1.0 =
* Improvements to Gutenberg Editor experience, including live preview of Form embeds
* Background color bug fix
* Shortcode support for optional 'css' and 'static' attributes that default to plugin settings
* Avoiding global namespace conflicts of on-demand chunks bug fix

= 8.0.3 =
* Pluggable bug fix

= 8.0.2 =
* Security fix to address CSRF vulnerability
* General fix to address browser warning for invalid cookie attribute

= 8.0.1 =
* removing php 7 feature usage

= 8.0.0 =
* Update ActiveCampaign forms embed to be compatible with Gutenberg editor
* Resolve account connection UI bug

= 7.1.4 =
* Updated listing

= 7.1.3 =
* Updated readme

= 7.1.2 =
* Update tracking code copy to be more specific to Site Tracking and Conversations.
* Fix old link to Forms page.
* Make install code toggle focusable.

= 7.1.1 =
* Include our own host header on requests.

= 7.1 =
* Update plug-in to enable Live Chat.

= 7.0 =
* Force upgrade prompt for users on 6.25.
    * The prior version (6.3) is technically smaller than 6.25 in semantic versioning so users on 6.25 won't ever see an upgrade prompt unless we got to 6.25.1 or 6.26.

= 6.3 =
* Added site tracking options for GDPR.

= 6.2.12 =
* Fix for when the "form_id" key is undefined.

= 6.2.11 =
* Fix for when the "site_tracking" key is undefined.

= 6.2.10 =
* Limit amount of ActiveCampaign account data shown in JavaScript (for site tracking).

= 6.2.9 =
* Fix for "Keep original form CSS" checkbox not being respected.

= 6.2.8 =
* Fix for `Undefined index: css` error.

= 6.2.7 =
* Fix for 6.2.6 change missing another check.

= 6.2.6 =
* Fix for certain error messages not being displayed properly.

= 6.25 =
* Fix for SSL issue (when the page is loaded via HTTPS and the AC account uses a CNAME, forms would not show up).
* **After upgrading go to WordPress ActiveCampaign settings and click "Update Settings" so it reloads the form code!**

= 6.2 =
* Fix for compatibility issue with Live Composer plugin.

= 6.1 =
* Fix for issue with new forms not displaying properly.

= 6.0 =
* Added support for new form builder.

= 5.93 =
* Fix for issue with captcha verification when using the Ajax ("Submit form without refreshing page") form submission option.

= 5.92 =
* Support for captcha validation when using the 'Submit form without refreshing page' (Ajax) option.
* Added success or error CSS classes to the Ajax response div.

= 5.91 =
* Updates to avoid conflicts with other plugins using the ActiveCampaign PHP API wrapper.

= 5.9 =
* Use current user's email for site tracking.

= 5.8 =
* Security fix.

= 5.7 =
* Removed ability to add custom form "action" URL.

= 5.6 =
* Patched major security bug.

= 5.5 =
* Added site tracking (optional setting).

= 5.2 =
* Default form behavior is now "sync." This coincided with WordPress version 3.9 release.

= 5.1 =
* Added button to TinyMCE toolbar to more easily choose and embed the form shortcode into the post body.

= 5.0 =
* Added support for multiple forms. Removed widget entirely.

= 4.5 =
* Added ActiveCampaign to the Settings menu so you can use the shortcode independent of the widget.

= 4.0 =
* Added many additional settings to control how your form is displayed and submitted.

= 3.5 =
* You can now use a shortcode to display your subscription form.

= 3.0 =
* Re-wrote widget backend to use most recent WordPress Widget structure.
* Streamlined code and API usage.
* Ability to reset or refresh your forms.
* Better form width detection.

= 2.1 =
* Changed internal API requests to use only API URL and Key instead of Username and Password.
* Provided option to remove style blocks from embedded form code, and converting `input type="button"` into `input type="submit"`.

= 2.0 =
* Re-configured to work with ActiveCampaign version 5.4.
* Improved some areas.

= 1.1 =
* Verified this works with latest versions of WordPress and ActiveCampaign.
* Updated installation instructions.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 6.3 =
* After upgrading go to ActiveCampaign settings and make sure your Site Tracking setting and options are set appropriately.

= 6.25 =
* After upgrading go to ActiveCampaign settings and click "Update Settings" so it reloads the form code.

= 6.1 =
* After upgrading go to ActiveCampaign settings and click "Update" again so it reloads the form code.

= 6.0 =
* After upgrading go to ActiveCampaign settings and click "Update" again so it reloads the form code.

= 5.9 =
* Site tracking users: the current logged-in user will now be associated with each page visit.

= 5.8 =
* UPGRADE IMMEDIATELY - security fix. After upgrading go to ActiveCampaign settings and click "Update" again so it reloads the form code.

= 5.7 =
* Custom form "action" URL's will no longer work.

= 5.6 =
* UPGRADE IMMEDIATELY - security bug patched (involving the API key being exposed). After upgrading go to ActiveCampaign settings and click "Update" again so it reloads the form code.

= 5.5 =
* If site tracking is enabled it will embed some JavaScript code on each of your front-end pages.

= 5.2 =
* Default behavior of the form is now "sync" (add or update). If you had "Add Subscriber" chosen it will now perform "add or update." If you had "Sync Subscriber" chosen the behavior will remain the same.

= 5.0 =
* The widget is removed entirely (in favor of the shortcode) so if you have a form in a sidebar, you'll now need to add a basic text widget with the shortcode in it. You choose your forms under the ActiveCampaign settings section.

= 4.0 =
* If you use the Ajax option, you will need jQuery enabled for your WordPress site.

= 2.1 =
* This version requires the use of API URL and Key instead of Username and Password.

= 2.0 =
* Version 2.0 will NOT work with ActiveCampaign versions < 5.4.

= 1.1 =
* Installation instructions updated if you are having trouble installing it.
