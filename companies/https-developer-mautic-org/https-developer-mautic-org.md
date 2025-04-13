# https://developer.mautic.org/

[ NAV ![](https://developer.mautic.org/images/navbar.png) ](https://developer.mautic.org/)
[ ](https://developer.mautic.org/)
[php](https://developer.mautic.org/) [json](https://developer.mautic.org/)
  * Introduction
    * Submitting Code to Mautic
    * Symfony
    * Development Environment
      * Setup
      * Environments
      * Cache


  * Cache Bundle
    * Namespace versus tag
      * Pools clearing
    * Configuration
    * Delivered adapters
    * Clearing the cache
    * Features auto pruning on adapter initialization
    * Usage
      * PSR-6
      * PSR-16


  * Plugins
    * Migrations/Deprecations
      * 1.2.0
      * 2.0.0
      * 3.0.0
    * Plugin Directory Structure
    * Install/Upgrade
      * onPluginInstall()
      * installPluginSchema()
      * onPluginUpdate()
      * updatePluginSchema()
    * Plugin Config File
      * General
      * Routes
      * Menu
      * Services
      * Categories
      * Parameters
    * Translations
      * Domains
      * INI files
      * Using the translator
      * Using the translator in your javascript
    * MVC
      * Controllers
      * Models
      * Views
    * Services
      * Factory Service
      * User
      * Security
      * Translator
      * Router
      * Request
      * Session
      * Database/Entity Manager
      * Config Parameters
      * Event Dispatcher
      * Paths Helper
      * IP Lookup Helper
      * Plugin Config Helper
      * Cookie Helper
      * Mail Helper
      * Model Factory
    * Database
    * Roles and Permissions
      * How Permissions Work
      * Using Permissions
      * Creating Custom Permissions
    * Custom Config Params
      * Config Event Subscriber
      * Config Form
      * Config Template
    * Integration Framework
      * Using the Integration Framework
      * Basics
      * Plugin Schema
      * Integration Authentication
      * Integration Configuration
      * Integration Sync Engine
      * Integration Builders
    * Manipulating Contacts (Leads)
    * Extending Mautic
      * Extending API
      * Extending Broadcasts
      * Extending Campaigns
      * Extending Categories
      * Extending Contacts (Leads)
      * Extending Emails
      * Extending Forms
      * Extending Integrations
      * Extending Maintenance Cleanup
      * Extending Landing Pages
      * Extending Points
      * Extending Reports
      * Extending Webhooks
      * Extending UI
    * Miscellaneous
      * Flash Messages
      * Notifications
      * Helpers
      * Commands
      * Forms
      * Events
      * Implementing Translation Support to Entities
      * Implementing Variant (A/B Test) Support to Entities


  * Marketplace
    * Marketplace under the hood
    * How to list a plugin in the Mautic Marketplace
    * How to get included in the allow-list
    * Best Practices


  * Themes
    * Theme Directory Structure
    * Theme zip package
    * Theme Config File
    * Theme Thumbnail
    * Slots
      * Slot definition
      * Slot containers
    * Sections
      * Section
      * Section Wrapper
    * Theme HTML Files
      * email.html.twig
      * form.html.twig
      * message.html.twig
      * page.html.twig


  * REST API
    * Error Handling
    * Mautic version check
    * Authorization
      * OAuth 1a
      * OAuth 2
      * Basic Authentication
    * API Rate limiter
    * Libraries
      * PHP Library
    * Endpoints
    * Assets
      * Get Asset
      * List Assets
      * Create Asset
      * Edit Asset
      * Delete Asset
    * Campaigns
      * Get Campaign
      * List Campaigns
      * List Campaign Contacts
      * Create Campaign
      * Clone A Campaign
      * Edit Campaign
      * Delete Campaign
      * Add Contact to a Campaign
      * Remove Contact from a Campaign
    * Categories
      * Get Category
      * List Contact Categories
      * Create Category
      * Edit Category
      * Delete Category
      * Assign a Category
    * Companies
      * Get Company
      * List Contact Companies
      * Create Company
      * Edit Company
      * Delete Company
      * Add Contact to a Company
      * Remove Contact from a Company
    * Contacts
      * Get Contact
      * List Contacts
      * Create Contact
      * Create Batch Contact
      * Edit Contact
      * Edit Batch Contact
      * Delete Contact
      * Delete Batch Contact
      * Add Do Not Contact
      * Remove from Do Not Contact
      * Add UTM Tags
      * Remove UTM Tags from a contact
      * Add Points
      * Subtract Points
      * List Available Owners
      * List Available Fields
      * List Contact Notes
      * Get Segment Memberships
      * Change List Memberships
      * Get Campaign Memberships
      * Change Campaign Memberships
      * Get Contact’s Events
      * Get activity events for specific contact
      * Get Activity events for all contacts
      * Get Contact’s Companies
      * Get Contact’s Devices
    * Data - Dashboard widget data
      * Get list of available widget types
      * Get an individual widget data by type.
      * “Emails in time” widget
      * “Sent email to contacts” widget
      * “Most hit email redirects” widgets
    * Dynamic Content
      * Get Dynamic Content
      * List Dynamic Contents
      * Create Dynamic Content
      * Edit Dynamic Content
      * Delete Dynamic Content
    * Emails
      * Get Email
      * List Emails
      * Create Email
      * Edit Email
      * Delete Email
      * Send Email to Contact
      * Send Email to Segment
      * Create a reply to a send email send row
    * Fields
      * Get Field
      * List Contact Fields
      * Create Field
      * Edit Field
      * Delete Field
    * Files
      * Get List of files
      * Create File
      * Delete File
    * Forms
      * Get Form
      * List Forms
      * Create Form
      * Edit Form
      * Delete Form
      * Delete Form Fields
      * Delete Form Actions
      * List Form Submissions
      * List Form Submissions for a contact
      * Get Form Submission
    * Marketing Messages
      * Get Marketing Message
      * List Marketing Messages
      * Create Marketing Message
      * Edit Marketing Message
      * Delete Marketing Message
    * Notes
      * Get Note
      * List Contact Notes
      * Create Note
      * Edit Note
      * Delete Note
    * Notifications
      * Get Notification
      * List Notifications
      * Create Notification
      * Edit Notification
      * Delete Notification
    * Pages
      * Get Page
      * List Pages
      * Create Page
      * Edit Page
      * Delete Page
    * Point Actions
      * Get Point Action
      * List Point Actions
      * Create Point Action
      * Edit Point Action
      * Delete Point Action
      * Get Point Action Types
    * Point Triggers
      * Get Point Trigger
      * List Point Triggers
      * Create Point Trigger
      * Edit Point Trigger
      * Delete Point Trigger
      * Delete Point Trigger Events
      * Get Point Trigger Event Types
    * Reports
      * Get Report
      * List Reports
    * Roles
      * Get Role
      * List Contact Roles
      * Create Role
      * Edit Role
      * Delete Role
    * Segments
      * Get Segment
      * List Contact Segments
      * Create Segment
      * Edit Segment
      * Delete Segment
      * Add Contact to a Segment
      * Add Contacts to a Segment
      * Remove Contact from a Segment
    * Text messages
      * Get Text message
      * List Text messages
      * Create Text message
      * Edit Text message
      * Delete Text message
      * Send SMS to Contact
    * Stages
      * Get Stage
      * List Contact Stages
      * Create Stage
      * Edit Stage
      * Delete Stage
      * Add Contact to a Stage
      * Remove Contact from a Stage
    * Stats
      * Get Available Stat Tables
      * Get Stats from a table
    * Tags
      * Get Tag
      * List Tags
      * Create Tag
      * Edit Tag
      * Delete Tag
    * Themes
      * Get theme
      * Set Temporary File Path
      * Get List of themes
      * Create Theme
      * Delete File
    * Tweets
      * Get Tweet
      * List Tweets
      * Create Tweet
      * Edit Tweet
      * Delete Tweet
    * Users
      * Get User
      * List Contact Users
      * Create User
      * Edit User
      * Delete User
      * Get Self User
      * Check User Permissions
    * Webhooks
      * Get Webhook
      * List Webhooks
      * Create Webhook
      * Edit Webhook
      * Delete Webhook
      * List available webhook triggers


  * Webhooks
    * Available webhook actions
    * The webhook workflow
    * Create a webhook
    * Test a webhook
    * Immediate or queued webhooks
    * Queued event order
    * Authenticity verification
    * Examples webhook script


  * MauticJS API
    * mtc.js
    * Hooking into the Tracking Process and Returning Custom Responses
    * JS Form Processing Hooks
      * onValidate()
      * onValidateStart()
      * onValidateEnd(formValid)
      * onErrorMark(callbackData)
      * onErrorClear(containerId)
      * onResponse(response)
      * onResponseStart(response)
      * onResponseEnd(response)
      * onMessageSet(messageObject)
      * onSubmitButtonDisable(messageObject)
      * onSubmitButtonEnable()
      * onShowNextPage()
      * onShowPreviousPage()
    * MauticJS API Functions
      * MauticJS.serialize(object)
      * MauticJS.documentReady(functionName|function)
      * MauticJS.iterateCollection(collection)(functionName|function)
      * MauticJS.log(arguments)
      * MauticJS.createCORSRequest(method, url)
      * MauticJS.makeCORSRequest(method, url, data, callbackSuccess, callbackError)
      * MauticJS.parseTextToJSON(maybeJSON)
      * MauticJS.insertScript(scriptUrl)


# Introduction[](https://developer.mautic.org/#introduction)
Welcome to the Mautic Developer Documentation. This documentation will go over how to build a Mautic Plugin that extends the features of Mautic, how to build custom themes, and how to integrate applications outside of Mautic using its REST API. 
## Submitting Code to Mautic[](https://developer.mautic.org/#submitting-code-to-mautic)
Development is open and available to any member of the Mautic community. All fixes and improvements are done through pull requests to the code on 
Read all about [contributing to Mautic](https://contribute.mautic.org/contributing-to-mautic/developer) as a Developer.
Read more about the PR process on the Mautic [Governance](https://www.mautic.org/about/governance) page.
The code should try to follow 
## Symfony[](https://developer.mautic.org/#symfony)
Mautic is built on 
There are some structural differences between Mautic and standard Symfony. Below is a list of where you will find some of standard Symfony locations in Mautic:
Symfony | Mautic  
---|---  
src/ | app/bundles (Mautic core) or plugins/ (Mautic plugins)  
web/ | /  
AcmeBundle/Resources/config | AcmeBundle/Config  
AcmeBundle/Resources/views | AcmeBundle/Views  
AcmeBundle/Resources/public | AcmeBundle/Assets  
AcmeBundle/Resources/translations/domain.en_US.ini | AcmeBundle/Translations/en_US/domain.ini  
Most of Symfony’s standard locations, such as the Resources/views and Resources/translations directories, should still function with Mautic. However, it may be required to handle service registration, etc with native Symfony processes if not using the Mautic methods defined in this document.
## Development Environment[](https://developer.mautic.org/#development-environment)
### Setup[](https://developer.mautic.org/#setup)
It is assumed that the system already has 
To setup the developer environment, simply fork and clone the source from `composer install` on the source.
Open your browser and complete the installation through the Mautic installer. You can also execute the install process from command line: * Add a `local.php` file in app/config * Edit the `local.php` file using the following template (adapt to your own settings): `php <?php $parameters = array(     'db_driver' => 'pdo_mysql',     'db_host' => 'localhost',     'db_table_prefix' => null,     'db_port' => '3306',     'db_name' => 'mautic',     'db_user' => 'root',     'db_password' => 'root_password',     'db_backup_tables' => true,     'db_backup_prefix' => 'bak_', ); ` * Execute the following command and add your own options: `php bin/console mautic:install http://your.mautic.instance`
### Environments[](https://developer.mautic.org/#environments)
There are three environments in Mautic: prod, dev, and test.
**prod** is used when accessing the site through index.php.
**dev** is used when accessing the site through index_dev.php. Using Mautic in the dev environment will activate Symfony’s profiler toolbar, has more strict error handling, will display information about exceptions, and will not cache as much (see below). Note that steps should be taken to ensure index_dev.php is not accessible to the public as it could potentially reveal sensitive information. It is restricted to localhost by default. However, there are two ways to allow access to index_dev.php from a non-localhost. The first option is to set a header from the web-server with the IP addresses assigned to `MAUTIC_DEV_HOSTS`. The second and easier option is to add an array to your installation’s `app/config/local.php` file as `'dev_hosts' = ['123.123.123.123', '124.124.124.124'],` then clear the [cache](https://developer.mautic.org/#cache). **Note** : If you’re using PHP-FPM (e.g. when using Docker/DDEV), you need to have `cgi.fix_pathinfo = 1` in your PHP configuration, otherwise `/index_dev.php/*` might not work. Read more about the implications of this setting 
**test** is used mainly for PHP Unit Tests.
### Cache[](https://developer.mautic.org/#cache)
Symfony makes heavy use of a filesystem cache. Frequently clearing this cache will be required when developing for Mautic. By default, the cache is located in app/cache/ENV where ENV is the environment currently accessed (i.e. dev or prod). To rebuild the cache, the ENV can just be deleted or run the Symfony command `php app/console cache:clear --env=ENV` If a specific environment is not passed to the command via `--env=ENV`, the dev environment will be used by default.
In the dev environment, translations, views, and assets are not cached. However, changes to these files will require the cache to be cleared for them to take effect in the prod environment. Changes to Mautic config files, Symfony config files, etc will require the cache to be cleared regardless of environment.
The typical rule of thumb is, if Mautic is not acting as you expect after making changes, try clearing your cache.  If you get class could not be found or cannot redeclare class errors when using the cache:clear command, manually delete the app/cache/ENV folder then run the command and/or browse to the site to rebuild. 
# Cache Bundle[](https://developer.mautic.org/#cache-bundle)
Enables PSR-6 and PSR-16 caching. Check: 
## Namespace versus tag[](https://developer.mautic.org/#namespace-versus-tag)
This bundle introduces tags to cache. All its adapters are fully tag aware which makes the use of namespace obsolete for daily use.
Previously if you wanted to keep control on cache section and did not want to hold the index of all keys to clear you would have to use namespace.
Disadvantage of this approach is a new adapter being created for each namespace.
```
    /** @var CacheProvider $cache */
    $cache = $this->get('mautic.cache.provider');

    /** @var CacheItemInterface $item */
    $item = $cache->getItem('test_tagged_Item');
    $item->set('yesa!!!');
    $item->tag(['firstTag', 'secondTag']);
    $item->expiresAfter(20000);

```

All you need to do now is to clear all tagged items:
```
$cache->invalidateTags(['firstTag']);

```

### Pools clearing[](https://developer.mautic.org/#pools-clearing)
Removing Cache Items¶
Cache Pools include methods to delete a cache item, some of them or all of them. The most common is `Psr\\Cache\\CacheItemPoolInterface::deleteItem`, which deletes the cache item identified by the given key.
```
$isDeleted = $cache->deleteItem('user_'.$userId);

```

Use the Psr\Cache\CacheItemPoolInterface::deleteItems method to delete several cache items simultaneously (it returns true only if all the items have been deleted, even when any or some of them don’t exist):
## Configuration[](https://developer.mautic.org/#configuration)
Plugin comes preconfigured to utilize filesystem caching.
These are the default settings: `php 'cache_adapter'  => 'mautic.cache.adapter.filesystem', 'cache_prefix'   => 'app', 'cache_lifetime' => 86400 `
They can be overridden in **local.php** like this:
```
'cache_adapter'  => 'mautic.cache.adapter.redis',
'cache_prefix'   => 'app_cache',
'cache_lifetime' => 86400,

```

## Delivered adapters[](https://developer.mautic.org/#delivered-adapters)
  * mautic.cache.adapter.filesystem
  * mautic.cache.adapter.memcached `php 'memcached' => [      'servers' => ['memcached://localhost'],      'options' => [          'compression'          => true,          'libketama_compatible' => true,          'serializer'           => 'igbinary',      ],  ], `
  * mautic.cache.adapter.redis Redis configuration in **local.php** : `php 'redis' => [      'dsn' => 'redis://localhost',      'options' => [          'lazy' => false,          'persistent' => 0,          'persistent_id' => null,          'timeout' => 30,          'read_timeout' => 0,          'retry_interval' => 0,      ]  ], `


In order to use another adapter just set it up as a service
## Clearing the cache[](https://developer.mautic.org/#clearing-the-cache)
The cache is cleared when **cache:clear** command is run. The cache can be cleared by running
```
bin/console mautic:cache:clear

```

## Features auto pruning on adapter initialization[](https://developer.mautic.org/#features-auto-pruning-on-adapter-initialization)
## Usage[](https://developer.mautic.org/#usage)
### PSR-6[](https://developer.mautic.org/#psr-6)
```
    /** @var CacheProvider $cache */
    $cache = $this->get('mautic.cache.provider');

    /** @var CacheItemInterface $item */
    $item = $cache->getItem('test_tagged_Item');
    $item->set('yesa!!!');
    $item->tag(['firstTag', 'secondTag']);
    $item->expiresAfter(20000);

    $cache->save($item);

    $item = $cache->getItem('test_nottagged_Item2');
    $item->tag(['firstTag']);
    $cache->save($item);

    $item = $cache->getItem('test_nottagged_Item3');
    $item->tag(['secondTag']);
    $cache->save($item);

    $cache->commit();

    var_dump($cache->getItem('test_nottagged_Item2')->isHit());
    var_dump($cache->getItem('test_nottagged_Item3')->isHit());

    $cache->invalidateTags(['firstTag']);

    var_dump($cache->getItem('test_nottagged_Item2')->isHit());
    var_dump($cache->getItem('test_nottagged_Item3')->isHit());

    $cache->commit();

```

### PSR-16[](https://developer.mautic.org/#psr-16)
```
        /** @var CacheProvider $cache */
        $cache = $this->get('mautic.cache.provider');


        $simpleCache = $cache->getSimpleCache();
        $test = $simpleCache->get('test_value');

        var_dump($test);

```

# Plugins[](https://developer.mautic.org/#plugins)
Plugins are bundles that can extend the functionality of Mautic. They can be very simple or very complex and have access to leverage pretty much all that Symfony offers. Just as as reminder, the basics are covered in this document. If more advanced processes are required, the 
Mautic plugins are located in the plugins/ directory and must be namespaced with MauticPlugin. 
## Migrations/Deprecations[](https://developer.mautic.org/#migrations/deprecations)
The following is a list of deprecations and migrations required to support latest versions of Mautic.____
### 1.2.0[](https://developer.mautic.org/#1.2.0)
1.2.0 deprecated the Mautic Addon with it’s successor, the Plugin. Mautic addons will continue to work but should be migrated to a plugin before Mautic 2.0 when support will be dropped.
The migration path is as follows:
  1. Move the plugin from addons/ to plugins/
  2. Replace the namespace `MauticAddon` with `MauticPlugin`
  3. Replace the MauticFactory getModel() notation of `addon.` to `plugin.`
  4. Replace the permission notation of `addon:` to `plugin:`
  5. Change the plugin’s bundle class to extend `PluginBundleBase` instead of `AddonBundleBase`
  6. In the plugin’s bundle class, use the function’s `onPluginInstall()` and `onPluginUpdate()` instead of the deprecated `onInstall()` and `onUpdate()`
  7. Migrate Entity use of annotations for ORM to the static PHP function `loadMetadata()`
  8. Migrate Entity use of annotations for the serializer (used with the REST API) to the static PHP function `loadApiMetadata()`


### 2.0.0[](https://developer.mautic.org/#2.0.0)
The big ticket item with 2.0.0 is the deprecation of MauticFactory which will be phased out during the 2.x release cycles and to be removed in 3.0. Where possible, please use direct dependency injection of services rather than relying on MauticFactory.
  1. MauticFactory deprecated - use dependency injection of required services. Many MauticFactory helper functions have been replaced with [services](https://developer.mautic.org/#services).
  2. Models need to be registered as services using a specific nomenclature. See [Models](https://developer.mautic.org/#models) for more information.
  3. The static callback function for campaign actions and decisions has been deprecated. Please see [Extending Campaigns](https://developer.mautic.org/#extending-campaigns) for more information on the new event based method. (Form submit actions, point triggers, and the like will follow suit with a similar migration throughout the lifecycle of 2.0 but for now still uses the static callback method).
  4. Minimum PHP version has been increased to 5.6.19 and thus newer PHP code goodies are available for developers (traits, etc)
  5. Themes have been completely revamped although the old format is still supported for now. Please see [Themes](https://developer.mautic.org/#themes) for the new format.
  6. Some routes for /leads/* were removed in favor of /contacts/*. I.e. /api/leads is now /api/contacts, /s/leads is now /s/contacts, and so forth. The route names were also updated. For example, `mautic_lead_action` is now `mautic_contact_action` and so forth. 


### 3.0.0[](https://developer.mautic.org/#3.0.0)
See 
## Plugin Directory Structure[](https://developer.mautic.org/#plugin-directory-structure)
```
<?php
// plugins/HelloWorldBundle/HelloWorldBundle.php

namespace MauticPlugin\HelloWorldBundle;

use Mautic\PluginBundle\Bundle\PluginBundleBase;

class HelloWorldBundle extends PluginBundleBase
{
    // Nothing more required
}


```

The directory structure of an plugin will vary based on the features implemented. 
At a minimum, the following structure is required:
HelloWorldBundle/  
- - - Config/  
- - - - - config.php  
- - - HelloWorldBundle.php
Read more about the [config file](https://developer.mautic.org/#plugin-config-file).
The HelloWorldBundle.php file registers the bundle with Symfony. See the code block for the minimum required code.
A typical MVC plugin may look something like:
HelloWorldBundle/  
- - - [Assets/](https://developer.mautic.org/#asset-helper)  
- - - - - - images/   
- - - - - - - - - earth.png  
- - - - - - - - - mars.png  
- - - - - - helloworld.js  
- - - - - - helloworld.css  
- - - [Config/](https://developer.mautic.org/#plugin-config-file)  
- - - - - - config.php  
- - - [Controller/](https://developer.mautic.org/#controllers)  
- - - - - - DefaultController.php  
- - - [Model/](https://developer.mautic.org/#models)  
- - - - - - ContactModel.php  
- - - - - - WorldModel.php  
- - - [Translations/](https://developer.mautic.org/#translations)/  
- - - - - - en_US/  
- - - - - - - - - flashes.ini  
- - - - - - - - - messages.ini  
- - - [Views/](https://developer.mautic.org/#views)  
- - - - - - Contact/  
- - - - - - - - - form.html.php  
- - - - - - World/  
- - - - - - - - - index.html.php  
- - - - - - - - - list.html.php  
- - - HelloWorldBundle.php  
- - - HelloWorldEvents.php
Each of the other directories and files are explained elsewhere in the document. 
## Install/Upgrade[](https://developer.mautic.org/#install/upgrade)
**THIS IS NOW DEPRECATED AND DISCOURAGED FROM USE. USE THE[INTEGRATION FRAMEWORK’S MIGRATION](https://developer.mautic.org/#plugin-schema) INSTEAD.**
```
<?php
// plugins/HelloWorldBundle/HelloWorldBundle.php

namespace MauticPlugin\HelloWorldBundle;

use Doctrine\DBAL\Schema\Schema;
use Mautic\PluginBundle\Bundle\PluginBundleBase;
use Mautic\PluginBundle\Entity\Plugin;
use Mautic\CoreBundle\Factory\MauticFactory;

class HelloWorldBundle extends PluginBundleBase
{

    /**
     * Called by PluginController::reloadAction when adding a new plugin that's not already installed
     *
     * @param Plugin        $plugin
     * @param MauticFactory $factory
     * @param null          $metadata
     */

    static public function onPluginInstall(Plugin $plugin, MauticFactory $factory, $metadata = null)
    {
        if ($metadata !== null) {
            self::installPluginSchema($metadata, $factory);
        }

        // Do other install stuff
    }

    /**
    * Called by PluginController::reloadAction when the plugin version does not match what's installed
    *
    * @param Plugin        $plugin
    * @param MauticFactory $factory
    * @param null          $metadata
    * @param Schema        $installedSchema
    *
    * @throws \Exception
    */
    static public function onPluginUpdate(Plugin $plugin, MauticFactory $factory, $metadata = null, Schema $installedSchema = null)
    {
        $db             = $factory->getDatabase();
        $platform       = $db->getDatabasePlatform()->getName();
        $queries        = array();
        $fromVersion    = $plugin->getVersion();

        // Simple example
        switch ($fromVersion) {
            case '1.0':
                switch ($platform) {
                    case 'mysql':
                        $queries[] = 'ALTER TABLE ' . MAUTIC_TABLE_PREFIX . 'worlds CHANGE description LONGTEXT DEFAULT NULL';
                        break;

                    case 'postgresql':
                        $queries[] = 'ALTER TABLE ' . MAUTIC_TABLE_PREFIX . 'worlds ALTER description ALTER TYPE TEXT';
                        break;
                }

                break;
        }

        if (!empty($queries)) {

            $db->beginTransaction();
            try {
                foreach ($queries as $q) {
                    $db->query($q);
                }

                $db->commit();
            } catch (\Exception $e) {
                $db->rollback();

                throw $e;
            }
        }
    }
}

```

Currently, plugins are installed by uploading the plugin to the plugins folder and the cache manually deleted (`app/cache/prod`). Then, the admin must click the Install/Upgrade Plugins button in the Plugin manager. When that happens, new plugins found will have the static method `onPluginInstall()` called from the [plugin’s bundle file](https://developer.mautic.org/#plugin-directory-structure). If the plugin has already been installed, and the version has changed, then `onPluginUpdate()` is called.
By default, `onPluginInstall()` will execute `installPluginSchema()`. This function will generate and execute schema based on found [Entity](https://developer.mautic.org/#Database) classes.
`updatePluginSchema()` is available for use with `onPluginUpdate()`, however it is not called by default. The reason is that it uses Doctrine to generate schema differences and executes the queries. This is not recommended due to the risk of Doctrine making incorrect assumptions that will lead to data loss. If `updatePluginSchema()` is relied upon, it is very important to test thoroughly to ensure the desired outcome. It is recommended to write a migration path for both MySQL and PostgreSQL with native queries instead.
### onPluginInstall()[](https://developer.mautic.org/#onplugininstall\(\))
Executed when a plugin is first installed. By default, the plugin’s database schema will be generated and installed based on the Entity class’ `loadMetadata` function.
Argument | Type | Description  
---|---|---  
$plugin | Mautic\PluginBundle\Entity\Plugin | The plugin entity with information gleaned from the plugin’s config file.  
$factory | Mautic\CoreBundle\Factory\MauticFactory | Mautic’s factory class to provide access to Mautic’s services.  
$metadata | array\ | null  
### installPluginSchema()[](https://developer.mautic.org/#installpluginschema\(\))
Argument | Type | Description  
---|---|---  
$metadata | array\ | null  
$factory | Mautic\CoreBundle\Factory\MauticFactory | Mautic’s factory class to provide access to Mautic’s services.  
### onPluginUpdate()[](https://developer.mautic.org/#onpluginupdate\(\))
Argument | Type | Description  
---|---|---  
$plugin | Mautic\PluginBundle\Entity\Plugin | The plugin entity with information gleaned from the plugin’s config file.  
$factory | Mautic\CoreBundle\Factory\MauticFactory | Mautic’s factory class to provide access to Mautic’s services.  
$metadata | array\ | null  
$installedSchema | \Doctrine\DBAL\Schema\Schema | Schema of currently installed tables  
### updatePluginSchema()[](https://developer.mautic.org/#updatepluginschema\(\))
Argument | Type | Description  
---|---|---  
$metadata | array\ | null  
$installedSchema | \Doctrine\DBAL\Schema\Schema | Schema of currently installed tables  
$factory | Mautic\CoreBundle\Factory\MauticFactory | Mautic’s factory class to provide access to Mautic’s services.  
## Plugin Config File[](https://developer.mautic.org/#plugin-config-file)
Mautic leverages a simple array config file that will register routes, menu items, services and custom configuration parameters.
### General[](https://developer.mautic.org/#general)
```
<?php
// plugins/HelloWorldBundle/Config/config.php

return array(
    'name'        => 'Hello World',
    'description' => 'This is an example config file for a simple Hellow World plugin.',
    'author'      => 'Marty Mautibot',
    'version'     => '1.0.0',

```

The general config options will define what should be listed in the Plugin manager.
The version should be “[onUpdate callback](https://developer.mautic.org/#update) should be executed. 
### Routes[](https://developer.mautic.org/#routes)
> If copying, do not copy `<?php //continued` as it is simply used to force sytax highlighting.
```
<?php // continued

    'routes'   => array(
        'main' => array(
            'plugin_helloworld_world' => array(
                'path'       => '/hello/{world}',
                'controller' => 'HelloWorldBundle:Default:world',
                'defaults'    => array(
                    'world' => 'earth'
                ),
                'requirements' => array(
                    'world' => 'earth|mars'
                )
            ),
            'plugin_helloworld_list'  => array(
                'path'       => '/hello/{page}',
                'controller' => 'HelloWorldBundle:Default:index'
             ),
            'plugin_helloworld_admin' => array(
                'path'       => '/hello/admin',
                'controller' => 'HelloWorldBundle:Default:admin'
            ),
        ),
        'public' => array(
            'plugin_helloworld_goodbye' => array(
                'path'       => '/hello/goodbye',
                'controller' => 'HelloWorldBundle:Default:goodbye'
            ),
            'plugin_helloworld_contact' => array(
                'path'       => '/hello/contact',
                'controller' => 'HelloWorldBundle:Default:contact'
            )
        ),
        'api' => array(
            'plugin_helloworld_api' => array(
                'path'       => '/hello',
                'controller' => 'HelloWorldBundle:Api:howdy',
                'method'     => 'GET'
            )
        )
    ),

```

Routes define the URL paths that will be used to execute the plugin’s controller actions. See [Routing](https://developer.mautic.org/#routing) for specifics on how routes work.
#### Firewalls[](https://developer.mautic.org/#firewalls)
There are three firewalls to define the routes behind.
Firewall | Description  
---|---  
**main** | Secure area of Mautic (/s/ will be auto prepended to the path). The user will be required to login to access this path.  
**public** | Public access without needing authentication. The URL will be appended directly to Mautic’s base URL.  
**api** | Secure API area of Mautic (/api/ will be auto prepended to the path). OAuth authorization will be required to access the path.  
Each firewall accepts an array of defined routes. Each key, the route’s name, must be unique across all bundles and firewalls. Paths must be unique across the same firewall. **Order does matter** as the first matching route will be used.
#### Route definitions[](https://developer.mautic.org/#route-definitions)
Array Key | Required | Type | Description  
---|---|---|---  
**path** | REQUIRED | string | Defines the path for the URL. Placeholders can be defined using curly brackets. Parameters are passed into the controller function as arguments.  
**controller** | REQUIRED | string | Defines the controller and function to call when the path is accessed. This should be in Symfony’s controller notation of BundleName:ControllerClass:controllerMethod. See [Controllers](https://developer.mautic.org/#controllers) for more information.  
**method** | OPTIONAL | string | Restricts the route to a specific method, i.e. GET, POST, etc  
**defaults** | OPTIONAL | array | Defines default values for path placeholders. If a default is defined, it is not required in the URL. In the code example, /hello will be the same as /hello/earth and the controller’s $world argument will default to ‘earth’ as well.  
**requirements** | OPTIONAL | array | Defines regex matches placeholders must match in order for the route to be recognized. For example, for plugin_helloworld_world in the code example, world is restricted to earth or mars. Anything else will not be recognized by the route.  
**format** | OPTIONAL | string | Sets the request format for the Request response, i.e. Content-Type header. The api firewall will automatically set this to json.  
**condition** | OPTIONAL | string | Very flexible expression to set when the route should match. Refer to   
Note that there are some internally used placeholders that Mautic will set defaults and requirements for (if not overridden by the route)
{page} will default to 1 with a requirement of \d+
{objectId} will default to 0 
{id} will have a requirement of \d+ if under the api firewall
Each route’s name must be unique across all bundles and firewalls and paths must be unique with the same firewall.  Order does matter. The first route the path matches will be used. 
**Debugging Routes** There are a few CLI commands that make help with debugging routes.
```
php app/console router:debug

```
```
php app/console router:debug article_show

```
```
php app/console router:match /blog/my-latest-post

```

### Menu[](https://developer.mautic.org/#menu)
```
<?php // continued

    'menu'     => array(
        'main' => array(
            'priority' => 4,
            'items'    => array(
                'plugin.helloworld.index' => array(
                    'id'        => 'plugin_helloworld_index',
                    'iconClass' => 'fa-globe',
                    'access'    => 'plugin:helloworld:worlds:view',
                    'parent'    => 'mautic.core.channels',
                    'children'  => array(
                        'plugin.helloworld.manage_worlds'     => array(
                            'route' => 'plugin_helloworld_list'
                        ),
                        'mautic.category.menu.index' => array(
                            'bundle' => 'plugin:helloWorld'
                        )
                    )
                )
            )
        ),
        'admin' => array(
            'plugin.helloworld.admin' => array(
                'route'     => 'plugin_helloworld_admin',
                'iconClass' => 'fa-gears',
                'access'    => 'admin',
                'checks'    => array(
                    'parameters' => array(
                        'helloworld_api_enabled' => true
                    )
                ),
                'priority'  => 60
            )
        )
    ),

```

Menu defines the menu items to display in the different menus.
#### Menu types[](https://developer.mautic.org/#menu-types)
Mautic 2.0 has four customizable menus. 
Menu Name | Location  
---|---  
**main** | Main menu on the left  
**admin** | Admin menu accessible through the cogwheel in upper right hand side of Mautic  
**profile** | Profile menu accessible through clicking the username in upper right hand side of Mautic  
**extra** | Displays to the right of the Mautic logo in the upper left hand. Only shows if there are menu items injected.  
#### Priority[](https://developer.mautic.org/#priority)
To control the placement of the menu item set, set an array with 'priority’ and 'items’ keys. Priority can be negative to position the items lower than others or positive to position them higher. If the menu items are returned without setting priority, like the admin menu in the code example, priority is treated as 9999.
To control the priority of individual menu items, set `priority` it’s definition array.
#### Parent[](https://developer.mautic.org/#parent)
To place a menu item in another bundles parent menu item, for example Channels or Components, define the `parent` key with the key of the menu item this item should display under. For example, to show an item under the Channels parent menu item, use `'parent'    => 'mautic.core.channels',`. 
#### Menu item definitions[](https://developer.mautic.org/#menu-item-definitions)
The menu item’s name should be the [language string key](https://developer.mautic.org/#translations) that will be displayed as the item’s link. 
Item definitions:
Array Key | Required | Type | Description  
---|---|---|---  
**route** | OPTIONAL | string | The route name as defined in [routes](https://developer.mautic.org/#routes). Do not set a route to treat the item as a parent to activate a submenu.  
**routeParameters** | OPTIONAL | array | Route placeholder values to use when generating the URL  
**id** | OPTIONAL | string | Sets the id of the <a /> attribute. This will default to what is set as route. This is used in conjuction with `returnUrl` returned in a controller’s response so that the correct menu item is highlighted when ajax is used to navigate the interface.  
**iconClass** | OPTIONAL | string | Font Awesome class to set the icon for the menu item.  
**access** | OPTIONAL | string | Set the [permission](https://developer.mautic.org/#security) required for this item to display to the user currently logged in. Can also set 'admin’ to restrict to Administrators only.  
**checks** | OPTIONAL | array | Restricts display of the link based on either configured parameters or the GET request. It will accept a 'parameters’ and/or 'request’ array of key => value pairs that must be true to display the menu item.  
**bundle** | OPTIONAL | string | Required only for [category integration](https://developer.mautic.org/#categories).  
**parent** | OPTIONAL | string | Display this item under another parent menu item.  
**priority** | OPTIONAL | int | Set the priority for ordering this menu item with it’s siblings.  
### Services[](https://developer.mautic.org/#services)
```
<?php // continued 

    'services'    => array(
        'events' => array(
            'plugin.helloworld.leadbundle.subscriber' => array(
                'class' => 'MauticPlugin\HelloWorldBundle\EventListener\LeadSubscriber'
            )
        ),
        'forms'  => array(
            'plugin.helloworld.form' => array(
                'class' => 'MauticPlugin\HelloWorldBundle\Form\Type\HelloWorldType',
                'alias' => 'helloworld'
            )
        ),
        'helpers' => array(
            'mautic.helper.helloworld' => array(
                'class'     => 'MauticPlugin\HelloWorldBundle\Helper\HelloWorldHelper',
                'alias'     => 'helloworld'
            )
        ),
        'other'   => array(
            'plugin.helloworld.mars.validator' => array(
                'class'     => 'MauticPlugin\HelloWorldBundle\Form\Validator\Constraints\MarsValidator',
                'arguments' => 'mautic.factory',
                'tag'       => 'validator.constraint_validator',
                'alias'     => 'helloworld_mars'
            )
        )
    ),


```

Services are PHP objects stored in the service container and are used all throughout Mautic. They can be as simple or as complex as required. Read more about Symfony’s service container 
#### Service types[](https://developer.mautic.org/#service-types)
Mautic allows easy configuration for four types of services:
Type | Description  
---|---  
**events** | Defines event subscriber classes used to listen to events dispatched throughout Mautic and auto-tagged with 'kernel.event_subscriber.’ The defined class must extend \Mautic\CoreBundle\EventListener\CommonSubscriber. Read more about subscribers [here](https://developer.mautic.org/#subscribers).  
**forms** | Defines custom [form types](https://developer.mautic.org/#forms) and auto-tagged with 'form.type.’  
**helpers** | Defines custom template helpers available through the $view variable in [views](https://developer.mautic.org/#views). These services are auto-tagged with 'templating.helper.’  
**models** | Defines [model services](https://developer.mautic.org/#models)  
**other** | All other custom services.  
#### Service definitions[](https://developer.mautic.org/#service-definitions)
Each key within the service types array is the name of the service and must be unique. Use the following to define the service:
Array Key | Required | Type | Description  
---|---|---|---  
**class** | REQUIRED | string | Namespace to the service class (not that it does not start with a backslash)  
**arguments** | OPTIONAL | string or array | String of a single argument to pass to the construct or an array of arguments to pass. Arguments enclosed with %% will be treated as a [parameter](https://developer.mautic.org/#parameters). To pass a specific string, enclose the argument with double quotations “”. Anything else that is not a boolean or a namespaced class (string with \ in it) will be treated as the name of another registered service. Often, this will simply be [mautic.factory](https://developer.mautic.org/#factory-service).  
**alias** | OPTIONAL | string | Sets the alias used by the service. For example, the key for the template helpers, $view, array or the string to retrieve a specific form type.  
**tag** | OPTIONAL | string  
**tags** | OPTIONAL | array | Array of of tags  
**tagArguments** | OPTIONAL | array | Array of attributes for the tag. See   
**scope** | OPTIONAL | string | Defines the   
**factory** | OPTIONAL | string | Preferred method for using a factory class.   
**factoryService** | OPTIONAL | string |  `factory` instead.  
**factoryMethod** | OPTIONAL | string | Method name in the `factory` instead.  
**methodCalls** | OPTIONAL | array | Array of methods to be called after a service is created passing in the array of arguments provided. Should be in the format of 'methodName’ => array('service_name’, ’%parameter%’)  
**decoratedService** | OPTIONAL | array  
**public** | OPTIONAL | bool  
**lazy** | OPTIONAL | bool  
**synthetic** | OPTIONAL | bool  
**synthetic** | OPTIONAL | bool  
**file** | OPTIONAL | string  
**configurator** | OPTIONAL | array  
### Categories[](https://developer.mautic.org/#categories)
```
<?php // continued

    'categories' => array(
        'plugin:helloWorld' => 'mautic.helloworld.world.categories'
    ),

```

Defines category types available or the Category manager. See [Extending Categories](https://developer.mautic.org/#extending-categories).
### Parameters[](https://developer.mautic.org/#parameters)
```
<?php // continued

    'parameters' => array(
        'helloworld_api_enabled' => false
    )
);

```

The parameters array define and set default values for [custom configuration parameters](https://developer.mautic.org/#custom-config-params) specific to the plugin. 
To obtain the values of these parameters, use the [`mautic.helper.core_parameters` service](https://developer.mautic.org/#config-parameters).
Any parameter to be written to the system’s local config file should be defined here. 
## Translations[](https://developer.mautic.org/#translations)
Mautic uses INI files for translations.
HelloWorldBundle/  
- - - Translations/  
- - - - - - en_US/  
- - - - - - - - - messages.ini
All plugins should include strings for the United States English locale (en_US) as it is the default for the system. 
The directory structure for translations should be `Translations/locale/domain.ini`.
### Domains[](https://developer.mautic.org/#domains)
Language strings can be organized into domains. Each domain should be its own file in the plugin’s language locale folder(s). The plugin can use any domain it wants but Mautic makes consistent use of three domains:
Domain | Description  
---|---  
messages | Default domain for the translator service when no domain is specified  
flashes | Domain for [flash messages](https://developer.mautic.org/#flash-messages)  
validators | Domain for [form validation](https://developer.mautic.org/#validation) messages  
### INI files[](https://developer.mautic.org/#ini-files)
> Sample INI files
```
; plugins/HelloWorldBundle/Translations/en_US/messages.ini

plugin.helloworld.contact_us="Contact Us"
plugin.helloworld.goodbye="Goodbye and have a good day!"
plugin.helloworld.greeting="Hello %name%!"
plugin.helloworld.index="Hello World"
plugin.helloworld.manage_worlds="Manage Worlds"
plugin.helloworld.number_of_planets="{0}0 planets|{1}1 planet|]1,Inf[%planets% planets"
plugin.helloworld.world="World"
plugin.helloworld.worlds="%world% Description"

```
```
; plugins/HelloWorldBundle/Translations/en_US/flashes.ini

plugin.helloworld.notice.thank_you="Thank you %name% for your interest! We will be in contact soon." 
plugin.helloworld.notice.planet_demoted="%planet% has been demoted to a dwarf planet." 
plugin.helloworld.error.planet_demotion_failed="%planet% could not be demoted because the scientists say so."

```

General guidelines for the translation keys:
  1. Segment the key using a period
  2. Use underscores to separate words
  3. Must be unique
  4. Be short yet descriptive
  5. Use all lowercase letters and numbers (no punctuation in the key other than period or underscore)


Guidelines for translation strings:
  1. Wrap placeholders with %%
  2. Use a single key for duplicate translation strings.
  3. Use “ for double quotes
  4. HTML is allowed


### Using the translator[](https://developer.mautic.org/#using-the-translator)
Refer to the [translator service](https://developer.mautic.org/#translator) to learn how to use translations in the code.
### Using the translator in your javascript[](https://developer.mautic.org/#using-the-translator-in-your-javascript)
If your bundle implements custom javascript where translations are required, you can get them by the `Mautic.translate(key, params)` method.
Create a `javascript.ini` in the same directory as the `messages.ini` as described above. Any translation strings added to that file will be available when translating in javascript.
For example, if your `javascript.ini` file contained the following translation strings:
```
mautic.core.dynamic_content="Dynamic Content"
mautic.core.dynamic_content.new="Dynamic Content %number%"

```

You can request those translation strings in your javascript by passing the key to the `Mautic.translate()` function.
```
Mautic.translate("mautic.core.dynamic_content");
// outputs "Dynamic Content"

```

String interpolation for messages with variables works with js translations just as you’d expect.
```
Mautic.translate("mautic.core.dynamic_content.new", {number: 4});
// outputs "Dynamic Content 4"

```

## MVC[](https://developer.mautic.org/#mvc)
Mautic uses a Model-View-Controller structure to manage user interaction on the frontend (views) with the underlying code processes (controllers and models). ([Entity and Repository classes](https://developer.mautic.org/#database) are also used to manage interaction with the database).
In Symfony, and thus Mautic, the controller is the center of the MVC structure. The route requested by the user determines the controller method to call. The controller will then communicate with the model to get or manipulate data then display it to the user through the view.
### Controllers[](https://developer.mautic.org/#controllers)
```
<?php
// plugins/HelloWorldBundle/Controller/DefaultController.php

namespace MauticPlugin\HelloWorldBundle\Controller;

use Mautic\CoreBundle\Controller\FormController;

class DefaultController extends FormController
{
    /**
     * Display the world view
     *
     * @param string $world
     *
     * @return JsonResponse|\Symfony\Component\HttpFoundation\Response
     */
    public function worldAction($world = 'earth')
    {
        /** @var \MauticPlugin\HelloWorldBundle\Model\WorldModel $model */
        $model = $this->getModel('helloworld.world');

        // Retrieve details about the world
        $worldDetails = $model->getWorldDetails($world);

        return $this->delegateView(
            array(
                'viewParameters'  => array(
                    'world'   => $world,
                    'details' => $worldDetails
                ),
                'contentTemplate' => 'HelloWorldBundle:World:details.html.php',
                'passthroughVars' => array(
                    'activeLink'    => 'plugin_helloworld_world',
                    'route'         => $this->generateUrl('plugin_helloworld_world', array('world' => $world)),
                    'mauticContent' => 'helloWorldDetails'
                )
            )
        );
    }

    /**
     * Contact form
     *
     * @return JsonResponse|\Symfony\Component\HttpFoundation\Response
     */
    public function contactAction()
    {
        // Create the form object
        $form = $this->get('form.factory')->create('helloworld_contact');

        // Handle form submission if POST        
        if ($this->request->getMethod() == 'POST') {
            $flashes = array();

            // isFormCancelled() checks if the cancel button was clicked
            if ($cancelled = $this->isFormCancelled($form)) {

                // isFormValid() will bind the request to the form object and validate the data
                if ($valid = $this->isFormValid($form)) {

                    /** @var \MauticPlugin\HelloWorldBundle\Model\ContactModel $model */
                    $model = $this->getModel('helloworld.contact');

                    // Send the email
                    $model->sendContactEmail($form->getData());

                    // Set success flash message
                    $flashes[] = array(
                        'type'    => 'notice',
                        'msg'     => 'plugin.helloworld.notice.thank_you',
                        'msgVars' => array(
                            '%name%' => $form['name']->getData()
                        )
                    );
                }
            }

            if ($cancelled || $valid) {
                // Redirect to /hello/world

                return $this->postActionRedirect(
                    array(
                        'returnUrl'       => $this->generateUrl('plugin_helloworld_world'),
                        'contentTemplate' => 'HelloWorldBundle:Default:world',
                        'flashes'         => $flashes
                    )
                );
            } // Otherwise show the form again with validation error messages
        }

        // Display the form
        return $this->delegateView(
            array(
                'viewParameters'  => array(
                    'form' => $form->createView()
                ),
                'contentTemplate' => 'HelloWorldBundle:Contact:form.html.php',
                'passthroughVars' => array(
                    'activeLink' => 'plugin_helloworld_contact',
                    'route'      => $this->generateUrl('plugin_helloworld_contact')
                )
            )
        );
    }
}

```

#### Matching Routes to Controller Methods[](https://developer.mautic.org/#matching-routes-to-controller-methods)
The controller method called is determined by the [route defined in the config](https://developer.mautic.org/#routes). Take this example,
```
plugin_helloworld_admin' => array(
    'path'       => '/hello/admin',
    'controller' => 'HelloWorldBundle:Default:admin'
 ),

```

The controller is noted as `HelloWorldBundle:Default:admin`. Broken down, that will translate to:
HelloWorldBundle | \MauticPlugin\HelloWorldBundle\Controller  
---|---  
Default | DefaultController  
admin | adminAction()  
Controller notation is in the format of `BundleName:ControllerName:controllerMethod`. To use a controller within a subfolder of Controller, use `BundleName:Subdirectory\ControllerName:controllerMethod`. 
Thus when a browser calls up `/hello/admin`, `\MauticPlugin\HelloWorldBundle\Controller\DefaultController\adminAction()` will be called.
What about route placeholders? Symfony is super smart and will pass those into the controller’s method as arguments (the method’s arguments must be the same as the route’s placeholders to be matched up).
```
'plugin_helloworld_world' => array(
    'path'       => '/hello/{world}',
    'controller' => 'HelloWorldBundle:Default:world',
    'defaults'    => array(
        'world' => 'earth'
    ),
    'requirements' => array(
        'world' => 'earth|mars'
    )
),

```

The matching method for that route will look be `public function worldAction($world = 'earth')`.
Notice that because the route defines a default for `name`, the controller method must also set the same default. If the route looked like this instead:
```
'plugin_helloworld_world' => array(
    'path'       => '/hello/{world}',
    'controller' => 'HelloWorldBundle:Default:world',
    'requirements' => array(
        'world' => 'earth|mars'
    )
),

```

Then the method would need to be `public function worldAction($world)`.
#### Extending Mautic’s Controllers[](https://developer.mautic.org/#extending-mautic's-controllers)
Mautic has several controllers that provide some helper functions.
##### Mautic\CoreBundle\Controller\CommonController[](https://developer.mautic.org/#mautic\\corebundle\\controller\\commoncontroller)
Controllers extending this will make [MauticFactory](https://developer.mautic.org/#factory-service) available via `$this->factory` and [Request](https://developer.mautic.org/#request) via `$this->request`. 
It also provides the following helper methods:
###### delegateView($args)[](https://developer.mautic.org/#delegateview\($args\))
Mautic is ajax driven and thus must support both http requests and ajax requests for content. `delegateView` is wrapper method that determines if the request is for ajax content or the full DOM then generates and returns the appropriate response. 
The $args argument is an array with the required elements for generating the view, ajax or http. It will accept the following parameters:
Key | Required | Type | Description  
---|---|---|---  
contentTemplate | REQUIRED | string | Defines the view template to load. This should be in view notation of BundleName:ViewName:template.html.php. Refer to [views](https://developer.mautic.org/#views) for more information.  
viewParameters | OPTIONAL | array | Array of variables with values made available to the template. Each key will be a variable available to the template.  
passthroughVars | OPTIONAL | array | Array of variables returned as part of the ajax response used by Mautic and/or the plugin’s onLoad JS callback.  
Due to the use of ajax, there are some elements of the `passthroughVars` array that Mautic will use internally to manipulate the user interface. For responses that include main content, i.e. routes a user would click to, should set at least `activeLink` and `route`.
Key | Required | Type | Description  
---|---|---|---  
activeLink | OPTIONAL | string | The [ID of the menu item](https://developer.mautic.org/#items) that should be activated dynamically to match the ajax response  
route | OPTIONAL | string | The route that should be pushed to the browser’s address bar to match the ajax response  
mauticContent | OPTIONAL | string | Used to generate the Javascript method to call after the ajax content has been injected into the DOM. The same function will also be called on a page refresh/full page load if set via `$view['slots']` in the template. For example, if this is set as `helloWorldDetails`, Mautic will check for the existence of and executes `Mautic.helloWorldDetailsOnLoad()`. Refer to [Processing Ajax Content](https://developer.mautic.org/#processing-ajax-content) for more information regarding this and [Asset Helper](https://developer.mautic.org/#asset-helper) for injecting assets into the head for ajax generated content.  
callback | OPTIONAL | string | A Mautic namespaced JS function that will be executed before the response is injected into the DOM. If set, Mautic will pass the response to the function and not process the content. It will be up to the callback function to handle the rest of the process.  
redirect | OPTIONAL | string | The URL to force a page redirect rather than inject ajax content.  
target | OPTIONAL | string | jQuery selector to inject the content into. By default, the app’s main content selector will be used.  
replaceContent | OPTIONAL | string | Determines if Mautic should replace the target selector with the ajax content or set as its inner HTML. Return ‘true’ as a string to replace the selector.  
###### delegateRedirect($url)[](https://developer.mautic.org/#delegateredirect\($url\))
Delegates the appropriate response for redirects. 
If an ajax request, a json response with `{redirect: $url}` will be returned allowing the executing JS code to force the redirect.
If an http request, then a redirect response is returned (i.e redirect header).
###### postActionRedirect($args)[](https://developer.mautic.org/#postactionredirect\($args\))
Similar to delegateView(), this method will delegate the appropriate response based on the request. This method can be used after performing some action, such as saving a form. It accepts the same elements in the $args array as delegateView() but also accepts the following:
Key | Required | Type | Description  
---|---|---|---  
returnUrl | OPTIONAL | string | The URL to redirect to. It will default to /s/dashboard if not set. This will also auto-populate passthroughVars[route] if not set.  
flashes | OPTIONAL | array | Array of flash messages to display after redirecting. See [Flash Messages](https://developer.mautic.org/#flash-messages) for more information.  
forwardController | OPTIONAL | bool | By default, the request is forwarded to a controller method rather than directly loading a view template. This means that contentTemplate should be in controller notation (BundleName:ControllerName:controllerMethod) rather than view notation (BundleName:ViewName:template.html.php). Set this to false to directly load a view template rather than forwarding to another controller.  
##### Mautic\CoreBundle\Controller\FormController[](https://developer.mautic.org/#mautic\\corebundle\\controller\\formcontroller)
This controller extends CommonController and provides helper methods for managing forms. See [Forms](https://developer.mautic.org/#forms) for more information.
##### Mautic\CoreBundle\Controller\AjaxController[](https://developer.mautic.org/#mautic\\corebundle\\controller\\ajaxcontroller)
This controller also extends CommonController and is a companion to some of the built-in Javascript helpers. See [Javascript methods](https://developer.mautic.org/#javascript-methods) for more information.
### Models[](https://developer.mautic.org/#models)
```
<?php
// plugins/HelloWorldBundle/Model/ContactModel.php

namespace MauticPlugin\HelloWorldBundle\Model;

use Mautic\CoreBundle\Model\CommonModel;

class ContactModel extends CommonModel
{

    /**
     * Send contact email
     * 
     * @param array $data
     */
    public function sendContactEmail($data)
    {
        // Get mailer helper - pass the mautic.helper.mailer service as a dependency
        $mailer = $this->mailer;

        $mailer->message->addTo(
            $this->factory->getParameter('mailer_from_email')
        );

        $this->message->setFrom(
            array($data['email'] => $data['name'])
        );

        $mailer->message->setSubject($data['subject']);

        $mailer->message->setBody($data['message']);

        $mailer->send();
    }
}

```

Models are used to retrieve and process data between controllers and views. Models aren’t required for plugins but, if used, Mautic provides means to easily obtain the model objects and some commonly used methods.
#### Model Classes[](https://developer.mautic.org/#model-classes)
Model’s should be registered as [`model` services](https://developer.mautic.org/#service-types). The names of these services should match the following nomenclature: `mautic.UNIQUE_BUNDLE_IDENTIFIER.model.MODEL_IDENTIFIER`. `UNIQUE_BUNDLE_IDENTIFIER` can be whatever is desired but must be unique across all Mautic bundles and plugins. `MODEL_IDENTIFIER` just has to be unique for the given bundle. For example, the model example code could be registered as `mautic.helloworld.model.contact`. This allows the helper functions to retrieve model objects to find the correct model service. 
Custom models can extend one of two Mautic base models to leverage some helper functions:
##### \Mautic\CoreBundle\Model\AbstractCommonModel[](https://developer.mautic.org/#\\mautic\\corebundle\\model\\abstractcommonmodel)
This is the basic model that mainly provides access to services frequently used with models.
Property | Service  
---|---  
$this->factory |  [Mautic’s factory service](https://developer.mautic.org/#factory-service) - deprecated as of 2.0; use direct dependency injection where possible  
$this->em | [Entity manager service](https://developer.mautic.org/#database)  
$this->security | [Mautic’s security service](https://developer.mautic.org/#security)  
$this->dispatcher | [Event dispatcher service](https://developer.mautic.org/#events)  
$this->translator | [Translator service](https://developer.mautic.org/#translator)  
##### \Mautic\CoreBundle\Model\FormModel[](https://developer.mautic.org/#\\mautic\\corebundle\\model\\formmodel)
The FormModel extends AbstractCommonModel and provides a set of helper methods for interacting with entities and repositories. To read more about these methods, refer to the [Database](https://developer.mautic.org/#database) section. 
#### Getting Model Objects[](https://developer.mautic.org/#getting-model-objects)
```
<?php

/** @var \Mautic\LeadBundle\Model\LeadModel $leadModel */
$leadModel = $this->getModel('lead'); // shortcut for lead.lead

/** @var \Mautic\LeadBundle\Model\ListModel $leadListModel */
$leadListModel = $this->getModel('lead.list');

/** @var \MauticPlugin\HelloWorldBundle\Model\ContactModel $contactModel */
$contactModel = $this->getModel('helloworld.contact');

```

If using a model in another service or model, inject the model service as a dependency. If in a controller, use the `getModel()` helper function.
### Views[](https://developer.mautic.org/#views)
```
<?php
//plugins/HelloWorldBundle/Views/World/details.html.php

// Check if the request is Ajax
if (!$app->getRequest()->isXmlHttpRequest()) {

    // Set tmpl for parent template
    $view['slots']->set('tmpl', 'Details');

    // Extend index.html.php as the parent
    $view->extend('HelloWorldBundle:World:index.html.php');
}
?>

<div>
    <!-- Desired content/markup -->
</div>

```
```
<?php
// plugins/HelloWorldBundle/Views/World/index.html.php

// Extend the base content
$view->extend('MauticCoreBundle:Default:content.html.php');

// Get tmpl from sub-template
$tmpl = $view['slots']->get('tmpl', 'Details');

// Tell Mautic to call JS onLoad method
$view['slots']->set('mauticContent', 'helloWorld'.$tmpl);

// Set the page and header title
$header = ($tmpl == 'World')
    ? $view['translator']->trans(
        'plugin.helloworld.worlds',
        array('%world%' => ucfirst($world))
    ) : $view['translator']->trans('plugin.helloworld.manage_worlds');
$view['slots']->set('headerTitle', $header);
?>

<div class="helloworld-content">
    <?php $view['slots']->output('_content'); ?>
</div>

```

Views take data given it from the controller and displays the content to the user. Templates can be called from the controller or from within other templates.
It was discussed in the Controller’s [delegateView() method](https://developer.mautic.org/#delegateredirect\($url\)) how to render a view from a controller. Remember that delegateView uses contentTemplate to determine what view to render.
Similar to controller notation, views are noted as `HelloWorldBundle:Contact:form.html.php` which will point to the file `/path/to/mautic/plugins/HelloWorldBundle/Views/Contact/form.html.php`. 
View notation is in the format of `BundleName:ViewName:template.html.php`. To use a view that has been nested in Views, use `BundleName:ViewName\Subfolder:template.html.php`. 
#### View Parameters[](https://developer.mautic.org/#view-parameters)
Remember the array passed via viewParameters in the Controller’s [delegateView() method](https://developer.mautic.org/#delegateview\($args\))? Here is where the elements of that array will be made available as variables. 
For example, `$world` will be available and assigned the value of `mars` from the following example: 
```
 'viewParameters'  => array(
     'world' => 'mars'
 ),
 
```

By default there are a couple variables available and should not be overridden by the controller
Variable | Description  
---|---  
**$view** | Contains all the helper objects available to templates along with providing methods for extending and/or rendering other templates.  
**$app** | Gives access to request and session to views via `$app->getRequest()` and `$app->getSession()`  
#### Extending Views[](https://developer.mautic.org/#extending-views)
```
<?php

// Extends the full document with menu, page header, etc
$view->extend('MauticCoreBundle:Default:content.html.php');

```
```
<?php

// Extends the "slim" document which includes just the head and body with main content; does not include menu, page header, etc.
$view->extend('MauticCoreBundle:Default:content.html.php');

```

Because of the use of Ajax, views must also be able to return main content vs the entire document. This is done by extending Mautic’s base templates. Notice the notation is the same as what is used in controllers.
To determine if the request is Ajax or not, use `$app->getRequest()->isXmlHttpRequest()`. Another option is to make the determination in the controller and pass it in the `viewParameters` array.
Of course, this can also be used to extend custom templates as demonstrated in [this code example](https://developer.mautic.org/#views).
The controller should call the sub-template.  It may help to note that extended templates are rendered inside out. So if `HelloWorldBundle:World:details.html.php` extends `HelloWorldBundle:World:index.html.php` which extends `MauticCoreBundle:Default:content.html.php`, the content of details.html.php will be rendered first and injected into index.html.php as it is rendered. `HelloWorldBundle:World:template1.html.php` will be rendered last. 
To include the content from the sub-template in the parent template, use `$view['slots']->output('_content');`. See the [Slots Helper](https://developer.mautic.org/#slots-helper) for more information.
#### Rendering Views within Views[](https://developer.mautic.org/#rendering-views-within-views)
To render the content of another template from within a template, simply use `echo $view->render('BundleName:ViewName:template.html.php', array('parameter' => 'value'));`
#### Template Helpers[](https://developer.mautic.org/#template-helpers)
There are a number of template helper objects and helper view templates that are built into Mautic.
##### Slots Helper[](https://developer.mautic.org/#slots-helper)
```
<?php

// Set a slot with content; will overwrite if slot already exists 
$view['slots']->set('name', 'the content');

// Append content to slot rather than overwrite
$view['slots']->append('name', ' and more content');
$view['slots']->append('existingArray', 
    array(
        'append' => 'me'
    )
);

// Get the slot content
$content = $view['slots']->get('name', 'default value');

// Output the content; note that echo is not required
$view['slots']->output('name');

// Check if a slot exists
if ($view['slots']->has('name')) {
    // Do something
}

```

As seen with extending views, the slots helper is used to pass content up through parent templates. Remember that extended templates are rendered inside out. So, content can be set in a sub template and accessed from the parent template but content set in a parent template, will not be available to the sub-template.
##### Asset Helper[](https://developer.mautic.org/#asset-helper)
```
<?php

// Generate relative URL to image
echo '<img src="' . $view['assets']->getUrl('plugins/HelloWorldBundle/assets/images/earth.png') . '" />';

// Dynamically insert script into head
echo $view['assets']->includeScript('plugins/HelloWorldBundle/assets/helloworld.js');

// Dynamically insert stylesheet into head
echo $view['assets']->includeStylesheet('plugins/HelloWorldBundle/assets/helloworld.css');

```

The asset helper, accessed via `$view['assets']`, is used to load assets into the DOM including images, script and stylesheets. 
`$view['assets']` should always be used to ensure that assets work with Mautic installed in the web root, installed in a subdirectory, ran under the dev environment (index_dev.php), and/or ran under the prod environment. 
The asset helper also provides a way to insert scripts and stylesheets into the head for ajax loaded content using `$view['assets']->includeScript()` and `$view['assets']->includeStylesheet()`.
##### Router Helper[](https://developer.mautic.org/#router-helper)
```
<a href="<?php echo $view['router']->generate('plugin_helloworld_world', array('world' => 'mars')); ?>" data-toggle="ajax" />Mars</a>

```

The router helper, `$view['router']`, works as explained in the [Router](https://developer.mautic.org/#router).
##### Translation Helper[](https://developer.mautic.org/#translation-helper)
```
<h1><?php echo $view['translator']->trans('plugin.helloworld.worlds', array('%world%', 'Mars'); ?></h1>

```

The translation helper, `$view['translator']`, works as explained in the [Translator](https://developer.mautic.org/#translator) section.
##### Date Helper[](https://developer.mautic.org/#date-helper)
```
<?php

// Can be string or \DateTime object; if string, it's assumed local time unless noted otherwise via third argument to helper methods
$datetime = '2015-04-12 20:56:00';

// Formats per full date system config setting 
$fullDateTime = $view['date']->toFull($datetime);

// Formats per short date system config setting
$shortDateTime = $view['date']->toShort($datetime);

// Formats per date only system config setting
$date = $view['date']->toDate($datetime);

// Formats per time only system config setting
$time = $view['date']->toTime($datetime);

// Formats as date only config setting + time only config setting
$datetime = $view['date']->toFullConcat($datetime);

// Formats date as Yesterday, 8:02 pm (Today or Tomorrow); otherwise 'x days ago'  
$text = $view['date']->toText($datetime);

// Format a string that is not already in local time
$fullDateTime = $view['date']->toFull($datetime, 'Y-m-d H:i:s', 'UTC');

```

The date helper can be used to format dates based on system and/or user settings. 
The first argument to the various methods can either be a date/time string or a \DateTime object. If a string, it is expected to be formatted as ‘Y-m-d H:i:s’ and already in the user’s and/or system’s local time. If it is not, pass the format as the second argument and the timezone (string) as the third.
##### Form Helper[](https://developer.mautic.org/#form-helper)
```
<?php echo $view['form']->form($form); ?>

```

The form helper, `$view['form']`, works as explained in the [Form](https://developer.mautic.org/#form-template-helper) section.
#### View Helper Templates[](https://developer.mautic.org/#view-helper-templates)
@todo
#### Processing Ajax Content[](https://developer.mautic.org/#processing-ajax-content)
Mautic provides built in ways to ajaxify links, modals, and forms.
##### Ajax Links[](https://developer.mautic.org/#ajax-links)
```
<a href="<?php echo $view['router']->generate('plugin_helloworld_world', array('world' => 'mars')); ?>" data-toggle="ajax" />Mars</a>

```

To ajaxify a link, set the attribute `data-target="ajax"`
##### Ajax Modals[](https://developer.mautic.org/#ajax-modals)
```
<a href="<?php echo $view['router']->generate('plugin_helloworld_world', array('world' => 'mars')); ?>" 
   data-toggle="ajaxmodal"
   data-target="#MauticSharedModal"
   data-header="<?php echo $view['translator']->trans('plugin.helloworld.worlds', array('%world%', 'Mars')); ?>">Mars</a>

```

Mautic uses Bootstrap modals but Bootstrap lacks an easy way to dynamically retrieve content more than once. Thus, Mautic provides the attribute `data-toggle="ajaxmodal"` to help with this.
`data-target` should be the selector of the model to inject the content into. Mautic has a modal, `#MauticSharedModal` on standby to be used for this very purpose.
`data-header` will set the modal’s header.
##### Ajax Forms[](https://developer.mautic.org/#ajax-forms)
When using Symfony’s [form services](https://developer.mautic.org/#forms), the form will be auto-ajaxified.
##### Ajax Content Callbacks[](https://developer.mautic.org/#ajax-content-callbacks)
```
Mautic.helloWorldDetailsOnLoad = function(container, response) {
    // Manipulate content 
};

Mautic.helloWorldDetailsOnUnload = function(container, response) {
    // Manipulate content 
};

```

Mautic provides a way to execute a javascript function after it injects ajax content into the DOM. This can be useful to activate various JS driven features such as typeaheads, charts, bind events, etc.
To take advantage of this, utilize the mauticContent element in the passthroughVars array from the controller’s [delegateView()](https://developer.mautic.org/#delegateView\($args\)). The value of this variable will determine what function should be called after the content has been injected.
For example, the method `Mautic.helloWorldDetailsOnLoad()` will be called for the following: 
```
 'passthroughVars' => array(
     'activeLink'    => 'plugin_helloworld_world',
     'route'         => $this->generateUrl('plugin_helloworld_world', array('world' => $world)),
     'mauticContent' => 'helloWorldDetails'
 )
 
```

When the user browses away from the page, `Mautic.helloWorldDetailsOnUnload()` will be called to give opportunity to destroy objects if necessary.
Both the OnLoad and OnUnload methods are passed two arguments.
Argument | Description  
---|---  
container | The selector that was used as the target of the ajax content.  
response | The object from the ajax response, i.e. set in the passthroughVars from the Controller  
`mauticContent` should also be set via `$view['slots']` in the [view’s](https://developer.mautic.org/#slots-helper) main page. 
```
$view['slots']->set('mauticContent', 'helloBundleDetails');

```

Doing so will ensure `Mautic.helloWorldDetailsOnLoad()` is also called when there is a page refresh.
## Services[](https://developer.mautic.org/#services)
These are the services used commonly throughout Mautic.
### Factory Service[](https://developer.mautic.org/#factory-service)
`\Mautic\Factory\MauticFactory` is deprecated as of 2.0 and will be phased out through 2.x release cycles and completely removed in 3.0. Direct dependency injection into the services should be used instead where possible. 
For [controllers](https://developer.mautic.org/#controllers), extend either `\Mautic\CoreBundle\Controller\CommonController` or `\Mautic\CoreBundle\Controller\FormController` and it will be available via `$this->factory` by default. Otherwise, obtain the factory from the service container via `$factory = $this->container->get('mautic.factory');`
For [models](https://developer.mautic.org/#models), it will be available via `$this->factory` by default.
For custom [services](https://developer.mautic.org/#services), pass ‘mautic.factory’ as an argument and MauticFactory will be passed into the __construct of the service.
### User[](https://developer.mautic.org/#user)
```
<?php
$user = $this->get('mautic.helper.user')->getUser();

$firstName = $user->getFirstname();
$lastName  = $user->getLastname();
$email     = $user->getEmail();
$profile   = $user->getProfile();

$role = $user->getRole()->getName();

if ($role->isAdmin()) {
    // do something
}

```

  * Service name: `mautic.helper.user`
  * Class: `Mautic\CoreBundle\Helper\UserHelper`


`getUser()` will return the [entity](https://developer.mautic.org/#database), `\Mautic\UserBundle\Entity\User` that can then be used to get information about the currently logged in user.
### Security[](https://developer.mautic.org/#security)
```
<?php

$security = $this->get('mautic.security');

// Check if user is granted a single permission
if ($security->isGranted('plugin:helloWorld:worlds:view')) {
    // do something
}

// Check if user is granted multiple permissions (must be granted to all to be true)
if ($security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:create',
    )
)
) {
    //do something
}

// Check if user is granted to at least one permission
if ($security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:edit',
    ),
    'MATCH_ONE'
)
) {
    //do something
}

// Get an array of user permissions
$permissions = $security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:edit',
    ),
    'RETURN_ARRAY'
);

if ($permissions['plugin:helloWorld:worlds:view']) {
    // do something
}

// Check to see if a user is anonymous (not logged in)
if ($security->isAnonymous()) {
    // do something
}

```

  * Service name: `mautic.security`
  * Class: `Mautic\CoreBundle\Security\Permissions\CorePermissions`


Using the service to check permissions is explained more in [Using Permissions](https://developer.mautic.org/#using-permissions).
### Translator[](https://developer.mautic.org/#translator)
```
<?php

$translator = $this->get('translator');

// Simple string
echo $translator->trans('plugin.helloworld.goodbye');

// Simple string with placeholders
echo $translator->trans('plugin.helloworld.greeting', array('%name%' => $name));

// String from a domain other than messages (will use planets.ini)
echo $translator->trans('plugin.helloworld.worlds', array('%world%' => $world), 'planets');

// Plural translations
$planetCount = 3;
echo $translator->transChoice('plugin.helloworld.number_of_planets', $planetCount, array('%planets%' => $planetCount));

// Check to see if a translation key exists
if ($translator->hasId('plugin.helloworld.goodbye')) {
    echo $translator->trans('plugin.helloworld.goodbye');
} else {
    // other logic
}

// Use the first key if it exists, otherwise use the second (helpful to prevent managing duplicate keys with the same string)
echo $translator->transConditional('plugin.helloworld.planets.' . $planet, 'plugin.helloworld.dwarf_planets. ' . $planet);

```

  * Service name: `translator`
  * Class: `Mautic\CoreBundle\Translation\Translator`
  * Docs: 


Use the translator service to include translated strings in the code. Depending on where the translation is necessary will determine how to obtain the service.
To use the template service in view templates, simply use the [template helper](https://developer.mautic.org/#translation-helper), `$view['translator']`.
The translator service has the following functions to help with translating strings:
**Simple translation**  
`trans($id, array $parameters = array(), $domain = null, $locale = null)`
  
`transChoice($id, $number, array $parameters = array(), $domain = null, $locale = null)`
**Check to see if a key exists**  
`hasId($id, $domain = null, $locale = null)`
**Use the $preferred key if it exists, if not, use $alternative**  
`transConditional($preferred, $alternative, $parameters = array(), $domain = null, $locale = null)`
### Router[](https://developer.mautic.org/#router)
```
<?php 

$router = $this->get('router');

// Relative URL
$url = $router->generateUrl('plugin_helloworld_admin');

// URL with placeholders
$url = $router->generateUrl('plugin_helloworld_world', array('%world%', 'mars'));

// Absolute URL
$absoluteUrl = $router->generateUrl('plugin_helloworld_admin', array(), true);

```
```
<?php 
// Deprecated - use path or url instead
$url = $view['router']->generate('plugin_helloworld_admin'); // result is /hello/admin

// Generate a path in a view template
$path = $view['router']->path('plugin_helloworld_admin'); // result is /hello/admin
$url  = $view['router']->url('plugin_helloworld_admin'); // result is http://yoursite.com/hello/admin


```

  * Service name: `router`
  * Class: `Symfony\Bundle\FrameworkBundle\Routing\Router`
  * Docs: 


For views, use the `$view['router']` helper. The difference with the [template helper](https://developer.mautic.org/#router-helper) is that `url()` or `path()` is used instead of `generateUrl()` of the `router` service.
### Request[](https://developer.mautic.org/#request)
```
<?php

$request = $this->get('request_stack')->getCurrentRequest();

// $_GET
$get = $request->query->all();

// $_POST
$post = $request->request->all();

// $_COOKIE
$cookies = $request->cookies->all();

// $_SERVER
$server = $request->server->all();

// Headers
$headers = $request->headers->all();

// Attributes - custom parameters
$headers = $request->attributes->all();

// Check if a parameter exists
if ($request->request->has('hello')) {
    // do something
}

// Retrieve value of a specific parameter setting mars as default
$world = $request->query->get('world', 'mars');

// Set custom request value
$request->attributes->set('hello', 'world');

// Get the value of a nested array
$mars = $request->request->get('world[mars]', array(), true);

```

  * Service name: `request_stack`
  * Class: `Symfony\Component\HttpFoundation\RequestStack`
  * Docs: 


There are multiple ways to obtain the request service.
If the controller is extending one of [Mautic’s controllers](https://developer.mautic.org/#controllers), it is already available via `$this->request`. Alternatively, Symfony will `Symfony\Component\HttpFoundation\Request`.
For services, pass the `request_stack` service then use `$request = $requestStack->getCurrentRequest()`.
From within a view, use `$app->getRequest()`.
### Session[](https://developer.mautic.org/#session)
```
<?php

$session        = $this->get('session');
$requestSession = $request->getSession(); // Shortcut to session

// Get all session parameters
$all = $session->all();

// Get specific parameter setting mars as default
$world = $session->get('helloworld.world', 'mars');

// Check if a parameter exists
if ($session->has('helloworld.world')) {
    // do something
}

// Set a session parameter
$session->set('helloworld.world', 'mars');

// Remove a session parameter
$session->remove('helloworld.world');

// Clear the whole session
$session->clear();

```

  * Service name: `session`
  * Class: `Symfony\Component\HttpFoundation\Session`
  * Docs: 


To access the session service in a view, use `$app->getSession()`.
### Database/Entity Manager[](https://developer.mautic.org/#database/entity-manager)
```
<?php
// From controller
$em         = $this->getDoctrine()->getManager();
$repository = $em->getRepository('HelloWorldBundle:World');
$worlds     = $repository->getEntities();

/** @var \MauticPlugin\HelloWorldBundle\Entity\World $world */
foreach ($worlds as $world) {
    $world->upVisitCount();
}

$repository->saveEntities($worlds);

```

Doctrine includes an ORM and DBAL layers. 
ORM/entity manager:
  * Service name: `doctrine.orm.default_entity_manager`
  * Class: `Doctrine\ORM\EntityManager`


DBAL (direct DB driver):
  * Service name: `doctrine.dbal.connection`
  * Class: `Doctrine\DBAL\Connection`


The entity manager can be used to interact with the bundle’s repositories and entities. See [Database](https://developer.mautic.org/##database) for more info. 
### Config Parameters[](https://developer.mautic.org/#config-parameters)
```
<?php 
$config = $this->get('mautic.helper.core_parameters');

$apiEnabled = $config->getParameter('helloworld_api_enabled', false);

```

  * Service name: `mautic.helper.core_parameters`
  * Class: `Mautic\CoreBundle\Helper\CoreParametersHelper`


### Event Dispatcher[](https://developer.mautic.org/#event-dispatcher)
```
<?php

$dispatcher = $this->get('event_dispatcher');
if ($dispatcher->hasListeners(HelloWorldEvents::ARMAGEDDON)) {
    $event = $dispatcher->dispatch(HelloWorldEvents::ARMAGEDDON, new ArmageddonEvent($world));

    if ($event->shouldPanic()) {
        throw new \Exception("Run for the hills!");
    }
}

```

  * Service name: `event_dispatcher`
  * Class: `Symfony\Component\EventDispatcher\EventDispatcher`
  * Implements `Symfony\Component\EventDispatcher\EventDispatcherInterface` (When type hinting, use this class since different environments may use different classes for the dispatcher)
  * Docs: 


Dispatch [custom events](https://developer.mautic.org/#custom-events) using the `event_dispatcher` service.
### Paths Helper[](https://developer.mautic.org/#paths-helper)
```
<?php 
$pathsHelper = $this->get('mautic.helper.paths');

$relativeImagesDir = $pathsHelper->getSystemPath('images'); // media/images
$absoluteImageDir  = $pathsHelper->getSystemPath('images', true); // /home/user/public_html/media/images

```

  * Service name: `mautic.helper.paths`
  * Class: `Mautic\CoreBundle\Helper\PathsHelper`


This helper should be used when retrieving system paths for Mautic (images, themes, cache, etc)
There is also a `tmp` or `temporary` option to store temporary files. It should be used by developers for such use case instead of the general `cache` location. 
### IP Lookup Helper[](https://developer.mautic.org/#ip-lookup-helper)
```
<?php 
$ipHelper = $this->get('mautic.helper.ip_lookup');

$requestIp = $ipHelper->getIpAddressFromRequest(); // 1.2.3.4

/** @var \Mautic\CoreBundle\Entity\IpAddress $ipAddressEntity */
$ipAddressEntity = $ipHelper->getIpAddress();

/** @var array $details */
$details = $ipAddressEntity->getIpDetails();

echo $details['city'];

```

  * Service name: `mautic.helper.ip_lookup`
  * Class: `Mautic\CoreBundle\Helper\IpLookupHelper`


This helper can be used to retrieve the real IP for the request.
### Plugin Config Helper[](https://developer.mautic.org/#plugin-config-helper)
```
<?php 
$configHelper = $this->get('mautic.helper.bundle');

$menu = $configHelper->getBundleConfig('HelloWorldBundle', 'menu', true);

```

  * Service name: `mautic.helper.bundle`
  * Class: `Mautic\CoreBundle\Helper\BundleHelper`


This can be used to get the configuration array of a bundle/plugin’s Config/config.php file.
### Cookie Helper[](https://developer.mautic.org/#cookie-helper)
```
<?php

$cookieHelper = $this->get('mautic.helper.cookie');
$cookieHelper->setCookie('name', 'value', 3600);

$cookieHelper->deleteCookie('name');

```

  * Service name: `mautic.helper.cookie`
  * Class: `Mautic\CoreBundle\Helper\CookieHelper`


The cookie helper can be used to set cookies based on system settings.
### Mail Helper[](https://developer.mautic.org/#mail-helper)
```
<?php
$mailer = $this->get('mautic.helper.mailer')->getMailer();

// To address; can use setTo(), addCc(), setCc(), addBcc(), or setBcc() as well
$mailer->addTo($toAddress, $toName);

// Set a custom from; will use system settings by default
$mailer->setFrom(
    $this->user->getEmail(),
    $this->user->getFirstName().' '.$this->user->getLastName()
);

// Set subject
$mailer->setSubject($email['subject']);

// Set content
$mailer->setBody($content);
$mailer->parsePlainText($content);

// Optional lead tracking (array)
$mailer->setLead($lead);
$mailer->setIdHash();

// Send the mail, pass true to dispatch through event listeners (for replacing tokens, etc)
if ($mailer->send(true)) {

    // Optional to create a stat to allow a web view, tracking, etc
    $mailer->createLeadEmailStat();
} else {
    $errors = $mailer->getErrors();
    $failedRecipients = $errors['failures'];
}

```
```
<?php
// Using queue() for tokenization support

use Mautic\EmailBundle\Swiftmailer\Exception\BatchQueueMaxException;

$mailer = $this->get('mautic.helper.mailer')->getMailer();
$failed = array();

$mailer->enableQueue();
foreach ($emailList as $email) {
    try {
        if (!$mailer->addTo($email['email'], $email['name'])) {
            // Clear the errors so it doesn't stop the next send
            $mailer->clearErrors();

            $failed[] = $email;

            continue;
        }
    } catch (BatchQueueMaxException $e) {
        // Queue full so flush (send) then try again
        if (!$mailer->flushQueue()) {
            $errors = $mailer->getErrors();
            $failed = array_merge($failed, $errors['failures']);
        }

        if (!$mailer->addTo($email['email'], $email['email'], $email['name'])) {
            // ...
        }
    }
}

// Flush pending
if (!$mailer->flushQueue()) {
    // ...
}

```

The mail helper can be used to send email, running the content through the event listeners to search/replace tokens, manipulate the content, etc. 
Some transports, such as Mandrill, support tokenized emails for multiple recipients. The mail helper makes it easy to leverage this feature by using it’s `queue()` and `flushQueue()` functions in place of `send()`. If sending a batch of emails, it is recommended to use the `queue()` function. Although these classes will still work with using just `send()` for one off emails, if sending a batch of the same email to multiple contacts, enable tokenization/batch mode with `enableQueue()`. 
If using an Email entity (`\Mautic\EmailBundle\Entity\Email`), just pass the Email entity to `$mailer->setEmail($email)` and the subject, body, assets, etc will be extracted and automatically set.
#### Attachments[](https://developer.mautic.org/#attachments)
Attachments can be attached to emails by using the `attachFile()` function. You can also attach Mautic assets (`\Mautic\AssetBundle\Entity\Asset`) via `attachAsset()`.
Refer to the class for more details on available functions.
### Model Factory[](https://developer.mautic.org/#model-factory)
```
<?php

$channel   = 'email';
$channelId = 1;

if ($modelFactory->hasModel($channel)) {
    $model = $modelFactory->getModel($channel);

    if ($entity = $model->getEntity($channelId)) {
        echo $entity->getName();
    }
}

```

`Mautic/CoreBundle/Factory/ModelFactory` can be used in services that a model dependency is unknown at the time the service is created. This is great for scenarios where the channel and channel ID are stored in a database and the executing code needs to obtain information on the channel entity (name, etc). 
It has two methods: `hasModel($modelNameKey)` and `getModel($modelNameKey)`. `hasModel` simple checks to see if a model exists. It uses the same format as using the controller helper method `getModel()`. For example, to obtain the `Mautic\EmailBundle\Model\EmailModel` class, you could use something like the code example.
## Database[](https://developer.mautic.org/#database)
```
<?php
// plugins/HelloWorldBundle/Entity/World.php

namespace MauticPlugin\HelloWorldBundle\Entity;

use Doctrine\ORM\Mapping as ORM;
use Mautic\CategoryBundle\Entity\Category;
use Mautic\CoreBundle\Doctrine\Mapping\ClassMetadataBuilder;
use Mautic\CoreBundle\Entity\CommonEntity;

/**
 * Class World
 */
class World extends CommonEntity
{
    /**
     * @var int
     */
    private $id;

    /**
     * @var string
     */
    private $name;

    /**
     * @var string
     */
    private $description;

    /**
     * @var Category
     */
    private $category;

    /**
     * @var int
     */
    private $visitCount;

    /**
     * @var int
     */
    private $population = 0;

    /**
     * @var bool
     */
    private $isInhabited = false;

    /**
     * @param ORM\ClassMetadata $metadata
     */
    public static function loadMetadata (ORM\ClassMetadata $metadata)
    {
        $builder = new ClassMetadataBuilder($metadata);

        $builder->setTable('worlds')
            ->setCustomRepositoryClass('MauticPlugin\HelloWorldBundle\Entity\WorldRepository');

        // Helper functions
        $builder->addIdColumns();
        $builder->addCategory();
        $builder->addNamedField('visitorCount', 'int', 'visitor_count');
        $builder->addField('population', 'int');

        // Native means to build a field
        $builder->createField('isInhabited', 'bool')
            ->columnName('is_inhabited')
            ->nullable(false);
    }

    /**
     * @return mixed
     */
    public function getId()
    {
        return $this->id;
    }

    /**
     * @return mixed
     */
    public function getName()
    {
        return $this->name;
    }

    /**
     * @param mixed $name
     *
     * @return World
     */
    public function setName($name)
    {
        $this->name = $name;

        return $this;
    }

    /**
     * @return mixed
     */
    public function getDescription()
    {
        return $this->description;
    }

    /**
     * @param mixed $description
     *
     * @return World
     */
    public function setDescription($description)
    {
        $this->description = $description;

        return $this;
    }

    /**
     * @return Category
     */
    public function getCategory()
    {
        return $this->category;
    }

    /**
     * @param mixed $category
     *
     * @return World
     */
    public function setCategory(Category $category)
    {
        $this->category = $category;

        return $this;
    }

    /**
     * @return mixed
     */
    public function getVisitCount()
    {
        return $this->visitCount;
    }

    /**
     * @param mixed $visitCount
     *
     * @return World
     */
    public function setVisitCount($visitCount)
    {
        $this->visitCount = $visitCount;

        return $this;
    }

    /**
     * Increase the visit count by one
     */
    public function upVisitCount()
    {
        $this->visitCount++;
    }

    /**
     * Get planet population
     */
    public function getPopulation()
    {
        return $this->population;
    }

    /**
     * @param int $population
     *
     * @return World
     */
    public function setPopulation($population)
    {
        $this->population = $population;

        return $this;
    }

    /**
     * @return boolean
     */
    public function isIsInhabited()
    {
        return $this->isInhabited;
    }

    /**
     * @param boolean $isInhabited
     *
     * @return World
     */
    public function setIsInhabited($isInhabited)
    {
        $this->isInhabited = $isInhabited;

        return $this;
    }
}

```
```
<?php
// plugins/HelloWorldBundle/Entity/WorldRepository.php

namespace MauticPlugin\HelloWorldBundle\Entity;

use Mautic\CoreBundle\Entity\CommonRepository;

/**
 * WorldRepository
 */
class WorldRepository extends CommonRepository
{

    public function getEntities($args = array())
    {
        $q = $this
            ->createQueryBuilder('w')
            ->leftJoin('a.category', 'c');

        $args['qb'] = $q;

        return parent::getEntities($args);
    }
}

```

Mautic uses [Doctrine](https://developer.mautic.org/#http://doctrine-orm.readthedocs.org/en/latest/), a database object relational mapper (ORM) and database abstraction layer (DBAL) library.
Most of Mautic use 
#### Usage[](https://developer.mautic.org/#usage)
Refer to 
#### Metadata/Schema[](https://developer.mautic.org/#metadata/schema)
Mautic uses Doctrine’s 
#### Installing/Updating Schema[](https://developer.mautic.org/#installing/updating-schema)
When an plugin is installed or updated, the bundle’s onInstall or onUpgrade functions are called. These functions can be used to manipulate the database schema. See [Install/Upgrade](https://developer.mautic.org/#install/upgrade).
#### Table Prefix[](https://developer.mautic.org/#table-prefix)
Mautic allows custom table prefixes. If using ORM, there is no need to include the prefix as Mautic will automatically handle it. However, if there is a need to use Doctrine’s DBAL layer directly, the contstant `MAUTIC_TABLE_PREFIX` can be used in conjuction with the table name.
#### Description of tables[](https://developer.mautic.org/#description-of-tables)
This is not yet a comprehensive list of all database tables. Contributions are 
  * `leads`: contacts
  * `lead_lists`: segments
  * `lead_lists_leads`: membership of contacts within segments
  * `lead_tags`: tags
  * `lead_tags_xrefs`: associations of tags with contacts
  * `migrations`: tracks which 


#### ORM Arrays and DateTime[](https://developer.mautic.org/#orm-arrays-and-datetime)
When using ORM, Mautic will automatically convert DateTime properties to UTC and to the system/user’s profile timezone on retrieval. However, if using DBAL, DateTime strings must be converted to UTC before persisting and to the local timezone on retrieval. See [Date/Time Helper](https://developer.mautic.org/#date/time-helper) to assist with conversions.
For arrays, ORM will auto serialize and unserialize. DBAL will need to manually handle this.
## Roles and Permissions[](https://developer.mautic.org/#roles-and-permissions)
Mautic provides a means of defining custom permissions for roles through Permission objects.
### How Permissions Work[](https://developer.mautic.org/#how-permissions-work)
Permissions are calculated based on bits assigned to an plugin’s level and permission. Bits are integers that increase by doubling the value. 1, 2, 4, 8, 16, 32, 64, 128, 512, 1024, and so forth. The bits should never be assigned numbers in between such as 3 or 5 as the permission will not be correctly calculated in such cases.
For example, let’s say HelloWorldBundle needs to manage access to user’s Worlds entity. A permission set for `plugin:helloWorld:worlds` might look like
Permission | Bit  
---|---  
view | 1  
edit | 2  
create | 4  
delete | 8  
full | 16  
`plugin:helloWorld:worlds:view` is a typically notation for requesting permission in Mautic. The notation tells Mautic to check for the `view` permission for the plugin, HelloWorldBundle, within the `worlds` level. Levels allow plugin’s to set permissions for multiple areas. 
Mautic will take the summation of the bits for the permissions given to a role and store it in the database. For example, if a role is given view and edit access, the stored bit is 3. If given view and create access, the stored bit is 5.
When a permission check is required, e.g. `plugin:helloWorld:worlds:create`, Mautic will check if bit of 4 is set in the role’s generated bit for `plugin:helloWorld:worlds`. If so, permission is granted.
The permission `full` is reserved to grant access to all previous permissions within the level and thus should always be the highest bit. 
### Using Permissions[](https://developer.mautic.org/#using-permissions)
```
<?php

$security = $this->get('mautic.security');

// Check if user is granted a single permission
if ($security->isGranted('plugin:helloWorld:worlds:view')) {
    // do something
}

// Check if user is granted multiple permissions (must be granted to all to be true)
if ($security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:create',
    )
)
) {
    //do something
}

// Check if user is granted to at least one permission
if ($security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:edit',
    ),
    'MATCH_ONE'
)
) {
    //do something
}

// Get an array of user permissions
$permissions = $security->isGranted(
    array(
        'plugin:helloWorld:worlds:view',
        'plugin:helloWorld:worlds:edit',
    ),
    'RETURN_ARRAY'
);

if ($permissions['plugin:helloWorld:worlds:view']) {
    // do something
}

// Check if user has access to view leads
if ($security->isGranted('lead:leads:viewother')) {
    // do something
}

```

To determine if a user has a specific permission, use Mautic’s security service which can be obtained from the [`mautic.security` service](https://developer.mautic.org/#security).
As suggested above, Mautic uses a special permission notation to refer to a specific permission. For core bundles, `bundleName:permissionLevel:permission` is used. For plugins, append `plugin:`, i.e. `plugin:bundleName:permissionLevel:permission`. `plugin:` tells Mautic to look for the permission class in the plugins/ directory and `MauticPlugin` namespace. 
The permission level and permissions are set by the core bundle or plugin. For example, Mautic’s core UserBundle has `users` and `roles` levels with `view`, `edit`, `create`, `delete` and `full` permissions for each. 
To check if a user has permission to edit roles, use `$mauticSecurity->isGranted('user:roles:edit');`
### Creating Custom Permissions[](https://developer.mautic.org/#creating-custom-permissions)
```
<?php
// plugins/HelloWorldBundle/Security/Permissions/HelloWorldPermissions.php

namespace MauticPlugin\HelloWorldBundle\Security\Permissions;

use Symfony\Component\Form\FormBuilderInterface;
use Mautic\CoreBundle\Security\Permissions\AbstractPermissions;

/**
 * Class HelloWorldPermissions
 */
class HelloWorldPermissions extends AbstractPermissions
{

    /**
     * Define available permissions
     *
     * @param $params
     */
    public function __construct($params)
    {
        parent::__construct($params);

        $this->permissions = array(

            // Custom level
            'worlds' => array(

                // Custom permissions
                'use_telescope' => 1,
                'send_probe'    => 2,
                'visit'         => 4,
                // Full will almost always be included and should be significantly higher than the
                // others in case new permissions need to be added later 
                'full'          => 1024
            )
        );

        // Add standard category permissions
        $this->addStandardPermissions('categories');
    }

    /**
     * Append the permission form fields to the Role form
     *
     * @param FormBuilderInterface $builder
     * @param array                $options
     * @param array                $data
     */
    public function buildForm(FormBuilderInterface &$builder, array $options, array $data)
    {
        // Add standard category form fields
        $this->addStandardFormFields('helloWorld', 'categories', $builder, $data);

        // Add custom 'worlds' level form fields
        $builder->add(

            // Form element name should be bundleName:permissionLevel
            'helloWorld:worlds',

            // Should always be permissionlist type
            'permissionlist',
            array(
                'choices' => array(
                    'use_telescope' => 'plugin.helloworld.permissions.use_telescope',
                    'send_probe'    => 'plugin.helloworld.permissions.send_probe',
                    'visit'         => 'plugin.helloworld.permissions.visit',
                    'full'          => 'mautic.core.permissions.full',
                ),
                'label'   => 'plugin.helloworld.permissions',

                // Set existing data
                'data'    => (!empty($data['worlds']) ? $data['worlds'] : array()),

                // Bundle name (used to build frontend form)
                'bundle'  => 'helloWorld',

                // Permission level (used to build frontend form)
                'level'   => 'worlds'
            )
        );
    }

    /**
     * Permission set identifier; should be bundleName
     * 
     * @return string
     */
    public function getName()
    {
        return 'helloWorld';
    }
}

```

An plugin can create it’s own set of permissions by creating a Permission class. See the code example for a skeleton outline of what the class will look like.
Each permission class should extend `Mautic\CoreBundle\Security\Permissions\AbstractPermissions`.
Then, for most permission classes, three methods are needed: `__construct()`, `buildForm()` and `getName()`.
**__construct()**
The construct method should do two things. It should call `parent::__construct($params)` or it should set `$this->params = $params;`. 
Then it should define `$this->permissions`. `$this->permissions` is an array of permission levels that are each arrays with permissions assigned to bits. For example, in the code block, a custom permission level of `worlds` is defined with the permissions of `use_telescope`, `send_probe`, `visit` and `full`. To check to see if a user has permission to the level `worlds` and permission `send_probe`, `$mauticSecurity->isGranted('plugin:helloWorld:worlds:send_probe')` would be used.
Mautic provides a few helper methods for common permission sets:
Method | Description  
---|---  
addStandardPermissions() | Set view, edit, create, delete, publish (with option to exclude), and full permissions.  
addExtendedPermissions() | Set creator level restrictions: viewown, viewother, editown, editother, create, deleteown, deleteother, publishown (with option to exclude), publishother (with option to exclude), and full  
addManagePermission | Set single manage permission  
**buildForm()**
The buildForm method will append the permission toggles to the Role’s form (see [Forms](https://developer.mautic.org/#forms) for details on form builders). Review the comments in the code sample.
There are complimentary helper methods for the common permission sets:
Method | Description  
---|---  
addStandardFormFields() | Appends the standard permission sets to the form  
addExtendedFormFields() | Appends the extended, aka creator restricted, permissions to the form  
addManageFormFields() | Appends the single manager element to the form  
**getName()** This method is absolutely required and should match both the bundleName and the name of the file. For example, if `HelloWorldBundle` is the bundle’s name, then this would be `helloWorld` with a filename of `HelloWorldPermissions.php`.
#### Permission Aliases[](https://developer.mautic.org/#permission-aliases)
```
<?php

    protected function getSynonym($name, $level)
    {
        if ($name == 'send_satellite') {
            // Set real permission name
            $name = 'send_probe';
        }

        return array($name, $level);
    }

```

To add a permission alias, use the `getSynonym()` method. Basically this method is called before each requested permission is determined giving opportunity to change the permission level or name as needed.
For example, `parent::getSynonym()` will recognize `editown` as `edit` if `editown` isn’t defined in the permission class’ `$this->permissions` property for the requested level.
#### Manipulating Permissions before Saving[](https://developer.mautic.org/#manipulating-permissions-before-saving)
```
 <?php

     /**
      * @param array $permissions     Plugin specific permissions
      * @param       $allPermissions  All role permissions
      * @param bool  $isSecondRound   Is round two after permissions have been updated by all permission classes 
      *
      * @return bool Return true if a second round is required; default false
      */
     public function analyzePermissions(array &$permissions, $allPermissions, $isSecondRound = false)
     {
         foreach ($permissions as $level => &$perms) {
             foreach ($perms as $perm) {
                 $include = array();
                 switch ($perm) {
                     case 'send_probe':
                         $include = array('use_telescope');
                         break;
                     case 'visit':
                         $include = array('use_telescope', 'send_probe');
                         break;
                 }
                 if (!empty($include)) {
                     foreach ($include as $r) {
                         list($ignore, $r) = $this->getSynonym($level, $r);
                         if ($this->isSupported($level, $r) && !in_array($r, $perms)) {
                             $perms[] = $r;
                         }
                     }
                 }
             }
         }

         // Return true if this method needs a second round after all the other bundles have adjusted permissions
         return false;
     }

```

Plugin’s can adjust permissions based on other selected permissions in order to prevent ‘user error.’ For example, if a user has permission to `edit`, then the user also needs permission to `view` whether that was selected in the Role form or not. The method `analyzePermissions()` can be be used for this which gives opportunity to the plugin to modify permissions based on other selections before persisting to the database. 
Sometimes, it may be necessary to re-adjust based on a permission that is outside the plugin’s control. In this case, `analyzePermissions()` can return true and it will be called again after all the permissions have been analyzed by the other bundles and plugins. In this case, the argument `$isSecondRound` will be true.
#### Advanced isGranted Logic[](https://developer.mautic.org/#advanced-isgranted-logic)
If it is necessary to perform some logic other than simply comparing bits, the permission class can override the parent’s `public function isGranted($userPermissions, $name, $level)` and do whatever is necessary for it’s own permission levels and individual permissions.
#### Advanced isSupported Logic[](https://developer.mautic.org/#advanced-issupported-logic)
The same can be applied for the method `isSupported()` which is used to determine if a bundle or plugin includes the requested permission and permission level. This can also be used to provide BC support.
## Custom Config Params[](https://developer.mautic.org/#custom-config-params)
Mautic’s configuration is stored in app/config/local.php. Plugin’s can leverage custom config parameters to use within it’s code.
Each configuration option desired should be defined and have a default set in the [plugin’s config file](https://developer.mautic.org/#parameters). This prevents Symfony from throwing errors if the parameter is used during cache compilation or if accessed directly from the container without checking if it exists first. Defining the parameters in the plugin’s config file will ensure that it always exists.
To add config options to the Configuration page, an [event subscriber](https://developer.mautic.org/#subscribers), a config [form type](https://developer.mautic.org/#forms), and a [specific view](https://developer.mautic.org/#views) are required.
To translate the plugin’s tab in the configuration form, be sure to include `mautic.config.tab.helloworld_config` in the plugin’s messages.ini file. Of course replace helloworld_config with whatever is used as the formAlias when registering the form in the event subscriber (explained below). 
### Config Event Subscriber[](https://developer.mautic.org/#config-event-subscriber)
```
<?php
// plugins/HelloWorldBundle/EventListener/ConfigSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\ConfigBundle\Event\ConfigEvent;
use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\ConfigBundle\ConfigEvents;
use Mautic\ConfigBundle\Event\ConfigBuilderEvent;

/**
 * Class ConfigSubscriber
 */
class ConfigSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            ConfigEvents::CONFIG_ON_GENERATE => array('onConfigGenerate', 0),
            ConfigEvents::CONFIG_PRE_SAVE    => array('onConfigSave', 0)
        );
    }

    /**
     * @param ConfigBuilderEvent $event
     */
    public function onConfigGenerate(ConfigBuilderEvent $event)
    {
        $event->addForm(
            array(
                'formAlias'  => 'helloworld_config',
                'formTheme'  => 'HelloWorldBundle:FormTheme\Config',
                'parameters' => $event->getParametersFromConfig('HelloWorldBundle')
            )
        );
    }

    /**
     * @param ConfigEvent $event
     */
    public function onConfigSave(ConfigEvent $event)
    {
        /** @var array $values */
        $values = $event->getConfig();

        // Manipulate the values
        if (!empty($values['helloworld_config']['custom_config_option'])) {
            $values['helloworld_config']['custom_config_option'] = htmlspecialchars($values['helloworld_config']['custom_config_option']);
        }

        // Set updated values 
        $event->setConfig($values);
    }
}

```

The event subscriber will listen to the `ConfigEvents::CONFIG_ON_GENERATE` and `ConfigEvents::CONFIG_PRE_SAVE` events. 
The `ConfigEvents::CONFIG_ON_GENERATE` is dispatched when the configuration form is built giving the plugin an opportunity to inject it’s own tab and config options.
To do this, the plugin must register it’s configuration details through the method assigned to the `ConfigEvents::CONFIG_ON_GENERATE` event. The \Mautic\ConfigBundle\Event\ConfigBuilderEvent object is passed into the method and expects the method to call `addForm()`. `addForm()` expects an array with the following elements:
Key | Description  
---|---  
**formAlias** | Alias of the form type class that sets the expected form elements  
**formTheme** | View to format the configuration form elements, i.e, `HelloWorldBundle:FormTheme\Config`  
**parameters** | Array of custom config elements. `$event->getParametersFromConfig('HelloWorldBundle')))` can be used to glean them from the plugin’s config file.  
The `ConfigEvents::CONFIG_PRE_SAVE` is called before the values from the form are rendered and saved to the local.php file. This gives the plugin an opportunity to clean up or manipulate the data before it is written.
Remember that the subscriber must be registered through the plugin’s config in the `services[events]` [section](https://developer.mautic.org/#services).
### Config Form[](https://developer.mautic.org/#config-form)
```
<?php
// plugins/HelloWorldBundle/Form/Type/ConfigType.php

namespace MauticPlugin\HelloWorldBundle\Form\Type;

use Symfony\Component\Form\AbstractType;
use Symfony\Component\Form\FormBuilderInterface;

/**
 * Class ConfigType
 */
class ConfigType extends AbstractType
{
    /**
     * @param FormBuilderInterface $builder
     * @param array                $options
     */
    public function buildForm(FormBuilderInterface $builder, array $options)
    {
        $builder->add(
            'custom_config_option',
            'text',
            array(
                'label' => 'plugin.helloworld.config.custom_config_option',
                'data'  => $options['data']['custom_config_option'],
                'attr'  => array(
                    'tooltip' => 'plugin.helloworld.config.custom_config_option_tooltip'
                )
            )
        );
    }

    /**
     * {@inheritdoc}
     */
    public function getName()
    {
        return 'helloworld_config';
    }
}

```

The form type is used to generate the form fields in the main configuration form. Refer to [Forms](https://developer.mautic.org/#forms) for more information on using form types.
Remember that the form type must be registered through the plugin’s config in the `services[forms]` [section](https://developer.mautic.org/#services).
### Config Template[](https://developer.mautic.org/#config-template)
```
<?php
// plugins/HelloWorldBundle/Views/FormTheme/Config/_config_helloworld_config_widget.html.php

?>

<div class="panel panel-primary">
    <div class="panel-heading">
        <h3 class="panel-title"><?php echo $view['translator']->trans('mautic.config.tab.helloworld_config'); ?></h3>
    </div>
    <div class="panel-body">
        <?php foreach ($form->children as $f): ?>
            <div class="row">
                <div class="col-md-6">
                    <?php echo $view['form']->row($f); ?>
                </div>
            </div>
        <?php endforeach; ?>
    </div>
</div>

```

Registering a formTheme as `HelloWorldBundle:FormTheme\Config` in the event listener told the ConfigBundle to look in the HelloWorldBundle’s Views/FormTheme/Config folder for templates. Specifically, it will look for a template named `_config_{formAlias}_widget.html.php` where `{formAlias}` is the same as `formAlias` set in the plugin’s `ConfigEvents::CONFIG_ON_GENERATE` event listener.
The template should be in a panel format to match the rest of the config UI.
## Integration Framework[](https://developer.mautic.org/#integration-framework)
The IntegrationsBundle is meant to be a drop in replacement for Mautic’s PluginBundle’s AbstractIntegration class. It provides cleaner interfaces for configuring, authenticating and syncing contacts/companies with 3rd party integrations.
An example HelloWorld plugin is available 
### Using the Integration Framework[](https://developer.mautic.org/#using-the-integration-framework)
_If the integration requires authentication with the 3rd party service_
  1. [Register the integration](https://developer.mautic.org/#registering-the-integration-for-authentication) as an integration that requires configuration options.
  2. Create a custom Symfony form type for the required credentials and return it as part of the [config interface](https://developer.mautic.org/#mauticpluginintegrationsbundleintegrationinterfacesconfigformauthinterface).
  3. Create a custom service that builds and configures the Guzzle client required to authenticate and communicate with the 3rd party service. Use an [existing supported factory or create a new one](https://developer.mautic.org/#authentication-providers).


_If the integration has extra configuration settings for features unique to it_
  1. [Register the integration](https://developer.mautic.org/#registering-the-integration-for-configuration) as an integration that requires configuration options.
  2. Create a custom Symfony form type for the features and return it as part of the [config interface](https://developer.mautic.org/#mauticpluginintegrationsbundleintegrationinterfacesconfigformfeaturesettingsinterface).


_If the integration syncs with Mautic’s contacts and/or companies_
  1. Read about [the sync engine](https://developer.mautic.org/#integration-sync-engine).


_If the integration includes a builder integration (email or landing page)_
  1. [Register the integration](https://developer.mautic.org/#registering-the-integration-for-builders) as an integration that provides a custom builder. 
  2. Configure what featured builders the integration supports (Mautic currently supports “email” and “page” builders).


### Basics[](https://developer.mautic.org/#basics)
Each integration provides its unique name as registered with Mautic, icon, and display name. When an integration is registered, the integration helper classes will manage the `\Mautic\PluginBundle\Entity\Integration` object through `\Mautic\IntegrationsBundle\Integration\Interfaces\IntegrationInterface`. It handles decryption and encryption of the integration’s API keys so the implementing code never has to.
##### Registering the Integration[](https://developer.mautic.org/#registering-the-integration)
All integrations whether it uses the config, auth or sync interfaces must have a class that registers itself with Mautic. The integration will be listed no the `/s/plugins` page.
In the plugin’s `Config/config.php`, register the integration using the tag `mautic.basic_integration`.
```
<?php
return [
    // ...
    'services' => [
        // ...
        'integrations' => [
            'helloworld.integration' => [
                'class' => \MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration::class,
                'tags'  => [
                    'mautic.basic_integration',
                ],
            ],
            // ...
        ],
        // ...
    ],
    // ...
];

```

The `HelloWorldIntegration` will need to implement `\Mautic\IntegrationsBundle\Integration\Interfaces\IntegrationInterface` and `\Mautic\IntegrationsBundle\Integration\Interfaces\BasicInterface` interfaces. Most use cases can simply extend the `\Mautic\IntegrationsBundle\Integration\BasicIntegration` abstract class then define the `getName()`, `getDisplayName()` and `getIcon()` methods.
```
<?php
namespace MauticPlugin\HelloWorldBundle\Integration;

use MauticPlugin\IntegrationsBundle\Integration\BasicIntegration;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\BasicInterface;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\IntegrationInterface;

class HelloWorldIntegration extends BasicIntegration
{
    const NAME = 'HelloWorld';

    public function getName(): string
    {
        return self::NAME;
    }

    public function getDisplayName(): string
    {
        return 'Hello World';
    }

    public function getIcon(): string
    {
        return 'plugins/HelloWorldBundle/Assets/img/helloworld.png';
    }
}

```

### Plugin Schema[](https://developer.mautic.org/#plugin-schema)
The integration framework provides a means for plugins to better manage their schema. Queries are in migration files that match the plugin’s versions number in it’s config. When the a plugin is installed or upgraded, it will loop over the migration files up to the latest version.
#### AbstractPluginBundle[](https://developer.mautic.org/#abstractpluginbundle)
The plugin’s root bundle class should extend `MauticPlugin\IntegrationsBundle\Bundle\AbstractPluginBundle`.
```
<?php

declare(strict_types=1);

namespace MauticPlugin\HelloWorldBundle;

use MauticPlugin\IntegrationsBundle\Bundle\AbstractPluginBundle;

class HelloWorldBundle extends AbstractPluginBundle
{
}

```

#### Plugin Migrations[](https://developer.mautic.org/#plugin-migrations)
Each migration file should be stored in the plugin’s `Migration` folder with a name that matches `Version_X_Y_Z.php` where `X_Y_Z` matches the semantic versioning of the plugin. Each file should contain the incremental schema changes for the plugin up to the latest version which should match the version in the plugin’s Config/config.php file.
There are two methods. `isApplicable` should return true/false if the migration should be ran. `up` should register the SQL to execute.
```
<?php

declare(strict_types=1);

namespace MauticPlugin\HelloWorldBundle\Migrations;

use Doctrine\DBAL\Schema\Schema;
use Doctrine\DBAL\Schema\SchemaException;
use Mautic\IntegrationsBundle\Migration\AbstractMigration;

class Version_1_0_1 extends AbstractMigration
{
    private $table = 'hello_world';

    protected function isApplicable(Schema $schema): bool
    {
        try {
            return !$schema->getTable($this->concatPrefix($this->table))->hasColumn('is_enabled');
        } catch (SchemaException $e) {
            return false;
        }
    }

    protected function up(): void
    {
        $this->addSql("ALTER TABLE `{$this->concatPrefix($this->table)}` ADD `is_enabled` tinyint(1) 0");

        $this->addSql("CREATE INDEX {$this->concatPrefix('is_enabled')} ON {$this->concatPrefix($this->table)}(is_enabled);");
    }
}

```

### Integration Authentication[](https://developer.mautic.org/#integration-authentication)
The integrations bundle provides factories and helpers to create Guzzle Client classes for common authentication protocols. 
#### Registering the Integration for Authentication[](https://developer.mautic.org/#registering-the-integration-for-authentication)
If the integration requires the user to authenticate through the web (OAuth2 three legged), the integration needs to tag a service with `mautic.auth_integration` to handle the authentication process (redirecting to login, request the access token, etc). This service will need to implement `\Mautic\IntegrationsBundle\Integration\Interfaces\AuthenticationInterface`.
```
<?php
return [
    // ...
    'services' => [
        // ...
        'integrations' => [
            // ...
            'helloworld.integration.authentication' => [
                'class' => \MauticPlugin\HelloWorldBundle\Integration\Support\AuthSupport::class,
                'tags'  => [
                    'mautic.auth_integration',
                ],
            ],
            // ...
        ],
        // ...
    ],
    // ...
];

```

The `AuthSupport` class must implement `\Mautic\IntegrationsBundle\Integration\Interfaces\AuthenticationInterface`.
```
<?php
namespace MauticPlugin\HelloWorldBundle\Integration\Support;

use MauticPlugin\HelloWorldBundle\Connection\Client;
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Integration\ConfigurationTrait;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\AuthenticationInterface;
use Symfony\Component\HttpFoundation\Request;

class AuthSupport implements AuthenticationInterface
{
    use ConfigurationTrait;

    /**
     * @var Client
     */
    private $client;

    public function __construct(Client $client)
    {
        $this->client = $client;
    }

    public function getName(): string
    {
        return HelloWorldIntegration::NAME;
    }

    public function getDisplayName(): string
    {
        return 'Hello World';
    }

    /**
     * Returns true if the integration has already been authorized with the 3rd party service.
     *
     * @return bool
     */
    public function isAuthenticated(): bool
    {
        $apiKeys = $this->getIntegrationConfiguration()->getApiKeys();

        return !empty($apiKeys['access_token']) && !empty($apiKeys['refresh_token']);
    }

    /**
     * Authenticate and obtain the access token
     *
     * @param Request $request
     *
     * @return string
     */
    public function authenticateIntegration(Request $request): string
    {
        $code = $request->query->get('code');

        $this->client->authenticate($code);

        return 'Success!';
    }
}

```

#### Authentication Providers[](https://developer.mautic.org/#authentication-providers)
The integrations bundle comes with a number of popular authentication protocols available to use as Guzzle clients. New ones can be created by implementing `\Mautic\IntegrationsBundle\Auth\Provider\AuthProviderInterface.`
**The examples below use anonymous classes. Of course, use OOP with services and factories to generate credential, configuration, and client classes.** The best way to get configuration values such as username, password, consumer key, consumer secret, etc is by using the `mautic.integrations.helper` (`\Mautic\IntegrationsBundle\Helper\IntegrationsHelper`) service in order to leverage the configuration stored in the `Integration` entity’s api keys. 
```
<?php
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

$username = $apiKeys['username'] ?? null;
$password = $apiKeys['password'] ?? null;

//...

```

##### Api Key[](https://developer.mautic.org/#api-key)
Use the `mautic.integrations.auth_provider.api_key` service (`\Mautic\IntegrationsBundle\Auth\Provider\ApiKey\HttpFactory`) to obtain a `GuzzleHttp\ClientInterface` that uses an API key for all requests. Out of the box, the factory supports a parameter API key or a header API key.
###### Parameter Based API Key[](https://developer.mautic.org/#parameter-based-api-key)
To use the parameter based API key, create a credentials class that implements `\Mautic\IntegrationsBundle\Auth\Provider\ApiKey\Credentials\ParameterCredentialsInterface`. 
```
<?php
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Provider\ApiKey\Credentials\ParameterCredentialsInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\ApiKey\HttpFactory;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$apiKeys = $integration->getIntegrationConfiguration()->getApiKeys();

$credentials = new class($apiKeys['api_key']) implements ParameterCredentialsInterface {
    private $key;

    public function __construct(string $key)
    {
        $this->key = $key;
    }

    public function getKeyName(): string
    {
        return 'apikey';
    }

    public function getApiKey(): string
    {
        return $this->key;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials);
$response = $client->get('https://api-url.com/fetch');

```

###### Header Based API Key[](https://developer.mautic.org/#header-based-api-key)
```
<?php
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Provider\ApiKey\Credentials\HeaderCredentialsInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\ApiKey\HttpFactory;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$apiKeys = $integration->getIntegrationConfiguration()->getApiKeys();

$credentials = new class($apiKeys['api_key']) implements HeaderCredentialsInterface {
    private $key;

    public function __construct(string $key)
    {
        $this->key = $key;
    }

    public function getKeyName(): string
    {
        return 'X-API-KEY';
    }

    public function getApiKey(): string
    {
        return $this->key;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials);
$response = $client->get('https://api-url.com/fetch');

```

##### Basic Auth[](https://developer.mautic.org/#basic-auth)
Use the `mautic.integrations.auth_provider.basic_auth` service (`\Mautic\IntegrationsBundle\Auth\Provider\BasicAuth\HttpFactory`) to obtain a `GuzzleHttp\ClientInterface` that uses basic auth for all requests.
```
<?php
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;
use MauticPlugin\IntegrationsBundle\Auth\Provider\BasicAuth\HttpFactory;
use MauticPlugin\IntegrationsBundle\Auth\Provider\BasicAuth\CredentialsInterface;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

$credentials = new class($apiKeys['username'], $apiKeys['password']) implements CredentialsInterface {
    private $username;
    private $password;

    public function __construct(string $username, string $password)
    {
        $this->username = $username;
        $this->password = $password;
    }

    public function getUsername(): string
    {
        return $this->username;
    }

    public function getPassword(): string
    {
        return $this->password;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials);
$response = $client->get('https://api-url.com/fetch');

```

##### OAuth1a[](https://developer.mautic.org/#oauth1a)
###### OAuth1a Three Legged[](https://developer.mautic.org/#oauth1a-three-legged)
This has not been implemented yet.
###### OAuth1a Two Legged[](https://developer.mautic.org/#oauth1a-two-legged)
OAuth1A two legged does not require a user to login as would three legged. 
```
<?php
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;
use MauticPlugin\IntegrationsBundle\Auth\Provider\OAuth1aTwoLegged\HttpFactory;
use MauticPlugin\IntegrationsBundle\Auth\Provider\OAuth1aTwoLegged\CredentialsInterface;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

$credentials = new class(
    'https://api-url.com/oauth/token', 
    $apiKeys['consumer_key'], 
    $apiKeys['consumer_secret']
) implements CredentialsInterface {
    private $authUrl;
    private $consumerKey;
    private $consumerSecret;

    public function __construct(string $authUrl, string $consumerKey, string $consumerSecret)
    {
        $this->authUrl        = $authUrl;
        $this->consumerKey    = $consumerKey;
        $this->consumerSecret = $consumerSecret;
    }

    public function getAuthUrl(): string
    {
        return $this->authUrl;
    }

    public function getConsumerKey(): ?string
    {
        return $this->consumerKey;
    }

    public function getConsumerSecret(): ?string
    {
        return $this->consumerSecret;
    }

    /**
     * Not used in this example. Tsk tsk for breaking the interface segregation principle
     *
     * @return string|null
     */
    public function getToken(): ?string
    {
        return null;
    }

    /**
     * Not used in this example. Tsk tsk for breaking the interface segregation principle
     *
     * @return string|null
     */
    public function getTokenSecret(): ?string
    {
        return null;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials);
$response = $client->get('https://api-url.com/fetch');

```

##### OAuth2[](https://developer.mautic.org/#oauth2)
Use the OAuth2 factory according to the grant type required. `\Mautic\IntegrationsBundle\Auth\Provider\Oauth2ThreeLegged\HttpFactory` supports `code` and `refresh_token` grant types. `\Mautic\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\HttpFactory` supports `client_credentials` and `password`.
The OAuth2 factories leverages [https://github.com/kamermans/guzzle-oauth2-subscriber] as a middleware.
###### Client Configuration[](https://developer.mautic.org/#client-configuration)
Both OAuth2 factories leverage `\Mautic\IntegrationsBundle\Auth\Provider\AuthConfigInterface` object to configure things such as configuring the signer (basic auth, post form data, custom), token factory, token persistence, and token signer (bearer auth, basic auth, query string, custom). Use the appropriate interfaces as required for the use case (see the interfaces in `plugins/IntegrationsBundle/Auth/Support/Oauth2/ConfigAccess`). 
See [https://github.com/kamermans/guzzle-oauth2-subscriber] for additional details on configuring the credentials and token signers or creating custom token persistence and factories. 
###### Integration Token Persistence[](https://developer.mautic.org/#integration-token-persistence)
For most use cases, a token persistence service to fetch and store the access tokens generated by using refresh tokens, etc will be required. The integrations bundle provides one that natively uses the `\Mautic\PluginBundle\Entity\Integration` entity’s api keys. Anything stored through the service is automatically encrypted. 
Use the `mautic.integrations.auth_provider.token_persistence_factory` service (`\Mautic\IntegrationsBundle\Auth\Support\Oauth2\Token\TokenPersistenceFactory`) to generate a `TokenFactoryInterface` to be returned by the `\Mautic\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenFactoryInterface` interface. 
```
<?php
use kamermans\OAuth2\Persistence\TokenPersistenceInterface;
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenPersistenceInterface;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\Token\TokenPersistenceFactory;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

/** @var $tokenPersistenceFactory TokenPersistenceFactory */
$tokenPersistence = $tokenPersistenceFactory->create($integration);

$config = new class($tokenPersistence) implements ConfigTokenPersistenceInterface {
    private $tokenPersistence;

    public function __construct(TokenPersistenceInterface$tokenPersistence)
    {
        $this->tokenPersistence = $tokenPersistence;
    }

    public function getTokenPersistence(): TokenPersistenceInterface
    {
        return $this->tokenPersistence;
    }
};

```

The token persistence service will automatically manage `access_token`, `refresh_token`, and `expires_at` from the authentication process which are stored in the `Integration` entity’s api keys array.
###### Token Factory[](https://developer.mautic.org/#token-factory)
In some cases, the 3rd party service may return additional values that are not traditionally part of the oauth2 spec and these values are required for further communication with the api service. In this case, the integration bundle’s `\Mautic\IntegrationsBundle\Auth\Support\Oauth2\Token\IntegrationTokenFactory` can be used to capture those extra values and store them in the `Integration` entity’s api keys array. 
The `IntegrationTokenFactory` can then be returned in a `\Mautic\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenFactoryInterface` when configuring the `Client`. 
```
<?php
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenFactoryInterface;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\Token\IntegrationTokenFactory;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\Token\TokenFactoryInterface;

$tokenFactory = new IntegrationTokenFactory(['something_extra']);

$config = new class($tokenFactory) implements ConfigTokenFactoryInterface {
    private $tokenFactory;

    public function __construct(TokenFactoryInterface $tokenFactory)
    {
        $this->tokenFactory = $tokenFactory;
    }

    public function getTokenFactory(): TokenFactoryInterface
    {
        return $this->tokenFactory;
    }
};

```

##### OAuth2 Two Legged[](https://developer.mautic.org/#oauth2-two-legged)
###### Password Grant[](https://developer.mautic.org/#password-grant)
Below is an example of the password grant for a service that uses a scope (optional interface). The use of the token persistence is assuming the access token is valid for a period of time (i.e. an hour). 
```
<?php
use kamermans\OAuth2\Persistence\TokenPersistenceInterface;
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\Credentials\PasswordCredentialsGrantInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\Credentials\ScopeInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\HttpFactory;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenPersistenceInterface;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

$credentials = new class(
    'https://api-url.com/oauth/token',
    'scope1,scope2',
    $apiKeys['client_id'],
    $apiKeys['client_secret'],
    $apiKeys['username'],
    $apiKeys['password']
) implements PasswordCredentialsGrantInterface, ScopeInterface {
    private $authorizeUrl;
    private $scope;
    private $clientId;
    private $clientSecret;
    private $username;
    private $password;

    public function getAuthorizationUrl(): string
    {
        return $this->authorizeUrl;
    }

    public function getClientId(): ?string
    {
        return $this->clientId;
    }

    public function getClientSecret(): ?string
    {
        return $this->clientSecret;
    }

    public function getPassword(): ?string
    {
        return $this->password;
    }

    public function getUsername(): ?string
    {
        return $this->username;
    }

    public function getScope(): ?string
    {
        return $this->scope;
    }
};

/** @var $tokenPersistenceFactory TokenPersistenceFactory */
$tokenPersistence = $tokenPersistenceFactory->create($integration);
$config           = new class($tokenPersistence) implements ConfigTokenPersistenceInterface {
    private $tokenPersistence;

    public function __construct(TokenPersistenceInterface$tokenPersistence)
    {
        $this->tokenPersistence = $tokenPersistence;
    }

    public function getTokenPersistence(): TokenPersistenceInterface
    {
        return $this->tokenPersistence;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials, $config);
$response = $client->get('https://api-url.com/fetch');

```

###### Client Credentials Grant[](https://developer.mautic.org/#client-credentials-grant)
Below is an example of the client credentials grant for a service that uses a scope (optional interface). The use of the token persistence is assuming the access token is valid for a period of time (i.e. an hour). 
```
<?php
use kamermans\OAuth2\Persistence\TokenPersistenceInterface;
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\Credentials\ClientCredentialsGrantInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\Credentials\ScopeInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\HttpFactory;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenPersistenceInterface;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

$credentials = new class(
    'https://api-url.com/oauth/token',
    'scope1,scope2',
    $apiKeys['client_id'],
    $apiKeys['client_secret']
) implements ClientCredentialsGrantInterface, ScopeInterface {
    private $authorizeUrl;
    private $scope;
    private $clientId;
    private $clientSecret;

    public function getAuthorizationUrl(): string
    {
        return $this->authorizeUrl;
    }

    public function getClientId(): ?string
    {
        return $this->clientId;
    }

    public function getClientSecret(): ?string
    {
        return $this->clientSecret;
    }

    public function getScope(): ?string
    {
        return $this->scope;
    }
};

/** @var $tokenPersistenceFactory TokenPersistenceFactory */
$tokenPersistence = $tokenPersistenceFactory->create($integration);
$config           = new class($tokenPersistence) implements ConfigTokenPersistenceInterface {
    private $tokenPersistence;

    public function __construct(TokenPersistenceInterface$tokenPersistence)
    {
        $this->tokenPersistence = $tokenPersistence;
    }

    public function getTokenPersistence(): TokenPersistenceInterface
    {
        return $this->tokenPersistence;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials, $config);
$response = $client->get('https://api-url.com/fetch');

```

##### OAuth2 Three Legged[](https://developer.mautic.org/#oauth2-three-legged)
Three legged OAuth2 with the code grant is the most complex to implement because it involves redirecting the user to the 3rd party service to authenticate then sent back to Mautic to initiate the access token process using a code returned in the request. 
The first step is to register the integration as a [`\Mautic\IntegrationsBundle\Integration\Interfaces\AuthenticationInterface`](https://developer.mautic.org/#registering-the-integration-for-authentication). The `authenticateIntegration()` method will be used to initiate the access token process using the `code` returned in the request after the user logs into the 3rd party service. The integrations bundle provides a route that can be used as the redirect or callback URIs through the named route `mautic_integration_public_callback` that requires a `integration` parameter. This redirect URI can be displayed in the UI by using `AuthIntegrationsHelper` then execute its `authenticateIntegration()`. 
```
<?php
namespace MauticPlugin\HelloWorldBundle\Integration\Support;

use GuzzleHttp\ClientInterface;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\AuthenticationInterface;
use Symfony\Component\HttpFoundation\Request;
use Symfony\Component\HttpFoundation\Response;

class AuthSupport implements AuthenticationInterface {
    /**
     * @var ClientInterface
     */
    private $client;

    // ...

    public function authenticateIntegration(Request $request): Response
    {
        $code = $request->query->get('code');

        $this->client->authenticate($code);

        return new Response('OK!');
    }
}

```

The trick here is that the `Client`’s `authenticate` method will configure a `ClientInterface` then make a call to any valid API url (_this is required_). By making a call, the middleware will initiate the access token process and store it in the `Integration` entity’s api keys through the [`TokenPersistenceFactory`](https://developer.mautic.org/#integration-token-persistence). The URL is recommended to be something simple like a version check or fetching info for the authenticated user.
Here is an example of a client, assuming that the user has already logged in and the code is in the request.
```
<?php
use kamermans\OAuth2\Persistence\TokenPersistenceInterface;
use MauticPlugin\HelloWorldBundle\Integration\HelloWorldIntegration;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2ThreeLegged\Credentials\CodeInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2ThreeLegged\Credentials\CredentialsInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2ThreeLegged\Credentials\RedirectUriInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\Credentials\ScopeInterface;
use MauticPlugin\IntegrationsBundle\Auth\Provider\Oauth2TwoLegged\HttpFactory;
use MauticPlugin\IntegrationsBundle\Auth\Support\Oauth2\ConfigAccess\ConfigTokenPersistenceInterface;
use MauticPlugin\IntegrationsBundle\Helper\IntegrationsHelper;
use Symfony\Component\HttpFoundation\Request;
use Symfony\Component\Routing\Router;

/** @var $integrationsHelper IntegrationsHelper */
$integration = $integrationsHelper->getIntegration(HelloWorldIntegration::NAME);

/** @var Router $router */
$redirectUrl = $router->generate('mautic_integration_public_callback', ['integration' => HelloWorldIntegration::NAME]);

$configuration = $integration->getIntegrationConfiguration();
$apiKeys       = $configuration->getApiKeys();

/** @var Request $request */
$code = $request->get('code');

$credentials = new class(
    'https://api-url.com/oauth/authorize',
    'https://api-url.com/oauth/token',
    $redirectUrl,
    'scope1,scope2',
    $apiKeys['client_id'],
    $apiKeys['client_secret'],
    $code
) implements CredentialsInterface, RedirectUriInterface, ScopeInterface, CodeInterface {
    private $authorizeUrl;
    private $tokenUrl;
    private $redirectUrl;
    private $scope;
    private $clientId;
    private $clientSecret;
    private $code;

    public function __construct(string $authorizeUrl, string $tokenUrl, string $redirectUrl, string $scope, string $clientId, string $clientSecret, ?string $code)
    {
        $this->authorizeUrl = $authorizeUrl;
        $this->tokenUrl     = $tokenUrl;
        $this->redirectUrl  = $redirectUrl;
        $this->scope        = $scope;
        $this->clientId     = $clientId;
        $this->clientSecret = $clientSecret;
        $this->code         = $code;
    }

    public function getAuthorizationUrl(): string
    {
        return $this->authorizeUrl;
    }

    public function getTokenUrl(): string
    {
        return $this->tokenUrl;
    }

    public function getRedirectUri(): string
    {
        return $this->redirectUrl;
    }

    public function getClientId(): ?string
    {
        return $this->clientId;
    }

    public function getClientSecret(): ?string
    {
        return $this->clientSecret;
    }

    public function getScope(): ?string
    {
        return $this->scope;
    }

    public function getCode(): ?string
    {
        return $this->code;
    }
};

/** @var $tokenPersistenceFactory TokenPersistenceFactory */
$tokenPersistence = $tokenPersistenceFactory->create($integration);
$config           = new class($tokenPersistence) implements ConfigTokenPersistenceInterface {
    private $tokenPersistence;

    public function __construct(TokenPersistenceInterface$tokenPersistence)
    {
        $this->tokenPersistence = $tokenPersistence;
    }

    public function getTokenPersistence(): TokenPersistenceInterface
    {
        return $this->tokenPersistence;
    }
};

/** @var $factory HttpFactory */
$client   = $factory->getClient($credentials, $config);
$response = $client->get('https://api-url.com/fetch');

```

### Integration Configuration[](https://developer.mautic.org/#integration-configuration)
The integration plugin provides interfaces to display and store configuration options that can be accessed through the `\Mautic\PluginBundle\Entity\Integration` object. 
#### Registering the Integration for Configuration[](https://developer.mautic.org/#registering-the-integration-for-configuration)
To tell the IntegrationsBundle that this integration has configuration options, tag the integration or support class with `mautic.config_integration` in the plugin’s `app/config.php`.
```
<?php
return [
    // ...
    'services' => [
        // ...
        'integrations' => [
            // ...
            'helloworld.integration.configuration' => [
                'class' => \MauticPlugin\HelloWorldBundle\Integration\Support\ConfigSupport::class,
                'tags'  => [
                    'mautic.config_integration',
                ],
            ],
            // ...
        ],
        // ...
    ],
    // ...
];

```

The `ConfigSupport` class must implement `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormInterface`.
```
<?php
namespace MauticPlugin\HelloBundle\Integration\Support;

use MauticPlugin\HelloWorldBundle\Form\Type\ConfigAuthType;
use MauticPlugin\IntegrationsBundle\Integration\DefaultConfigFormTrait;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\ConfigFormInterface;
use MauticPlugin\IntegrationsBundle\Integration\Interfaces\ConfigFormAuthInterface;

class ConfigSupport implements ConfigFormInterface, ConfigFormAuthInterface
{
    use DefaultConfigFormTrait;

    public function getDisplayName(): string
    {
        return 'Hello World';
    }

    /**
     * Return a custom Symfony form field type class that will be used on the Enabled/Auth tab.
     * This should include things like API credentials, URLs, etc. All values from this form fields
     * will be encrypted before being persisted.
     *
     * @link https://symfony.com/doc/2.8/form/create_custom_field_type.html#defining-the-field-type
     *
     * @return string
     */
    public function getAuthConfigFormName(): string
    {
        return ConfigAuthType::class;
    }
}

```

#### Interfaces[](https://developer.mautic.org/#interfaces)
There are multiple interfaces that can be used to add form fields options to the provided configuration tabs. 
##### Enabled/Auth Tab[](https://developer.mautic.org/#enabled/auth-tab)
These interfaces provide the configuration options for authenticating with the 3rd party service. Read more about how to use integrations bundle’s [auth providers here](https://developer.mautic.org/#integration-authentication).
######  `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormAuthInterface`[](https://developer.mautic.org/#\\mautic\\integrationsbundle\\integration\\interfaces\\configformauthinterface)
Used in the example above. This interface provides the Symfony form type class that defines the fields to be stored as the api keys. 
```
<?php
$apiKeys  = $integrationHelper->get(HelloWorldIntegration::NAME)->getIntegrationConfiguration()->getApiKeys();
$username = $apiKeys['username'];

```

#####  `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormCallbackInterface`[](https://developer.mautic.org/#\\mautic\\integrationsbundle\\integration\\interfaces\\configformcallbackinterface)
If the integration leverages an auth provider that requires a callback URL or something similar, this interface provides a means to return a translation string to display in the UI. For example, OAuth2 requires a redirect URI. If the admin has to configure the OAuth credentials in the 3rd party service and needs to know what URL to use in Mautic as the return URI, or callback URL, use the `getCallbackHelpMessageTranslationKey()` method. 
#### Feature Interfaces[](https://developer.mautic.org/#feature-interfaces)
#####  `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormFeatureSettingsInterface`[](https://developer.mautic.org/#\\mautic\\integrationsbundle\\integration\\interfaces\\configformfeaturesettingsinterface)
This interface provides the Symfony form type class that defines the fields to be displayed on the Features tab. These values are not encrypted.
```
<?php
$featureSettings  = $integrationHelper->get(HelloWorldIntegration::NAME)->getIntegrationConfiguration()->getFeatureSettings();
$doSomething      = $featureSettings['doSomething'];

```

####  `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormFeaturesInterface`[](https://developer.mautic.org/#\\mautic\\integrationsbundle\\integration\\interfaces\\configformfeaturesinterface)
Currently the integrations bundle provides default features. To use these features, implement this interface. `getSupportedFeatures` will return an array of supported features. For example, if the integration syncs with Mautic contacts, `getSupportedFeatures()` could `return [ConfigFormFeaturesInterface::FEATURE_SYNC];`.
##### Contact/Company Syncing Interfaces[](https://developer.mautic.org/#contact/company-syncing-interfaces)
The integrations bundle provides a sync framework for 3rd party services to sync with Mautic’s contacts and companies. The `\Mautic\IntegrationsBundle\Integration\Interfaces\ConfigFormSyncInterface` determines the configuration options for this sync feature. Refer to the method docblocks in the interface for more details. 
Read more about how to leverage the [sync framework](https://developer.mautic.org/#integration-sync-engine).
### Integration Sync Engine[](https://developer.mautic.org/#integration-sync-engine)
The sync engine supports bidirectional syncing between Mautic’s contact and companies with 3rd party objects. The engine generates a “sync report” from Mautic that it converts to a “sync order” for the integration to process. It then asks for a “sync report” from the integration which it converts to a “sync order” for Mautic to process. 
When building the report, Mautic or the integration will fetch the objects that have been modified or created within the specified timeframe. If the integration supports changes at the field level, it should tell the report on a per field basis when the field was last updated. Otherwise, it should tell the report when the object itself was last modified. These dates are used by the “sync judge” to determine which value should be used in a bi-directional sync.
The sync is initiated using the `mautic:integrations:sync` command. For example: `php app/console mautic:integrations:sync HelloWorld --start-datetime="2020-01-01 00:00:00" --end-datetime="2020-01-02 00:00:00"`. (Use `php bin/console` for Mautic 3). 
#### Registering the Integration for the Sync Engine[](https://developer.mautic.org/#registering-the-integration-for-the-sync-engine)
To tell the IntegrationsBundle that this integration provides a syncing feature, tag the integration or support class with `mautic.sync_integration` in the plugin’s `app/config.php`.
```
<?php
return [
    // ...
    'services' => [
        // ...
        'integrations' => [
            // ...
            'helloworld.integration.sync' => [
                'class' => \MauticPlugin\HelloWorldBundle\Integration\Support\SyncSupport::class,
                'tags'  => [
                    'mautic.sync_integration',
                ],
            ],
            // ...
        ],
        // ...
    ],
    // ...
];

```

The `SyncSupport` class must implement `\Mautic\IntegrationsBundle\Integration\Interfaces\SyncInterface`.
#### Syncing[](https://developer.mautic.org/#syncing)
##### The Mapping Manual[](https://developer.mautic.org/#the-mapping-manual)
The mapping manual tells the sync engine which integration should be synced with which Mautic object (contact or company), the integration fields that were mapped to Mautic fields, and the direction the data is supposed to flow. 
See 
##### The Sync Data Exchange[](https://developer.mautic.org/#the-sync-data-exchange)
This is where the sync takes place and is executed by the `mautic:integrations:sync` command. Mautic and the integration will build their respective reports of new or modified objects then execute the order from the other side. 
See 
###### Building Sync Report[](https://developer.mautic.org/#building-sync-report)
The sync report tells the sync engine what objects are new and/or modified between the two timestamps given by the engine (or up to the integration discretion if it is a first time sync). Objects should be processed in batches which can be done using the `RequestDAO::getSyncIteration()`. The sync engine will execute `SyncDataExchangeInterface::getSyncReport()` until a report comes back with no objects.
If the integration supports field level change tracking, it should tell the report so that the sync engine can merge the two data sets more accurately. 
See 
###### Executing the Sync Order[](https://developer.mautic.org/#executing-the-sync-order)
The sync order contains all the changes the sync engine has determined should be written to the integration. The integration should communicate back the ID of any objects created or adjust objects as needed such as if they were converted from one to another or deleted.
See 
### Integration Builders[](https://developer.mautic.org/#integration-builders)
Builders can register itself as a “builder” for email and/or landing pages. 
#### Registering the Integration as a Builder[](https://developer.mautic.org/#registering-the-integration-as-a-builder)
To tell the IntegrationsBundle that this integration has configuration options, tag the integration or support class with `mautic.config_integration` in the plugin’s `app/config.php`.
```
<?php
return [
    // ...
    'services' => [
        // ...
        'integrations' => [
            // ...
            'helloworld.integration.builder' => [
                'class' => \MauticPlugin\HelloWorldBundle\Integration\Support\BuilderSupport::class,
                'tags'  => [
                    'mautic.builder_integration',
                ],
            ],
            // ...
        ],
        // ...
    ],
    // ...
];

```

The `BuilderSupport` class must implement `\Mautic\IntegrationsBundle\Integration\Interfaces\BuilderInterface`.
The only method currently defined for the interface is `isSupported` which should return a boolean if it supports the given feature. Currently, Mautic supports `email` and `page` (landing pages). This will determine what themes should be displayed as an option for the given builder/feature. 
## Manipulating Contacts (Leads)[](https://developer.mautic.org/#manipulating-contacts-\(leads\))
```
<?php

/** @var \Mautic\LeadBundle\Model\LeadModel $leadModel */
$leadModel = $this->getModel('lead');

/** @var \Mautic\LeadBundle\Entity\Lead $currentLead */
$currentLead = $leadModel->getCurrentLead();

// To obtain the tracking ID as well, pass true
list($currentLead, $trackingId, $trackingIdIsNewlyGenerated) = $leadModel->getCurrentLead(true);

// To obtain just the tracking ID; pass true as an argument to force regeneration of the tracking ID and cookies
list($trackingId, $trackingIdIsNewlyGenerated) = $leadModel->getTrackingCookie();

// Set the currently tracked lead and generate tracking cookies
$lead = new Lead();
// ...
$leadModel->setCurrentLead($lead);

// Set a lead for system use purposes (i.e. events that use getCurrentLead()) but without generating tracking cookies
$leadModel->setSystemCurrentLead($lead);


```
In Mautic 1.4, Leads were renamed to Contacts. However, much of the code still refers to contacts as leads. 
Many plugins extending Mautic will be manipulating leads in one way or another. Here is a quick summary of how to obtain the current lead and/or manipulate the leads data.
#### Lead Tracking[](https://developer.mautic.org/#lead-tracking)
Leads are tracked by two cookies. The first cookie notes which ID the lead is tracked under Mautic as. The second is to track the lead’s activity for the current session (defaults to 30 minutes and resets during each lead interaction).
`mautic_session_id` holds the value of the lead’s current session ID. That value is then name of the cookie that holds the lead’s ID. 
Review the sample code on how to obtain the currently tracked lead.
As of Mautic 2.2.0, a cookie is also placed on any domain with mtc.js embedded (that’s allowed by Mautic’s CORS settings) as `mtc_id`. This will contain the ID of the currently tracked contact.
#### Creating New Leads[](https://developer.mautic.org/#creating-new-leads)
```
<?php
// Currently tracked lead based on cookies
$leadModel = $this->getModel('lead');
$lead = $leadModel->getCurrentLead();
$leadId = $lead->getId();

// OR generate a completely new lead with
$lead = new Lead();
$lead->setNewlyCreated(true);
$leadId = null;

// IP address of the request
$ipAdddress = $this->get('mautic.helper.ip_lookup')->getIpAddress();

// Updated/new fields
$leadFields = array(
    'firstname' => 'Bob',
    //...
);

// Optionally check for identifier fields to determine if the lead is unique
$uniqueLeadFields    = $this->getModel('lead.field')->getUniqueIdentiferFields();
$uniqueLeadFieldData = array();

// Check if unique identifier fields are included
$inList = array_intersect_key($leadFields, $uniqueLeadFields);
foreach ($inList as $k => $v) {
    if (empty($query[$k])) {
        unset($inList[$k]);
    }

    if (array_key_exists($k, $uniqueLeadFields)) {
        $uniqueLeadFieldData[$k] = $v;
    }
}

// If there are unique identifier fields, check for existing leads based on lead data
if (count($inList) && count($uniqueLeadFieldData)) {
    $existingLeads = $this->getDoctrine()->getManager()->getRepository('MauticLeadBundle:Lead')->getLeadsByUniqueFields(
        $uniqueLeadFieldData,
        $leadId // If a currently tracked lead, ignore this ID when searching for duplicates
    );
    if (!empty($existingLeads)) {
        // Existing found so merge the two leads
        $lead = $leadModel->mergeLeads($lead, $existingLeads[0]);
    }

    // Get the lead's currently associated IPs
    $leadIpAddresses = $lead->getIpAddresses();

    // If the IP is not already associated, do so (the addIpAddress will automatically handle ignoring
    // the IP if it is set to be ignored in the Configuration)
    if (!$leadIpAddresses->contains($ipAddress)) {
        $lead->addIpAddress($ipAddress);
    }
}

// Set the lead's data
$leadModel->setFieldValues($lead, $leadFields);

// Save the entity
$leadModel->saveEntity($lead);

// Set the updated lead
$leadModel->setCurrentLead($lead);

```

To create a new lead, use the `\Mautic\LeadBundle\Entity\Lead` entity. Review the code sample.
## Extending Mautic[](https://developer.mautic.org/#extending-mautic)
### Extending API[](https://developer.mautic.org/#extending-api)
```
<?php
// plugins/HelloWorldBundle/Config/config.php

return array(
    // ...

    'routes'   => array(

        // ...

        'api' => array(
            'plugin_helloworld_api' => array(
                'path'       => '/hello/worlds',
                'controller' => 'HelloWorldBundle:Api:worlds',
                'method'     => 'GET'
            )
        )
    ),

    // ...
);

```
```
<?php
// plugins/HelloWorldBundle/Controller/ApiController.php

namespace Mautic\LeadBundle\Controller\Api;

use FOS\RestBundle\Util\Codes;
use Mautic\ApiBundle\Controller\CommonApiController;

class ApiController extends CommonApiController
{

    /**
     * Get a list of worlds
     * 
     * @return \Symfony\Component\HttpFoundation\Response
     */
    public function getWorldsAction()
    {
        if (!$this->get('mautic.security')->isGranted('plugin:helloWorld:worlds:view')) {
            return $this->accessDenied();
        }

        $filter  = $this->request->query->get('filter', null);
        $limit   = $this->request->query->get('limit', null);
        $start   = $this->request->query->get('start', null);

        /** @var \MauticPlugin\HelloWorldBundle\Model\WorldsModel $model */
        $model   = $this->getModel('helloworld.worlds');

        $worlds  = $model->getWorlds($filter, $limit, $start);
        $worlds  = $this->view($worlds, Codes::HTTP_OK);

        return $this->handleView($worlds);
    }
}

```

To add custom API endpoints, simply define the routes under the API firewall in the [plugin’s config file](https://developer.mautic.org/#routes). This will place the route behind /api which will only be accessible if the requester has been authorized via OAuth.
The api controller(s), should extend `Mautic\ApiBundle\Controller\CommonApiController` to leverage the helper methods provided and to utilize the REST views.
### Extending Broadcasts[](https://developer.mautic.org/#extending-broadcasts)
Broadcasts are communications sent in bulk through a channel such as email (segment emails). Mautic 2.2.0 introduced a new event to execute the sending of these bulk communications via the `mautic:broadcasts:send` command.
```
<?php
// plugins\HelloWorldBundle\EventListener\BroadcastSubscriber

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\CoreEvents;
use Mautic\CoreBundle\Event\ChannelBroadcastEvent;
use MauticPlugin\HelloWorldPlugin\Model\WorldModel;

/**
 * Class BroadcastSubscriber
 */
class BroadcastSubscriber extends CommonSubscriber
{
    /**
     * @var WorldModel
     */
    protected $model;

    /**
     * BroadcastSubscriber constructor.
     *
     * @param WorldModel $model
     */
    public function __construct(WorldModel $model)
    {
        $this->model = $model;
    }

    /**
     * {@inheritdoc}
     */
    public static function getSubscribedEvents()
    {
        return [
            CoreEvents::CHANNEL_BROADCAST => ['onChannelBroadcast', 0]
        ];
    }


    public function onDataCleanup (ChannelBroadcastEvent $event)
    {
        if (!$event->checkContext('world')) {
            return;
        }

        // Get list of published broadcasts or broadcast if there is only a single ID
        $id         = $event->getId();
        $broadcasts = $this->model->getRepository()->getPublishedBroadcasts($id);
        $output     = $event->getOutput();

        while (($broadcast = $broadcasts->next()) !== false) {
            list($sentCount, $failedCount, $ignore) = $this->model->sendIntergalacticMessages($broadcast[0], null, 100, true, $output);
            $event->setResults($this->translator->trans('plugin.helloworld').': '.$broadcast[0]->getName(), $sentCount, $failedCount);
        }
    }
}

```

To hook into the `mautic:broadcasts:send` command, create a listening for the `\Mautic\CoreBundle\CoreEvents::CHANNEL_BROADCAST` event. The event listener should check for the appropriate context and ID. See example code.
### Extending Campaigns[](https://developer.mautic.org/#extending-campaigns)
```
<?php
// plugins/HelloWorldBundle/EventListener/CampaignSubscriber.php

namespace MauticPlugin\HelloWorldBundle\Events;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\CampaignBundle\Event as Events;
use Mautic\CampaignBundle\CampaignEvents;
use Mautic\CampaignBundle\Event\CampaignExecutionEvent;

/**
 * Class CampaignSubscriber
 */
class CampaignSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            CampaignEvents::CAMPAIGN_ON_BUILD => array('onCampaignBuild', 0),
            HelloWorldEvents::BLASTOFF        => array('executeCampaignAction', 0),
            HelloWorldEvents::VALIDATE_VISIT  => array('validateCampaignDecision', 0)
        );
    }

    /**
     * Add campaign decision and actions
     *
     * @param Events\CampaignBuilderEvent $event
     */
    public function onCampaignBuild(Events\CampaignBuilderEvent $event)
    {
        // Register custom action
        $event->addAction(
            'helloworld.send_offworld',
            array(
                'eventName'       => HelloWorldEvents::BLASTOFF,
                'label'           => 'plugin.helloworld.campaign.send_offworld',
                'description'     => 'plugin.helloworld.campaign.send_offworld_descr',
                // Set custom parameters to configure the decision
                'formType'        => 'helloworld_worlds',
                // Set a custom formTheme to customize the layout of elements in formType
                'formTheme'       => 'HelloWorldBundle:FormTheme\SubmitAction',
                // Set custom options to pass to the form type, if applicable
                'formTypeOptions' => array(
                    'world' => 'mars'
                )
            )
        );

        // Register custom decision (executes when a lead "makes a decision" i.e. executes some direct action
        $event->addDecision(
            'helloworld.visits_mars',
            array(
                'eventName'       => HelloWorldEvents::VALIDATE_VISIT,
                'label'           => 'plugin.helloworld.campaign.visits_mars',
                'description'     => 'plugin.helloworld.campaign.visits_mars_descr',
                // Same as registering an action
                'formType'        => false,
                'formTypeOptions' => array()
            )
        );
    }

    /**
     * Execute campaign action
     *
     * @param CampaignExecutionEvent $event
     */
    public function executeCampaignAction (CampaignExecutionEvent $event)
    {
        // Do blastoff

        $event->setResult(true);
    }

    /**
     * Validate campaign decision
     *
     * @param CampaignExecutionEvent $event
     */
    public function validateCampaignDecision (CampaignExecutionEvent $event)
    {
        $valid = ($event->getEventDetails()->getId() === $event->getConfig()['id']);
        $event->setResult($valid);
    }
}

```

Plugins can add their own campaign actions, decisions, or conditions by listening to the `\Mautic\CampaignBundle\CampaignEvents::CAMPAIGN_ON_BUILD` event. Read more about [listeners and subscribers](https://developer.mautic.org/#events). 
#### Campaign Actions[](https://developer.mautic.org/#campaign-actions)
To add an action, use the `$event->addAction($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string to use for the draggable’s label  
**eventName** | REQUIRED | string | The name of the event that should be dispatched to handle this action. The plugin will need to also create it’s own listener for the event.  
**description** | OPTIONAL | string | The language string to use for the draggable’s tooltip  
**formType** | OPTIONAL | string | The alias of a custom form type used to set config options for the decision  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
**associatedDecisions** | OPTIONAL | array | Array of keys registered as decisions that this action can attached to. Defaults to any decision.  
**anchorRestrictions** | OPTIONAL | array | Array of anchors (the places on an event in the builder this action can be attached to). The format is eventType.anchorName. Event types can be source, decision, action, or condition. anchorName includes top, bottom, inaction (yes/green), action (no/red) or leadsource. For example, by passing an array with `decision.inaction`, this action will not be attachable to the inaction/red anchor of a decision.  
**callback** | DEPRECATED | mixed | Deprecated as of 2.0 and support to be removed in 3.0; use eventName instead. Static callback function that will be called for the action and should contain the logic to execute the custom action  
The listener for dispatched event will have the `Mautic\CampaignBundle\Event\CampaignExecutionEvent` injected. To note that the action was successfully executed, use `$event->setResult($result)`. `$result` can be a boolean or an array. Setting false will cause the action to be retried. If an array, it will be stored in the campaign event log’s metadata array (useful for displaying information in the contact time-line).
Use `$event->setFailed()` to note that an event failed but should not be retried. Failed events do not appear in a contact’s time-line.
#### Campaign Decisions[](https://developer.mautic.org/#campaign-decisions)
```
 <?php
 // Trigger configured 'helloworld.visits_mars' decisions

 /** @var \Mautic\CampaignBundle\Model\CampaignModel $campaignModel */
 $campaignModel = $this->getModel('campaign.event');

 // Can be anything and passed into action callbacks as $eventDetails
 $customPassthrough = array();

 // Some optional unique identifier for this specific trigger that is used mainly for debug logging; for example, can be a concatenation of the decision name + lead ID
 $uniqueTriggerId   = 'something_something';

 $campaignModel->triggerEvent('helloworld.visits_mars', $customPassthroughToActions, $uniqueTriggerId);

```

Campaign decisions are registered exactly as a campaign action except it uses the `$event->addDecision($identifier, $parameters)` method. The only difference in the `$parameters` arguments is that the listener for the `eventName` is used to validate the decision rather than execute some action and it accepts a `associatedActions` array instead of `associatedDecisions`. For example, if the decision is configured to only apply to a specific ID chosen by the user (defined in the `formType`), the listener could compare the decision’s `$event->getEventDetails()->getId()` (see example) with the event’s`$event->getConfig()['id']`. If the decision should execute the actions associated with it, set `$event->setResult(true);`. Otherwise `$event->setResult(false);` and nothing will be executed or logged.
For custom decisions to work, there must be a trigger executed when the lead makes the decision. Thus, where ever is appropriate in the plugin’s code logic, add something similar to what’s in the example code block. 
The `triggerEvent()` method will pull all the triggered decisions (`helloworld.visits_mars` in the code example) for published campaigns the lead is in, dispatch the decisions event (if configured) for validation, then execute the associated actions if appropriate.
#### Campaign Conditions[](https://developer.mautic.org/#campaign-conditions)
Campaign conditions are registered with `addCondition()` and accepts the same arguments as `addDecision()`. The listener also receives an instance of `Mautic\CampaignBundle\Event\CampaignExecutionEvent`. To mark a condition as true or false, use `$event->setResult($result);`.
### Extending Categories[](https://developer.mautic.org/#extending-categories)
Mautic has a CategoryBundle that can be leveraged to incorporate categories into a plugin.
#### Adding categories[](https://developer.mautic.org/#adding-categories)
As of Mautic 1.2.1, register categories through the plugin’s config.php file by adding the following as a key to the returned config array:
```
    'categories' => array(
        'plugin:helloWorld' => 'mautic.helloworld.world.categories'
    ),

```

The category keys need be prefixed with `plugin:` as it is used in determining permissions to manage categories. The `helloWorld` should match the permission class name.
#### Configuring Categories for Menu[](https://developer.mautic.org/#configuring-categories-for-menu)
It is now recommended to not show the category in the main Menu.
To add a category menu item for the plugin, simply add the following to `menu` [config](https://developer.mautic.org/#menu) for whichever menu the item should appear (`main` or `admin`):
```
    'mautic.category.menu.index' => array(
        'bundle' => 'plugin:helloWorld'
    )

```

The `bundle` value needs be prefixed with `plugin:` as it is used in determining permissions to manage categories. The `helloWorld` should be the bundle name of the plugin.
#### Configuring Categories for Routes[](https://developer.mautic.org/#configuring-categories-for-routes)
There is no need to add custom routes for categories. However, when [generating a URL](https://developer.mautic.org/#router) to the plugin’s category list, use
```
$categoryUrl = $router->generateUrl('mautic_category_index', array('bundle' => 'plugin:helloWorld'));

```

#### Including Category in Forms[](https://developer.mautic.org/#including-category-in-forms)
To add a category select list to a [form](https://developer.mautic.org/#forms), use `category` as the form type and pass `bundle` as an option:
```
    //add category
    $builder->add('category', 'category', array(
        'bundle' => 'plugin:helloWorld'
    ));

```

#### Restricting Category Management[](https://developer.mautic.org/#restricting-category-management)
To restrict access to catgories, use the following in the plugin’s [Permission class](https://developer.mautic.org/#roles-and-permissions).
In `__construct()` add `$this->addStandardPermissions('categories');` then in `buildForm()`, add `$this->addStandardFormFields('helloWorld', 'categories', $builder, $data);`.
See a code example in [Roles and Permissions](https://developer.mautic.org/#roles-and-permissions).
The two standard helper methods will add the permissions of `view`, `edit`, `create`, `delete`, `publish`, and `full` for categories.
### Extending Contacts (Leads)[](https://developer.mautic.org/#extending-contacts-\(leads\))
#### Contact Timeline/History[](https://developer.mautic.org/#contact-timeline/history)
```
<?php
// plugins/HelloWorldBundle/EventListener/LeadSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\LeadBundle\Event\LeadTimelineEvent;
use Mautic\LeadBundle\LeadEvents;

/**
 * Class LeadSubscriber
 */
class LeadSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return [
            LeadEvents::TIMELINE_ON_GENERATE => ['onTimelineGenerate', 0]
        ];
    }

    /**
     * Compile events for the lead timeline
     *
     * @param LeadTimelineEvent $event
     */
    public function onTimelineGenerate(LeadTimelineEvent $event)
    {
        // Add this event to the list of available events which generates the event type filters
        $eventTypeKey  = 'visited.worlds';
        $eventTypeName = $this->translator->trans('mautic.hello.world.visited_worlds');
        $event->addEventType($eventTypeKey, $eventTypeName);

        // Determine if this event has been filtered out
        if (!$event->isApplicable($eventTypeKey)) {

            return;
        }

        /** @var \MauticPlugin\HelloWorldRepository\Entity\WorldRepository $repository */
        $repository = $this->em->getRepository('HelloWorldBundle:World');

        // $event->getQueryOptions() provide timeline filters, etc.
        // This method should use DBAL to obtain the events to be injected into the timeline based on pagination
        // but also should query for a total number of events and return an array of ['total' => $x, 'results' => []].
        // There is a TimelineTrait to assist with this. See repository example.
        $stats = $repository->getVisitedWorldStats($event->getLead()->getId(), $event->getQueryOptions());

        // If isEngagementCount(), this event should only inject $stats into addToCounter() to append to data to generate
        // the engagements graph. Not all events are engagements if they are just informational so it could be that this
        // line should only be used when `!$event->isEngagementCount()`. Using TimelineTrait will determine the appropriate
        // return value based on the data included in getQueryOptions() if used in the stats method above.
        $event->addToCounter($eventTypeKey, $stats);

        if (!$event->isEngagementCount()) {
            // Add the events to the event array
            foreach ($stats['results'] as $stat) {
                if ($stat['dateSent']) {
                    $event->addEvent(
                        [
                            // Event key type
                            'event'           => $eventTypeKey,
                            // Event name/label - can be a string or an array as below to convert to a link
                            'eventLabel'      => [
                                'label' => $stat['name'],
                                'href'  => $this->router->generate(
                                    'mautic_dynamicContent_action',
                                    ['objectId' => $stat['dynamic_content_id'], 'objectAction' => 'view']
                                )
                            ],
                            // Translated string displayed in the Event Type column
                            'eventType'       => $eventTypeName,
                            // \DateTime object for the timestamp column
                            'timestamp'       => $stat['dateSent'],
                            // Optional details passed through to the contentTemplate
                            'extra'           => [
                                'stat' => $stat,
                                'type' => 'sent'
                            ],
                            // Optional template to customize the details of the event in the timeline
                            'contentTemplate' => 'MauticDynamicContentBundle:SubscribedEvents\Timeline:index.html.php',
                            // Font Awesome class to display as the icon
                            'icon'            => 'fa-envelope'
                        ]
                    );
                }
            }
        }
    }
}

```

##### TIMELINE_ON_GENERATE Event Listener[](https://developer.mautic.org/#timeline_on_generate-event-listener)
To inject events into a contact’s timeline, create an event listener that listens to the `LeadEvents::TIMELINE_ON_GENERATE` event. Using this event, the plugin can inject unique items into the timeline and also into the engagements graph on each page. 
The event listener will receive a `Mautic\LeadBundle\Event\LeadTimelineEvent` object. The commonly used methods are defined below:
Method | Description  
---|---  
**isApplicable** | Determines if this event is applicable and not filtered out.  
**addEventType()** | Required - Add this event to the list of available events.  
**getLead()** | Get the Lead entity the event is dispatched for  
**getQueryOptions()** | Used to get pagination, filters, etc needed to generate an appropriate query  
**addToCounter()** | Used to add total number of events (across all pages) to the counters. This also generates the numbers for the engagements graph.  
**addEvent()** | Required - Injects an event into the timeline. Accepts an array with the keys defined as below.  
**addEvent($event) Key Definitions** Key|Required|Type|Description —|——–|—-|———– **event** |REQUIRED|string|The key for this event. Eg. world.visited **eventType** |REQUIRED|string|The translated string representing this event type. Eg. Worlds visited **timestamp** |REQUIRED|\DateTime|DateTime object when this event took place **eventLabel** |OPTIONAL|string/array|The translated string to display in the event name. Examples include names of items, page titles, etc. This can also be an array of [‘label’ => “, 'href’ => ”] to have the entry converted to a link. This will default to eventType if not defined. **extra** |OPTIONAL|array|Whatever should be passed through to the content template to generate the details view for this event **contentTemplate** |OPTIONAL|string|Template that should be used to generate the details view for this event. Eg. HelloBundle:SubscribedEvents\Timeline:index.html.php **icon** |OPTIONAL|Font Awesome class
##### TIMELINE_ON_GENERATE Repository Method[](https://developer.mautic.org/#timeline_on_generate-repository-method)
```
<?php
//plugins/HelloWorldBundle/Entity/WorldRepository.php

namespace Mautic\LeadBundle\Entity;

use Mautic\CoreBundle\Entity\CommonRepository;
use Mautic\LeadBundle\Entity\TimelineTrait;

/**
 * Class WorldRepository
 */
class WorldRepository extends CommonRepository
{
    use TimelineTrait;

    /**
     * @param       $leadId
     * @param array $options
     */
    public function getTimelineStats($leadId, array $options = [])
    {
        $query = $this->getEntityManager()->getConnection()->createQueryBuilder();

        $query->select('w.id, w.name, w.visited_count, w.date_visited, w.visit_details')
            ->from(MAUTIC_TABLE_PREFIX.'world_visits', 'w')
            ->where($query->expr()->eq('w.lead_id', (int) $leadId));

        if (isset($options['search']) && $options['search']) {
            $query->andWhere(
                $query->expr()->like('w.name', $query->expr()->literal('%' . $options['search'] . '%'))
            );
        }

        return $this->getTimelineResults($query, $options, 'w.name', 'w.date_visited', ['visit_details'], ['date_visited']);
    }
}

```

To assist with the generation of events, the `Mautic\LeadBundle\Entity\TimelineTrait` has been created.
To leverage this, accept the array from `$event->getQueryOptions()` in the repository method. Create a DBAL QueryBuilder object (`$this->getEntityManager()->getConnection()->createQueryBuilder()`) and define the basics of the array, including filtering by lead id and search filter. Then pass the QueryBuilder object to the `getTimelineResults()` method along with the following arguments:
Key | Required | Type | Description  
---|---|---|---  
**$query** | REQUIRED | QueryBuilder | DBAL QueryBuilder object defining basics of the query.  
**$options** | REQUIRED | array | Array generated and passed into method by $event->getQueryOptions() in the event listener above  
**$eventNameColumn** | REQUIRED | string | Name of the column (with table prefix) that should be used when sorting by event name  
**$timestampColumn** | REQUIRED | string | Name of the column (with table prefix) that should be used when sorting by timestamp  
**$serializedColumns** | OPTIONAL | array | When using DBAL, arrays are not auto unserialized by Doctrine. Define the columns here (as returned by the query results) to auto unserialize.  
**$dateTimeColumns** | OPTIONAL | array | When using DBAL, datetime columns are not auto converted to \DateTime objects by Doctrine. Define the columns here (as returned by the query results) to auto do so.  
**$resultsParserCallback** | OPTIONAL | callback | Callback to custom parse a result. This is optional and mainly used to handle a column result when all results are already being looped over for $serializedColumns and $dateTimeColumns.  
### Extending Emails[](https://developer.mautic.org/#extending-emails)
```
<?php
// plugins/HelloWorldBundle/EventListener/EmailSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\EmailBundle\EmailEvents;
use Mautic\EmailBundle\Event\EmailBuilderEvent;
use Mautic\EmailBundle\Event\EmailSendEvent;

/**
 * Class EmailSubscriber
 */
class EmailSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            EmailEvents::EMAIL_ON_BUILD   => array('onEmailBuild', 0),
            EmailEvents::EMAIL_ON_SEND    => array('onEmailGenerate', 0),
            EmailEvents::EMAIL_ON_DISPLAY => array('onEmailGenerate', 0)
        );
    }

    /**
     * Register the tokens and a custom A/B test winner
     *
     * @param EmailBuilderEvent $event
     */
    public function onEmailBuild(EmailBuilderEvent $event)
    {
        // Add email tokens
        $content = $this->templating->render('HelloWorldBundle:SubscribedEvents\EmailToken:token.html.php');
        $event->addTokenSection('helloworld.token', 'plugin.helloworld.header', $content);

        // Add AB Test Winner Criteria
        $event->addAbTestWinnerCriteria(
            'helloworld.planetvisits',
            array(
                // Label to group by
                'group'    => 'plugin.helloworld.header',

                // Label for this specific a/b test winning criteria
                'label'    => 'plugin.helloworld.emailtokens.',

                // Static callback function that will be used to determine the winner
                'callback' => '\MauticPlugin\HelloWorldBundle\Helper\AbTestHelper::determinePlanetVisitWinner'
            )
        );
    }

    /**
     * Search and replace tokens with content
     *
     * @param EmailSendEvent $event
     */
    public function onEmailGenerate(EmailSendEvent $event)
    {
        // Get content
        $content = $event->getContent();

        // Search and replace tokens
        $content = str_replace('{hello}', 'world!', $content);

        // Set updated content
        $event->setContent($content);
    }
}

```

There are two way to extend emails: email tokens used to insert dynamic content into an email and a/b test winning criteria . Both leverage the `\Mautic\EmailBundle\EmailEvents::EMAIL_ON_BUILD` event. Read more about [listeners and subscribers](https://developer.mautic.org/#events).
#### Email Tokens[](https://developer.mautic.org/#email-tokens)
Email tokens are placeholders that are inserted into an email that can be replaced by dynamic content when the email is sent or viewed in the browser.
`$event->addTokenSection($uniqueId, $headerTranslationKey, $htmlContent)` is used to generate the section for drag and drop tokens in the email builder. 
`$uniqueId` must be unique. 
`$headerTranslationKey` is the translation key that will be used to create the section’s header.
`$htmlContent` is the HTML that will be inserted into the builder’s token list for this token’s section. `$this->templating->render()` can be used to render a specific view’s content (using [view notation](https://developer.mautic.org/#views). There is free reign as to what the HTML will look like but the important part is that the elements representing the tokens must have the attribute `data-token="{token_text}"` in order for the builder to recognize them.
For example, `<a href="#" data-token="{hello}" class="btn btn-default btn-block">Translated Token Text</a>`
##### Custom Token Handling[](https://developer.mautic.org/#custom-token-handling)
To convert the token into a link while requesting what the links text should be, use the attributes `data-token='<a href="%url={hello}%">%text%</a>' data-drop="showBuilderLinkModal"` (replacing `hello` with the plugin’s custom token).
To request simple feedback from the user and inject it into the token, use the attributes `data-token='{hello=%world%}' data-drop="showBuilderFeedbackModal"`. A modal will appear with a simple input box. Whatever the user inputs will replace `%world%`.
If you need more control or more customization, create and define a custom JS function within the Mautic namespace (i.e. `Mautic.customFunction` and use the attribute `data-drop="customFunction"`. When a user drops the token, `Mautic.customFunction()` passing the arguments event (jQuery Event), ui (jQuery UI object with draggable, helper, etc), editorId (ID of the inline CkEditor).
```
Mautic.customFunction = function (event, ui, editorId) {
    var token  = mQuery(ui.draggable).data('token');
    
    // Do something fancy then insert token
        
    Mautic.insertBuilderEditorToken(editorId, token);
};

```

#### Email A/B Test Winner Criteria[](https://developer.mautic.org/#email-a/b-test-winner-criteria)
To add a custom an a/b test winner criteria, i.e. a test to compare specific aspects of an email to determine what made it more successful over it’s variants, use `$event->addAbTestWinnerCriteria($uniqueId, $parameters)`.
`$parameters` can have the following elements:
Key | Required | Type | Description  
---|---|---|---  
**group** | REQUIRED | string | Translation string to group criteria by in the dropdown select list  
**label** | OPTIONAL | string | Label for this option in the drop down list  
**callback** | REQUIRED | mixed | Static callback function that will be called to determine the winner when the email detail page is viewed  
**formType** | OPTIONAL | string | The alias of a custom form type used to set config options for the decision  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
The callback can accept the following variables (determined via ReflectionMethod::invokeArgs()):
Variable | Type | Description  
---|---|---  
**$properties** | array | Array of elements saved from the configured formType; keyed by email ID in the case of multiple variants  
**$factory** | Mautic\CoreBundle\Factory\MauticFactory | [Mautic’s factory service](https://developer.mautic.org/#factory-service)  
**$email** | Mautic\EmailBundle\Entity\Email | Email entity for the displayed email  
**$parent** | Mautic\EmailBundle\Entity\Email | Email entity for the parent of the email entity  
**$children** | Doctrine\Common\Collections\ArrayCollection | All variants of the parent email  
The callback function should return an array keyed with the following elements:
Key | Type | Description  
---|---|---  
**winners** | array | Array of IDs of the winners (array in case of a tie)  
**support** | mixed | Passed to the view defined by supportTemplate below in order to render visual support for the winners (such as a graph, etc)  
**supportTemplate** | string | View notation to render content for the A/B stats modal. For example, `HelloWorldBundle:SubscribedEvents\AbTest:graph.html.php`  
```
return array(
   'winners'         => $winners,
   'support'         => $support,
   'supportTemplate' => 'HelloWorldBundle:SubscribedEvents\AbTest:graph.html.php'
);

```

#### Monitored Inbox Integration[](https://developer.mautic.org/#monitored-inbox-integration)
```
<?php
// plugins/HelloWorldBundle/EventListener/MonitoredInboxSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\EmailBundle\EmailEvents;
use Mautic\EmailBundle\Event\MonitoredEmailEvent;
use Mautic\EmailBundle\Event\ParseEmailEvent;
use Mautic\EmailBundle\MonitoredEmail\Mailbox;

/**
 * Class MonitoredInboxSubscriber
 */
class MonitoredInboxSubscriber extends CommonSubscriber
{
    private $bundle = 'HelloWorldBundle';
    private $monitor =  'deep_space_emails';

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return [
            EmailEvents::MONITORED_EMAIL_CONFIG => ['onConfig', 0],
            EmailEvents::EMAIL_PRE_FETCH        => ['onPreFetch', 0],
            EmailEvents::EMAIL_PARSE            => ['onParse', 0],
        ];
    }

    /**
     * Inject the IMAP folder settings into the Configuration
     *
     * @param MonitoredEmailEvent $event
     */
    public function onConfig(MonitoredEmailEvent $event)
    {
        /**
         * The first argument is something unique to recognize this plugin.
         * The second argument should be something unique to identify this monitored inbox.
         * The third argument is the label for this monitored inbox.
         */
         $event->addFolder($this->bundle, $this->monitor, 'mautic.world.monitored_deep_space_emails');
    }

    /**
     * Inject search criteria for which messages to fetch from the configured folder.
     *
     * @param ParseEmailEvent $event
     */
    public function onPreFetch(ParseEmailEvent $event)
    {
        $event->setCriteriaRequest($this->bundle, $this->monitor, Mailbox::CRITERIA_UNSEEN. " " . Mailbox::CRITERIA_FROM ." aliens@andromeda");
    }

    /**
     * Parse the messages
     *
     * @param ParseEmailEvent $event
     */
    public function onParse(ParseEmailEvent $event)
    {
        if ($event->isApplicable($this->bundle, $this->monitor)) {
            $messages = $event->getMessages();

            /** @var \Mautic\EmailBundle\MonitoredEmail\Message $message */
            foreach ($messages as $message) {
                // Do something
            }
        }
    }
}

```

Plugins have access to hook into the `mautic:email:fetch` command to fetch email from a specific inbox/folder and process the content of the message. Starting in 2.1.1, the plugin also has access to inject specific search criteria for the messages to be processed.
To do this, the plugin needs to add an event listener for three events:
  1. `EmailEvents::MONITORED_EMAIL_CONFIG` This event is dispatched to inject the fields into Mautic’s Configuration to configure the IMAP inbox and folder that should be monitored.
  2. `EmailEvents::EMAIL_PRE_FETCH` This event is dispatched during the execution of the `mautic:email:fetch` command. It’s used to inject search criteria for the messages desired.
  3. `EmailEvents::EMAIL_PARSE` This event parses the messages fetched by the command.


### Extending Forms[](https://developer.mautic.org/#extending-forms)
```
<?php
// plugins/HelloWorldBundle/EventListener/FormSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use MauticPlugin\HelloWorldBundle\HelloWorldEvents;
use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\FormBundle\Event as Events;
use Mautic\FormBundle\FormEvents;

/**
 * Class FormSubscriber
 */
class FormSubscriber extends CommonSubscriber
{

    /**
     * {@inheritdoc}
     */
    static public function getSubscribedEvents()
    {
        return array(
            FormEvents::FORM_ON_BUILD     => array('onFormBuilder', 0),
            FormEvents::ON_FORM_VALIDATE  => ['onFormValidate', 0],

        );
    }

    /**
     * Add a simple email form
     *
     * @param FormBuilderEvent $event
     */
    public function onFormBuilder(Events\FormBuilderEvent $event)
    {
        // Register a form submit actions
        $event->addSubmitAction(
            'helloworld.sendemail',
            [
                // Label to group by in the dropdown
                'group'       => 'plugin.helloworld.header',

                // Label to list by in the dropdown
                'label'       => 'plugin.helloworld.formaction.send_email',
                'description' => 'plugin.helloworld.formaction.send_email_descr',

                // Form service for custom config options
                'formType'    => 'helloworld_worlds',
                'formTheme'   => 'HelloWorldBundle:FormTheme\SubmitAction',

                // Callback method to be executed after the submission 
                'eventName'    => HelloWorldEvents::FORM_SUBMIT_ACTION
            ]
        );

        // Register a custom validation service
        $event->addValidator(
            'helloworld.customfield',
            [
                'eventName' => HelloWorldEvents::FORM_VALIDATION,
                'fieldType' => 'helloworld.customfield', // Optional - otherwise all fields will be sent through this listener for validation
                'formType' => \MauticPlugin\HelloWorldBundle\Form\Type\HelloWorldType::class // Optional - otherwise just default required option should be generated to validation tab 

            ]
        );

        // Register a custom form field
        $event->addFormField(
            'helloworld.customfield',
            [
                // Field label
                'label'    => 'plugin.helloworld.formfield.customfield',

                // Form service for the field's configuration
                'formType' => 'helloworld_worlds',

                // Template to use to render the formType
                'template' => 'HelloWorldBundle:SubscribedEvents\FormField:customfield.html.php'
            ]
        );
    }


    /**
     * @param Events\ValidationEvent $event
     */
    public function onFormValidate(Events\ValidationEvent $event)
    {
        $field = $event->getField();
        if ($field->getType() === 'helloworld.customfield' && !empty($field->getValidation()['c_enable'])) {
            if (empty($field->getValidation()['helloworld_customfield_enable_validationmsg'])) {
                $event->failedValidation($field->getValidation()['helloworld_customfield_enable_validationmsg']);
            } else {
                $event->failedValidation('plugin.helloworld.formfield.customfield.invalid');
            }
        }
    }
}

```

Forms can be extended by listening to the `\Mautic\FormBundle\FormEvents::FORM_ON_BUILD` event. Read more about [listeners and subscribers](https://developer.mautic.org/#events). 
#### Form Fields[](https://developer.mautic.org/#form-fields)
To add a custom form field, use the `$event->addFormField($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string for the option in the dropdown  
**formType** | REQUIRED | string | The alias of a custom form type used to set config options  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
**template** | REQUIRED | string | View template used to render the formType  
**valueFilter** | OPTIONAL | mixed | Filter to use to clean the submitted value as supported by InputHelper or a callback function that accepts the arguments `\Mautic\FormBundle\Entity\Field $field` and `$value`.  
**valueConstraints** | OPTIONAL | mixed | Callback function to use to validate the value; the function should accept the arguments `\Mautic\FormBundle\Entity\Field $field` and `$filteredValue`.  
**builderOptions** | OPTIONAL | array | Array of boolean options for the form builder:   
addHelpMessage = true/false  
addShowLabel = true/false  
addDefaultValue = true/false  
addLabelAttributes = true/false  
addInputAttributes = true/false  
addIsRequired = true/false  
#### Form Submit Actions[](https://developer.mautic.org/#form-submit-actions)
To add an action, use the `$event->addSubmitAction($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string for the option in the dropdown  
**description** | OPTIONAL | string | The language string to use for the option’s tooltip  
**eventName** | REQUIRED | string | This is the custom event name that will be dispatched to handle this action (`callback` has been deprecated)  
**formType** | OPTIONAL | string | The alias of a custom form type used to set config options  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
**template** | OPTIONAL | string | View template used to render the formType  
**validator** | DEPRECATED | mixed | Static callback function called to validate the form submission. Deprecated - Register a validator using the `$event->addValidator()`.  
**callback** | DEPRECATED | mixed | Static callback function called after a submission (submit action logic goes here). Deprecated - use eventName instead.  
The subscriber registered to listen to the `eventName` will be passed an instance of `Mautic\FormBundle\Events\SubmissionEvent` with the details about the post. 
Sometimes, it is necessary to handle something after all the other submit actions have done their thing - like redirect to another page. This is done by registering a post submit callback through the subscriber that processes the action. You can either inject the `Symfony\Component\HttpFoundation\Response` at that time with `$event->setPostSubmitCallbackResponse($response);` or register another custom event to be dispatched after all submit actions have been processed using `$event->setPostSubmitCallback($key, ['eventName' => HelloWorld::ANOTHER_CUSTOM_EVENT]);`.
#### Form Validations[](https://developer.mautic.org/#form-validations)
To add a custom validation, use the `$event->addValidator($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**eventName** | REQUIRED | string | The name of the custom event that will be dispatched to validate the form or specific field  
**fieldType** | optional | string | The key to a custom form type (for example something registered by `addFormField()`) to limit this listener to. Otherwise every field will be sent to listener.  
**formType** | optional | string | Form type class to generate additional fields to validator tab  
The listener for the form event will receive a `Mautic\FormBundle\Event\ValidationEvent` object. Obtain the field with `$event->getField();` do the logic then to fail a validation, execute `$event->failedValidation('I said so.');`.
### Extending Integrations[](https://developer.mautic.org/#extending-integrations)
```
<?php
<?php
// plugins\HelloWorldBundle\Integration\MarsIntegration

namespace MauticPlugin\HelloWorldBundle\Integration;

use Mautic\PluginBundle\Entity\Integration;
use Mautic\PluginBundle\Integration\AbstractIntegration;
use Mautic\PluginBundle\Helper\oAuthHelper;

/**
 * Class MarsIntegration
 */
class MarsIntegration extends AbstractIntegration
{
    /**
     * Returns the name of the social integration that must match the name of the file
     * For example, IcontactIntegration would need Icontact here
     *
     * @return string
     */
    public function getName()
    {
        return 'Mars';
    }

    /**
     * Display name for the integration which defaults to getName() unless defined here
     */
    public function getDisplayName()
    {
        return 'Red Mars'
    }

    /**
     * Get the type of authentication required for this API.  Values can be none, key, oauth2 or callback
     * (will call $this->authenticationTypeCallback)
     *
     * @return string
     */
    public function getAuthenticationType()
    {
        return 'oauth2';
    }

    /**
     * OAuth2 authentication URL
     */
    public function getAuthenticationUrl()
    {
        return 'https://somesite.com/oauth/authorize';
    }

    /**
     * OAuth2 access token URL
     */
    public function getAccessTokenUrl()
    {
        return 'https://somesite.com/oauth/access_token';
    }

    /**
     * Get a list of supported features for this integration
     *
     * @return array
     */
    public function getSupportedFeatures()
    {
        return array(
            'public_profile',
            'public_activity'
        );
    }
}

```

Integrating 3rd party services in Mautic can be done by defining an Integration class for the service. For example, the MauticSocialBundle has several social media service classes defined in \Plugins\MauticSocialBundle\Integration. Each integration class handles the authorization process, integration configuration, etc.
#### Integration Class[](https://developer.mautic.org/#integration-class)
Each plugin can have multiple integrations by defining each as it’s own Integration class in the bundle’s Integration folder. The class should extend `\Mautic\PluginBundle\Integration\AbstractIntegration`. It defines the integration and provides a number of helper functions including OAuth authorization/request signing functions.
#### Integration Image[](https://developer.mautic.org/#integration-image)
Each integration is displayed on a “card” in the Manage Plugins area. To set an image for the integration, include an image in the bundle’s Assets\img. It should be 128x128px, be in a png, and have the same name as returned by `getName()` as lower case. For example, `\MauticPlugin\HelloWorldBundle\Integration\MarsIntegration` should have an image `plugins\HelloWorldBundle\Assets\img\mars.png`. 
#### Authorization[](https://developer.mautic.org/#authorization)
Out of the box, the AbstractIntegration class can handle standard key, OAuth1a, and OAuth2 specifications. The authorization type is defined by the `getAuthenticationType()` function. Each input required by the user (i.e username, password, etc) are defined by an array of keyName => label elements returned by `getRequiredKeyFields()`. This function is not required if using standard specs of key, OAuth1a, or OAuth2.
#### Functions[](https://developer.mautic.org/#functions)
Some of the main functions used are described below. Review the AbstractIntegration class and the functions docblocks for more details.
Keys saved by the integration are encrypted. To access the unencrypted versions in the Integration class, use the array `$this->keys`. 
Any of the functions defined in AbstractIntegration can be overridden per special needs of the specific Integration being implemented.
Area | Function | Description  
---|---|---  
Auth | getRequiredKeyFields | Returns an array of keyName => label elements for settings required from the user, i.e. username, password, client id, client secret, key, etc. Each element will be displayed as an input in the integration’s settings.  
Auth | getSecretKeys | Any keyName returned by getRequiredKeyFields that is considered secret or a password should be returned in an array by this function so that it’s properly masked in the form.  
Auth & Request | getClientIdKey | Used to define the “username” for the integration. It defaults to ‘client_id’ for authentication type oauth2 and 'keyName’ for the keyName authentication type.  
Auth & Request | getClientSecretKey | Used to define the “password” for the integration. By default, only oauth2 uses this and returns 'client_secret’.  
Auth | getAuthLoginUrl | Defines the login URL for the oauth1a spec  
Auth | getRequestToken | Used by the oauth1a spec to retrieve a request token during authorization  
Auth | getRequestTokenUrl | Used by the oauth1a spec to define the request token URL  
Auth | getAuthenticationUrl | Defines the login URL for the oauth2 spec  
Auth | getAccessTokenUrl | Defines the access token URL for the oauth2 spec  
Auth | getAuthScope | Defines the scope for the oauth2 spec  
Auth | getAuthCallbackUrl | Used to define the callback URL for oauth1a or oauth2 specs. This defaults to the mautic_integration_auth_callback route.  
Auth | prepareResponseForExtraction | Called by extractAuthKeys() to manipulate the data prior to checking validating the response by checking that the keyName returned by getAuthTokenKey() is part of the response. If not, it calls getErrorsFromResponse().  
Auth | getErrorsFromResponse | Called by extractAuthKeys() to extract errors from the response into a string.  
Auth & Request | prepareRequest | Called by makeRequest() to manipulate or prepare parameters, settings, headers, etc before sending to the URL  
Auth & Request | parseCallbackResponse | Called by makeRequest() to parse the response for the request into an array.  
Auth & Request | getAuthTokenKey | Returns the keyName that’s used to sign a request. Used by oauth1a (oauth_token) and oauth2 (access_token) specs.  
Request | getBearerToken | Generate a bearer token if required by the oauth2 spec  
General | isConfigured | Called to determine if the integration has been correctly configured.  
General | isAuthorized | Called to determine if the integration is authorized (or peforms a reauth if an oauth2 spec has refresh tokens stored)  
Request | makeRequest | Can be used to make API requests. It automatically handles standard key, oauth1a and oauth2 specs.  
Form | getFormSettings | Returns an array of options of what to display in integration’s configuration form. The two options used at this time is `requires_callback` (true to show a readonly input with the callback returned by getAuthCallbackUrl()) and `requires_authorization` (true to display the authorization button).  
Form | getFormNotes | Returns an array of “helper notes” to display in the various areas of the form.  
#### makeRequest()[](https://developer.mautic.org/#makerequest\(\))
makeRequest() can be used to automatically sign outgoing requests and/or authentication processes. Of course, any integration can inherit and override this class to suit the integrations needs. It accepts the following parameters:
Name | Type | Description  
---|---|---  
$url | string | The url to make the request to  
$parameters | array | An array of parameters to submit with the request. If $method is GET, these will be appended to the query string. Otherwise, they will be part of the POST body.  
$method | string | The request method i.e. get, post, put, patch, delete  
$settings | array | Configures the behavior of the makeRequest function. Built in optional settings are below.  
##### Settings[](https://developer.mautic.org/#settings)
Key | Type | Description  
---|---|---  
auth_type | string | Overrides the authentication type for the request. If not set, getAuthenticationType() is used.  
query | array | Append parameters to the query of the request URL.  
content_type | string | Sets the content type header for the request.  
encode_parameters | string | If set to json, parameters in the POST will be json encoded prior to making the request.  
headers | array | Array of custom headers to append to the request.  
ssl_verifypeer | bool | Set the CURLOPT_SSL_VERIFYPEER to true.  
curl_options | array | Custom set of curl options to apply to the request.  
return_raw | bool | If true, return the response rather than running it through parseCallbackResponse first.  
authorize_session | bool | Used by prepareRequest() and parseCallbackResponse() to change the behavior based on whether the if the request is obtaining authorization or just making an API call.  
### Extending Maintenance Cleanup[](https://developer.mautic.org/#extending-maintenance-cleanup)
```
<?php
// plugins\HelloWorldBundle\EventListener\MaintenanceSubscriber

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Doctrine\DBAL\Connection;
use Mautic\CoreBundle\CoreEvents;
use Mautic\CoreBundle\Event\MaintenanceEvent;
use Mautic\CoreBundle\Factory\MauticFactory;

/**
 * Class MaintenanceSubscriber
 */
class MaintenanceSubscriber extends CommonSubscriber
{
    /**
     * @var Connection
     */
    protected $db;

    /**
     * MaintenanceSubscriber constructor.
     *
     * @param MauticFactory $factory
     * @param Connection    $db
     */
    public function __construct(MauticFactory $factory, Connection $db)
    {
        parent::__construct($factory);

        $this->db = $db;
    }

    /**
     * {@inheritdoc}
     */
    public static function getSubscribedEvents()
    {
        return [
            CoreEvents::MAINTENANCE_CLEANUP_DATA => ['onDataCleanup', -50]
        ];
    }

    /**
     * @param $isDryRun
     * @param $date
     *
     * @return int
     */
    public function onDataCleanup (MaintenanceEvent $event)
    {
        $qb = $this->db->createQueryBuilder()
            ->setParameter('date', $event->getDate()->format('Y-m-d H:i:s'));

        if ($event->isDryRun()) {
            $rows = (int) $qb->select('count(*) as records')
                ->from(MAUTIC_TABLE_PREFIX.'worlds', 'w')
                ->where(
                    $qb->expr()->gte('w.date_added', ':date')
                )
                ->execute()
                ->fetchColumn();
        } else {
            $rows = (int) $qb->delete(MAUTIC_TABLE_PREFIX.'worlds')
                ->where(
                    $qb->expr()->lte('date_added', ':date')
                )
                ->execute();
        }

        $event->setStat($this->translator->trans('mautic.maintenance.hello_world'), $rows, $qb->getSQL(), $qb->getParameters());
    }
}

```

To hook into the `mautic:maintenance:cleanup` command, create a listening for the `\Mautic\CoreBundle\CoreEvents::MAINTENANCE_CLEANUP_DATA` event. The event listener should check if data should be deleted or a counted. Use `$event->setStat($key, $affectedRows, $sql, $sqlParameters)` to give feedback to the CLI command. Note that `$sql` and `$sqlParameters` are only used for debugging and shown only in the dev environment.
The plugin should check if a dry run is requested using `$event->isDryRun()` before deleting records! 
### Extending Landing Pages[](https://developer.mautic.org/#extending-landing-pages)
```
<?php
// plugins/HelloWorldBundle/EventListener/PageSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\PageBundle\PageEvents;
use Mautic\PageBundle\Event\PageBuilderEvent;
use Mautic\PageBundle\Event\PageSendEvent;

/**
 * Class PageSubscriber
 */
class PageSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            PageEvents::PAGE_ON_BUILD   => array('onPageBuild', 0),
            PageEvents::PAGE_ON_DISPLAY => array('onPageDisplay', 0)
        );
    }

    /**
     * Register the tokens and a custom A/B test winner
     *
     * @param PageBuilderEvent $event
     */
    public function onPageBuild(PageBuilderEvent $event)
    {
        // Add page tokens
        $content = $this->templating->render('HelloWorldBundle:SubscribedEvents\PageToken:token.html.php');
        $event->addTokenSection('helloworld.token', 'plugin.helloworld.header', $content);

        // Add AB Test Winner Criteria
        $event->addAbTestWinnerCriteria(
            'helloworld.planetvisits',
            array(
                // Label to group by
                'group'    => 'plugin.helloworld.header',

                // Label for this specific a/b test winning criteria
                'label'    => 'plugin.helloworld.pagetokens.',

                // Static callback function that will be used to determine the winner
                'callback' => '\MauticPlugin\HelloWorldBundle\Helper\AbTestHelper::determinePlanetVisitWinner'
            )
        );
    }

    /**
     * Search and replace tokens with content
     *
     * @param PageSendEvent $event
     */
    public function onPageDisplay(PageSendEvent $event)
    {
        // Get content
        $content = $event->getContent();

        // Search and replace tokens
        $content = str_replace('{hello}', 'world!', $content);

        // Set updated content
        $event->setContent($content);
    }
}

```

There are two way to extend pages: page tokens used to insert dynamic content into a page and a/b test winning criteria . Both leverage the `\Mautic\PageBundle\PageEvents::PAGE_ON_BUILD` event. Read more about [listeners and subscribers](https://developer.mautic.org/#events).
#### Page Tokens[](https://developer.mautic.org/#page-tokens)
Page tokens are handled exactly the same as [Email Tokens](https://developer.mautic.org/#page-tokens).
#### Page A/B Test Winner Criteria[](https://developer.mautic.org/#page-a/b-test-winner-criteria)
Custom landing page A/B test winner criteria is handled exactly the same as [page A/B test winner criteria](https://developer.mautic.org/#page-a/b-test-winner-criteria) with the only differences being that the `callback` function is passed `Mautic\PageBundle\Entity\Page $page` and `Mautic\PageBundle\Entity\Page $parent` instead. Of course `$children` is an ArrayCollection of Page entities as well.
### Extending Points[](https://developer.mautic.org/#extending-points)
Custom point actions and triggers can be added by listening to their respective on build events. Read more about [listeners and subscribers](https://developer.mautic.org/#events).
#### Point Actions[](https://developer.mautic.org/#point-actions)
To add a custom point action used to give a lead x points for doing a certain action, add a listener to the `\Mautic\PointBundle\PointEvents::POINT_ON_BUILD` event then configure the custom point action with `$event->addAction($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string for the option in the dropdown  
**formType** | OPTIONAL | string | The alias of a custom form type used to set config options.  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
**template** | OPTIONAL | string | View template used to render the formType  
**callback** | OPTIONAL | mixed | Static callback function used to validate the action. Return true to add the points to the lead.  
In order for the custom point action to work, add something like the following in the code logic when the lead executes the custom action:
`$this->getModel('point')->triggerAction('page.hit', $event->getHit());`
#### Point Triggers[](https://developer.mautic.org/#point-triggers)
To add a custom point trigger used to execute a specific action once a lead hits X number of points, add a listener to the `\Mautic\PointBundle\PointEvents::TRIGGER_ON_BUILD` event then configure the custom point trigger with `$event->addEvent($identifier, $parameters)` method. `$identifier` must be something unique. The `$parameters` array can contain the following elements:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string for the option in the dropdown  
**formType** | OPTIONAL | string | The alias of a custom form type used to set config options.  
**formTypeOptions** | OPTIONAL | array | Array of options to include into the formType’s $options argument  
**formTypeCleanMasks** | OPTIONAL | array | Array of input masks to clean a values from formType  
**formTypeTheme** | OPTIONAL | string | Theme to customize elements for formType  
**template** | OPTIONAL | string | View template used to render the formType  
**callback** | OPTIONAL | mixed | Static callback function used to execute the custom action.  
### Extending Reports[](https://developer.mautic.org/#extending-reports)
```
<?php
// plugins\HelloWorldBundle\EventListener\ReportSubscriber

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\CoreBundle\Helper\GraphHelper;
use Mautic\ReportBundle\Event\ReportBuilderEvent;
use Mautic\ReportBundle\Event\ReportGeneratorEvent;
use Mautic\ReportBundle\Event\ReportGraphEvent;
use Mautic\ReportBundle\ReportEvents;
use Mautic\CoreBundle\Helper\Chart\ChartQuery;
use Mautic\CoreBundle\Helper\Chart\LineChart;

/**
 * Class ReportSubscriber
 */
class ReportSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents ()
    {
        return array(
            ReportEvents::REPORT_ON_BUILD          => array('onReportBuilder', 0),
            ReportEvents::REPORT_ON_GENERATE       => array('onReportGenerate', 0),
            ReportEvents::REPORT_ON_GRAPH_GENERATE => array('onReportGraphGenerate', 0)
        );
    }

    /**
     * Add available tables, columns, and graphs to the report builder lookup
     *
     * @param ReportBuilderEvent $event
     *
     * @return void
     */
    public function onReportBuilder (ReportBuilderEvent $event)
    {
        // Use checkContext() to determine if the report being requested is this report
        if ($event->checkContext(array('worlds'))) {
            // Define the columns that are available to the report.
            $prefix  = 'w.';
            $columns = array(
                $prefix . 'visit_count' => array(
                    'label' => 'mautic.hellobundle.report.visit_count',
                    'type'  => 'int'
                ),
                $prefix . 'world' => array(
                    'label' => 'mautic.hellobundle.report.world',
                    'type'  => 'text'
                ),
            );

             // Several helper functions are available to append common columns such as categories, publish state fields, lead, etc.  Refer to the ReportBuilderEvent class for more details.
            $columns = $filters = array_merge($columns, $event->getStandardColumns($prefix), $event->getCategoryColumns());

            // Optional to override and update filters, i.e. change it to a select list for the UI
            $filters[$prefix.'world']['type'] = 'select';
            $filters[$prefix.'world']['list'] = array(
                'earth' => 'Earth',
                'mars'  => 'Mars'
            );

            // Add the table to the list
            $event->addTable('worlds',
                array(
                    'display_name' => 'mautic.helloworld.worlds',
                    'columns'      => $columns,
                    'filters'      => $filters // Defaults to columns if not set
                )
            );

            // Register available graphs; can use line, pie, or table
            $event->addGraph('worlds', 'line', 'mautic.hellobundle.graph.line.visits');
        }
    }

    /**
     * Initialize the QueryBuilder object used to generate the report's data.
     * This should use Doctrine's DBAL layer, not the ORM so be sure to use
     * the real schema column names (not the ORM property names) and the
     * MAUTIC_TABLE_PREFIX constant.
     *
     * @param ReportGeneratorEvent $event
     *
     * @return void
     */
    public function onReportGenerate (ReportGeneratorEvent $event)
    {
        $context = $event->getContext();
        if ($context == 'worlds') {
            $qb = $event->getQueryBuilder();

            $qb->from(MAUTIC_TABLE_PREFIX . 'worlds', 'w');
            $event->addCategoryLeftJoin($qb, 'w');

            $event->setQueryBuilder($qb);
        }
    }

    /**
     * Generate the graphs
     *
     * @param ReportGraphEvent $event
     *
     * @return void
     */
    public function onReportGraphGenerate (ReportGraphEvent $event)
    {
        if (!$event->checkContext('worlds')) {
            return;
        }

        $graphs   = $event->getRequestedGraphs();
        $qb       = $event->getQueryBuilder();

        foreach ($graphs as $graph) {
            $queryBuilder = clone $qb;
            $options      = $event->getOptions($graph);
            /** @var ChartQuery $chartQuery */
            $chartQuery    = clone $options['chartQuery'];
            $chartQuery->applyDateFilters($queryBuilder, 'date_added', 'v');

            switch ($graph) {
                case 'mautic.hellobundle.graph.line.visits':
                    $chart = new LineChart(null, $options['dateFrom'], $options['dateTo']);
                    $chartQuery->modifyTimeDataQuery($queryBuilder, 'date_added', 'v');
                    $visits = $chartQuery->loadAndBuildTimeData($queryBuilder);
                    $chart->setDataset($options['translator']->trans('mautic.hellobundle.graph.line.visits'), $visits);
                    $data         = $chart->render();
                    $data['name'] = $graph;
                    $data['iconClass'] = 'fa-tachometer';
                    $event->setGraph($graph, $data);

                    break;
            }
        }
    }
}

```

Adding and rendering custom reports are done by listening to the `\Mautic\ReportBundle\ReportEvents::REPORT_ON_BUILD`, `ReportEvents::REPORT_ON_GENERATE` and `ReportEvents::REPORT_ON_GRAPH_GENERATE` events.
#### Defining the Report[](https://developer.mautic.org/#defining-the-report)
Defining the report is done through the `ReportEvents::REPORT_ON_BUILD` event. This is where the plugin will define the context of the report, available columns for table data, available filters for the table data (defaults to columns) and available graphs. See the code example’s `onReportBuilder` for details.
##### Column Definition[](https://developer.mautic.org/#column-definition)
Each column array can include the following properties:
Key | Required | Type | Description  
---|---|---|---  
**label** | REQUIRED | string | The language string for the column  
**type** | REQUIRED | string | Column type  
**alias** | OPTIONAL | string | An alias for the returned value. Useful in conjuction with `formula`  
**formula** | OPTIONAL | string | SQL formula instead of a column. e.g. `SUBSTRING_INDEX(e.type, \'.\', 1)`  
**link** | OPTIONAL | string | Route name to convert the value into a hyperlink. Used usually with an ID of an Entity. The route must accept `objectAction` and `objectId` parameters.  
##### Filter Definition[](https://developer.mautic.org/#filter-definition)
Filter definitions are optional as Mautic will default to the column list. But sometimes it’s useful to replace filter values with a select list. Filter definitions can accept the same properties as columns but can also accept the following:
Key | Required | Type | Description  
---|---|---|---  
**list** | OPTIONAL | array | Used when `type` is `select` for a filter. Provides the dropdown options for a select input. Format should be `value => label`  
**operators** | OPTIONAL | array | Custom list of operators to allow for this filter. See `Mautic\ReportBundle\Builder\MauticReportBuilder::OPERATORS` for a examples.  
#### Generate the QueryBuilder[](https://developer.mautic.org/#generate-the-querybuilder)
The `ReportEvents::REPORT_ON_GENERATE` event is dispatched when a report is to be generated and displayed. In this function, the plugin should define the QueryBuilder object used to generate the table data. 
Use `$event->checkContext()` to determine if the report requested is the subscribers report.
Note that the `ReportEvents::REPORT_ON_GENERATE` event should use Doctrine’s DBAL layer QueryBuilder obtained via `$qb = $event->getQueryBuilder();`. 
There are a number of helper functions to append joins for commonly used relationships such as category, leads, ip address, etc. Refer to the ReportGeneratorEvent class for more details.
#### Graphs[](https://developer.mautic.org/#graphs)
Graphs are generated using `ReportEvents::REPORT_ON_GRAPH_GENERATE` event. The listener should check the context then generate and set the graph data. There are several classes to assist with generating classes. See 
### Extending Webhooks[](https://developer.mautic.org/#extending-webhooks)
Webhooks allow for Mautic to send data to external services via an endpoint url.
Webhooks work by using event listeners for two main purposes:
  1. An event listener to add webhook types to the webhook user interface.
  2. An event listener to whichever action you want to trigger a webhook payload to be queued.


##### Additional Steps[](https://developer.mautic.org/#additional-steps)
Additional steps that you must take in your own bundle are:
  1. Create your own event dispatching for your bundle’s custom event and payload
  2. Register your custom event listeners in your bundle’s configuration file as a service.
  3. Refer to [receiving webhooks](https://developer.mautic.org/#receiving-webhook-payloads) section to receive payloads in your application.


#### Webhook Type Listener[](https://developer.mautic.org/#webhook-type-listener)
Use the `WebhookEvents::WebhookBuilderEvent` to add a webhook type to the webhook interface.  ```
<?php
namespace Mautic\YourBundle\EventListener;

use Mautic\WebhookBundle\WebhookEvents;
use Mautic\WebhookBundle\Event\WebhookBuilderEvent;
use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\YourBundle\YourBundleEvents;

/**
 * Class WebhookSubscriber
 *
 * @package Mautic\YourBundle\EventListener
 */

class WebhookSubscriber extends CommonSubscriber
{
    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            WebhookEvents::WEBHOOK_ON_BUILD => array('onWebhookBuild', 0)
        );
    }

    /**
     * Add event triggers and actions
     *
     * @param WebhookBuilderEvent $event
     */
    public function onWebhookBuild(WebhookBuilderEvent $event)
    {
        // add checkbox to the webhook form for new leads
        $type  = array(
            'label'       => 'mautic.bundlename.webhook.event.type.new',
            'description' => 'mautic.bundlename.webhook.event.type.new_desc', // note: we don't currently use a description, but may in the future so we have supported it here
        );

        // add it to the list
        $event->addEvent(YourBundle::ACTION_TO_TRIGGER, $type);

         // Note: you may create multiple arrays and call the $event->addEvent method multiple times
         // in this function to add several types all at once.
    }
}
?>

```

Add an event listener for the `WebhookEvents::WEBHOOK_ON_BUILD` event, call the addEvent method and pass it an argument for your payload event constant, and an array of a label and a description to be added to the Webhook user interface.
`YourBundle::ACTION_TO_TRIGGER` is a constant that should be an event registered in your bundle. We use the constant to save the type in the database and query for later. You will use the same constant later, so its important to be consistent.
#### Payload Event Listener[](https://developer.mautic.org/#payload-event-listener)
Add an event listener which extends the `WebhookSubscriberBase` class. This event should be dispatched in your bundle when you wish to create a payload.  ```
<?php

namespace Mautic\YourBundle\EventListener;

// its important to use the WebhookSubscriberBase event listener
// as it does a lot of heavy lifting for you.

use Mautic\WebhookBundle\EventListener\WebhookSubscriberBase;

// you should change this to your bundle's event class
use Mautic\LeadBundle\LeadEvents;

// you should change this to the event type that you are going to use.
// in our case it will be a lead event.
use Mautic\LeadBundle\Event\LeadEvent;

use JMS\Serializer\Serializer;
use Mautic\CoreBundle\Factory\MauticFactory;
use Doctrine\ORM\NoResultException;
use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\LeadBundle\Event\PointsChangeEvent;
use Mautic\ApiBundle\Serializer\Exclusion\PublishDetailsExclusionStrategy;

/**
 * Class LeadSubscriber
 *
 * @package Mautic\Webhook\EventListener
 */
class LeadSubscriber extends WebhookSubscriberBase
{
    /**
     * @return array
     */
    static public function getSubscribedEvents ()
    {
        return array(
            // note this is the same constant we would have used in the addEvent() listener!
            LeadEvents::LEAD_POST_SAVE => array('onLeadNewUpdate', 0)
        )
    }

    /*
     * Generic method to execute when a lead does something
     */
    public function onLeadNewUpdate(LeadEvent $event)
    {
        // serializer groups are defined and optionally used in your bundle's entity.
        // Use these format your payload in JSON formats.
        $serializerGroups = array("leadDetails", "userList", "publishDetails", "ipAddress");

        // the beginning part of building our webhook payload of a lead entity
        $entity = $event->getLead();

        // our payload goes into an array
        $payload = array(
            'lead'      => $entity,
        );

        // we want to only trigger a payload if the lead is new
        if ($event->isNew()) {

            // again please note the use of the constant here - this should be consistent with the constant we register to the webhook form
            $webhookEvents = $this->getEventWebooksByType(LeadEvents::LEAD_POST_SAVE);

            // The webhook model is made available because we've extended the WebhookSubscriberBase class.
            $this->webhookModel->QueueWebhooks($webhookEvents, $payload, $serializerGroups);


        }
    }
}

```

The next step is to add an event listener for the action you want to actually use for creating payloads. This could be anything you want, your bundle will have to have an event type and use the event dispatcher to execute the event.
Here is an example listener to create a lead payload whenever a new lead is added to Mautic.
You can add the listener to any bundle. Be sure to register it in your bundle’s config.php file.
The event constant that you return in the `getSubscriberEvents()` method should match the event type from the previous listener. This is used in a database query, so it must match exactly for the payload to be included in the hook POST to the endpoint URL. 
You can refer to the model for more documentation on the `QueueWebhooks` method. In short you want to pass the event entities that this payload is being queued against The payload, which is an array, and finally the serializer groups for formatting the JSON.
This should complete the set up, registering and executing custom webhook events and payloads.
#### Receiving Webhook Payloads[](https://developer.mautic.org/#receiving-webhook-payloads)
> A sample new lead post payload
```
{"mautic.lead_post_save":{"lead":{"id":null,"points":0,"color":null,"fields":{"core":{"title":{"id":1,"group":"core","label":"Title","alias":"title","type":"lookup","value":null},"firstname":{"id":2,"group":"core","label":"First Name","alias":"firstname","type":"text","value":"Hello"},"lastname":{"id":3,"group":"core","label":"Last Name","alias":"lastname","type":"text","value":"World"},"company":{"id":4,"group":"core","label":"Company","alias":"company","type":"lookup","value":null},"position":{"id":5,"group":"core","label":"Position","alias":"position","type":"text","value":null},"email":{"id":6,"group":"core","label":"Email","alias":"email","type":"email","value":"example@email.com"},"phone":{"id":7,"group":"core","label":"Phone","alias":"phone","type":"tel","value":null},"mobile":{"id":8,"group":"core","label":"Mobile","alias":"mobile","type":"tel","value":null},"fax":{"id":9,"group":"core","label":"Fax","alias":"fax","type":"text","value":null},"address1":{"id":10,"group":"core","label":"Address Line 1","alias":"address1","type":"text","value":null},"address2":{"id":11,"group":"core","label":"Address Line 2","alias":"address2","type":"text","value":null},"city":{"id":12,"group":"core","label":"City","alias":"city","type":"lookup","value":null},"state":{"id":13,"group":"core","label":"State","alias":"state","type":"region","value":null},"zipcode":{"id":14,"group":"core","label":"Zipcode","alias":"zipcode","type":"lookup","value":null},"country":{"id":15,"group":"core","label":"Country","alias":"country","type":"country","value":null},"website":{"id":16,"group":"core","label":"Website","alias":"website","type":"text","value":null}},"social":{"twitter":{"id":17,"group":"social","label":"Twitter","alias":"twitter","type":"text","value":null},"facebook":{"id":18,"group":"social","label":"Facebook","alias":"facebook","type":"text","value":null},"googleplus":{"id":19,"group":"social","label":"Google+","alias":"googleplus","type":"text","value":null},"skype":{"id":20,"group":"social","label":"Skype","alias":"skype","type":"text","value":null},"instagram":{"id":21,"group":"social","label":"Instagram","alias":"instagram","type":"text","value":null},"foursquare":{"id":22,"group":"social","label":"Foursquare","alias":"foursquare","type":"text","value":null}},"personal":[],"professional":[]},"lastActive":null,"owner":null,"ipAddresses":[],"dateIdentified":null,"preferredProfileImage":null},"timestamp":"2015-08-18T18:53:33+00:00"}}
```
Click the `JSON` tab to see a sample lead JSON payload. 
Webhooks enable Mautic to send data for leads, points, and email opens to outside applications. It does this by taking an outside application’s endpoint url, and sending an HTTP post request to that location. In that post we include the relevant data the the event that has been fired.
To listen to the webhook posts, developers should create a publicly accessible endpoint location in their application. That endpoint should be available to receive a POST request from Mautic. The contents of the payload will vary based on the events that the user wishes to include in the payload.
An excellent way of testing to see the data that will be included is using 
### Extending UI[](https://developer.mautic.org/#extending-ui)
#### Injecting Buttons[](https://developer.mautic.org/#injecting-buttons)
```
<?php
// plugins/HelloWorldBundle/Event/ButtonSubscriber.php

namespace MauticPlugin\HelloWorldBundle\EventListener;


use Mautic\CoreBundle\CoreEvents;
use Mautic\CoreBundle\Event\CustomButtonEvent;
use Mautic\CoreBundle\EventListener\CommonSubscriber;
use Mautic\CoreBundle\Templating\Helper\ButtonHelper;
use Mautic\LeadBundle\Entity\Lead;

class ButtonSubscriber extends CommonSubscriber
{
    public static function getSubscribedEvents()
    {
        return [
            CoreEvents::VIEW_INJECT_CUSTOM_BUTTONS => ['injectViewButtons', 0]
        ];
    }

    /**
     * @param CustomButtonEvent $event
     */
    public function injectViewButtons(CustomButtonEvent $event)
    {
        // Injects a button into the toolbar area for any page with a high priority (displays closer to first)
        $event->addButton(
            [
                'attr'      => [
                    'class'       => 'btn btn-default btn-sm btn-nospin',
                    'data-toggle' => 'ajaxmodal',
                    'data-target' => '#MauticSharedModal',
                    'href'        => $this->router->generate('mautic_world_action', ['objectAction' => 'doSomething']),
                    'data-header' => 'Extra Button',
                ],
                'tooltip'   => $this->translator->trans('mautic.world.dosomething.btn.tooltip'),
                'iconClass' => 'fa fa-star',
                'priority'  => 255,
            ],
            ButtonHelper::LOCATION_TOOLBAR_ACTIONS
        );

        // 
        if ($lead = $event->getItem()) {
            if ($lead instanceof Lead) {
                $sendEmailButton = [
                    'attr'      => [
                        'data-toggle' => 'ajaxmodal',
                        'data-target' => '#MauticSharedModal',
                        'data-header' => $this->translator->trans(
                            'mautic.world.dosomething.header',
                            ['%email%' => $event->getItem()->getEmail()]
                        ),
                        'href'        => $this->router->generate(
                            'mautic_world_action',
                            ['objectId' => $event->getItem()->getId(), 'objectAction' => 'doSomething']
                        ),
                    ],
                    'btnText'   => 'Extra Button',
                    'iconClass' => 'fa fa-star',
                    'primary'   => true,
                    'priority'  => 255,
                ];

                // Inject a button into the page actions for the specified route (in this case /s/contacts/view/{contactId})
                $event
                    ->addButton(
                        $sendEmailButton,
                        // Location of where to inject the button; this can be an array of multiple locations
                        ButtonHelper::LOCATION_PAGE_ACTIONS,
                        ['mautic_contact_action', ['objectAction' => 'view']]
                    )
                    // Inject a button into the list actions for each contact on the /s/contacts page
                    ->addButton(
                        $sendEmailButton,
                        ButtonHelper::LOCATION_LIST_ACTIONS,
                        'mautic_contact_index'
                    );
            }
        }
    }
}

```

As of Mautic 2.3.0, support for plugins to inject buttons throughout Mautic’s UI has been added by listening to the `CoreEvents::VIEW_INJECT_CUSTOM_BUTTONS` event.
There are five places in Mautic’s UI that buttons can be injected into:
Location | Description  
---|---  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::LOCATION_LIST_ACTIONS | Drop down actions per each item in list views.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::LOCATION_TOOLBAR_ACTIONS | Top right above list view tables to the right of the table filter. Preferably buttons with icons only.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::LOCATION_PAGE_ACTIONS | Main page buttons to the right of the page title (New, Edit, etc). Primary buttons will be displayed as buttons while the rest will be displayed in a drop down.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::LOCATION_NAVBAR | Top of the page to the left of the account/profile menu. Buttons with text and/or icons.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::LOCATION_BULK_ACTIONS | Buttons inside the bulk dropdown (around the checkall checkbox of lists).  
Buttons use a priority system to determine order. The higher the priority, the closer to first the button is displayed. The lower the priority, the closer to last. For a button dropdown, setting a button as `primary` will display the button in the button group rather than the dropdown.
##### Button Array Format[](https://developer.mautic.org/#button-array-format)
The array defining the button can include the following keys:
Key | Type | Description  
---|---|---  
attr | array | Array of attributes to be appended to the button (data attributes, href, etc)  
btnText | string | Text to display for the button  
iconClass | string | Font Awesome class to use as the icon within the button  
tooltip | string | Text to display as a tooltip  
primary | boolean | For button dropdown formats, this will display the button in the group rather than in the dropdown  
priority | int | Determines the order of buttons. Higher the priority, closer to the first the button will be placed. Buttons with the same priority wil be ordered alphabetically.  
If a button is to display a confirmation modal, the key `confirm` can be used. A `confirm` array can have the following keys:
Key | Type | Description  
---|---|---  
message | string | Translated message to display in the confirmation window  
confirmText | string | Text to display as the confirm button  
confirmAction | string | HREF of the button  
cancelText | string | Text to display as the cancel button  
cancelCallback | string | Mautic namespaced Javascript method to be executed when the cancel button is clicked  
confirmCallback | string | Mautic namespaced Javascript method to be executed when the confirm button is clicked  
precheck | string | Mautic namespaced Javascript method to be executed prior to displaying the confirmation modal  
btnClass | string | Class for the button  
iconClass | string | Font Awesome class to use as the icon  
btnTextAttr | string | string of attributes to append to the button’s inner text  
attr | array | Array of attributes to append to the button’s outer tag  
tooltip | string | Translated string to display as a tooltip  
tag | string | Tag to use as the button. Defaults to an `a` tag.  
wrapOpeningTag | string | Tag/html to wrap button in. Defaults to nothing.  
wrapClosingTag | string | Tag/thml to close wrapOpeningTag. Defaults to nothing.  
On the same nested level as the `confirm` key can include `primary` and/or `priority`. 
#### Defining Button Locations[](https://developer.mautic.org/#defining-button-locations)
```
<?php
$dropdownOpenHtml = '<button type="button" class="btn btn-default btn-nospin  dropdown-toggle" data-toggle="dropdown" aria-expanded="false"><i class="fa fa-caret-down"></i></button>'
          ."\n";
$dropdownOpenHtml .= '<ul class="dropdown-menu dropdown-menu-right" role="menu">'."\n";

echo $view['buttons']->reset($app->getRequest(), 'custom_location')->renderButtons($dropdownOpenHtml, '</ul>');

```

A plugin can define it’s own locations that other plugins can leverage by using the template `buttons` helper.
There are three types of button groups supported:
Type | Description  
---|---  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::TYPE_BUTTON_DROPDOWN | Primary buttons are displayed in a button group while others in a dropdown menu.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::TYPE_DROPDOWN | Buttons displayed in a dropdown menu.  
\Mautic\CoreBundle\Templating\Helper\ButtonHelper::TYPE_GROUP | A group of buttons side by side.  
Dropdowns require the wrapping HTML to be passed to the `renderButtons` method.
## Miscellaneous[](https://developer.mautic.org/#miscellaneous)
### Flash Messages[](https://developer.mautic.org/#flash-messages)
```
<?php

// From within a controller

$this->addFlash(
    'mautic.translation.key',
    array('%placeholder%' => 'some text'),
    'notice', // Notification type
    'flashes', // Translation domain
    $addNotification // Add a notification entry
);

```
```
<?php

// From within a model or other service with access to the translator and session services

$translatedString = $this->translator->trans(, 
    array(
        '%placeholder%' => 'some text'
    ),
    'flashes'
);
$this->session->getFlashBag()->add('notice', $translatedString);

```

To create an alert, aka flash message, you can use the flash bag in the session.
If your controller extends one of [Mautic’s common controllers](https://developer.mautic.org/#controllers), you can simply use the helper function `addFlash()`.
From a model, or any service, you can use the session to obtain the flash bag.
`$flashBag = $this->get('session')->getFlashBag();`
### Notifications[](https://developer.mautic.org/#notifications)
```
<?php
// From within a controller

$this->addNotification($message, $type, $isRead, $header, $iconClass, new \DateTime());

```
```
<?php

// From within a model or other service that has access to the mautic.core.model.notification service

$notificationModel->addNotification($message, $type, $isRead, $header, $iconClass, $datetime );


```

Mautic also has a notification center. By default, addFlash() will also add a notification to the center. But, a message can be manually added as well. 
Controllers can use the helper function while models and other services can obtain the NotificationModel.
### Helpers[](https://developer.mautic.org/#helpers)
Mautic has many helper classes available. A few of the most commonly used ones are highlighted below.
#### Input Helper[](https://developer.mautic.org/#input-helper)
The input helper can be used to ensure clean strings from user input.
```
<?php

use \Mautic\CoreBundle\Helper\InputHelper;

// ...

$clean = InputHelper::clean($input);
$clean = InputHelper::int($input);
$clean = InputHelper::alphanum($input);
$clean = InputHelper::html($input);

// and others; refer to the class for more options

```

#### Date/Time Helper[](https://developer.mautic.org/#date/time-helper)
The date/time helper can be used to convert between UTC and the local timezone. 
```
<?php

$dtHelper  = new \Mautic\CoreBundle\Helper\DateTimeHelper('2015-07-20 21:39:00', 'Y-m-d H:i:m', 'local');
$utcString = $dtHelper->toUtcString();

// refer to the class for other functions

```

#### ChartQuery and Graphs[](https://developer.mautic.org/#chartquery-and-graphs)
There are several classes available to assist with generating chart data.
```
<?php
use Mautic\CoreBundle\Helper\Chart\LineChart;
use Mautic\CoreBundle\Helper\Chart\ChartQuery;

$chart = new LineChart($unit, $dateFrom, $dateTo, $dateFormat);
$query = new ChartQuery($this->em->getConnection(), $dateFrom, $dateTo);
$q     = $query->prepareTimeDataQuery('lead_points_change_log', 'date_added', $filter);
$data  = $query->loadAndBuildTimeData($q);
$chart->setDataset($this->translator->trans('mautic.point.changes'), $data);
$data  = $chart->render();

```

##### ChartQuery[](https://developer.mautic.org/#chartquery)
ChartQuery is a helper class to get the chart data from the database. Instantiate it with the Doctrine connection object, date from and date to. Those dates must be instances of the DateTime class. ChartQuery will automatically guess the time unit (hours, days, weeks, months or years) based on the items between the date range. However, if you want to receive the data from a specific time unit, pass it as the fourth parameter (H, d, W, m, Y).
ChartQuery also fills in the missing items (if any) which is required to display the data properly in the line chart generated by the 
##### LineChart[](https://developer.mautic.org/#linechart)
LineChart is used in Mautic to display a date/time related data where the time is on the horizontal axis and the values are in the vertical axis. ChartJS’ line charts can display multiple datasets in one chart. Instantiate the LineChart with a unit (null for unit guessing), from date, to date (the same as for the ChartQuery) and a date format (null for automatically generated date format).
All the params you need to instantiate the LineChart are used to generate the labels of the horizontal axis. To add the dataset to the LineChart object, use the `setDataset($label, $data)` method where the label is string and data is an array generated by the ChartQuery. The color of each dataset will be generated automatically.
Call the `render()` method to get the data prepared for ChartJS.
##### PieChart[](https://developer.mautic.org/#piechart)
A PieChart can be instantiated simply by `new PieChart()`. To add a dataset, use again the `setDataset($label, $value)` method where the label is a string and value is integer.
Call the `render()` method to get the data prepared for ChartJS.
##### BarChart[](https://developer.mautic.org/#barchart)
BarChart is used to display different variants of the same value where the variants are in the horizontal axis and the value is in vertical axis. To create a bar chart, use `new BarChart($labels)` where labels is an array of all the variants. Each variant can have multiple datasets. To add a dataset, use the `setDataset($label, $data, $order)` method where the label is string, data is array of values for each variant. Order can be used to move the dataset before already created dataset.
Call the `render()` method to get the data prepared for ChartJS.
```
<?php echo $view->render('MauticCoreBundle:Helper:chart.html.php', array('chartData' => $data, 'chartType' => 'line', 'chartHeight' => 300)); ?>

```

##### Frontend[](https://developer.mautic.org/#frontend)
At the frontend, simply use the prepared chart template, pass in the chart data, the chart type (line/bar/pie) and the chart height. The width is responsive.
### Commands[](https://developer.mautic.org/#commands)
Support for new CLI commands can be added using 
#### Moderated Commands[](https://developer.mautic.org/#moderated-commands)
```
<?php
// plugins\HelloWorldBundle\Command\WorldCommand.php

namespace MauticPlugin\HelloWorldBundle\Command;

use Mautic\CoreBundle\Command\ModeratedCommand;
use Symfony\Component\Console\Input\InputInterface;
use Symfony\Component\Console\Output\OutputInterface;

/**
 * CLI Command to send a scheduled broadcast.
 */
class WorldCommand extends ModeratedCommand
{
    /**
     * {@inheritdoc}
     */
    protected function configure()
    {
        // ...

        // Important to append options used by ModeratedCommand
        parent::configure();
    }

    /**
     * @param InputInterface  $input
     * @param OutputInterface $output
     *
     * @return int
     */
    protected function execute(InputInterface $input, OutputInterface $output)
    {
        // Validate if the command is already has an instance running
        // A third argument can be passed here if this command is running something unique such as an ID
        if (!$this->checkRunStatus($input, $output)) {
            return 0;
        }

        // Execute some stuff

        // Complete this execution
        $this->completeRun();

        return 0;
    }
}

```

Mautic provide an method for moderating commands meaning it will only allow one instance to run at a time. To utilize this method, extend the `Mautic\CoreBundle\Command\ModeratedCommand` class.
### Forms[](https://developer.mautic.org/#forms)
Mautic leverages Symfony’s Form component and form classes. Refer to 
#### Form Types[](https://developer.mautic.org/#form-types)
As stated in Symfony’s documentation referenced above, form type classes are the best way to go. Mautic makes it easy to register [Services](https://developer.mautic.org/#services) section.
#### Data Sanitization[](https://developer.mautic.org/#data-sanitization)
```
<?php
// plugins/HelloWorldBundle/Form/Type/WorldType.php

// ...
use Mautic\CoreBundle\Form\EventListener\CleanFormSubscriber;

// ...
    public function buildForm(FormBuilderInterface $builder, array $options)
    {
        $builder->addEventSubscriber(
            new CleanFormSubscriber(
                [
                    'content'    => 'html', 
                    'customHtml' => 'html'
                ]
            )
        );

       // ...
    }
// ...

```

Form data is not automatically sanitized. Mautic provides a form event subscriber to handle this. 
In your `Mautic\CoreBundle\Form\EventListener\CleanFormSubscriber` event subscriber. 
The array provided to `CleanFormSubscriber` should contain the names of the form fields as keys and the values the masks to use to sanitize the data. Any un-specified form field will use the `clean` mask by default.
#### Manipulating Forms[](https://developer.mautic.org/#manipulating-forms)
A form event listener must be used if a form needs to be manipulated based on submitted data such as changing defined fields, adjust constraints, or changing select choices based on submitted values. Refer to 
#### Validating Data[](https://developer.mautic.org/#validating-data)
Review 
There are two common means of validating form data.
##### Using Entity Static Callback[](https://developer.mautic.org/#using-entity-static-callback)
```
<?php
// plugins/HelloWorldBundle/Entity/World.php

// ...
use Symfony\Component\Validator\Constraints\NotBlank;
use Symfony\Component\Validator\Mapping\ClassMetadata;
use Symfony\Component\Form\Form;

// ...
  /**
     * @param ClassMetadata $metadata
     */
    public static function loadValidatorMetadata (ClassMetadata $metadata)
    {
        $metadata->addPropertyConstraint(
            'name',
            new NotBlank(
                array(
                    'message' => 'mautic.core.name.required'
                )
            )
        );

        $metadata->addPropertyConstraint(
            'population', 
            new NotBlank(
                array(
                    'message' => 'mautic.core.value.required',
                    'groups'  => array('VisitedWorld')
                )

            )
        );
    }

    /**
     * @param Form $form
     *
     * @return array
     */
    public static function determineValidationGroups (Form $form)
    {
        $data   = $form->getData();
        $groups = array('AllWorlds');

        if (!$data->getId() || ($data->getId() && $data->getVisitCount() > 0)) {
            $groups[] = 'VisitedWorld';
        }

        return $groups;
    }
// ...

```

If the underlying data of a form is an Entity object, a static method `loadValidatorMetadata` can be defined in the Entity class. This will automatically be called when Symfony is processing form data.
A form can also use 
```
<?php
// plugins/HelloWorldBundle/Form/Type/WorldType.php

//...
    /**
     * {@inheritdoc}
     */
    public function setDefaultOptions (OptionsResolverInterface $resolver)
    {
        $resolver->setDefaults(array(
            'data_class'        => 'MauticPlugin\HelloWorld\Entity\World',
            'validation_groups' => array(
                'MauticPlugin\HelloWorld\Entity\World',
                'determineValidationGroups',
            )
        ));
    }
// ...

```

##### Using Constraints[](https://developer.mautic.org/#using-constraints)
A 
```
<?php
// plugins/HelloWorldBundle/Form/Type/WorldType.php

// ...

use Symfony\Component\Validator\Constraints\NotBlank;

// ...

    public function buildForm(FormBuilderInterface $builder, array $options)
    {
          $builder->add(
              'name',
              'text',
              array(
                  'label'       => 'mautic.core.name',
                  'label_attr'  => array('class' => 'control-label'),
                  'attr'        => array(
                      'class'   => 'form-control'
                  ),
                  'constraints' => array(
                      new NotBlank(
                          array(
                              'message' => 'mautic.core.value.required'
                          )
                      )
                  )
              )
          );
    }

// ...

```

### Events[](https://developer.mautic.org/#events)
```
<?php
// plugins\HelloWorldBundle\EventListener\LeadSubscriber

namespace MauticPlugin\HelloWorldBundle\EventListener;

use Mautic\LeadBundle\Event as Events;
use Mautic\LeadBundle\LeadEvents;

/**
 * Class LeadSubscriber
 *
 * @package Mautic\LeadBundle\EventListener
 */
class LeadSubscriber extends CommonSubscriber
{

    /**
     * @return array
     */
    static public function getSubscribedEvents()
    {
        return array(
            LeadEvents::LEAD_POST_SAVE     => array('onLeadPostSave', 0),
            LeadEvents::LEAD_POST_DELETE   => array('onLeadDelete', 0)
        );
    }

    public function onLeadPostSave(LeadEvent $event)
    {
        $lead = $event->getLead();

        // do something
    }

    public function onLeadDelete(LeadEvent $event)
    {
        $lead = $event->getLead();

        $deletedId = $lead->deletedId;

        // do something
    }
}

```

Mautic leverages Symfony’s EventDispatcher to execute and communicate various actions through Mautic. Plugin’s can hook into these to extend the functionality of Mautic. Refer to [Extending Mautic](https://developer.mautic.org/#extending-mautic) for some of the ways to do this.
#### Subscribers[](https://developer.mautic.org/#subscribers)
The easiest way to listen to various events is to use an event subscriber. Read more about subscribers in 
Plugin event subscribers can extend `\Mautic\CoreBundle\EventListener\CommonSubscriber` which gives access to commonly used dependencies and also allows registering the subscriber service through the bundles’s config file. But, it does not have to and instead See [Services](https://developer.mautic.org/#services) for more information on registering event services. 
#### Available Events[](https://developer.mautic.org/#available-events)
There are many events available throughout Mautic. Depending on the desired functionality, look at the core bundle’s *Event.php file in the root of the bundle. For example, Lead related events are defined and described in `app\bundles\LeadBundle\LeadEvents.php`. These final classes provide the names of the events to listen to. Always use the event constants to ensure future changes to event names will not break the plugin.
#### Custom Events[](https://developer.mautic.org/#custom-events)
A plugin can create and dispatch it’s own events. 
Custom events require three things:
```
<?php
// plugins\HelloWorldBundle\HelloWorldEvents.php

namespace MauticPlugin\HelloWorldBundle;

/**
 * Class HelloWorldEvents
 */
final class HelloWorldEvents
{
    /**
     * The helloworld.armageddon event is dispatched when a world is doomed by a giant meteor
     *
     * The event listener receives a MauticPlugin\HelloWorldBundle\Event\ArmageddonEvent instance.
     *
     * @var string
     */
    const ARMAGEDDON = 'helloworld.armageddon';
}

```

1) Class defining the available events for the plugin using a `final` class with constants
```
<?php
// plugins\HelloWorldBundle\Event\ArmageddonEvent.php

namespace MauticPlugin\HelloWorldBundle\Event;

use Symfony\Component\EventDispatcher\Event;
use MauticPlugin\HelloWorldBundle\Entity\World;

class ArmageddonEvent extends Event
{
    /** @var World  */
    protected $world;

    /** @var bool  */    
    protected $falseAlarm = false;

    public function __construct(World $world)
    {
        $this->world = $world;
    }

    public function shouldPanic()
    {
        return ('earth' == $this->world->getName());
    }

    public function setIsFalseAlarm()
    {
        $this->falseAlarm = true;
    }

    public function getIsFalseAlarm()
    {
        return $this->falseAlarm;
    }
}

```

2) The Event class that is received by the listeners. This class should extend `Symfony\Component\EventDispatcher\Event`. It will be created when the event is dispatched and should have any information listeners need to act on it.
```
<?php

$dispatcher = $this->get('event_dispatcher');
if ($dispatcher->hasListeners(HelloWorldEvents::ARMAGEDDON)) {
    $event = $dispatcher->dispatch(HelloWorldEvents::ARMAGEDDON, new ArmageddonEvent($world));

    if ($event->shouldPanic()) {
        throw new \Exception("Run for the hills!");
    }
}

```

3) The code that dispatches the event where appropriate using the [`event_dispatcher` service](https://developer.mautic.org/#event-dispatcher).
### Implementing Translation Support to Entities[](https://developer.mautic.org/#implementing-translation-support-to-entities)
Mautic has some helper methods with adding support for translated content to an entity.
#### \Mautic\CoreBundle\Entity\TranslationInterface[](https://developer.mautic.org/#\\mautic\\corebundle\\entity\\translationinterface)
This Entity interface ensures that everything is needed in order for Mautic to handle translations correctly for an entity.
#### \Mautic\CoreBundle\Entity\TranslationEntityTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\entity\\translationentitytrait)
This trait provides properties needed to define an Entity’s language and relationships to other items. In the Entity’s `loadMetadata()` method, be sure to call `$this->addTranslationMetadata()`.
#### \Mautic\CoreBundle\TranslationModelTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\translationmodeltrait)
This trait provides the method `getTranslatedEntity()` that will determine the entity to use as the translation based on the `$lead` and/or the `HTTP_ACCEPT_LANGUAGE` header. It also has a `postTranslationEntitySave()` that should be called at the end of the Entity’s `saveEntity()` method. 
#### \Mautic\CoreBundle\Doctrine\TranslationMigrationTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\doctrine\\translationmigrationtrait)
To ease the generation of schema to match the Entity, use this trait then execute `$this->addTranslationSchema()`.
#### Translated Entity Form[](https://developer.mautic.org/#translated-entity-form)
Add a `locale` and `translatedParent` form fields like the code example. 
```
<?php 
// plugins/HelloWorldPlugin/Form/Type/WorldType.php

    $transformer = new \Mautic\CoreBundle\Form\Transformer\IdToEntityModelTransformer($this->em, 'HelloWorldBundle:World');
    $builder->add(
        $builder->create(
            'translationParent',
            'world_list',
            array(
                'label'       => 'mautic.core.form.translation_parent',
                'label_attr'  => array('class' => 'control-label'),
                'attr'        => array(
                    'class'   => 'form-control',
                    'tooltip' => 'mautic.core.form.translation_parent.help'
                ),
                'required'    => false,
                'multiple'    => false,
                'empty_value' => 'mautic.core.form.translation_parent.empty',
                'top_level'   => 'translation',
                'ignore_ids'  => array((int) $options['data']->getId())
            )
        )->addModelTransformer($transformer)
    );

    $builder->add(
        'language',
        'locale',
        array(
            'label'      => 'mautic.core.language',
            'label_attr' => array('class' => 'control-label'),
            'attr'       => array(
                'class'   => 'form-control',
                'tooltip' => 'mautic.page.form.language.help',
            ),
            'required'   => false,
            'empty_data' => 'en'
        )
    );

```

### Implementing Variant (A/B Test) Support to Entities[](https://developer.mautic.org/#implementing-variant-\(a/b-test\)-support-to-entities)
Mautic has some helper methods with adding support for creating variants of a given entity. This becomes particularly useful for A/B testing.
#### \Mautic\CoreBundle\Entity\VariantInterface[](https://developer.mautic.org/#\\mautic\\corebundle\\entity\\variantinterface)
This Entity interface ensures that everything is needed in order for Mautic to handle the variants correctly for an entity.
#### \Mautic\CoreBundle\Entity\VariantEntityTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\entity\\variantentitytrait)
This trait provides properties needed to define an Entity’s relationship to other items. In the Entity’s `loadMetadata()` method, be sure to call `$this->addVariantMetadata()`.
#### \Mautic\CoreBundle\VariantModelTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\variantmodeltrait)
This trait provides the methods `preVariantSaveEntity()`, `postVariantSaveEntity()` and `convertVariant()`. `preVariantSaveEntity()` should be executed prior to `saveEntity` then `postVariantSaveEntity()`. See example.
```
<?php
// plugins/HelloWorldBundle/Model/WorldModel.php

// Reset a/b test if applicable
$variantStartDate = new \DateTime();
// setVariantHits is the stat tracker properties for this variant
$resetVariants    = $this->preVariantSaveEntity($entity, ['setVariantHits'], $variantStartDate);

parent::saveEntity($entity, $unlock);

$this->postVariantSaveEntity($entity, $resetVariants, $entity->getRelatedEntityIds(), $variantStartDate);

```

#### \Mautic\CoreBundle\Doctrine\VariantMigrationTrait[](https://developer.mautic.org/#\\mautic\\corebundle\\doctrine\\variantmigrationtrait)
To ease the generation of schema to match the Entity, use this trait then execute `$this->addVariantSchema()`.
#### Translated Entity Form[](https://developer.mautic.org/#translated-entity-form)
Add `variantParent` field’s like the code example. In the example, the `variantParent` value is set in the controller due to a `Add A/B Test` button is clicked. The specific use for the plugin may require a select list rather than a hidden field. Change this to meet the code’s needs.
```
<?php 
// plugins/HelloWorldPlugin/Form/Type/WorldType.php

$transformer = new \Mautic\CoreBundle\Form\Transformer\IdToEntityModelTransformer($this->em, 'HelloWorldBundle:World');
$builder->add(
   $builder->create(
       'variantParent',
       'hidden'
   )->addModelTransformer($transformer)
);

```

# Marketplace[](https://developer.mautic.org/#marketplace)
Mautic 4 comes with a Marketplace directly in the Mautic administration user interface and command line interface as well.
## Marketplace under the hood[](https://developer.mautic.org/#marketplace-under-the-hood)
The Marketplace use 
## How to list a plugin in the Mautic Marketplace[](https://developer.mautic.org/#how-to-list-a-plugin-in-the-mautic-marketplace)
Please check the resources on the 
## How to get included in the allow-list[](https://developer.mautic.org/#how-to-get-included-in-the-allow-list)
Please check the resources on the 
## Best Practices[](https://developer.mautic.org/#best-practices)
Please check the best practices on the 
# Themes[](https://developer.mautic.org/#themes)
Custom themes for public facing areas of Mautic can be generated but require a bit of Twig experience.
The themes use the same templating formats as 
## Theme Directory Structure[](https://developer.mautic.org/#theme-directory-structure)
Each theme directory must have at least a config.json file and a html directory with the public facing template’s for the feature’s it supports. All themes should have a `html/message.html.twig` file. See below for a typical directory structure:
`themes/blank/` - [`config.json`](https://developer.mautic.org/#theme-config-file) - [`thumbnail.png`](https://developer.mautic.org/#theme-thumbnail) - `html/` - [`base.html.twig`](https://developer.mautic.org/#theme-html-files) - [`email.html.twig`](https://developer.mautic.org/#theme-html-files) - [`form.html.twig`](https://developer.mautic.org/#theme-html-files) - [`message.html.twig`](https://developer.mautic.org/#theme-html-files) - [`page.html.twig`](https://developer.mautic.org/#theme-html-files)
## Theme zip package[](https://developer.mautic.org/#theme-zip-package)
If you want to make your theme installable via the Theme Manager, make a zip package from it. The zip package name must be the same as the final folder name of the theme in the /themes folder. The contents of the zip folder must contain the theme files directly, not in a subfolder. You can download an existing theme via the Theme Manager to see an example ZIP file.
## Theme Config File[](https://developer.mautic.org/#theme-config-file)
```
{"name":"Theme Name","author":"John Doe","authorUrl":"https://john-doe-the-mautic-theme-builder.com","features":["page","email","form"]}
```

The config file defines the name of the theme and the features it supports.
The config file should return an array with the following keys:
Key | Type | Description  
---|---|---  
name | string | Name of the theme  
author | string | Name of the theme author  
authorUrl | string | URL to the author’s website  
features | array | Array of features the theme supports. Options currently are email, form, and/or page  
## Theme Thumbnail[](https://developer.mautic.org/#theme-thumbnail)
The thumbnail should be a screenshot of the theme with demo content. The width x height should be 575 x 600 px. This thumbnail will be available for Mautic users for quick theme preview in the Email edit form, Landing Page edit form and the Theme Manager.
Mautic will be look for thumbnail.png for default but if you want a specific image for your [email, page, form] template you can add a thumbnail_feature.png. 
Example
Feature | thumbnail name  
---|---  
email | thumbnail_email.png  
form | thumbnail_form.png  
page | thumbnail_page.png  
## Slots[](https://developer.mautic.org/#slots)
### Slot definition[](https://developer.mautic.org/#slot-definition)
The slot can be defined by a single HTML attribute `data-slot="{slot type here}"`. For example, the text slot can be defined even with the demo content.
When the theme is opened in the builder, the div with attribute `data-slot="text"` will make the text inside the div editable within the inline Froala editor.
Example:
```
<div data-slot="text">
    <a>@JaneDoe</a> has invited you to join Awesome inc!
</div>

```

The slot types currently built:
#### Image[](https://developer.mautic.org/#image)
Inserts a single image into the div. User can click on it and edit it with options which provides Froala editor (link, change image source, alt text, …)
#### Button[](https://developer.mautic.org/#button)
Inserts a HTML button. User can define text, URL as well as padding, size and position.
#### Text[](https://developer.mautic.org/#text)
Inserts a new text slot which you can edit with a HTML editor, so you can insert even media like images and videos in it.
#### Separator[](https://developer.mautic.org/#separator)
Inserts a horizontal line to separate content.
### Slot containers[](https://developer.mautic.org/#slot-containers)
As stated before, users can drag & drop the new slots into the theme. So as a theme developer, you have to define where the user can drop the slots. You can do it again with a single HTML attribute `data-slot-container="1"`.
Example:
```
<div data-slot-container="1">
    <div data-slot="text">
        <a>@JaneDoe</a> has invited you to join Awesome inc!
    </div>
</div>

```

This way the builder will let users drop the new slots into this container. In the example above there is already one predefined slot which user can move to another container, remove or edit.
This functionality will provide you with lots of creative freedom for designing and developing your own unique email and landing pages. Have a unique design? Share it with the community! We would love to see how you’re using Mautic to engage your audience.
## Sections[](https://developer.mautic.org/#sections)
Sections are full width parts of the theme which can let user to change the background color in the section wrapper (full monitor width) and in the section content itself. Since Mautic 2.7.0 it’s possible to move the sections up or down, delete the sections and even create a new ones with layout of 1,2 or 3 columns.
### Section[](https://developer.mautic.org/#section)
The section holds the content. It should be centered and should have fixed width. This fixed width should be consistent with all other sections. Section also wraps the content. The section can be any block HTML element with attribute `data-section="1"`.
Example:
```
<div data-section="1">
    <div data-slot-container="1">
        <div data-slot="text">
            <a>@JaneDoe</a> has invited you to join Awesome inc!
        </div>
    </div>
</div>

```

### Section Wrapper[](https://developer.mautic.org/#section-wrapper)
Section wrapper must have 100% width of the browser window. You thus have to split your theme into several “rows” if you want to enable the users to change the background of each section. The section wrapper can be any block HTML element with attribute `data-section-wrapper="1"`.
Example:
```
<div data-section-wrapper="1">
    <div data-section="1">
      <div data-slot-container="1">
          <div data-slot="text">
              <a>@JaneDoe</a> has invited you to join Awesome inc!
          </div>
      </div>
    </div>
</div>

```

## Theme HTML Files[](https://developer.mautic.org/#theme-html-files)
Notice that in the directory structure above, there is a base.html.twig file. This is not necessary but used in the example to define the base HTML document which each some of the following files extend.
### email.html.twig[](https://developer.mautic.org/#email.html.twig)
```
{# themes/HelloBundle/html/email.html.twig #} 
<html>
    <head>
        <title>{subject}</title>
    </head>
    <body style="margin:0">
        <div data-section-wrapper="1">
            <center>
                <table data-section="1" style="width: 600;" width="600" cellpadding="0" cellspacing="0">
                    <tbody>
                        <tr>
                            <td>
                                <div data-slot-container="1" style="min-height: 30px">
                                    <div data-slot="text">
                                        <br>
                                        <h2>Hello there!</h2>
                                        <br>
                                        We haven't heard from you for a while...
                                        <br>
                                        <br>
                                        {unsubscribe_text} | {webview_text}
                                        <br>
                                    </div>
                                </div>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </center>
        </div>
    </body>
</html>


```

This file defines the document for building an email template. Of course this file should follow html based email etiquette. Throughout the document should be output for the slots defined as data attributes.
### form.html.twig[](https://developer.mautic.org/#form.html.twig)
```
{# themes/thellotheme/html/form.html.twig #} 

{% extends ":"~template~":base.html.twig" %}

{% block content %}
    {% if message is defined %}
        <div>
            <h2>{{ message|raw }}</h2>
        </div>
    {% endif %}

    <div>
        {% if header is defined %}
        <h4>{{ header }}</h4>
        {% endif %}
        {{ content|raw }}
    </div>
{% endblock %}

```

This file generates the html document for a form when viewed via it’s public URL. This does not style the fields of a form. That will be described below. 
Each form.html.twig file should output a `message`, `header`, and `content` variables. 
#### Customizing the Form[](https://developer.mautic.org/#customizing-the-form)
To provide custom form field templates or to manipulate the form body, create the following directory structure:
themes/HelloWorld/  
- - - html/   
- - - - - - MauticFormBundle  
- - - - - - - - - Builder <– for customizing the form structure itself  
- - - - - - - - - Field <– for customizing form field types  

Copy from `app/bundles/FormBundle/Views/Builder/form.html.php` in the theme’s Builder directory or one or more of the fields templates in `app/bundles/FormBundle/Views/Field/*.html.php` into the theme’s Field directory. Then customize to the desired layout. Note that these must be PHP templates.
#### Styling the embedded forms[](https://developer.mautic.org/#styling-the-embedded-forms)
The embedded forms can be styled by the `themes/{your theme name}/html/MauticFormBundle/Builder/style.html.twig` file. The best way is to copy the content of the 
### message.html.twig[](https://developer.mautic.org/#message.html.twig)
```
{# themes/hellotheme/html/message.html.twig #}

{% extends ":"~template~":base.html.twig" %}

{% block content %}
    <div>
        <h2>{{ message|raw }}</h2>
        {% if content is defined %}
        <div>{{ content|raw }}</div>
        {% endif %}
    </div>
{% endblock %}

```

This file is a simple message file mainly used as the landing page for when a lead unsubscribes or resubscribes to the system’s emails. But may be used by other areas so should be included in all themes.
It requires echo'ing two variables: `message` and `content`. `message` houses the string message such as “You have been unsubscribed…” `content` will either be empty or house the HTML of a form that’s been associated with the email as an “unsubscribe form.” 
### page.html.twig[](https://developer.mautic.org/#page.html.twig)
```
{# themes/hellotheme/html/message.html.twig #}
{% extends ":"~template~":base.html.twig" %}

{% block content %}
<!DOCTYPE html>
<html>
    <head>
        {% if page is defined %}
        <title>{pagetitle}</title>
        <meta name="description" content="{pagemetadescription}">
        {% endif %}
        {{ outputHeadDeclarations() }}
    </head>
    <body>
        {{ outputScripts('bodyOpen') }}
        {% block content %}{% endblock %}
        {{ outputScripts('bodyClose') }}
    </body>
</html>
{% endblock %}

```

page.html.twig is exactly the same as email.html.twig except that it’ll be used for landing pages instead. Thus, it can be more robust with the HTML document.
# REST API[](https://developer.mautic.org/#rest-api)
Mautic provides a REST API to manipulate leads and/or obtain information for various entities of Mautic. 
All Mautic API endpoints require an OAuth1a signtature or OAuth2 access token. 
## Error Handling[](https://developer.mautic.org/#error-handling)
If an OAuth error is encountered, it’ll be a JSON encoded array similar to:
```
{
  "error": "invalid_grant",
  "error_description": "The access token provided has expired."
}

```

If a system error encountered, it’ll be a JSON encoded array similar to:
```
{
    "error": {
        "message": "You do not have access to the requested area/action.",
        "code": 403
    }
}

```

## Mautic version check[](https://developer.mautic.org/#mautic-version-check)
In case your API service wants to support several Mautic versions with different features, you might need to check the version of Mautic you communicate with. Since Mautic 2.4.0 the version number is added to all API response headers. The header name is `Mautic-Version`. With Mautic PHP API library you can get the Mautic version like this:
```
// Make any API request:
$api = $this->getContext('contacts');
$response = $api->getList('', 0, 1);

// Get the version number from the response header:
$version = $api->getMauticVersion();

```

`$version` will be in a semantic versioning format: `[major].[minor].[patch]`. For example: `2.4.0`. If you’ll try it on the latest GitHub version, the version will have `-dev` at the end. Like `2.5.1-dev`.
## Authorization[](https://developer.mautic.org/#authorization)
Mautic uses OAuth or Basic Authentication (as of Mautic 2.3.0) for API authorization. It supports both 
The Mautic administrator should enable the API in the Configuration -> API Settings. This will add the “API Credentials” to the admin menu. A client/consumer ID and secret should then be generated which will be used in the following processes. 
All authorization requests should be made to the specific Mautic instances URL, i.e. `https://your-mautic.com`.
The OAuth processes can be a pain. If possible, it’s best to use an OAuth library for the language being used. If PHP, it is recommended that Mautic’s [PHP library](https://developer.mautic.org/#php-library) be used. 
### OAuth 1a[](https://developer.mautic.org/#oauth-1a)
```
<?php
use Mautic\Auth\ApiAuth;

// $initAuth->newAuth() will accept an array of OAuth settings
$settings = array(
    'baseUrl'      => 'https://your-mautic.com',
    'version'      => 'OAuth1a',
    'clientKey'    => '5ad6fa7asfs8fa7sdfa6sfas5fas6asdf8',
    'clientSecret' => 'adf8asf7sf54asf3as4f5sf6asfasf97dd', 
    'callback'     => 'https://your-callback.com'
);

// Initiate the auth object
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);

// Initiate process for obtaining an access token; this will redirect the user to the authorize endpoint and/or set the tokens when the user is redirected back after granting authorization

if ($auth->validateAccessToken()) {
    if ($auth->accessTokenUpdated()) {
        $accessTokenData = $auth->getAccessTokenData();

        //store access token data however you want
    }
}

```

The OAuth 1a method is recommended for servers that are not behind https. Note that OAuth 1a access tokens do not expire. 
OAuth 1a can be a complicated method due to the need to generate a signature for the request. If anything is off with the signature, the request will not be validated.
#### Authorization[](https://developer.mautic.org/#authorization)
##### Step One - Obtain a Request Token[](https://developer.mautic.org/#step-one---obtain-a-request-token)
The first step is to obtain a request token that will be used when directing the user to the authorization page. 
Make a POST to the request token endpoint `/oauth/v1/request_token`:
```
POST /oauth/v1/request_token
Authorization: 
        OAuth oauth_callback="https%3A%2F%2Fyour-callback-uri.com",
              oauth_consumer_key="CONSUMER_KEY",
              oauth_nonce="UNIQUE_STRING",
              oauth_signature="GENERATED_REQUEST_SIGNATURE",
              oauth_signature_method="HMAC-SHA1",
              oauth_timestamp="1318467427",
              oauth_version="1.0"

```

(note that the header has been wrapped for legibility)
Review [Generating the Authorization Header](https://developer.mautic.org/#generating-the-authorization-header) on the specifics of generating the OAuth header.
The response will be a query string:
```
oauth_token=REQUEST_TOKEN&oauth_token_secret=REQUEST_TOKEN_SECRET&oauth_expires_in=3600

```

Parse the string and use the parameters in the next step as indicated. 
These must be preserved in some kind of persistent storage as they will be used when obtaining the access token. 
Note that the refresh token is only good for the number of seconds specified in `oauth_expires_in`. 
##### Step Two - Authorization[](https://developer.mautic.org/#step-two---authorization)
Now redirect the user to the authorization endpoint `oauth/v1/authorize` with the request token as part of the URL’s query.
If the callback is something different than what is configured in Mautic, url encode it and include in the query as `oauth_callback`.
```
/oauth/v1/authorize?oauth_token=REQUEST_TOKEN&oauth_callback=https%3A%2F%2Fyour-callback-uri.com

```

The user will login and Mautic will redirect back to the either the consumer’s configured callback or to the `oauth_callback` included in the query.
The callback will include `oauth_token` and `oauth_verifier` in the URL’s query. 
Compare the `oauth_token` in the query with that obtained in step two to ensure they are the same and prevent cross-site request forgery.
`oauth_verifier` will need to be part of the header generated in step three.
##### Step Three - Obtain an Access Token[](https://developer.mautic.org/#step-three---obtain-an-access-token)
[Generate the Authorization header](https://developer.mautic.org/#generating-the-authorization-header) and make a POST to the access token endpoint `/oauth/v1/access_token`.
When generating the header, the `oauth_token_secret` returned in step two should be used as the `TOKEN_SECRET` in the composite key. 
`oauth_verifier` from step two should be part of the Authorization header generated.
```
POST /oauth/v1/access_token
Authorization: 
        OAuth oauth_callback="https%3A%2F%2Fyour-callback-uri.com",
              oauth_consumer_key="CONSUMER_KEY",
              oauth_nonce="UNIQUE_STRING",
              oauth_signature="GENERATED_REQUEST_SIGNATURE",
              oauth_signature_method="HMAC-SHA1",
              oauth_timestamp="1318467427",
              oauth_verifier="OAUTH_VERIFIER_FROM_STEP_TWO"
              oauth_version="1.0"

```

(note that the header has been wrapped for legibility)
The response should include a query string with the access token:
```
oauth_token=ACCESS_TOKEN&oauth_token_secret=ACCESS_TOKEN_SECRET

```
Mautic’s OAuth 1a access tokens do not expire but the user can deauthorize them. If the access token is invalid, a `401` response will be returned. 
The `oauth_token` can be included in the authorize header and the `oauth_token_secret` should be used as the `TOKEN_SECRET` in the composite key when signing API requests.
#### Generating the Authorization Header[](https://developer.mautic.org/#generating-the-authorization-header)
The OAuth header may include the following parameters:
Key | Description  
---|---  
oauth_callback | Optional, URL encoded callback to redirect the user to after authorization. If the callback URL is set in Mautic, this must match.  
oauth_consumer_key | The consumer key obtained from Mautic’s API Credentials  
oauth_nonce | Uniquely generated string that should be used only once  
oauth_signature | Signature generated from all applicable data for the request  
oauth_signature_method | Method for creating the signature. Currently, only `HMAC-SHA1` is supported.  
oauth_timestamp | Current unix timestamp  
oauth_token | The access token  
oauth_verifier | Returned after authorization and used when requesting an access token  
oauth_version | Should always be `1.0`  
When making a GET or POST request with parameters, all parameters should be included in the header as well. 
##### Step One - Build the Base String[](https://developer.mautic.org/#step-one---build-the-base-string)
The base string is used to generate the oauth_signature. 
The structure of the base string is as follows:
```
METHOD&URL_ENCODED_URI&NORMALIZED_PARAMETERS

```

`METHOD` should be the request method and should always be capitalized.
`URL_ENCODED_URI` should be the base URI the request is made to. It should not include any query parameters (query parameters should be part of `NORMALIZED_PARAMETERS`).
`NORMALIZED_PARAMETERS` should be a url encoded, alphabetically sorted query string of the above oauth parameters (except `oauth_signature`) plus the parameters of the request (query/post body). 
Each key and each value of the parameters must be url encoded individually as well. 
PHP should use `rawurlencode()` instead of `urlencode()`. 
Then each url encoded key/value pair should be concatenated into a single string with an ampersand (&) as the glue character.
For example, let’s say a request includes a query of `title=Mr&firstname=Joe&lastname=Smith`. The process would look something like the following (replacing `urlencode()` with whatever function is appropriate for the language being used). Of course realistically, natural sort and loop functions would be used.
```
urlencode(
    urlencode(firstname)=urlencode(Joe)
    &urlencode(lastname)=urlencode(smith)
    &urlencode(oauth_callback)=urlencode(https%3A%2F%2Fyour-callback-uri.com)
    &urlencode(oauth_consumer_key)=urlencode(kdjafs7fsdf86ads7a98a87df6ad9fsf98ad7f)
    &urlencode(oauth_nonce)=urlencode(ak877asdf6adf68asd9fas)
    &urlencode(oauth_signature_method)=urlencode(HMAC-SHA1)
    &urlencode(oauth_timestamp)=urlencode(1437604736)
    &urlencode(oauth_version)=urlencode(1.0)
    &urlencode(title)=urlencode(Mr)
)

```
Multidimensional arrays should use `foo=baz&foo=bar` rather than `foo[bar]=baz&foo[baz]=bar` when generating the normalized parameters string.  Notice that `oauth_callback`, if included, is DOUBLE url encoded. 
Put all together, a base string might look like:
```
GET&http%3A%2F%2Fyour-mautic.com%2Fapi&firstname%3DJoe%26lastName%3DSmith%26oauth_callback%3Dhttps%253A%252F%252Fyour-callback-uri.com%26oauth_consumer_key%3Dkdjafs7fsdf86ads7a98a87df6ad9fsf98ad7f%26oauth_nonce%3Dak877asdf6adf68asd9fas%26oauth_signature_method%3DHMAC-SHA1%26oauth_timestamp%3D1437604736%26oauth_version%3D1.0%26title%3DMr

```

##### Step Two - Build the Composite Key[](https://developer.mautic.org/#step-two---build-the-composite-key)
The composite key is used to encrypt the base string. It is composed of the consumer secret and the token secret if available (post authorization) combined with an ampersand (&). 
```
CLIENT_SECRET&TOKEN_SECRET

```

If the token secret is not available, i.e. during the request token process, then an ampersand (&) should still be used.
```
 CLIENT_SECRET&
 
```
`TOKEN_SECRET` Sources  
For `/oauth/v1/request_token`, `TOKEN_SECRET` is empty.  
  
For `/oauth/v1/access_token`, `TOKEN_SECRET` will be the `oauth_token_secret` returned by the request to `/oauth/v1/request_token`  
  
For all other API endpoints, `TOKEN_SECRET` will be the `oauth_token_secret` returned by the request to `/oauth/v1/access_token`
##### Step Three - Generate the Signature[](https://developer.mautic.org/#step-three---generate-the-signature)
Now, using the base string and the composite key, the signature can be generated using the appropriate HMAC function available to the language used. The signature generated should then be base64 encoded prior to being used in the Authorization header.
```
 base64_encode(
    hmac_sha1(BASE_STRING, COMPOSITE_KEY)
 )
 
```

The resulting string should then be used included in the header as `oauth_signature`.
#### Signing the API Request[](https://developer.mautic.org/#signing-the-api-request)
To sign the API request, [generate the Authorization header](https://developer.mautic.org/#generating-the-authorization-header) using the obtained access token.
```
POST /api/leads/new
Authorization: 
        OAuth oauth_callback="https%3A%2F%2Fyour-callback-uri.com",
              oauth_consumer_key="CONSUMER_KEY",
              oauth_nonce="UNIQUE_STRING",
              oauth_signature="GENERATED_REQUEST_SIGNATURE",
              oauth_signature_method="HMAC-SHA1",
              oauth_timestamp="1318467427",
              oauth_token="ACCESS_TOKEN"
              oauth_version="1.0"
              
title=Mr&firstname=Joe&lastname=Smith

```

(note that the header has been wrapped for legibility)
### OAuth 2[](https://developer.mautic.org/#oauth-2)
```
<?php
use Mautic\Auth\ApiAuth;

// $initAuth->newAuth() will accept an array of OAuth settings
$settings = array(
    'baseUrl'      => 'https://your-mautic.com',
    'version'      => 'OAuth2',
    'clientKey'    => '5ad6fa7asfs8fa7sdfa6sfas5fas6asdf8',
    'clientSecret' => 'adf8asf7sf54asf3as4f5sf6asfasf97dd', 
    'callback'     => 'https://your-callback.com'
);

// Initiate the auth object
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);

// Initiate process for obtaining an access token; this will redirect the user to the authorize endpoint and/or set the tokens when the user is redirected back after granting authorization

if ($auth->validateAccessToken()) {
    if ($auth->accessTokenUpdated()) {
        $accessTokenData = $auth->getAccessTokenData();

        //store access token data however you want
    }
}

```
Mautic supports only the authorization_code, refresh_token and client_credentials grant types. 
#### Authorization[](https://developer.mautic.org/#authorization)
##### Step One - Obtain Authorization Code[](https://developer.mautic.org/#step-one---obtain-authorization-code)
Redirect the user to the authorize endpoint `oauth/v2/authorize`:
```
GET /oauth/v2/authorize?
    client_id=CLIENT_ID
    &grant_type=authorization_code
    &redirect_uri=https%3A%2F%2Fyour-redirect-uri.com%2Fcallback
    &response_type=code
    &state=UNIQUE_STATE_STRING

```

(note that the query has been wrapped for legibility)
The state is optional but recommended to prevent CSRF attacks. It should be a uniquely generated string and stored locally in session, cookie, etc. to be compared with the returned value.  Note that the redirect_uri should be URL encoded.  As of 1.1.2, Mautic does not leverage OAuth2 scopes. 
The user will be prompted to login. Once they do, Mautic will redirect back to the URL specified in redirect_uri with a code appended to the query.
It may look something like: `https://your-redirect-uri.com?code=UNIQUE_CODE_STRING&state=UNIQUE_STATE_STRING`
The state returned should be compared against the original to ensure nothing has been tampered with. 
##### Step Two - Replace with an Access Token[](https://developer.mautic.org/#step-two---replace-with-an-access-token)
Obtain the value of the code from Step One then immediately POST it back to the access token endpoint `oauth/v2/token` with:
```
POST /oauth/v2/token

client_id=CLIENT_ID
    &client_secret=CLIENT_SECRET
    &grant_type=authorization_code
    &redirect_uri=https%3A%2F%2Fyour-redirect-uri.com%2Fcallback
    &code=UNIQUE_CODE_STRING

```

(note that the post body has been wrapped for legibility)
The response returned should be a JSON encoded string:
```
    {
        access_token: "ACCESS_TOKEN",
        expires_in: 3600,
        token_type: "bearer",
        scope: "",
        refresh_token: "REFRESH_TOKEN"
    }

```

This data should be stored in a secure location and used to authenticate API requests.
#### Refresh Tokens[](https://developer.mautic.org/#refresh-tokens)
The response’s `expires_in` is the number of seconds the access token is good for and may differ based on what is configured in Mautic. The code handling the authorization process should generate an expiration timestamp based on that value. For example `<?php $expiration = time() + $response['expires_in']; ?>`. If the access token has expired, the refresh_token should be used to obtain a new access token.
By default, the refresh token is valid for 14 days. - If your application requests a new access token using the refresh token within 14 days, no user interaction is needed. Your application gets both a new access token and a new refresh token (which is valid for another 14 days after it’s issued); - If your application does not request a new token using the refresh token within 14 days, user interaction is required in order to get new tokens.
The refresh token’s expiration time is configurable through Mautic’s Configuration. 
The application should monitor for a `400 Bad Response` response when requesting a new access token and redirect the user back through the authorization process. 
To obtain a new access token, a POST should be made to the access token’s endpoint `oauth/v2/token` using the `refresh_token` grant type.
```
POST /oauth/v2/token
    
client_id=CLIENT_ID
    &client_secret=CLIENT_SECRET
    &grant_type=refresh_token
    &refresh_token=REFRESH_TOKEN
    &redirect_uri=https%3A%2F%2Fyour-redirect-uri.com%2Fcallback

```

(note that the post body has been wrapped for legibility)
The response returned should be a JSON encoded string:
```
    {
        access_token: "NEW_ACCESS_TOKEN",
        expires_in: 3600,
        token_type: "bearer",
        scope: "",
        refresh_token: "REFRESH_TOKEN"
    }

```

#### Client Credentials[](https://developer.mautic.org/#client-credentials)
The Client Credentials grant is used when applications request an access token to access their own resources, not on behalf of a user.
To obtain a new access token, a POST should be made to the access token’s endpoint `oauth/v2/token` using the `client_credentials` grant type.
```
POST /oauth/v2/token
    
client_id=CLIENT_ID
    &client_secret=CLIENT_SECRET
    &grant_type=client_credentials

```

(note that the post body has been wrapped for legibility)
The response returned should be a JSON encoded string:
```
    {
        access_token: "NEW_ACCESS_TOKEN",
        expires_in: 3600,
        token_type: "bearer",
        scope: ""
    }

```

#### Authenticating the API Request[](https://developer.mautic.org/#authenticating-the-api-request)
Authenticating the API request with OAuth2 is easy. Choose one of the following methods that is appropriate for the application’s needs.
##### Authorization Header[](https://developer.mautic.org/#authorization-header)
By using an authorization header, any request method can be authenticated.
However, note that this method requires that the server Mautic is installed on passes headers to PHP or has access to the `apache_request_headers()` function. `apache_request_headers()` is not available to PHP running under fcgi. 
```
Authorization: Bearer ACCESS_TOKEN

```

##### Method Specific[](https://developer.mautic.org/#method-specific)
The access token can also be appended to the query or included in the body of a POST.
```
GET https://your-mautic.com/api/leads?access_token=ACCESS_TOKEN

```
```
POST https://your-mautic.com/api/leads/new

firstname=John&lastname=Smith&access_token=ACCESS_TOKEN

```

### Basic Authentication[](https://developer.mautic.org/#basic-authentication)
As of Mautic 2.3.0, support for basic authentication can be enabled through Mautic’s Configuration -> API Settings. As with OAuth2, it is only recommended to use basic authentication over HTTPS.
To authorize a request for basic authentication, set an `Authorization` header. 
  1. Combine the username and password of a Mautic user with a colon `:`. For example, `user:password`.
  2. Base64 encode the string from above. `dXNlcjpwYXNzd29yZA==`.
  3. Add an Authorization header to each API request as `Authorization: Basic dXNlcjpwYXNzd29yZA==`


## API Rate limiter[](https://developer.mautic.org/#api-rate-limiter)
You can configure rate limiter cache in local.php By default, filesystem is used as: `php api_rate_limiter_cache => [      'type'      => 'file_system', ],  `
You can configure memcached server: `php 'api_rate_limiter_cache' => [     'memcached' => [       'servers' =>         [           [             'host' => 'localhost',             'port' => 11211           ]         ]     ]   ], `
Or whatever cache you want described in 
## Libraries[](https://developer.mautic.org/#libraries)
### PHP Library[](https://developer.mautic.org/#php-library)
Mautic provides a 
#### Install via Composer[](https://developer.mautic.org/#install-via-composer)
To install using composer, simply run `composer require mautic/api-library`.
#### Install Manually[](https://developer.mautic.org/#install-manually)
```
require_once __DIR__ . '/lib/Mautic/MauticApi.php';

```
Refer to the README in the Github repository for further instructions on how to use the library or review the code examples included throughout this section. 
## Endpoints[](https://developer.mautic.org/#endpoints)
All responses are JSON encoded.  Base API Endpoint:   
`https://your-mautic.com/api`
## Assets[](https://developer.mautic.org/#assets)
Use this endpoint to obtain details on Mautic’s assets. 
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$assetApi = $api->newApi("assets", $auth, $apiUrl);


```

### Get Asset[](https://developer.mautic.org/#get-asset)
```
<?php

//...
$asset = $assetApi->get($id);

```
```
{"asset":{"id":1,"title":"Product Whitepaper","description":"Some description","alias":"whitepaper","language":"en","isPublished":true,"publishUp":"2015-06-07T06:28:27+00:00","publishDown":"2015-06-30T06:28:27+00:00","dateAdded":"2015-06-07T06:28:27+00:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-06-010T09:30:47+00:00","modifiedBy":1,"modifiedByUser":"Joe Smith","downloadCount":10,"uniqueDownloadCount":8,"revision":1,"category":{"createdByUser":"John Doe","modifiedByUser":"John Doe","id":19,"title":"test","alias":"test","description":null,"color":null,"bundle":"asset"},"extension":"pdf","mime":"application/pdf","size":269128,"downloadUrl":"https://your-mautic.com/asset/1:whitepaper"}}
```

Get an individual asset by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /assets/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Asset Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the asset  
title | string | Title/name of the asset  
description | string/null | Description of the asset  
alias | string | Used to generate the URL for the asset  
language | string | Locale of the asset  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the asset should be published  
publishDown | datetime/null | Date/time the asset should be un published  
dateAdded | datetime | Date/time asset was created  
createdBy | int | ID of the user that created the asset  
createdByUser | string | Name of the user that created the asset  
dateModified | datetime/null | Date/time asset was last modified  
modifiedBy | int | ID of the user that last modified the asset  
modifiedByUser | string | Name of the user that last modified the asset  
downloadCount | int | Total number of downloads  
uniqueDownloadCount | int | Unique number of downloads  
revision | int | Revision version  
category | object/null | Object with the category details  
extension | string | Extension of the asset  
mime | string | Mime type of the asset  
size | int | Filesize of the asset in bytes  
downloadUrl | string | Public download URL for the asset  
### List Assets[](https://developer.mautic.org/#list-assets)
```
<?php
// ...

$assets = $assetApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"assets":[{"id":1,"title":"Product Whitepaper","description":"Some description","alias":"whitepaper","language":"en","isPublished":true,"publishUp":"2015-06-07T06:28:27+00:00","publishDown":"2015-06-30T06:28:27+00:00","dateAdded":"2015-06-07T06:28:27+00:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-06-010T09:30:47+00:00","modifiedBy":1,"modifiedByUser":"Joe Smith","downloadCount":10,"uniqueDownloadCount":8,"revision":1,"category":null,"extension":"pdf","mime":"application/pdf","size":269128,"downloadUrl":"https://your-mautic.com/asset/1:whitepaper"}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /assets`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Asset](https://developer.mautic.org/#get-asset).
### Create Asset[](https://developer.mautic.org/#create-asset)
```
<?php 

/**
 * Local asset example
 */
// Upload a local file first
$apiContextFiles = $this->getContext('files');
$apiContextFiles->setFolder('assets');
$fileRequest = array(
    'file' => dirname(__DIR__).'/'.'mauticlogo.png'
);
$response = $apiContextFiles->create($fileRequest);

$data = array(
    'title' => 'Mautic Logo sent as a API request',
    'storageLocation' => 'local',
    'file' => $response['file']['name']
);

$asset = $assetApi->create($data);


/**
 * Remote asset example
 */
$data = array(
    'title' => 'PDF sent as a API request',
    'storageLocation' => 'remote',
    'file' => 'https://www.mautic.org/media/logos/logo/Mautic_Logo_DB.pdf'
);

$asset = $assetApi->create($data);


```

Create a new asset. There are 2 options: local or remote asset.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /assets/new`
**Post Parameters**
Name | Description  
---|---  
title | string  
storageLocation | string  
file | string  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Asset](https://developer.mautic.org/#get-asset).
### Edit Asset[](https://developer.mautic.org/#edit-asset)
```
<?php

$id   = 1;
$data = array(
    'type' => 'general',
);

// Create new a asset of ID 1 is not found?
$createIfNotFound = true;

$asset = $assetApi->edit($id, $data, $createIfNotFound);

```

Edit a new asset. Asset that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a asset if the given ID does not exist and clears all the asset information, adds the information from the request. **PATCH** fails if the asset with the given ID does not exist and updates the asset field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a asset and return a 404 if the asset is not found:
`PATCH /assets/ID/edit`
To edit a asset and create a new one if the asset is not found:
`PUT /assets/ID/edit`
**Post Parameters**
Name | Description  
---|---  
title | string  
storageLocation | string  
file | string  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the asset was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Asset](https://developer.mautic.org/#get-asset).
### Delete Asset[](https://developer.mautic.org/#delete-asset)
```
<?php

$asset = $assetApi->delete($id);

```

Delete a asset. In case of local storage location, the local file will be deleted as well.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /assets/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Asset](https://developer.mautic.org/#get-asset).
## Campaigns[](https://developer.mautic.org/#campaigns)
Use this endpoint to obtain details on Mautic’s campaigns.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth    = new ApiAuth();
$auth        = $initAuth->newAuth($settings);
$apiUrl      = "https://your-mautic.com";
$api         = new MauticApi();
$campaignApi = $api->newApi("campaigns", $auth, $apiUrl);

```

### Get Campaign[](https://developer.mautic.org/#get-campaign)
```
<?php

//...
$campaign = $campaignApi->get($id);

```
```
{"campaign":{"id":3,"name":"Email A/B Test","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"events":{"28":{"id":28,"type":"lead.changepoints","eventType":"action","name":"Adjust lead points","description":null,"order":1,"properties":{"points":20},"triggerDate":null,"triggerInterval":1,"triggerIntervalUnit":"d","triggerMode":"immediate","children":[],"parent":null,"decisionPath":null}}}}
```

Get an individual campaign by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /campaigns/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Campaign Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the campaign  
name | string | Name of the campaign  
description | string/null | Description of the campaign  
alias | string | Used to generate the URL for the campaign  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the campaign should be published  
publishDown | datetime/null | Date/time the campaign should be un published  
dateAdded | datetime | Date/time campaign was created  
createdBy | int | ID of the user that created the campaign  
createdByUser | string | Name of the user that created the campaign  
dateModified | datetime/null | Date/time campaign was last modified  
modifiedBy | int | ID of the user that last modified the campaign  
modifiedByUser | string | Name of the user that last modified the campaign  
events | array | Array of Event entities for the campaign. See below.  
**Event Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the event  
name | string | Name of the event  
description | string | Optional description for the event  
type | string | Type of event  
eventType | string | “action” or “decision”  
order | int | Order in relation to the other events (used for levels)  
properties | object | Configured properties for the event  
triggerMode | string | “immediate”, “interval” or “date”  
triggerDate | datetime/null | Date/time of when the event should trigger if triggerMode is “date”  
triggerInterval | int/null | Interval for when the event should trigger  
triggerIntervalUnit | string | Interval unit for when the event should trigger. Options are i = minutes, h = hours, d = days, m = months, y = years  
children | array | Array of this event’s children ,  
parent | object/null | This event’s parent  
decisionPath | string/null | If the event is connected into an action, this will be “no” for the non-decision path or “yes” for the actively followed path.  
### List Campaigns[](https://developer.mautic.org/#list-campaigns)
```
<?php
// ...

$campaigns = $campaignApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"campaigns":{"3":{"id":3,"name":"Welcome Campaign","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"events":{"22":{"id":22,"type":"email.send","eventType":"action","name":"Send welcome email","description":null,"order":1,"properties":{"email":1},"triggerMode":"immediate","triggerDate":null,"triggerInterval":null,"triggerIntervalUnit":null,"children":[],"parent":null,"decisionPath":null},"28":{"id":28,"type":"lead.changepoints","eventType":"action","name":"Adjust lead points","description":null,"order":2,"properties":{"points":20},"triggerMode":"immediate","triggerDate":null,"triggerInterval":null,"triggerIntervalUnit":null,"children":[],"parent":null,"decisionPath":null}}}}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /campaigns`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
published | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Campaign](https://developer.mautic.org/#get-campaign).
### List Campaign Contacts[](https://developer.mautic.org/#list-campaign-contacts)
This endpoint is basically an alias for the stats endpoint with ‘campaign_leads’ table and campaign_id specified. Other parameters are the same as in the stats endpoint.
```
<?php
// ...

$response = $campaignApi->getContacts($campaignId, $start, $limit, $order, $where);

```
```
{"total":"1","contacts":[{"campaign_id":"311","lead_id":"3126","date_added":"2017-01-25 15:11:10","manually_removed":"0","manually_added":"1"}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /campaigns/ID/contacts`
**Query Parameters**
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Create Campaign[](https://developer.mautic.org/#create-campaign)
```
<?php

$data = array(
    'name'        => 'Campaign A',
    'description' => 'This is my first campaign created via API.',
    'isPublished' => 1
);

$campaign = $campaignApi->create($data);

```

Create a new campaign. To see more advanced example with campaing events and so on, see the unit tests.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /campaigns/new`
**Post Parameters**
Name | Description  
---|---  
name | Campaign name is the only required field  
alias | string  
description | A description of the campaign.  
isPublished | A value of 0 or 1  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Campaign](https://developer.mautic.org/#get-campaign).
### Clone A Campaign[](https://developer.mautic.org/#clone-a-campaign)
```
<?php

$camnpaignId = 12;

$campaign = $campaignApi->cloneCampaign($campaignId);

```

Clone an existing campaign. To see more advanced example with campaign events and so on, see the unit tests.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /campaigns/clone/CAMPAIGN_ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Campaign](https://developer.mautic.org/#get-campaign).
### Edit Campaign[](https://developer.mautic.org/#edit-campaign)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New campaign name',
    'isPublished' => 0
);

// Create new a campaign of ID 1 is not found?
$createIfNotFound = true;

$campaign = $campaignApi->edit($id, $data, $createIfNotFound);

```

Edit a new campaign. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a campaign if the given ID does not exist and clears all the campaign information, adds the information from the request. **PATCH** fails if the campaign with the given ID does not exist and updates the campaign field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a campaign and return a 404 if the campaign is not found:
`PATCH /campaigns/ID/edit`
To edit a campaign and create a new one if the campaign is not found:
`PUT /campaigns/ID/edit`
**Post Parameters**
Name | Description  
---|---  
name | Campaign name is the only required field  
alias | Name alias generated automatically if not set  
description | A description of the campaign.  
isPublished | A value of 0 or 1  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the campaign was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Campaign](https://developer.mautic.org/#get-campaign).
### Delete Campaign[](https://developer.mautic.org/#delete-campaign)
```
<?php

$campaign = $campaignApi->delete($id);

```

Delete a campaign.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /campaigns/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Campaign](https://developer.mautic.org/#get-campaign).
### Add Contact to a Campaign[](https://developer.mautic.org/#add-contact-to-a-campaign)
```
<?php

//...
$response = $campaignApi->addContact($campaignId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually add a contact to a specific campaign.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /campaigns/CAMPAIGN_ID/contact/CONTACT_ID/add`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Remove Contact from a Campaign[](https://developer.mautic.org/#remove-contact-from-a-campaign)
```
<?php

//...
$response = $listApi->removeContact($campaignId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually remove a contact from a specific campaign.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /campaigns/CAMPAIGN_ID/contact/CONTACT_ID/remove`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
## Categories[](https://developer.mautic.org/#categories)
Use this endpoint to obtain details on Mautic’s categories or to manipulate category memberships.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth    = new ApiAuth();
$auth        = $initAuth->newAuth($settings);
$apiUrl      = "https://your-mautic.com";
$api         = new MauticApi();
$categoryApi = $api->newApi("categories", $auth, $apiUrl);

```

### Get Category[](https://developer.mautic.org/#get-category)
```
<?php

//...
$category = $categoryApi->get($id);

```
```
{"category":{"id":221,"title":"test","alias":"test4","description":null,"color":null,"bundle":"asset"}}
```

Get an individual category by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /categories/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Category Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the category  
isPublished | boolean | Whether the category is published  
dateAdded | datetime | Date/time category was created  
createdBy | int | ID of the user that created the category  
createdByUser | string | Name of the user that created the category  
dateModified | datetime/null | Date/time category was last modified  
modifiedBy | int | ID of the user that last modified the category  
modifiedByUser | string | Name of the user that last modified the category  
title | string | The category title  
alias | string | The category alias  
description | string | The category description  
color | string | The category color  
bundle | string | The bundle where the category will be available  
### List Contact Categories[](https://developer.mautic.org/#list-contact-categories)
```
<?php

//...
$categories = $categoryApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":8,"categories":[{"id":1,"title":"Bold","alias":"bold","description":null,"color":"b36262","bundle":"point"},[...]]}
```

Returns a list of contact categories available to the user. This list is not filterable.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /categories`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Category Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the category  
isPublished | boolean | Whether the category is published  
dateAdded | datetime | Date/time category was created  
createdBy | int | ID of the user that created the category  
createdByUser | string | Name of the user that created the category  
dateModified | datetime/null | Date/time category was last modified  
modifiedBy | int | ID of the user that last modified the category  
modifiedByUser | string | Name of the user that last modified the category  
title | string | The category title  
alias | string | The category alias  
description | string | The category description  
color | string | The category color  
bundle | string | The bundle where the category will be available  
### Create Category[](https://developer.mautic.org/#create-category)
```
<?php 

$data = array(
    'categoryname' => 'test',
    'categoryemail' => 'test@category.com',
    'categorycity' => 'Raleigh',
);

$category = $categoryApi->create($data);

```

Create a new category.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /categories/new`
**Post Parameters**
Name | Description  
---|---  
title | string  
bundle | string  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Category](https://developer.mautic.org/#get-category).
### Edit Category[](https://developer.mautic.org/#edit-category)
```
<?php

$id   = 1;
$data = array(
    'title' => 'test',
    'bundle' => 'asset'
);

// Create new a category of ID 1 is not found?
$createIfNotFound = true;

$category = $categoryApi->edit($id, $data, $createIfNotFound);

```

Edit a new category. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a category if the given ID does not exist and clears all the category information, adds the information from the request. **PATCH** fails if the category with the given ID does not exist and updates the category field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a category and return a 404 if the category is not found:
`PATCH /categories/ID/edit`
To edit a category and create a new one if the category is not found:
`PUT /categories/ID/edit`
**Post Parameters**
Name | Description  
---|---  
title | string  
bundle | string  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the category was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Category](https://developer.mautic.org/#get-category).
### Delete Category[](https://developer.mautic.org/#delete-category)
```
<?php

$category = $categoryApi->delete($id);

```

Delete a category.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /categories/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Category](https://developer.mautic.org/#get-category).
### Assign a Category[](https://developer.mautic.org/#assign-a-category)
To assign a category to an entity simply set `category = [ID]` to the payload. For example this is how a category 123 can be asssigned to a new Asset:
```
$data = array(
    'title' => 'PDF sent as a API request',
    'storageLocation' => 'remote',
    'file' => 'https://www.mautic.org/media/logos/logo/Mautic_Logo_DB.pdf'
    'category' => 123
);

$asset = $assetApi->create($data);

```

The category must exist in the Mautic instance and the entity must support categories,
## Companies[](https://developer.mautic.org/#companies)
Use this endpoint to obtain details on Mautic’s companies or to manipulate contact-company memberships.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth   = new ApiAuth();
$auth       = $initAuth->newAuth($settings);
$apiUrl     = "https://your-mautic.com";
$api        = new MauticApi();
$companyApi = $api->newApi("companies", $auth, $apiUrl);

```

### Get Company[](https://developer.mautic.org/#get-company)
```
<?php

//...
$company = $companyApi->get($id);

```
```
{"company":{"isPublished":true,"dateAdded":"2016-10-25T09:46:36+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":176,"fields":{"core":{"companywebsite":{"id":"91","label":"Website","alias":"companywebsite","type":"url","group":"core","field_order":"8","object":"company","value":null},[...]},"professional":{"companyannual_revenue":{"id":"90","label":"Annual Revenue","alias":"companyannual_revenue","type":"number","group":"professional","field_order":"10","object":"company","value":null},[...]},"other":[],"all":{"companywebsite":null,"companycountry":null,"companyzipcode":null,"companystate":null,"companycity":"Raleigh","companyphone":null,"companyemail":"test@company.com","companyaddress2":null,"companyaddress1":null,"companyname":"test","companyannual_revenue":null,"companyfax":null,"companynumber_of_employees":null,"companydescription":null}}}}
```

Get an individual company by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /companies/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Company Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the company  
isPublished | boolean | Whether the company is published  
dateAdded | datetime | Date/time company was created  
createdBy | int | ID of the user that created the company  
createdByUser | string | Name of the user that created the company  
dateModified | datetime/null | Date/time company was last modified  
modifiedBy | int | ID of the user that last modified the company  
modifiedByUser | string | Name of the user that last modified the company  
fields | array | Custom fields for the company  
### List Contact Companies[](https://developer.mautic.org/#list-contact-companies)
```
<?php

//...
$companies = $companyApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":13,"companies":{"176":{"isPublished":true,"dateAdded":"2016-10-25T09:46:36+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":176,"fields":{"core":{"companywebsite":{"id":"91","label":"Website","alias":"companywebsite","type":"url","group":"core","field_order":"8","object":"company","value":null},[...]},"professional":{"companyannual_revenue":{"id":"90","label":"Annual Revenue","alias":"companyannual_revenue","type":"number","group":"professional","field_order":"10","object":"company","value":null},[...]},"other":[],"all":{"companywebsite":null,"companycountry":null,"companyzipcode":null,"companystate":null,"companycity":"Raleigh","companyphone":null,"companyemail":"test@company.com","companyaddress2":null,"companyaddress1":null,"companyname":"test","companyannual_revenue":null,"companyfax":null,"companynumber_of_employees":null,"companydescription":null}}},[...]}}
```

Returns a list of contact companies available to the user. This list is not filterable.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /companies`
** Query Parameters **
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Company Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the company  
isPublished | boolean | Whether the company is published  
dateAdded | datetime | Date/time company was created  
createdBy | int | ID of the user that created the company  
createdByUser | string | Name of the user that created the company  
dateModified | datetime/null | Date/time company was last modified  
modifiedBy | int | ID of the user that last modified the company  
modifiedByUser | string | Name of the user that last modified the company  
fields | array | Custom fields for the company  
### Create Company[](https://developer.mautic.org/#create-company)
```
<?php

$data = array(
    'companyname' => 'test',
    'companyemail' => 'test@company.com',
    'companycity' => 'Raleigh',
    'overwriteWithBlank' => true
);

$company = $companyApi->create($data);

```

Create a new company.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /companies/new`
**Post Parameters**
Name | Description  
---|---  
companyname | Company name is the only required field. Other company fields can be sent with a value  
isPublished | A value of 0 or 1  
overwriteWithBlank | If true, then empty values are set to fields. Otherwise empty values are skipped  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Company](https://developer.mautic.org/#get-company).
### Edit Company[](https://developer.mautic.org/#edit-company)
```
<?php

$id   = 1;
$data = array(
    'companyname' => 'test',
    'companyemail' => 'test@company.com',
    'companycity' => 'Raleigh',
);

// Create new a company of ID 1 is not found?
$createIfNotFound = true;

$company = $companyApi->edit($id, $data, $createIfNotFound);

```

Edit a new company. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a company if the given ID does not exist and clears all the company information, adds the information from the request. **PATCH** fails if the company with the given ID does not exist and updates the company field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a company and return a 404 if the company is not found:
`PATCH /companies/ID/edit`
To edit a company and create a new one if the company is not found:
`PUT /companies/ID/edit`
**Post Parameters**
Name | Description  
---|---  
companyname | Company name is the only required field. Other company fields can be sent with a value  
isPublished | A value of 0 or 1  
overwriteWithBlank | If true, then empty values are set to fields. Otherwise empty values are skipped  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the company was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Company](https://developer.mautic.org/#get-company).
### Delete Company[](https://developer.mautic.org/#delete-company)
```
<?php

$company = $companyApi->delete($id);

```

Delete a company.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /companies/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Company](https://developer.mautic.org/#get-company).
### Add Contact to a Company[](https://developer.mautic.org/#add-contact-to-a-company)
```
<?php

//...
$response = $companyApi->addContact($companyId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually add a contact to a specific company.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /companies/COMPANY_ID/contact/CONTACT_ID/add`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Remove Contact from a Company[](https://developer.mautic.org/#remove-contact-from-a-company)
```
<?php

//...
$response = $companyApi->removeContact($contactId, $companyId);
if (empty($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually remove a contact to a specific company.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /companies/COMPANY_ID/contact/CONTACT_ID/remove`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
## Contacts[](https://developer.mautic.org/#contacts)
Use this endpoint to manipulate and obtain details on Mautic’s contacts.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth   = new ApiAuth();
$auth       = $initAuth->newAuth($settings);
$apiUrl     = "https://your-mautic.com";
$api        = new MauticApi();
$contactApi = $api->newApi("contacts", $auth, $apiUrl);

```

### Get Contact[](https://developer.mautic.org/#get-contact)
```
<?php

//...
$contact = $contactApi->get($id);

```
```
"contact":{"id":47,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","owner":{"id":1,"username":"joesmith","firstName":"Joe","lastName":"Smith"},"points":10,"lastActive":"2015-07-21T14:19:37-05:00","dateIdentified":"2015-07-21T12:27:12-05:00","color":"ab5959","ipAddresses":{"111.111.111.111":{"ipAddress":"111.111.111.111","ipDetails":{"city":"","region":"","country":"","latitude":"","longitude":"","isp":"","organization":"","timezone":""}}},"fields":{"core":{"title":{"id":"1","label":"Title","alias":"title","type":"lookup","group":"core","value":"Mr"},"firstname":{"id":"2","label":"First Name","alias":"firstname","type":"text","group":"core","value":"Jim"},"...":{"...":"..."}},"social":{"twitter":{"id":"17","label":"Twitter","alias":"twitter","type":"text","group":"social","value":"jimcontact"},"...":{"...":"..."}},"personal":[],"professional":[],"all":{"title":"Mr","firstname":"Jim","twitter":"jimcontact","...":"..."}}}
```

Get an individual contact by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
** Contact Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the contact  
isPublished | Boolean | True if the contact is published  
dateAdded | datetime | Date/time contact was created  
createdBy | int | ID of the user that created the contact  
createdByUser | string | Name of the user that created the contact  
dateModified | datetime/null | Date/time contact was last modified  
modifiedBy | int | ID of the user that last modified the contact  
modifiedByUser | string | Name of the user that last modified the contact  
owner | object | User object that owns the contact.  
points | int | Contact’s current number of points  
lastActive | datetime/null | Date/time for when the contact was last recorded as active  
dateIdentified | datetime/null | Date/time when the contact identified themselves  
color | string | Hex value given to contact from Point Trigger definitions based on the number of points the contact has been awarded  
ipAddresses | array | Array of IPs currently associated with this contact  
fields | array | Array of all contact fields with data grouped by field group. See JSON code example for format. This array includes an “all” key that includes an single level array of fieldAlias => contactValue pairs.  
tags | array | Array of tags associated with this contact. See JSON code example for format.  
utmtags | array | Array of UTM Tags associated with this contact. See JSON code example for format.  
doNotContact | array | Array of Do Not Contact objects. See JSON code example for format.  
### List Contacts[](https://developer.mautic.org/#list-contacts)
```
<?php

//...
$contacts = $contactApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":"1","contacts":{"47":{"id":47,"isPublished":true,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","owner":{"id":1,"username":"joesmith","firstName":"Joe","lastName":"Smith"},"points":10,"lastActive":"2015-07-21T14:19:37-05:00","dateIdentified":"2015-07-21T12:27:12-05:00","color":"ab5959","ipAddresses":{"111.111.111.111":{"ipAddress":"111.111.111.111","ipDetails":{"city":"","region":"","country":"","latitude":"","longitude":"","isp":"","organization":"","timezone":""}}},"fields":{"core":{"title":{"id":"1","label":"Title","alias":"title","type":"lookup","group":"core","value":"Mr"},"firstname":{"id":"2","label":"First Name","alias":"firstname","type":"text","group":"core","value":"Jim"},"...":{"...":"..."}},"social":{"twitter":{"id":"17","label":"Twitter","alias":"twitter","type":"text","group":"social","value":"jimcontact"},"...":{"...":"..."}},"personal":[],"professional":[],"all":{"title":"Mr","firstname":"Jim","twitter":"jimcontact","...":"..."}},"tags":[{"tag":"aTag"},{"tag":"bTag"}],"utmtags":[{"id":1,"query":{"page":"asd","cid":"fb1"},"referer":"https://example.com/","remoteHost":"example.com","userAgent":"Mozilla/5.0 (Windows NT 10.0; WOW64; rv:50.0) Gecko/20100101 Firefox/50.0","utmCampaign":"abcampaign","utmContent":"page","utmMedium":"social","utmSource":"fb","utmTerm":"test1"}],"doNotContact":[{"id":2,"reason":2,"comments":"","channel":"email","channelId":null}]}}}
```

Get a list of contacts.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts`
** Query Parameters **
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response. However, all properties in the response that are written in camelCase need to be changed a bit. Before every capital add an underscore `_` and then change the capital letters to non-capital letters. So `dateIdentified` becomes `date_identified`, `modifiedByUser` becomes `modified_by_user` etc.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
where | An array of advanced where conditions  
order | An array of advanced order statements  
#### Advanced filtering[](https://developer.mautic.org/#advanced-filtering)
In some cases you may want to filter by specific value(s). Use URL params like this:
In PHP: `php $where = [   [     'col' => 'phone',     'expr' => 'in',     'val' => '444444444,888888888',   ] ]; ` This design allows to add multiple conditions in the same request.
If you are not using PHP, here is URL-encoded example of the above where array: `GET https://[your_mauitc_domain]/api/contacts?where%5B0%5D%5Bcol%5D=phone&where%5B0%5D%5Bexpr%5D=in&where%5B0%5D%5Bval%5D=444444444,888888888`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
** Properties **
Same as [Get Contact](https://developer.mautic.org/#get-contact).
### Create Contact[](https://developer.mautic.org/#create-contact)
```
<?php

$data = array(
    'firstname' => 'Jim',
    'lastname'  => 'Contact',
    'email'     => 'jim@his-site.com',
    'ipAddress' => $_SERVER['REMOTE_ADDR'],
    'overwriteWithBlank' => true,
);

$contact = $contactApi->create($data);

```

Create a new contact.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /contacts/new`
** Post Parameters **
Name | Description  
---|---  
* | Any contact field alias can be posted as a parameter. For example, firstname, lastname, email, etc.  
ipAddress | IP address to associate with the contact  
lastActive | Date/time in UTC; preferablly in the format of Y-m-d H:m:i but if that format fails, the string will be sent through PHP’s strtotime then formatted  
owner | ID of a Mautic user to assign this contact to  
overwriteWithBlank | If true, then empty values are set to fields. Otherwise empty values are skipped  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
** Properties **
Same as [Get Contact](https://developer.mautic.org/#get-contact).
### Create Batch Contact[](https://developer.mautic.org/#create-batch-contact)
```
<?php

$data = array(
    array(
    'firstname' => 'Jim',
    'lastname'  => 'Contact',
    'email'     => 'jim@his-site.com',
    'ipAddress' => $_SERVER['REMOTE_ADDR']
    ),
    array(
        'firstname' => 'John',
    'lastname'  => 'Doe',
    'email'     => 'john@his-site.com',
    'ipAddress' => $_SERVER['REMOTE_ADDR']
    )
);
$contact = $contactApi->createBatch($data);

```

Create a batch of new contacts.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /contacts/batch/new`
** Post Parameters **
Name | Description  
---|---  
* | Any contact field alias can be posted as a parameter. For example, firstname, lastname, email, etc.  
ipAddress | IP address to associate with the contact  
lastActive | Date/time in UTC; preferablly in the format of Y-m-d H:m:i but if that format fails, the string will be sent through PHP’s strtotime then formatted  
owner | ID of a Mautic user to assign this contact to  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
** Properties **
Array of contacts. Record is the same as [Get Contact](https://developer.mautic.org/#get-contact).
### Edit Contact[](https://developer.mautic.org/#edit-contact)
```
<?php

$id   = 1;
$data = array(
    'email'     => 'jim-new-address@his-site.com',
    'ipAddress' => $_SERVER['REMOTE_ADDR'],    
);

// Create new a contact of ID 1 is not found?
$createIfNotFound = true;

$contact = $contactApi->edit($id, $data, $createIfNotFound);

```

Edit a new contact. Note that this supports PUT or PATCH depending on the desired behavior.
** PUT ** creates a contact if the given ID does not exist and clears all the contact information, adds the information from the request. **PATCH** fails if the contact with the given ID does not exist and updates the contact field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a contact and return a 404 if the contact is not found:
`PATCH /contacts/ID/edit`
To edit a contact and create a new one if the contact is not found:
`PUT /contacts/ID/edit`
** Post Parameters **
Name | Description  
---|---  
* | Any contact field alias can be posted as a parameter. For example, firstname, lastname, email, etc.  
ipAddress | IP address to associate with the contact  
lastActive | Date/time in UTC; preferably in the format of Y-m-d H:m:i but if that format fails, the string will be sent through PHP’s strtotime then formatted  
owner | ID of a Mautic user to assign this contact to  
overwriteWithBlank | If true, then empty values are set to fields. Otherwise empty values are skipped  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the contact was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
** Properties **
Same as [Get Contact](https://developer.mautic.org/#get-contact).
> Note: In order to remove tag from contact add minus `-` before it. For example: `tags: ['one', '-two']` - sending this in request body will add tag `one` and remove tag `two` from contact.
### Edit Batch Contact[](https://developer.mautic.org/#edit-batch-contact)
```
<?php

$data = array(
    array(
        'id'        => 1,
        'firstname' => 'Jim',
        'lastname'  => 'Contact',
        'email'     => 'jim@his-site.com',
        'ipAddress' => $_SERVER['REMOTE_ADDR']
    ),
    array(
        'id'        => 1,
        'firstname' => 'John',
        'lastname'  => 'Doe',
        'email'     => 'john@his-site.com',
        'ipAddress' => $_SERVER['REMOTE_ADDR']
    )
);

$contact = $contactApi->editBatch($data);

```

Edit several contacts in one request. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a contact if the given ID does not exist and clears all the contact information, adds the information from the request. **PATCH** fails if the contact with the given ID does not exist and updates the contact field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a contact and return a 404 if the contact is not found:
`PATCH /contacts/batch/edit`
To edit a contact and create a new one if the contact is not found:
`PUT /contacts/batch/edit`
**Post Parameters**
Name | Description  
---|---  
* | Any contact field alias can be posted as a parameter. For example, firstname, lastname, email, etc.  
ipAddress | IP address to associate with the contact  
lastActive | Date/time in UTC; preferably in the format of Y-m-d H:m:i but if that format fails, the string will be sent through PHP’s strtotime then formatted  
owner | ID of a Mautic user to assign this contact to  
overwriteWithBlank | If true, then empty values are set to fields. Otherwise empty values are skipped  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the contact was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Contacts array. Record same as [Get Contact](https://developer.mautic.org/#get-contact).
> Note: In order to remove tag from contact add minus `-` before it. For example: `tags: ['one', '-two']` - sending this in request body will add tag `one` and remove tag `two` from contact.
### Delete Contact[](https://developer.mautic.org/#delete-contact)
```
<?php

$contact = $contactApi->delete($id);

```

Delete a contact.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /contacts/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
** Properties **
Same as [Get Contact](https://developer.mautic.org/#get-contact).
### Delete Batch Contact[](https://developer.mautic.org/#delete-batch-contact)
```
<?php
$data = array(1, 2);
$contact = $contactApi->deleteBatch($data);

```

Delete contacts.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /contacts/batch/delete`
If you are not using PHP, here is a URL example:
`DELETE https://[your_mautic_domain]/api/contacts/batch/delete?ids=1,2`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Contacts array. Record same as [Get Contact](https://developer.mautic.org/#get-contact).
### Add Do Not Contact[](https://developer.mautic.org/#add-do-not-contact)
```
<?php

$contactApi->addDnc($contactId, $channel, $reason, $channelId, $comments);

```
```
{"channelId":"26","reason":"Integration issued DNC","comments":"Unsubscribed via API"}
```

Add a contact to DNC list
#### HTTP Request[](https://developer.mautic.org/#http-request)
To add Do Not Contact entry to a contact:
`POST /contacts/ID/dnc/CHANNEL/add`
**Data Parameters (optional)**
Name | Description  
---|---  
channel | Channel of DNC. For example ‘email’, 'sms’… Default is email.  
reason | Int value of the reason. Use Contacts constants: Contacts::UNSUBSCRIBED (1), Contacts::BOUNCED (2), Contacts::MANUAL (3). Default is Manual  
channelId | ID of the entity which was the reason for unsubscription  
comments | A text describing details of DNC entry  
#### Response[](https://developer.mautic.org/#response)
Same as [Get Contact](https://developer.mautic.org/#get-contact).
### Remove from Do Not Contact[](https://developer.mautic.org/#remove-from-do-not-contact)
```
<?php
$contactApi->removeDnc($contactId, $channel);

```

Remove a contact from DNC list
#### HTTP Request[](https://developer.mautic.org/#http-request)
To remove Do Not Contact entry from a contact:
`POST /contacts/ID/dnc/CHANNEL/remove`
**Data Parameters (optional)**
Name | Description  
---|---  
channel | Channel of DNC. For example 'email’, 'sms’… Default is email.  
#### Response[](https://developer.mautic.org/#response)
Same as [Get Contact](https://developer.mautic.org/#get-contact).
### Add UTM Tags[](https://developer.mautic.org/#add-utm-tags)
```
<?php

$data = array(
    'utm_campaign' => 'apicampaign',
    'utm_source'   => 'fb',
    'utm_medium'   => 'social',
    'utm_content'  => 'fbad',
    'utm_term'     => 'mautic api',
    'useragent'    => 'Mozilla/5.0 (Windows NT 10.0; WOW64; rv:50.0) Gecko/20100101 Firefox/50.0',
    'url'          => '/product/fbad01/',
    'referer'      => 'https://google.com/q=mautic+api',
    'query'        => ['cid'=>'abc','cond'=>'new'], // or as string with "cid=abc&cond=new"
    'remotehost'   => 'example.com',
    'lastActive'   => '2017-01-17T00:30:08+00:00'
 );
$contactApi->addUtm($contactId, $data);

```

Add UTM tags to a contact
#### HTTP Request[](https://developer.mautic.org/#http-request)
To add UTM tag entry to a contact:
`POST /contacts/ID/utm/add`
**UTM Parameters (required)**
While the parameter array is required, each utm tag entry is optional.
Name | Description  
---|---  
utm_campaign | The UTM Campaign parameter  
utm_source | The UTM Source parameter  
utm_medium | The UTM Medium parameter  
utm_content | The UTM Content parameter  
utm_term | The UTM Term parameter  
useragent | The browsers UserAgent. If provided a new Device entry will be created if necessary.  
url | The page url  
referer | The URL of the referer,  
query | Any extra query parameters you wish to include. Array or http query string  
remotehost | The Host name  
lastActive | The date that the action occured. Contacts lastActive date will be updated if included. Date format required `2017-01-17T00:30:08+00:00`.  
#### Response[](https://developer.mautic.org/#response)
Same as [Get Contact](https://developer.mautic.org/#get-contact) with the added UTM Tags.
### Remove UTM Tags from a contact[](https://developer.mautic.org/#remove-utm-tags-from-a-contact)
```
<?php
$contactApi->removeUtm($contactId, $utmId);

```

Remove a set of UTM Tags from a contact
#### HTTP Request[](https://developer.mautic.org/#http-request)
To remove UTM Tags from a contact:
`POST /contacts/ID/utm/UTMID/remove`
**Data Parameters**
None required.
#### Response[](https://developer.mautic.org/#response)
Same as [Get Contact](https://developer.mautic.org/#get-contact) without the removed UTM Tags.
### Add Points[](https://developer.mautic.org/#add-points)
```
<?php

$data = array(
     'eventName' => 'Score via api',
     'actionName' => 'Adding',
 );
$contactApi->addPoints($contactId, $pointDelta, $data);

```

Add contact points
#### HTTP Request[](https://developer.mautic.org/#http-request)
To add points to a contact and return a 404 if the lead is not found:
`POST /contacts/ID/points/plus/POINTS`
**Data Parameters (optional)**
Name | Description  
---|---  
eventName | Name of the event  
actionName | Name of the action  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "success": true } `
### Subtract Points[](https://developer.mautic.org/#subtract-points)
```
<?php

$data = array(
     'eventname' => 'Score via api',
     'actionname' => 'Subtracting',
 );
$contactApi->subtractPoints($contactId, $pointDelta, $data);

```

Subtract contact points
#### HTTP Request[](https://developer.mautic.org/#http-request)
To subtract points from a contact and return a 404 if the contact is not found:
`POST /contacts/ID/points/minus/POINTS`
**Data Parameters (optional)**
Name | Description  
---|---  
eventname | Name of the event  
actionname | Name of the action  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "success": true } `
### List Available Owners[](https://developer.mautic.org/#list-available-owners)
```
<?php

$owners = $contactApi->getOwners();

```
```
[{"id":1,"firstName":"Joe","lastName":"Smith"},{"id":2,"firstName":"Jane","lastName":"Smith"}]
```

Get a list of owners that can be used to assign contacts to when creating/editing.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/list/owners`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
** Owner Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the Mautic user  
firstName | string | First name of the Mautic user  
lastName | string | Last name of the Mautic user  
### List Available Fields[](https://developer.mautic.org/#list-available-fields)
```
<?php

$fields = $contactApi->getFieldList();

```
```
{"1":{"id":1,"label":"Title","alias":"title","type":"lookup","group":"core","order":1},"2":{"id":2,"label":"First Name","alias":"firstname","type":"text","group":"core","order":2},"3":{"id":3,"label":"Last Name","alias":"lastname","type":"text","group":"core","order":3},"...":{"...":"..."}}
```

Get a list of available contact fields including custom ones.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/list/fields`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
** Field Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the field  
label | string | Field label  
alias | string | Field alias used as the column name in the database  
type | string | Type of field. I.e. text, lookup, etc  
group | string | Group the field belongs to  
order | int | Field order  
### List Contact Notes[](https://developer.mautic.org/#list-contact-notes)
```
<?php

$notes = $contactApi->getContactNotes($id, $searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"notes":[{"id":1,"text":"<p>Jim is super cool!</p>","type":"general","dateTime":"2015-07-23T13:14:00-05:00"}]}
```

Get a list of notes for a specific contact.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/notes`
** Query Parameters **
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** Note Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the note  
text | string | Body of the note  
type | string | Type of note. Options are “general”, “email”, “call”, “meeting”  
dateTime | datetime | Date/time string of when the note was created.  
### Get Segment Memberships[](https://developer.mautic.org/#get-segment-memberships)
```
<?php

$segments = $contactApi->getContactSegments($id);

```
```
{"total":1,"segments":{"3":{"id":3,"name":"New Contacts","alias":"newcontacts"}}}
```

Get a list of contact segments the contact is a member of.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/segments`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** List Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the list  
name | string | Name of the list  
alias | string | Alias of the list used with search commands.  
dateAdded | datetime | Date/time string for when the contact was added to the list  
manuallyAdded | bool | True if the contact was manually added to the list versus being added by a filter  
manuallyRemoved | bool | True if the contact was manually removed from the list even though the list’s filter is a match  
### Change List Memberships[](https://developer.mautic.org/#change-list-memberships)
See [Segements](https://developer.mautic.org/#segments).
### Get Campaign Memberships[](https://developer.mautic.org/#get-campaign-memberships)
```
<?php

$campaigns = $contactApi->getContactCampaigns($id);

```
```
{"total":1,"campaigns":{"1":{"id":1,"name":"Welcome Campaign","dateAdded":"2015-07-21T14:11:47-05:00","manuallyRemoved":false,"manuallyAdded":false,"list_membership":[3]}}}
```

Get a list of campaigns the contact is a member of.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/campaigns`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** List Properties **
Name | Type | Description  
---|---|---  
id | int | ID of the campaign  
name | string | Name of the campaign  
dateAdded | datetime | Date/time string for when the contact was added to the campaign  
manuallyAdded | bool | True if the contact was manually added to the campaign versus being added by a contact list  
manuallyRemoved | bool | True if the contact was manually removed from the campaign when the contact’s list is assigned to the campaign  
listMembership | array | Array of contact list IDs this contact belongs to that is also associated with this campaign  
### Change Campaign Memberships[](https://developer.mautic.org/#change-campaign-memberships)
See [Campaigns](https://developer.mautic.org/#campaigns).
### Get Contact’s Events[](https://developer.mautic.org/#get-contact's-events)
```
<?php

$events = $contactApi->getEvents($id, $search, $includeEvents, $excludeEvents, $orderBy, $orderByDir, $page);

```

Warning: Deprecated. Use `getActivityForContact` instead.
** Query Parameters **
Name | Description  
---|---  
id | Contact ID  
filters[search] | String or search command to filter events by.  
filters[includeEvents][] | Array of event types to include.  
filters[excludeEvents][] | Array of event types to exclude.  
order | Array of Column and Direction [COLUMN, DIRECTION].  
page | What page number to load  
```
{"events":[{"event":"lead.identified","icon":"fa-user","eventType":"Contact identified","eventPriority":-4,"timestamp":"2016-06-09T21:39:08+00:00","featured":true}],"filters":{"search":"","includeEvents":["lead.identified"],"excludeEvents":[]},"order":["","ASC"],"types":{"lead.ipadded":"Accessed from IP","asset.download":"Asset downloaded","campaign.event":"Campaign action triggered","lead.create":"Contact created","lead.identified":"Contact identified","lead.donotcontact":"Do not contact","email.read":"Email read","email.sent":"Email sent","email.failed":"Failed","form.submitted":"Form submitted","page.hit":"Page hit","point.gained":"Point gained","stage.changed":"Stage changed","lead.utmtagsadded":"UTM tags recorded","page.videohit":"Video View Event"},"total":1,"page":1,"limit":25,"maxPages":1}
```

Get a list of contact events the contact created.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/events`
Warning: Deprecated. Use `GET /contacts/ID/activity` instead.
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** List Properties **
Name | Type | Description  
---|---|---  
events | array | List of events  
event | string | ID of the event type  
icon | string | Icon class from FontAwesome  
eventType | string | Human name of the event  
eventPriority | string | Priority of the event  
timestamp | timestamp | Date and time when the event was created  
featured | bool | Flag whether the event is featured  
filters | array | Filters used in the query  
order | array | Ordering used in the query  
types | array | Array of available event types  
total | int | Total number of events in the request  
page | int | Current page number  
limit | int | Limit of events per page  
maxPages | int | How many pages of events are there  
### Get activity events for specific contact[](https://developer.mautic.org/#get-activity-events-for-specific-contact)
```
<?php

$events = $contactApi->getActivityForContact($id, $search, $includeEvents, $excludeEvents, $orderBy, $orderByDir, $page, $dateFrom, $dateTo);

```

** Query Parameters **
Name | Description  
---|---  
id | Contact ID  
filters[search] | String or search command to filter events by.  
filters[includeEvents][] | Array of event types to include.  
filters[excludeEvents][] | Array of event types to exclude.  
filters[dateFrom] | Date from filter. Must be type of `\DateTime` for the PHP API libary and in format `Y-m-d H:i:s` for HTTP param  
filters[dateTo] | Date to filter. Must be type of `\DateTime` for the PHP API libary and in format `Y-m-d H:i:s` for HTTP param  
order | Array of Column and Direction [COLUMN, DIRECTION].  
page | What page number to load  
limit | Limit of events per page  
```
{"events":[{"event":"lead.identified","icon":"fa-user","eventType":"Contact identified","eventPriority":-4,"timestamp":"2016-06-09T21:39:08+00:00","featured":true}],"filters":{"search":"","includeEvents":["lead.identified"],"excludeEvents":[]},"order":["","ASC"],"types":{"asset.download":"Asset downloaded","campaign.event":"Campaign action triggered","campaign.event.scheduled":"Campaign event scheduled","lead.donotcontact":"Do not contact","email.failed":"Email failed","email.read":"Email read","email.sent":"Email sent","form.submitted":"Form submitted","lead.imported":"Imported","page.hit":"Page hit","point.gained":"Point gained","stage.changed":"Stage changed","lead.utmtagsadded":"UTM tags recorded","page.videohit":"Video view event"},"total":1,"page":1,"limit":25,"maxPages":1}
```

Get a list of contact events the contact had created.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/activity`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** List Properties **
Name | Type | Description  
---|---|---  
events | array | List of events  
event | string | ID of the event type  
icon | string | Icon class from FontAwesome  
eventType | string | Human name of the event  
eventPriority | string | Priority of the event  
timestamp | timestamp | Date and time when the event was created  
featured | bool | Flag whether the event is featured  
filters | array | Filters used in the query  
order | array | Ordering used in the query  
types | array | Array of available event types  
total | int | Total number of events in the request  
page | int | Current page number  
limit | int | Limit of events per page  
maxPages | int | How many pages of events are there  
### Get Activity events for all contacts[](https://developer.mautic.org/#get-activity-events-for-all-contacts)
```
<?php

$events = $contactApi->getActivity($search, $includeEvents, $excludeEvents, $orderBy, $orderByDir, $page, $dateFrom, $dateTo);

```

** Query Parameters **
Name | Description  
---|---  
filters[search] | String or search command to filter events by.  
filters[includeEvents][] | Array of event types to include.  
filters[excludeEvents][] | Array of event types to exclude.  
filters[dateFrom] | Date from filter. Must be type of `\DateTime` for the PHP API libary and in format `Y-m-d H:i:s` for HTTP param  
filters[dateTo] | Date to filter. Must be type of `\DateTime` for the PHP API libary and in format `Y-m-d H:i:s` for HTTP param  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
page | What page number to load  
```
{"events":[{"event":"meeting.attended","eventId":"meeting.attended65","eventLabel":"Attended meeting - Mautic instance","eventType":"Meeting attendance","timestamp":"2017-08-03T21:03:04+00:00","contactId":"12180","details":{"eventName":"mautic-instance","eventId":"371343405","eventDesc":"Mautic instance","joinUrl":""}},{"event":"webinar.attended","eventId":"webinar.attended67","eventLabel":"Attended webinar - Mautic","eventType":"Webinar attendance","timestamp":"2017-08-03T21:03:04+00:00","contactId":"12180","details":{"eventName":"mautic","eventId":"530287395","eventDesc":"Mautic","joinUrl":""}},{"event":"webinar.registered","eventId":"webinar.registered66","eventLabel":"Registered for webinar - Mautic","eventType":"Webinar registered for","timestamp":"2017-08-03T21:03:04+00:00","contactId":"12180","details":{"eventName":"mautic","eventId":"530287395","eventDesc":"Mautic","joinUrl":"https://global.gotowebinar.com/join/xxx/xxx"}},{"event":"campaign.event","eventId":"campaign.event892","eventLabel":{"label":"Contact field value \/ Campaign Date","href":"\/s\/campaigns\/view\/498"},"eventType":"Campaign action triggered","timestamp":"2017-08-03T00:58:25+00:00","contactId":"12281","details":{"log":{"dateTriggered":"2017-08-03T00:58:25+00:00","metadata":[],"type":"lead.field_value","isScheduled":"0","logId":"892","eventId":"1457","campaignId":"498","eventName":"Contact field value","campaignName":"Campaign Date"}}},{"event":"email.sent","eventId":"email.sent796","eventLabel":{"label":"2017-05-23 - Email - Leads - Nurture Flow (Monica) 1","href":"http:\/\/mautic.dev\/email\/view\/597a116ae69ca","isExternal":true},"eventType":"Email sent","timestamp":"2017-07-27T16:14:34+00:00","contactId":"16419","details":{"stat":{"id":"796","dateSent":"2017-07-27T16:14:34+00:00","subject":"How to make the case for digital","isRead":"0","isFailed":"0","viewedInBrowser":"0","retryCount":"0","idHash":"597a116ae69ca","openDetails":[],"storedSubject":"How to make the case for digital","timeToRead":false,"emailId":"78","emailName":"2017-05-23 - Email - Leads - Nurture Flow (Monica) 1"},"type":"sent"}},{"event":"email.read","eventId":"email.read769","eventLabel":{"label":"Custom Email: device test","href":"http:\/\/mautic.dev\/email\/view\/5966b0cd571f4","isExternal":true},"eventType":"Email read","timestamp":"2017-07-12T23:30:56+00:00","contactId":"13930","details":{"stat":{"id":"769","dateRead":"2017-07-12T23:30:56+00:00","dateSent":"2017-07-12T23:29:17+00:00","isRead":"1","isFailed":"0","viewedInBrowser":"0","retryCount":"0","idHash":"5966b0cd571f4","openDetails":[{"datetime":"2017-07-12 23:30:56","useragent":"Mozilla\/5.0 (Macintosh; Intel Mac OS X 10_12_5) AppleWebKit\/537.36 (KHTML, like Gecko) Chrome\/59.0.3071.115 Safari\/537.36","inBrowser":false},{"datetime":"2017-07-13 02:18:51","useragent":"Mozilla\/5.0 (Macintosh; Intel Mac OS X 10_12_5) AppleWebKit\/537.36 (KHTML, like Gecko) Chrome\/59.0.3071.115 Safari\/537.36","inBrowser":false}],"storedSubject":"device test","timeToRead":"PT1M39S"},"type":"read"}},{"event":"lead.ipadded","eventId":"lead.ipadded3263","eventLabel":"127.0.0.1","eventType":"Accessed from IP","timestamp":"2017-07-27T03:09:09+00:00","contactId":"3263","details":[]},{"event":"form.submitted","eventId":"form.submitted503","eventLabel":{"label":"3586 Test","href":"\/s\/forms\/view\/143"},"eventType":"Form submitted","timestamp":"2017-07-27T03:09:07+00:00","contactId":"16417","details":{"submission":{"id":503,"ipAddress":{"ip":"127.0.0.1"},"form":{"id":143,"name":"3586 Test","alias":"3586_test"},"dateSubmitted":"2017-07-27T03:09:07+00:00","referer":"http:\/\/mautic.dev\/form\/143","results":{"form_id":"143","email":"formtest7@test.com","f_name":""}},"form":{"id":143,"name":"3586 Test","alias":"3586_test"},"page":{}}},{"event":"page.hit","eventLabel":{"label":"Test","href":"\/s\/pages\/view\/8"},"eventType":"Page hit","timestamp":"2017-07-21T20:36:49+00:00","contactId":"16380","details":{"hit":{"userAgent":"Mozilla\/5.0 (Macintosh; Intel Mac OS X 10_12_5) AppleWebKit\/537.36 (KHTML, like Gecko) Chrome\/59.0.3071.115 Safari\/537.36","dateHit":"2017-07-21T20:36:49+00:00","url":"http:\/\/mautic.dev\/uncategorized\/translation-test1","query":{"pageUrl":"http:\/\/mautic.dev\/uncategorized\/translation-test1"},"clientInfo":"a:6:{s:4:\"type\";s:7:\"browser\";s:4:\"name\";s:6:\"Chrome\";s:10:\"short_name\";s:2:\"CH\";s:7:\"version\";s:4:\"59.0\";s:6:\"engine\";s:5:\"Blink\";s:14:\"engine_version\";s:0:\"\";}","device":"desktop","deviceOsName":"Mac","deviceBrand":"","deviceModel":"","pageId":"8"}}},{"event":"point.gained","eventLabel":"2: Page Hit Test \/ 20","eventType":"Point gained","timestamp":"2017-07-20T22:38:28+00:00","contactId":"16379","details":{"log":{"eventName":"2: Page Hit Test","actionName":"hit","dateAdded":"2017-07-20T22:38:28+00:00","type":"url","delta":"20","id":"2"}}},{"event":"lead.imported","eventId":"lead.imported6324","eventType":"Imported","eventLabel":{"label":"Contact import failed from FakeNameGenerator.com_20d05d9c.csv","href":"\/s\/contacts\/import\/view\/4"},"timestamp":"2017-07-17T21:42:35+00:00","details":{"id":"6324","bundle":"lead","object":"import","action":"failed","properties":{"line":2001,"file":"FakeNameGenerator.com_20d05d9c.csv","error":"No data found"},"userId":"2","userName":"Bob Smith","objectId":"4","dateAdded":"2017-07-17T21:42:35+00:00"}},{"event":"asset.download","eventId":"asset.download11","eventLabel":{"label":"Download Mautic","href":"\/s\/assets\/view\/1"},"eventType":"Asset downloaded","timestamp":"2017-04-04T01:49:13+00:00","details":{"asset":{"id":1,"title":"Download Mautic","alias":"download-mautic","description":"test"},"assetDownloadUrl":"http:\/\/mautic.dev\/asset\/1:download-mautic"}},],"filters":{"search":"","includeEvents":[],"excludeEvents":[]},"order":["timestamp","DESC"],"types":{"lead.ipadded":"Accessed from IP","asset.download":"Asset downloaded","meeting.attended":"Attended meeting","webinar.attended":"Attended webinar","campaign.event":"Campaign action triggered","campaign.event.scheduled":"Campaign event scheduled","lead.donotcontact":"Do not contact","email.failed":"Email failed","email.read":"Email read","email.sent":"Email sent","form.submitted":"Form submitted","lead.imported":"Imported","page.hit":"Page hit","point.gained":"Point gained","meeting.registered":"Registered for meeting","webinar.registered":"Registration to Webinar","stage.changed":"Stage changed","lead.utmtagsadded":"UTM tags recorded","page.videohit":"Video view event"},"total":12,"page":1,"limit":25,"maxPages":1}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/activity`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
** List Properties **
Name | Type | Description  
---|---|---  
events | array | List of events  
event | string | ID of the event type  
icon | string | Icon class from FontAwesome  
eventType | string | Human name of the event  
eventPriority | string | Priority of the event  
contactId | ID of the contact who created the event  
timestamp | timestamp | Date and time when the event was created  
featured | bool | Flag whether the event is featured  
filters | array | Filters used in the query  
order | array | Ordering used in the query  
types | array | Array of available event types  
total | int | Total number of events in the request  
page | int | Current page number  
limit | int | Limit of events per page  
maxPages | int | How many pages of events are there  
### Get Contact’s Companies[](https://developer.mautic.org/#get-contact's-companies)
```
<?php

$companies = $contactApi->getContactCompanies($contactId);

```json
{
  "total":1,
  "companies":[
    {
      "company_id":"420",
      "date_associated":"2016-12-27 15:03:43",
      "is_primary":"0",
      "companyname":"test",
      "companyemail":"test@company.com",
      "companycity":"Raleigh",
      "score":"0",
      "date_added":"2016-12-27 15:03:42"
    }
  ]
}

```

Get a list of contact’s companies the contact belongs to.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/companies`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
**List Properties**
Name | Type | Description  
---|---|---  
company_id | int | Company ID  
date_associated | datetime | Date and time when the contact was associated to the company  
date_added | datetime | Date and time when the company was created  
is_primary | bool | Flag whether the company association is primary (current)  
companyname | string | Name of the company  
companyemail | string | Email of the company  
companycity | string | City of the company  
score | int | Score of the company  
### Get Contact’s Devices[](https://developer.mautic.org/#get-contact's-devices)
```
<?php

$devices = $contactApi->getContactDevices($contactId);

```json
{
  "total":1,
  "devices":[
    {
      "id":60,
      "lead":[],
      "clientInfo":[],
      "device":"desktop",
      "deviceOsName":"Ubuntu",
      "deviceOsShortName":"UBT",
      "deviceOsPlatform":"x64"
    }
  ]
}

```

Get a list of contact’s devices the contact has used.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /contacts/ID/devices`
#### Response[](https://developer.mautic.org/#response)
`Expected response code: 200`
**List Properties**
Name | Type | Description  
---|---|---  
id | int | Device ID  
clientInfo | array | Array with various information about the client (browser)  
device | string | Device type; desktop, mobile..  
deviceOsName | string | Full device OS name  
deviceOsShortName | string | Short device OS name  
deviceOsPlatform | string | OS platform  
## Data - Dashboard widget data[](https://developer.mautic.org/#data---dashboard-widget-data)
Use this endpoint to obtain details on Mautic’s dashboard statistical data. 
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth   = new ApiAuth();
$auth       = $initAuth->newAuth($settings);
$apiUrl     = "https://your-mautic.com";
$api        = new MauticApi();
$contactApi = $api->newApi("data", $auth, $apiUrl);

```

### Get list of available widget types[](https://developer.mautic.org/#get-list-of-available-widget-types)
```
<?php
$data = $dataApi->getList();

```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /data`
`Expected Response Code: 200`
```
{"success":1,"types":{"Core Widgets":{"recent.activity":"Recent Activity"},"Contact Widgets":{"created.leads.in.time":"Created contacts in time","anonymous.vs.identified.leads":"Anonymous vs identified contacts","map.of.leads":"Map","top.lists":"Top segments","top.creators":"Top contact creators","top.owners":"Top contact owners","created.leads":"Created contacts"},"Page Widgets":{"page.hits.in.time":"Page visits in time","unique.vs.returning.leads":"Unique vs returning visitors","dwell.times":"Dwell times","popular.pages":"Popular landing pages","created.pages":"Created Landing pages"},"Point Widgets":{"points.in.time":"Points in time"},"Form Widgets":{"submissions.in.time":"Submissions in time","top.submission.referrers":"Top submission referrers","top.submitters":"Top submitters","created.forms":"Created forms"},"Email Widgets":{"emails.in.time":"Emails in time","sent.email.to.contacts":"Sent email to contacts","most.hit.email.redirects":"Most hit email redirects","ignored.vs.read.emails":"Ignored vs read","upcoming.emails":"Upcoming emails","most.sent.emails":"Most sent emails","most.read.emails":"Most read emails","created.emails":"Created emails"},"Asset Widgets":{"asset.downloads.in.time":"Downloads in time","unique.vs.repetitive.downloads":"Unique vs repetitive downloads","popular.assets":"Popular assets","created.assets":"Created assets"},"Campaign Widgets":{"events.in.time":"Events triggered in time","leads.added.in.time":"Leads added in time"}}}
```

### Get an individual widget data by type.[](https://developer.mautic.org/#get-an-individual-widget-data-by-type.)
```
<?php
$data = $dataApi->get($type, $options);

```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /data/{type}?dateFrom={YYYY-mm-dd}&dateTo={YYYY-mm-dd}&timeUnit={m}`
Returns response which can be directly visualized by the 
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
```
{"success":1,"cached":false,"execution_time":0.043900966644287,"data":{"chartType":"line","chartHeight":220,"chartData":{"labels":["Jan 2016","Feb 2016","Mar 2016","Apr 2016","May 2016"],"datasets":[{"label":"Submission Count","data":[12,6,0,0,0],"fillColor":"rgba(78,93,157,0.1)","strokeColor":"rgba(78,93,157,0.8)","pointColor":"rgba(78,93,157,0.75)","pointHighlightStroke":"rgba(78,93,157,1)"}]}}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /data/{type}?dateFrom={YYYY-mm-dd}&dateTo={YYYY-mm-dd}&timeUnit={m}&dataFormat={raw}`
Returns raw format which can be more easily processed.
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
```
{"success":1,"cached":false,"execution_time":0.039958000183105,"data":{"Submission Count":{"Jan 2016":12,"Feb 2016":6,"Mar 2016":0,"Apr 2016":0,"May 2016":0}}}
```

### “Emails in time” widget[](https://developer.mautic.org/#"emails-in-time"-widget)
#### Filter parameters[](https://developer.mautic.org/#filter-parameters)
**filter[companyId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided company.
**filter[campaignId (int)** Filter only emails from contacts that were sent as part of provided campaign.
**filter[segmentId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided segment.
#### Dataset parameter[](https://developer.mautic.org/#dataset-parameter)
**dataset (array)** - sent - opened - unsubscribed - clicked - bounced - failed Provide more datasets in response based on request.
#### HTTP Request:[](https://developer.mautic.org/#http-request:)
`GET /api/data/emails.in.time?dateFrom={YYYY-mm-dd}&dateTo={YYYY-mm-dd}&timeUnit={m}&filter[campaignId]={int}&filter[companyId]={int}&filter[segmentId]={int}&withCounts&dataset[]=sent&dataset[]=opened&dataset[]=unsubscribed&dataset[]=clicked`
### “Sent email to contacts” widget[](https://developer.mautic.org/#"sent-email-to-contacts"-widget)
#### Filter parameters[](https://developer.mautic.org/#filter-parameters)
**filter[companyId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided company.
**filter[campaignId (int)** Filter only emails from contacts that were sent as part of provided campaign.
**filter[segmentId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided segment.
#### HTTP Request:[](https://developer.mautic.org/#http-request:)
`GET /api/data/sent.email.to.contacts?dateFrom={YYYY-mm-dd}&dateTo={YYYY-mm-dd}&timeUnit={m}&filter[campaignId]={int}&filter[companyId]={int}&filter[segmentId]={int}&limit=10&offset=0`
### “Most hit email redirects” widgets[](https://developer.mautic.org/#"most-hit-email-redirects"-widgets)
#### Filter parameters[](https://developer.mautic.org/#filter-parameters)
**filter[companyId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided company.
**filter[campaignId (int)** Filter only emails from contacts that were sent as part of provided campaign.
**filter[segmentId](https://developer.mautic.org/int)** Filter only emails from contacts assigned to provided segment.
#### HTTP Request:[](https://developer.mautic.org/#http-request:)
`GET /api/data/most.hit.email.redirects?dateFrom={YYYY-mm-dd}&dateTo={YYYY-mm-dd}&timeUnit={m}&filter[campaignId]={int}&filter[companyId]={int}&filter[segmentId]={int}&limit=10&offset=0`
**Available data URL query params**
Name|Type|Example|Description —-|—-|———– timezone|string|America/New_York|PHP timezone dateFrom|string|2016-28-03|Date from in the YYYY-mm-dd HH:ii:ss format dateTo|string|2016-28-04|Date to in the YYYY-mm-dd HH:ii:ss format timeUnit|string|m|Date/Time unit. Available options: Y, m, W, d, H limit|int|10|Limit of the table widget items filter|array|[lead_id => 23]|filters which should be applied to the SQL query
## Dynamic Content[](https://developer.mautic.org/#dynamic-content)
Use this endpoint to obtain details on Mautic’s web dynamic content.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth         = new ApiAuth();
$auth             = $initAuth->newAuth($settings);
$apiUrl           = "https://your-mautic.com";
$api              = new MauticApi();
$dynamicContentApi = $api->newApi("dynamicContents", $auth, $apiUrl);

```

### Get Dynamic Content[](https://developer.mautic.org/#get-dynamic-content)
```
<?php

//...
$dynamicContent = $dynamicContentApi->get($id);

```
```
{"dynamicContent":{"isPublished":true,"dateAdded":"2016-06-20T11:26:51+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":"2016-08-08T16:36:27+00:00","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"DC13","category":null,"publishUp":null,"publishDown":null,"sentCount":0,"variantParent":null,"variantChildren":[]}}
```

Get an individual dynamicContent by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /dynamiccontents/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Dynamic Content Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the dynamic content  
name | string | Name of the dynamic content  
description | string/null | Description of the dynamic content  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the dynamic content should be published  
publishDown | datetime/null | Date/time the dynamic content should be un published  
dateAdded | datetime | Date/time dynamic content was created  
createdBy | int | ID of the user that created the dynamic content  
createdByUser | string | Name of the user that created the dynamic content  
dateModified | datetime/null | Date/time dynamic content was last modified  
modifiedBy | int | ID of the user that last modified the dynamic content  
modifiedByUser | string | Name of the user that last modified the dynamic content  
variantChildren | array | Array of Dynamic Content entities for variants of this landing dynamic content  
variantParent | object | The parent/main dynamic content if this is a variant (A/B test)  
sentCount | int | Count of how many times the dynamic content was sent  
### List Dynamic Contents[](https://developer.mautic.org/#list-dynamic-contents)
```
<?php
// ...

$dynamicContents = $dynamicContentApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":30,"dynamicContents":[{"isPublished":true,"dateAdded":"2016-06-20T11:27:09+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":"2016-08-22T17:14:01+00:00","modifiedBy":1,"modifiedByUser":"John Doe","id":2,"name":"CD2","category":null,"publishUp":null,"publishDown":null,"sentCount":0,"variantParent":null,"variantChildren":[]}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /dynamiccontents`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Dynamic Content](https://developer.mautic.org/#get-dynamic-content).
### Create Dynamic Content[](https://developer.mautic.org/#create-dynamic-content)
```
<?php

$data = array(
    'name'        => 'Dynamic Content A',
    'isPublished' => 1
);

$dynamicContent = $dynamicContentApi->create($data);

```

Create a new dynamicContent.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /dynamiccontents/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the dynamic content  
name | string | Name of the dynamic content  
description | string/null | Description of the dynamic content  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the dynamic content should be published  
publishDown | datetime/null | Date/time the dynamic content should be un published  
dateAdded | datetime | Date/time dynamic content was created  
createdBy | int | ID of the user that created the dynamic content  
createdByUser | string | Name of the user that created the dynamic content  
dateModified | datetime/null | Date/time dynamic content was last modified  
modifiedBy | int | ID of the user that last modified the dynamic content  
modifiedByUser | string | Name of the user that last modified the dynamic content  
variantChildren | array | Array of Dynamic Content entities for variants of this landing dynamic content  
variantParent | object | The parent/main dynamic content if this is a variant (A/B test)  
sentCount | int | Count of how many times the dynamic content was sent  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Dynamic Content](https://developer.mautic.org/#get-dynamic-content).
### Edit Dynamic Content[](https://developer.mautic.org/#edit-dynamic-content)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New dynamicContent name',
    'isPublished' => 0
);

// Create new a dynamicContent of ID 1 is not found?
$createIfNotFound = true;

$dynamicContent = $dynamicContentApi->edit($id, $data, $createIfNotFound);

```

Edit a new dynamicContent. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a dynamicContent if the given ID does not exist and clears all the dynamic content information, adds the information from the request. **PATCH** fails if the dynamic content with the given ID does not exist and updates the dynamic content field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a dynamicContent and return a 404 if the dynamic content is not found:
`PATCH /dynamiccontents/ID/edit`
To edit a dynamicContent and create a new one if the dynamic content is not found:
`PUT /dynamiccontents/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the dynamic content  
name | string | Name of the dynamic content  
description | string/null | Description of the dynamic content  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the dynamic content should be published  
publishDown | datetime/null | Date/time the dynamic content should be un published  
dateAdded | datetime | Date/time dynamic content was created  
createdBy | int | ID of the user that created the dynamic content  
createdByUser | string | Name of the user that created the dynamic content  
dateModified | datetime/null | Date/time dynamic content was last modified  
modifiedBy | int | ID of the user that last modified the dynamic content  
modifiedByUser | string | Name of the user that last modified the dynamic content  
variantChildren | array | Array of Dynamic Content entities for variants of this landing dynamic content  
variantParent | object | The parent/main dynamic content if this is a variant (A/B test)  
sentCount | int | Count of how many times the dynamic content was sent  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the dynamic content was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Dynamic Content](https://developer.mautic.org/#get-dynamic-content).
### Delete Dynamic Content[](https://developer.mautic.org/#delete-dynamic-content)
```
<?php

$dynamicContent = $dynamicContentApi->delete($id);

```

Delete a dynamicContent.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /dynamiccontents/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Dynamic Content](https://developer.mautic.org/#get-dynamic-content).
## Emails[](https://developer.mautic.org/#emails)
Use this endpoint to obtain details, create, update or delete Mautic’s emails.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$emailApi = $api->newApi("emails", $auth, $apiUrl);

```

### Get Email[](https://developer.mautic.org/#get-email)
```
<?php

//...
$email = $emailApi->get($id);

```
```
{"email":{"isPublished":true,"dateAdded":"2016-10-25T18:51:17+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":560,"name":"test","subject":"API test email","language":"en","category":null,"fromAddress":null,"fromName":null,"replyToAddress":null,"bccAddress":null,"customHtml":"<h1>Hi there!<\/h1>","plainText":null,"template":null,"emailType":"list","publishUp":null,"publishDown":null,"readCount":0,"sentCount":0,"revision":1,"assetAttachments":[],"variantStartDate":null,"variantSentCount":0,"variantReadCount":0,"variantParent":null,"variantChildren":[],"translationParent":null,"translationChildren":[],"unsubscribeForm":null,"dynamicContent":[{"tokenName":null,"content":null,"filters":[{"content":null,"filters":[{"glue":null,"field":null,"object":null,"type":null,"operator":null,"display":null,"filter":null}]}]}],"lists":[{"createdByUser":"John Doe","modifiedByUser":null,"id":256,"name":"test","alias":"test29","description":null}]}}
```

Get an individual email by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /emails/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Email Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the email  
name | string | Internal name of the email  
subject | stringl | Subject of the email  
fromAddress | string | The from email address if it’s different than the one in the Mautic configuration  
fromName | string | The from name if it’s different than the one in the Mautic configuration  
replyToAddress | string | The reply to email address if it’s different than the one in the Mautic configuration  
bccAddress | string | The BCC email address if it’s different than the one in the Mautic configuration  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the email should be published  
publishDown | datetime/null | Date/time the email should be un published  
dateAdded | datetime | Date/time email was created  
createdBy | int | ID of the user that created the email  
createdByUser | string | Name of the user that created the email  
dateModified | datetime/null | Date/time email was last modified  
modifiedBy | int | ID of the user that last modified the email  
modifiedByUser | string | Name of the user that last modified the email  
language | string | Language locale of the email  
readCount | int | Total email read count  
sentCount | int | Total email sent count  
revision | int | Email revision  
customHtml | string | The HTML content of the email  
plainText | string | The plain text content of the email  
template | string | The name of the template used as the base for the email  
emailType | string | If it is a segment (former list) email or template email. Possible values are ‘list’ and 'template’  
translationChildren | array | Array of Page entities for translations of this landing page  
translationParent | object | The parent/main page if this is a translation  
variantSentCount | int | Sent count since variantStartDate  
variantReadCount | int | Read count since variantStartDate  
variantChildren | array | Array of Email entities for variants of this landing email  
variantParent | object | The parent/main email if this is a variant (A/B test)  
variantSettings | array | The properties of the A/B test  
variantStartDate | datetime/null | The date/time the A/B test began  
category | object/null | Category information  
unsubscribeForm | int | Id of the form displayed in the unsubscribe page  
dynamicContent | object | Dynamic content configuration  
lists | array | Array of segment IDs which should be added to the segment email  
assetAttachments | array | asset IDs Array for email attachment  
### List Emails[](https://developer.mautic.org/#list-emails)
```
<?php
// ...

$emails = $emailApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"emails":[{"isPublished":true,"dateAdded":"2016-10-25T18:51:17+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":560,"name":"test","subject":"API test email","language":"en","category":null,"fromAddress":null,"fromName":null,"replyToAddress":null,"bccAddress":null,"customHtml":"<h1>Hi there!<\/h1>","plainText":null,"template":null,"emailType":"list","publishUp":null,"publishDown":null,"readCount":0,"sentCount":0,"revision":1,"assetAttachments":[],"variantStartDate":null,"variantSentCount":0,"variantReadCount":0,"variantParent":null,"variantChildren":[],"translationParent":null,"translationChildren":[],"unsubscribeForm":null,"dynamicContent":[{"tokenName":null,"content":null,"filters":[{"content":null,"filters":[{"glue":null,"field":null,"object":null,"type":null,"operator":null,"display":null,"filter":null}]}]}],"lists":[{"createdByUser":"John Doe","modifiedByUser":null,"id":256,"name":"test","alias":"test29","description":null}]}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /emails`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Email](https://developer.mautic.org/#get-email).
### Create Email[](https://developer.mautic.org/#create-email)
```
<?php 

$data = array(
    'title'        => 'Email A',
    'description' => 'This is my first email created via API.',
    'isPublished' => 1
);

$email = $emailApi->create($data);

```

Create a new email.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /emails/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the email  
name | string | Internal name of the email  
subject | stringl | Subject of the email  
fromAddress | string | The from email address if it’s different than the one in the Mautic configuration  
fromName | string | The from name if it’s different than the one in the Mautic configuration  
replyToAddress | string | The reply to email address if it’s different than the one in the Mautic configuration  
bccAddress | string | The BCC email address if it’s different than the one in the Mautic configuration  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the email should be published  
publishDown | datetime/null | Date/time the email should be un published  
language | string | Language locale of the email  
readCount | int | Total email read count  
sentCount | int | Total email sent count  
revision | int | Email revision  
customHtml | string | The HTML content of the email  
plainText | string | The plain text content of the email  
template | string | The name of the template used as the base for the email  
emailType | string | If it is a segment (former list) email or template email. Possible values are 'list’ and 'template’  
translationChildren | array | Array of Page entities for translations of this landing page  
translationParent | object | The parent/main page if this is a translation  
variantSentCount | int | Sent count since variantStartDate  
variantReadCount | int | Read count since variantStartDate  
variantChildren | array | Array of Email entities for variants of this landing email  
variantParent | object | The parent/main email if this is a variant (A/B test)  
variantSettings | array | The properties of the A/B test  
variantStartDate | datetime/null | The date/time the A/B test began  
category | object/null | Category information  
unsubscribeForm | int | Id of the form displayed in the unsubscribe page  
dynamicContent | object | Dynamic content configuration  
lists | array | Array of segment IDs which should be added to the segment email  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Email](https://developer.mautic.org/#get-email).
### Edit Email[](https://developer.mautic.org/#edit-email)
```
<?php

$id   = 1;
$data = array(
    'title'        => 'New email title',
    'isPublished' => 0
);

// Create new a email of ID 1 is not found?
$createIfNotFound = true;

$email = $emailApi->edit($id, $data, $createIfNotFound);

```

Edit a new email. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a email if the given ID does not exist and clears all the email information, adds the information from the request. **PATCH** fails if the email with the given ID does not exist and updates the email field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a email and return a 404 if the email is not found:
`PATCH /emails/ID/edit`
To edit a email and create a new one if the email is not found:
`PUT /emails/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the email  
name | string | Internal name of the email  
subject | stringl | Subject of the email  
fromAddress | string | The from email address if it’s different than the one in the Mautic configuration  
fromName | string | The from name if it’s different than the one in the Mautic configuration  
replyToAddress | string | The reply to email address if it’s different than the one in the Mautic configuration  
bccAddress | string | The BCC email address if it’s different than the one in the Mautic configuration  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the email should be published  
publishDown | datetime/null | Date/time the email should be un published  
language | string | Language locale of the email  
readCount | int | Total email read count  
sentCount | int | Total email sent count  
revision | int | Email revision  
customHtml | string | The HTML content of the email  
plainText | string | The plain text content of the email  
template | string | The name of the template used as the base for the email  
emailType | string | If it is a segment (former list) email or template email. Possible values are 'list’ and 'template’  
translationChildren | array | Array of Page entities for translations of this landing page  
translationParent | object | The parent/main page if this is a translation  
variantSentCount | int | Sent count since variantStartDate  
variantReadCount | int | Read count since variantStartDate  
variantChildren | array | Array of Email entities for variants of this landing email  
variantParent | object | The parent/main email if this is a variant (A/B test)  
variantSettings | array | The properties of the A/B test  
variantStartDate | datetime/null | The date/time the A/B test began  
category | object/null | Category information  
unsubscribeForm | int | Id of the form displayed in the unsubscribe page  
dynamicContent | object | Dynamic content configuration  
lists | array | Array of segment IDs which should be added to the segment email  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the email was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Email](https://developer.mautic.org/#get-email).
### Delete Email[](https://developer.mautic.org/#delete-email)
```
<?php

$email = $emailApi->delete($id);

```

Delete a email.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /emails/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Email](https://developer.mautic.org/#get-email).
### Send Email to Contact[](https://developer.mautic.org/#send-email-to-contact)
```
<?php

$email = $emailApi->sendToContact($emailId, $contactId);

```

Send a predefined email to existing contact.
Assets can be referenced for attaching documents (either ids of existing assets or ids returned by the 
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /emails/ID/contact/CONTACT_ID/send`
**Post Parameters**
Name | Type | Description  
---|---|---  
tokens | array | Array of tokens in email  
assetAttachments | array | Array of asset ids  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties** `json {     "success": 1 } `
### Send Email to Segment[](https://developer.mautic.org/#send-email-to-segment)
```
<?php

$email = $emailApi->send($id);

```

Send a segment email to linked segment(s).
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /emails/ID/send`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties** `json {     "success": 1,     "sentCount": 1,     "failedCount": 0 } `
### Create a reply to a send email send row[](https://developer.mautic.org/#create-a-reply-to-a-send-email-send-row)
This endpoint can create a record that a specific email stat row received a reply. It will also mark an email send stat as read.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /emails/reply/TRACKING_HASH`
Tracking hash is created as unique hash for each email send stat record.
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties** `json {     "success": 1, } `
## Fields[](https://developer.mautic.org/#fields)
Use this endpoint to work with Mautic’s contact/company fields.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$assetApi = $api->newApi("assets", $auth, $apiUrl);

// Get contact field context:
$fieldApi = $api->newApi("contactFields", $auth, $apiUrl);

// Or use 'companyFields' for company fields:
$fieldApi = $api->newApi("companyFields", $auth, $apiUrl);

```

### Get Field[](https://developer.mautic.org/#get-field)
```
<?php

//...
$field = $fieldApi->get($id);

```
```
{"field":{"isPublished":true,"dateAdded":"2016-11-10T13:02:52+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":165,"label":"API test field","alias":"api_test_field11","type":"text","group":null,"order":36,"object":"lead","defaultValue":null,"isRequired":false,"isPubliclyUpdatable":false,"isUniqueIdentifier":0,"properties":[]}}
```

Get an individual field by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /fields/contact/ID` or `GET /fields/company/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Field Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the field  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the field should be published  
publishDown | datetime/null | Date/time the field should be un published  
dateAdded | datetime | Date/time field was created  
createdBy | int | ID of the user that created the field  
createdByUser | string | Name of the user that created the field  
dateModified | datetime/null | Date/time field was last modified  
modifiedBy | int | ID of the user that last modified the field  
modifiedByUser | string | Name of the user that last modified the field  
label | string | Name of the field  
alias | string | Unique alias of the field used in the form field name attributes  
description | string/null | Description of the field  
type | string | Field type  
group | string | Groupd of the fields where the field belongs  
order | int | Order number of the field  
object | string | Which object use the field. Contact (lead) or Company.  
defaultValue | string | Default value of the field.  
isRequired | boolean | True if the field is required.  
isPubliclyUpdatable | boolean | True if the field value can be changed from public requests. The tracking pixel query for example.  
isUniqueIdentifier | boolean | True if the field is unique identifier and so the contacts should merge if the value of this field is the same.  
properties | array | Field options if the field type needs some.  
### List Contact Fields[](https://developer.mautic.org/#list-contact-fields)
```
<?php

//...
$fields = $fieldApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":71,"fields":[{"isPublished":true,"dateAdded":"2016-10-12T11:31:13+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":"2016-10-12T11:31:30+00:00","modifiedBy":1,"modifiedByUser":"John Doe","id":100,"label":"Multiselect test","alias":"multiselect_test","type":"multiselect","group":"core","order":3,"object":"lead","defaultValue":null,"isRequired":false,"isPubliclyUpdatable":false,"isUniqueIdentifier":false,"properties":{"list":[{"label":"PHP","value":"php"},{"label":"JS","value":"js"},{"label":"English","value":"en"}]}},[...]]}
```

**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /fields/contact` or `GET /fields/company`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Field Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the field  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the field should be published  
publishDown | datetime/null | Date/time the field should be un published  
dateAdded | datetime | Date/time field was created  
createdBy | int | ID of the user that created the field  
createdByUser | string | Name of the user that created the field  
dateModified | datetime/null | Date/time field was last modified  
modifiedBy | int | ID of the user that last modified the field  
modifiedByUser | string | Name of the user that last modified the field  
label | string | Name of the field  
alias | string | Unique alias of the field used in the form field name attributes  
description | string/null | Description of the field  
type | string | Field type  
group | string | Groupd of the fields where the field belongs  
order | int | Order number of the field  
object | string | Which object use the field. Contact (lead) or Company.  
defaultValue | string | Default value of the field.  
isRequired | boolean | True if the field is required.  
isPubliclyUpdatable | boolean | True if the field value can be changed from public requests. The tracking pixel query for example.  
isUniqueIdentifier | boolean | True if the field is unique identifier and so the contacts should merge if the value of this field is the same.  
properties | array | Field options if the field type needs some.  
### Create Field[](https://developer.mautic.org/#create-field)
```
<?php 

$data = array(
    'label' => 'API test field',
    'type' => 'text',
);

$field = $fieldApi->create($data);

```

**Multiselect Field** “`php <?php
$data = array( ‘label’ => 'API test field’, 'type’ => 'multiselect’, 'isPubliclyUpdatable’ => true, 'properties’ => array( 'list’ => array( array( 'label’ => 'label 1’, 'value’ => 'value 1’ ), array( 'label’ => 'label 2’, 'value’ => 'value 2’ ) ) ) );
$field = $fieldApi->create($data);
Create a new field.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /fields/contact/new` or `POST /fields/company/new`
**Post Parameters**
Name | Description  
---|---  
label | string  
alias | string  
description | string/null  
type | string  
group | string  
order | int  
object | string  
defaultValue | string  
isRequired | boolean  
isPubliclyUpdatable | boolean  
isUniqueIdentifier | boolean  
properties | array  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Field](https://developer.mautic.org/#get-field).
### Edit Field[](https://developer.mautic.org/#edit-field)
```
<?php

$id   = 1;
$data = array(
    'label' => 'API test field',
    'type' => 'text',
);

// Create new a field of ID 1 is not found?
$createIfNotFound = true;

$field = $fieldApi->edit($id, $data, $createIfNotFound);

```

Edit a new field. Field that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a field if the given ID does not exist and clears all the field infieldation, adds the infieldation from the request. **PATCH** fails if the field with the given ID does not exist and updates the field field values with the values field the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a field and return a 404 if the field is not found:
`PATCH /fields/contact/ID/edit` or `PATCH /fields/company/ID/edit`
To edit a field and create a new one if the field is not found:
`PUT /fields/contact/ID/edit` or `PUT /fields/company/ID/edit`
**Post Parameters**
Name | Description  
---|---  
label | string  
alias | string  
description | string/null  
type | string  
group | string  
order | int  
object | string  
defaultValue | string  
isRequired | boolean  
isPubliclyUpdatable | boolean  
isUniqueIdentifier | boolean  
properties | array  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the field was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Field](https://developer.mautic.org/#get-field).
### Delete Field[](https://developer.mautic.org/#delete-field)
```
<?php

$field = $fieldApi->delete($id);

```

Delete a field.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /fields/contact/ID/delete` or `DELETE /fields/company/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Field](https://developer.mautic.org/#get-field).
## Files[](https://developer.mautic.org/#files)
This endpoint is useful for working with files of images and assets.
_Note: Assets doesn’t have nor support subdirectories._
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$filesApi = $api->newApi("files", $auth, $apiUrl);

```

### Get List of files[](https://developer.mautic.org/#get-list-of-files)
```
<?php

// Get list of root media/images directory:
$files = $filesApi->getList();

// Get list of some sub-directory (flags in this case) of media/images:
$filesApi->setFolder('images/flags');
$files = $filesApi->getList();

// Get list of root media/files directory where the asset files are stored:
$files = $filesApi->setFolder('assets');
$files = $filesApi->getList();

```
```
{"files":{"3":"0b0f20185251d1c0cd5ff17950213fc9.png","4":"0f530efdf837d3005bd2ab81cc30e878.jpeg","5":"162a694f4101cb06c27c0a0699bd87c4.png","6":"16ada2e2ecfa3f1d8cbb5d633f0bd8c6.png",...}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /files/images` to get root images directory `GET /files/images?subdir=flags` to get images/flags directory `GET /files/assets` to get root assets directory
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Response Properties**
Name | Type | Description  
---|---|---  
files | array | List of requested files and directories  
### Create File[](https://developer.mautic.org/#create-file)
```
<?php
$data = array(
    'file' => dirname(__DIR__).'/'.'mauticlogo.png' // Must be a path to an existing file
);

// Create a file in root media/images directory:
$response = $fileApi->create($data);

// Create a file in some sub-directory (flags in this case) of media/images:
$filesApi->setFolder('images/flags');
$response = $fileApi->create($data);

// Create a file in media/files directory where the asset files are stored:
$files = $filesApi->setFolder('assets');
$response = $fileApi->create($data);

```

Creates a file. The file is sent via regular POST files array like a browser sends it during file upload.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /files/DIR/new`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "file":{       "link":"http:\/\/yourmautic\/media\/images\/2b912b934dd2a4da49a226d0bf68bfea.png",     "name":"2b912b934dd2a4da49a226d0bf68bfea.png"   } } `
**Response Properties**
Name | Type | Description  
---|---|---  
link | string | Appears only for files in image directory, not for assets  
name | string | File name of newly created file  
### Delete File[](https://developer.mautic.org/#delete-file)
```
<?php
// Delete a file from root media/images directory:
$response = $fileApi->delete($fileName);

// Delete a file from some sub-directory (flags in this case) of media/images:
$filesApi->setFolder('images/flags');
$response = $fileApi->delete($fileName);

// Delete a file from media/files directory where the asset files are stored:
$files = $filesApi->setFolder('assets');
$response = $fileApi->delete($fileName);

```

Delete a file.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /files/DIR/FILE/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "success": true } `
## Forms[](https://developer.mautic.org/#forms)
Use this endpoint to obtain details on Mautic’s forms.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$formApi  = $api->newApi("forms", $auth, $apiUrl);

```

### Get Form[](https://developer.mautic.org/#get-form)
```
<?php

//...
$form = $formApi->get($id);

```
```
{"form":{"id":3,"name":"Newlsetter","alias":"newsletter","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"cachedHtml":"\n\n<script...","template":null,"fields":{"26":{"id":26,"label":"Email","showLabel":false,"alias":"email","type":"text","defaultValue":null,"isRequired":true,"validationMessage":"Email is required","helpMessage":null,"order":1,"properties":{"placeholder":"Email address"},"labelAttributes":null,"inputAttributes":null,"containerAttributes":null},"27":{"id":27,"label":"Submit","showLabel":true,"alias":"submit","type":"button","defaultValue":null,"isRequired":false,"validationMessage":null,"helpMessage":null,"order":4,"properties":[],"labelAttributes":null,"inputAttributes":null,"containerAttributes":null}},"actions":{"4":{"id":4,"type":"email.send.lead","name":"Send thank you email","description":null,"order":1,"properties":{"email":21}}}}}
```

Get an individual form by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /forms/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Form Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the form  
name | string | Name of the form  
description | string/null | Description of the form  
alias | string | Used to generate the URL for the form  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the form should be published  
publishDown | datetime/null | Date/time the form should be un published  
dateAdded | datetime | Date/time form was created  
createdBy | int | ID of the user that created the form  
createdByUser | string | Name of the user that created the form  
dateModified | datetime/null | Date/time form was last modified  
modifiedBy | int | ID of the user that last modified the form  
modifiedByUser | string | Name of the user that last modified the form  
cachedHtml | string | Cached HTML for the form  
template | string/null | Name of the template used to generate the HTML  
fields | array | Array of Field entities for the form. See below.  
actions | array | Array of Action entities for the form. See below.  
**Field Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the field  
label | string | Label of the field  
showLabel | bool | Display the label of the field  
alias | string | Alias of the field (used as the database column)  
type | string | Field type  
defaultValue | string | Default value  
isRequired | bool | Field is required  
validationMessage | string | Validation message if required field is left empty  
helpMessage | string | Help message for the field  
order | int | Order of the field  
properties | array | Configured properties for the field  
labelAttributes | string/null | Custom HTML attributes for the label  
inputAttributes | Custom HTML attributes for the input  
containerAttributes | Custom HTML attributes for the container  
**Action Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the action  
type | string | Action type  
name | string | Name of the action  
description | string/null | Description of the action  
order | int | Action order  
properties | array | Configured properties for the action  
### List Forms[](https://developer.mautic.org/#list-forms)
```
<?php
// ...

$forms = $formApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"forms":[{"id":3,"name":"Newlsetter","alias":"newsletter","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"cachedHtml":"\n\n<script...","template":null,"fields":{"26":{"id":26,"label":"Email","showLabel":false,"alias":"email","type":"text","defaultValue":null,"isRequired":true,"validationMessage":"Email is required","helpMessage":null,"order":1,"properties":{"placeholder":"Email address"},"labelAttributes":null,"inputAttributes":null,"containerAttributes":null},"27":{"id":27,"label":"Submit","showLabel":true,"alias":"submit","type":"button","defaultValue":null,"isRequired":false,"validationMessage":null,"helpMessage":null,"order":4,"properties":[],"labelAttributes":null,"inputAttributes":null,"containerAttributes":null}},"actions":{"4":{"id":4,"type":"email.send.lead","name":"Send thank you email","description":null,"order":1,"properties":{"email":21}}}}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /forms`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### Create Form[](https://developer.mautic.org/#create-form)
```
<?php

$data = array(
    'name' => 'test',
    'formType' => 'standalone',
    'description' => 'API test',
    'fields' => array(
        array(
            'label' => 'field name',
            'type' => 'text'
        )
    ),
    'actions' => array(
        array(
            'name' => 'action name',
            'description' => 'action desc',
            'type' => 'lead.pointschange',
            'properties' => array(
                'operator' => 'plus',
                'points' => 2
            )
        )
    )
);

$form = $formApi->create($data);

```

Create a new form.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /forms/new`
**Post Parameters**
Same as [Get Form](https://developer.mautic.org/#get-form). Form fields and actions can be created/edited via the forms/actions arrays in the form array.
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### Edit Form[](https://developer.mautic.org/#edit-form)
```
<?php

$id   = 1;
$data = array(
    'name' => 'test',
    'formType' => 'standalone',
    'description' => 'API test',
    'fields' => array(
        array(
            'label' => 'A field that will be added',
            'type' => 'text'
        ),
        array(
            'id' => 1,
            'label' => 'A field that will be edited',
            'type' => 'text'
        )
    ),
    'actions' => array(
        array(
            'name' => 'action name',
            'description' => 'action desc',
            'type' => 'lead.pointschange',
            'properties' => array(
                'operator' => 'plus',
                'points' => 2
            )
        )
    )
);

// Create new a form of ID 1 is not found?
$createIfNotFound = true;

$form = $formApi->edit($id, $data, $createIfNotFound);

```

Edit a new form. Note that this supports PUT or PATCH depending on the desired behavior.
Make sure that whenever you want to edit a form field that you include the form field id in the request. Fields without an id are assumed to be new fields.
**PUT** creates a form if the given ID does not exist and clears all the form information, adds the information from the request. Form fields and actions will be also deleted if not present in the request. **PATCH** fails if the form with the given ID does not exist and updates the form field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a form and return a 404 if the form is not found:
`PATCH /forms/ID/edit`
To edit a form and create a new one if the form is not found:
`PUT /forms/ID/edit`
**Post Parameters**
Same as [Get Form](https://developer.mautic.org/#get-form). Form fields and actions can be created/edited via the forms/actions arrays in the form array.
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the form was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### Delete Form[](https://developer.mautic.org/#delete-form)
```
<?php

$form = $formApi->delete($id);

```

Delete a form.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /forms/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### Delete Form Fields[](https://developer.mautic.org/#delete-form-fields)
The following examples will show how to delete fields with ID 56 and 59.
```
<?php

$form = $formApi->deleteFields($formId, array(56, 59));

```

Delete a form fields.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /forms/ID/fields/delete?fields[]=56&fields[]=59`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### Delete Form Actions[](https://developer.mautic.org/#delete-form-actions)
The following examples will show how to delete actions with ID 56 and 59.
```
<?php

$form = $formApi->deleteActions($formId, array(56, 59));

```

Delete a form actions.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /forms/ID/actions/delete?actions[]=56&actions[]=59`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Form](https://developer.mautic.org/#get-form).
### List Form Submissions[](https://developer.mautic.org/#list-form-submissions)
```
<?php

$submissions = $formApi->getSubmissions($formId, $searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":"1","submissions":[{"id":1,"ipAddress":{"ip":"127.0.0.1"},"form":{"id":25,"name":"test","alias":"test","category":null},"lead":{"id":2183,"points":0,"color":null,"title":null,"firstname":null,"lastname":null,"company":null,"position":null,"email":"test@test.test","phone":null,"mobile":null,"address1":null,"address2":null,"city":null,"state":null,"zipcode":null,"timezone":null,"country":null},"trackingId":null,"dateSubmitted":"2017-07-17T09:52:29+00:00","referer":"http:\/\/mautic.dev\/s\/forms\/preview\/25","page":null,"results":{"email":"test@test.test"}}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /forms/FORM_ID/submissions`
**Query Parameters**
Name | Description  
---|---  
formId | ID of the form you want to get submissions for  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response, also can use column of joined table with prefix. Sort by submitted date is `s.date_submitted`  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the submission  
ipAddress | array | Associative array containing IP address of the client who made the submission  
form | array | Simplified associative array of the form containing id, name, alias and category  
lead | array | Associative array of the lead containing the core values as well as custom fields  
dateSubmitted | string | Date time string holding the UTC date and time when the submission was made  
referer | string | HTTP referer info  
results | array | Associative array of the form fields as the keys and submission values  
### List Form Submissions for a contact[](https://developer.mautic.org/#list-form-submissions-for-a-contact)
```
<?php

$submissions = $formApi->getSubmissionsForContact($formId, $contactId, $searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /forms/FORM_ID/submissions/contact/CONTACT_ID`
Response and properties same as [Get Form Submissions](https://developer.mautic.org/#get-form-submissions). Parameters too except the ContactId was added.
### Get Form Submission[](https://developer.mautic.org/#get-form-submission)
```
<?php

//...
$form = $formApi->getSubmission($formId, $submissionId);

```
```
{"submission":{"id":1,"ipAddress":{"ip":"127.0.0.1"},"form":{"id":25,"name":"test","alias":"test","category":null},"lead":{"id":2183,"points":0,"color":null,"title":null,"firstname":null,"lastname":null,"company":null,"position":null,"email":"test@test.test","phone":null,"mobile":null,"address1":null,"address2":null,"city":null,"state":null,"zipcode":null,"timezone":null,"country":null},"trackingId":null,"dateSubmitted":"2017-07-17T09:52:29+00:00","referer":"http:\/\/mautic.dev\/s\/forms\/preview\/25","page":null,"results":{"form_id":"25","email":"test@test.test"}}}
```

Get an individual form submission by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /forms/FORM_ID/submissions/SUBMISSION_ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Form Properties**
Same as [Get Form Submissions](https://developer.mautic.org/#get-form-submissions).
## Marketing Messages[](https://developer.mautic.org/#marketing-messages)
Use this endpoint to obtain details, create, update or delete Mautic’s messages.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$messageApi = $api->newApi("messages", $auth, $apiUrl);

```

### Get Marketing Message[](https://developer.mautic.org/#get-marketing-message)
```
<?php

//...
$message = $messageApi->get($id);

```
```
{"message":{"isPublished":true,"dateAdded":"2017-02-08T15:00:34+01:00","dateModified":"2017-02-08T15:00:35+01:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":1,"modifiedByUser":"John Doe","id":26,"name":"Thanks for the feedback!","description":"","publishUp":null,"publishDown":null,"channels":[{"id":55,"channel":"email","channelId":1197,"channelName":"Email A","isEnabled":true},{"id":57,"channel":"notification","channelId":null,"channelName":null,"isEnabled":false},{"id":56,"channel":"sms","channelId":103,"channelName":"SMS A","isEnabled":false},{"id":91,"channel":"tweet","channelId":null,"channelName":null,"isEnabled":false}]}}
```

Get an individual marketing message by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /messages/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Marketing Message Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the message  
name | string | Internal name of the message  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the message should be published  
publishDown | datetime/null | Date/time the message should be un published  
dateAdded | datetime | Date/time message was created  
createdBy | int | ID of the user that created the message  
createdByUser | string | Name of the user that created the message  
dateModified | datetime/null | Date/time message was last modified  
modifiedBy | int | ID of the user that last modified the message  
modifiedByUser | string | Name of the user that last modified the message  
channels | array | Array of channels configured for the marketing message  
### List Marketing Messages[](https://developer.mautic.org/#list-marketing-messages)
```
<?php
// ...

$messages = $messageApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"messages":{"1":{"isPublished":true,"dateAdded":"2017-02-03T16:51:58+00:00","dateModified":"2017-02-03T19:11:41+00:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"Live long and prosper","description":null,"publishUp":null,"publishDown":null,"channels":[{"id":1,"channel":"email","channelId":44,"channelName":"Email A","isEnabled":true},{"id":2,"channel":"sms","channelId":1,"channelName":"SMS A","isEnabled":true},{"id":3,"channel":"notification","channelId":75,"channelName":null,"isEnabled":false}]}}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /messages`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Marketing Message](https://developer.mautic.org/#get-message).
### Create Marketing Message[](https://developer.mautic.org/#create-marketing-message)
```
<?php 

$data = array(
    'name'        => 'Marketing Message A',
    'description' => 'This is my first message created via API.',
    'isPublished' => 1,
    'channels' => array(
        'email' => array(
            'channel' => 'email',
            'channelId' => 44,
            'isEnabled' => true,
        ),
        'sms' => array(
            'channel' => 'sms',
            'channelId' => 1,
            'isEnabled' => true,
        ),
        'notification' => array(
            'channel' => 'notification',
            'channelId' => 75,
            'isEnabled' => false,
        )
    )
);

$message = $messageApi->create($data);

```

Create a new message.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /messages/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the message  
name | string | Internal name of the message  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the message should be published  
publishDown | datetime/null | Date/time the message should be un published  
channels | array | Array of channels  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Marketing Message](https://developer.mautic.org/#get-message).
### Edit Marketing Message[](https://developer.mautic.org/#edit-marketing-message)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New message title',
    'isPublished' => 0
);

// Create new a message of ID 1 is not found?
$createIfNotFound = true;

$message = $messageApi->edit($id, $data, $createIfNotFound);

```

Edit a new message. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a message if the given ID does not exist and clears all the message information, adds the information from the request. **PATCH** fails if the message with the given ID does not exist and updates the message field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a message and return a 404 if the message is not found:
`PATCH /messages/ID/edit`
To edit a message and create a new one if the message is not found:
`PUT /messages/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the message  
name | string | Internal name of the message  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the message should be published  
publishDown | datetime/null | Date/time the message should be un published  
channels | array | Array of channels  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the message was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Marketing Message](https://developer.mautic.org/#get-message).
### Delete Marketing Message[](https://developer.mautic.org/#delete-marketing-message)
```
<?php

$message = $messageApi->delete($id);

```

Delete a message.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /messages/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Marketing Message](https://developer.mautic.org/#get-message).
## Notes[](https://developer.mautic.org/#notes)
Use this endpoint to obtain details on Mautic’s contact notes.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$noteApi  = $api->newApi("notes", $auth, $apiUrl);

```

### Get Note[](https://developer.mautic.org/#get-note)
```
<?php

//...
$note = $noteApi->get($id);

```
```
{"note":{"id":39,"text":"Contact note created via API request","type":"general","dateTime":null,"lead":{"id":1405,"points":0,"color":null,"fields":{"core":{"firstname":{"id":"2","label":"First Name","alias":"firstname","type":"text","group":"core","field_order":"42","object":"lead","value":"Note API test"},"lastname":{"id":"3","label":"Last Name","alias":"lastname","type":"text","group":"core","field_order":"44","object":"lead","value":null},[...]},}}}}
```

Get an individual note by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /notes/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Note Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the note  
lead | array | data of the contact  
text | string | Note text  
type | string | Note type  
datetime | datetime | Date and time related to the note.  
### List Contact Notes[](https://developer.mautic.org/#list-contact-notes)
```
<?php

//...
$notes = $noteApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":24,"notes":[{"id":1,"text":"A test note","type":"general","dateTime":"2016-06-14T18:07:00+00:00","lead":{"id":1,"points":0,"color":null,"fields":[]}},[...]]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /notes`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Note Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the note  
lead | array | data of the contact  
text | string | Note text  
type | string | Note type  
datetime | datetime | Date and time related to the note.  
### Create Note[](https://developer.mautic.org/#create-note)
```
<?php 

$contactID = 1;

$data = array(
    'lead' => $contactID,
    'text' => 'Note A',
    'type' => 'general',
);

$note = $noteApi->create($data);

```

Create a new note.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /notes/new`
**Post Parameters**
Name | Description  
---|---  
text | string  
type | string  
datetime | datetime  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Note](https://developer.mautic.org/#get-note).
### Edit Note[](https://developer.mautic.org/#edit-note)
```
<?php

$id   = 1;
$data = array(
    'text' => 'Note B',
    'type' => 'general',
);

// Create new a note of ID 1 is not found?
$createIfNotFound = true;

$note = $noteApi->edit($id, $data, $createIfNotFound);

```

Edit a new note. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a note if the given ID does not exist and clears all the note information, adds the information from the request. **PATCH** fails if the note with the given ID does not exist and updates the note field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a note and return a 404 if the note is not found:
`PATCH /notes/ID/edit`
To edit a note and create a new one if the note is not found:
`PUT /notes/ID/edit`
**Post Parameters**
Name | Description  
---|---  
text | string  
type | string  
datetime | datetime  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the note was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Note](https://developer.mautic.org/#get-note).
### Delete Note[](https://developer.mautic.org/#delete-note)
```
<?php

$note = $noteApi->delete($id);

```

Delete a note.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /notes/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Note](https://developer.mautic.org/#get-note).
## Notifications[](https://developer.mautic.org/#notifications)
Use this endpoint to obtain details on Mautic’s notifications.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth        = new ApiAuth();
$auth            = $initAuth->newAuth($settings);
$apiUrl          = "https://your-mautic.com";
$api             = new MauticApi();
$notificationApi = $api->newApi("notifications", $auth, $apiUrl);

```

### Get Notification[](https://developer.mautic.org/#get-notification)
```
<?php

//...
$notification = $notificationApi->get($id);

```
```
{"notification":{"isPublished":true,"dateAdded":"2016-09-14T14:03:05+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":"2016-09-15T08:40:46+00:00","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"The first notification","heading":"The first notification Heading","message":"The first notification Message","url":"http:\/\/mautic.org","language":"en","category":null,"publishUp":null,"publishDown":null,"readCount":0,"sentCount":0}}
```

Get an individual notification by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /notifications/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Notification Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the notification  
name | string | Title of the notification  
heading | string | Heading of the notification  
message | string | Message of the notification  
url | string | URL to go to when the notification is clicked  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the notification should be published  
publishDown | datetime/null | Date/time the notification should be un published  
dateAdded | datetime | Date/time notification was created  
createdBy | int | ID of the user that created the notification  
createdByUser | string | Name of the user that created the notification  
dateModified | datetime/null | Date/time notification was last modified  
modifiedBy | int | ID of the user that last modified the notification  
modifiedByUser | string | Name of the user that last modified the notification  
language | string | Language locale of the notification  
readCount | int | Total notification read count  
sentCount | int | Unique notification sent count  
category | null/object | Category  
### List Notifications[](https://developer.mautic.org/#list-notifications)
```
<?php
// ...

$notifications = $notificationApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"notifications":[{"isPublished":true,"dateAdded":"2016-09-14T14:03:05+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":"2016-09-15T08:40:46+00:00","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"The first notification","heading":"The first notification Heading","message":"The first notification Message","url":"http:\/\/mautic.org","language":"en","category":null,"publishUp":null,"publishDown":null,"readCount":0,"sentCount":0}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /notifications`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Notification](https://developer.mautic.org/#get-notification).
### Create Notification[](https://developer.mautic.org/#create-notification)
```
<?php 

$data = array(
    'name'    => 'Notification A',
    'heading' => 'Hello World!'
    'message' => 'This is my first notification created via API.',
);

$notification = $notificationApi->create($data);

```

Create a new notification.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /notifications/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the notification  
name | string | Title of the notification  
heading | string | Heading of the notification  
message | string | Message of the notification  
url | string | URL to go to when the notification is clicked  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the notification should be published  
publishDown | datetime/null | Date/time the notification should be un published  
language | string | Language locale of the notification  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Notification](https://developer.mautic.org/#get-notification).
### Edit Notification[](https://developer.mautic.org/#edit-notification)
```
<?php

$id   = 1;
$data = array(
    'name'    => 'Notification A',
    'heading' => 'Hello World!'
    'message' => 'This is my first notification created via API.',
);

// Create new a notification of ID 1 is not found?
$createIfNotFound = true;

$notification = $notificationApi->edit($id, $data, $createIfNotFound);

```

Edit a new notification. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a notification if the given ID does not exist and clears all the notification information, adds the information from the request. **PATCH** fails if the notification with the given ID does not exist and updates the notification field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a notification and return a 404 if the notification is not found:
`PATCH /notifications/ID/edit`
To edit a notification and create a new one if the notification is not found:
`PUT /notifications/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the notification  
name | string | Title of the notification  
heading | string | Heading of the notification  
message | string | Message of the notification  
url | string | URL to go to when the notification is clicked  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the notification should be published  
publishDown | datetime/null | Date/time the notification should be un published  
language | string | Language locale of the notification  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the notification was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Notification](https://developer.mautic.org/#get-notification).
### Delete Notification[](https://developer.mautic.org/#delete-notification)
```
<?php

$notification = $notificationApi->delete($id);

```

Delete a notification.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /notifications/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Notification](https://developer.mautic.org/#get-notification).
## Pages[](https://developer.mautic.org/#pages)
Use this endpoint to obtain details on Mautic’s landing pages.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$pageApi  = $api->newApi("pages", $auth, $apiUrl);

```

### Get Page[](https://developer.mautic.org/#get-page)
```
<?php

//...
$page = $pageApi->get($id);

```
```
{"page":{"id":3,"title":"Webinar Landing Page","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":"Events","language":"en","template":"blank","customHtml":"<!DOCTYPE ...","hits":0,"uniqueHits":0,"variantHits":0,"revision":1,"metaDescription":null,"redirectType":null,"redirectUrl":null,"translationChildren":[],"translationParent":null,"variantChildren":[],"variantParent":null,"variantSettings":[],"variantStartDate":null}}
```

Get an individual page by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /pages/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Page Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the page  
title | string | Title of the page  
description | string/null | Description of the page  
alias | string | Used to generate the URL for the page  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the page should be published  
publishDown | datetime/null | Date/time the page should be un published  
dateAdded | datetime | Date/time page was created  
createdBy | int | ID of the user that created the page  
createdByUser | string | Name of the user that created the page  
dateModified | datetime/null | Date/time page was last modified  
modifiedBy | int | ID of the user that last modified the page  
modifiedByUser | string | Name of the user that last modified the page  
language | string | Language locale of the page  
template | string | Template of the page  
customHtml | string | Static HTML of the page  
hits | int | Total page hit count  
uniqueHits | int | Unique page hit count  
revision | int | Page revision  
metaDescription | Meta description for the page’s   
redirectType | int | If unpublished, redirect with 301 or 302  
redirectUrl | string | If unpublished, the URL to redirect to if redirectType is set  
translationChildren | array | Array of Page entities for translations of this landing page  
translationParent | object | The parent/main page if this is a translation  
variantHits | Hit count since variantStartDate  
variantChildren | array | Array of Page entities for variants of this landing page  
variantParent | object | The parent/main page if this is a variant (A/B test)  
variantSettings | array | The properties of the A/B test  
variantStartDate | datetime/null | The date/time the A/B test began  
### List Pages[](https://developer.mautic.org/#list-pages)
```
<?php
// ...

$pages = $pageApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"pages":[{"id":3,"title":"Webinar Landing Page","description":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-15T15:06:02-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-20T13:11:56-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":"Events","language":"en","template":"blank","hits":0,"uniqueHits":0,"variantHits":0,"revision":1,"metaDescription":null,"redirectType":null,"redirectUrl":null,"translationChildren":[],"translationParent":null,"variantChildren":[],"variantParent":null,"variantSettings":[],"variantStartDate":null}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /pages`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Page](https://developer.mautic.org/#get-page).
### Create Page[](https://developer.mautic.org/#create-page)
```
<?php

$data = array(
    'title'        => 'Page A',
    'description' => 'This is my first page created via API.',
    'isPublished' => 1
);

$page = $pageApi->create($data);

```

Create a new page.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /pages/new`
**Post Parameters**
Name | Description  
---|---  
title | Page title is the only required field  
alias | string  
description | A description of the page.  
isPublished | A value of 0 or 1  
language | string  
metaDescription | Meta description for the page’s   
redirectType | int  
redirectUrl | string  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Page](https://developer.mautic.org/#get-page).
### Edit Page[](https://developer.mautic.org/#edit-page)
```
<?php

$id   = 1;
$data = array(
    'title'        => 'New page title',
    'isPublished' => 0
);

// Create new a page of ID 1 is not found?
$createIfNotFound = true;

$page = $pageApi->edit($id, $data, $createIfNotFound);

```

Edit a new page. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a page if the given ID does not exist and clears all the page information, adds the information from the request. **PATCH** fails if the page with the given ID does not exist and updates the page field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a page and return a 404 if the page is not found:
`PATCH /pages/ID/edit`
To edit a page and create a new one if the page is not found:
`PUT /pages/ID/edit`
**Post Parameters**
Name | Description  
---|---  
title | Page title is the only required field  
alias | Name alias generated automatically if not set  
description | A description of the page.  
isPublished | A value of 0 or 1  
language | string  
metaDescription | Meta description for the page’s   
redirectType | int  
redirectUrl | string  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the page was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Page](https://developer.mautic.org/#get-page).
### Delete Page[](https://developer.mautic.org/#delete-page)
```
<?php

$page = $pageApi->delete($id);

```

Delete a page.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /pages/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Page](https://developer.mautic.org/#get-page).
## Point Actions[](https://developer.mautic.org/#point-actions)
Use this endpoint to obtain details on Mautic’s point actions.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$pointApi = $api->newApi("points", $auth, $apiUrl);

```

### Get Point Action[](https://developer.mautic.org/#get-point-action)
```
<?php

//...
$point = $pointApi->get($id);

```
```
{"point":{"id":1,"name":"Opens Email","description":null,"type":"email.send","isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-19T00:34:11-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-19T00:41:44-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","delta":10,"properties":{"emails":[35]},"category":null}}
```

Get an individual point action by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Point Action Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the point  
name | string | Name of the point  
description | string/null | Description of the point  
category | string | Category name  
type | string | Point action type  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the point should be published  
publishDown | datetime/null | Date/time the point should be un published  
dateAdded | datetime | Date/time point was created  
createdBy | int | ID of the user that created the point  
createdByUser | string | Name of the user that created the point  
dateModified | datetime/null | Date/time point was last modified  
modifiedBy | int | ID of the user that last modified the point  
modifiedByUser | string | Name of the user that last modified the point  
delta | int | The number of points to give the lead when executing this action  
properties | array | Configured properties for this point action  
### List Point Actions[](https://developer.mautic.org/#list-point-actions)
```
<?php
// ...

$points = $pointApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"points":[{"id":1,"name":"Opens Email","description":null,"category":null"type":"email.send","isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-19T00:34:11-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-19T00:41:44-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","delta":10,"properties":{"emails":[35]}}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action).
### Create Point Action[](https://developer.mautic.org/#create-point-action)
```
<?php 

$data = array(
    'name' => 'test',
    'delta' => 5,
    'type' => 'page.hit',
    'description' => 'created as a API test'
);

$point = $pointApi->create($data);

```

Create a new point action.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /points/new`
**Post Parameters**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action). Point Action fields and actions can be created/edited via the point actions/actions arrays in the point action array.
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action).
### Edit Point Action[](https://developer.mautic.org/#edit-point-action)
```
<?php

$id   = 1;
$data = array(
    'name' => 'test',
    'delta' => 5,
    'type' => 'page.hit',
    'description' => 'created as a API test'
);

// Create new a point action of ID 1 is not found?
$createIfNotFound = true;

$point = $pointApi->edit($id, $data, $createIfNotFound);

```

Edit a new point action. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a point action if the given ID does not exist and clears all the point action inpoint actionation, adds the inpoint actionation from the request. Point Action fields and actions will be also deleted if not present in the request. **PATCH** fails if the point action with the given ID does not exist and updates the point action field values with the values point action the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a point action and return a 404 if the point action is not found:
`PATCH /points/ID/edit`
To edit a point action and create a new one if the point action is not found:
`PUT /points/ID/edit`
**Post Parameters**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action). Point Action fields and actions can be created/edited via the point actions/actions arrays in the point action array.
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the point action was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action).
### Delete Point Action[](https://developer.mautic.org/#delete-point-action)
```
<?php

$point = $pointApi->delete($id);

```

Delete a point action.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /points/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Point Action](https://developer.mautic.org/#get-point-action).
### Get Point Action Types[](https://developer.mautic.org/#get-point-action-types)
```
<?php

$point = $pointApi->getPointActionTypes();

```

Get array of available Point Action Types
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points/actions/types`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
```
{"pointActionTypes":{"asset.download":"Downloads an asset","email.send":"Is sent an email","email.open":"Opens an email","form.submit":"Submits a form","page.hit":"Visits a landing page","url.hit":"Visits specific URL"}}
```

See JSON code example.
## Point Triggers[](https://developer.mautic.org/#point-triggers)
Use this endpoint to obtain details on Mautic’s point triggers.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth   = new ApiAuth();
$auth       = $initAuth->newAuth($settings);
$apiUrl     = "https://your-mautic.com";
$api        = new MauticApi();
$triggerApi = $api->newApi("pointTriggers", $auth, $apiUrl);

```

### Get Point Trigger[](https://developer.mautic.org/#get-point-trigger)
```
<?php

//...
$trigger = $triggerApi->get($id);

```
```
{"trigger":{"id":1,"name":"Trigger test","description":null,"category":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-23T03:20:42-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":null,"modifiedBy":null,"modifiedByUser":null,l,"points":10,"color":"ab5959","events":{"1":{"id":1,"type":"email.send","name":"Send email","description":null,"order":1,"properties":{"email":21}}}}}
```

Get an individual point trigger by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points/triggers/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Point Trigger Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the point  
name | string | Name of the point  
description | string/null | Description of the point  
category | string | Category name  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the point should be published  
publishDown | datetime/null | Date/time the point should be un published  
dateAdded | datetime | Date/time point was created  
createdBy | int | ID of the user that created the point  
createdByUser | string | Name of the user that created the point  
dateModified | datetime/null | Date/time point was last modified  
modifiedBy | int | ID of the user that last modified the point  
modifiedByUser | string | Name of the user that last modified the point  
points | int | The minimum number of points before the trigger events are executed  
color | string | Color hex to highlight the lead with. This value does NOT include the pound sign (#)  
events | array | Array of TriggerEvent entities for this trigger. See below.  
**Trigger Event Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the event  
type | string | Event type  
name | string | Name of the event  
description | string | Description of the event  
order | int | Event order  
properties | array | Configured properties for the event  
### List Point Triggers[](https://developer.mautic.org/#list-point-triggers)
```
<?php
// ...

$triggers = $triggerApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"triggers":[{"id":1,"name":"Trigger test","description":null,"category":null,"isPublished":true,"publishUp":null,"publishDown":null,"dateAdded":"2015-07-23T03:20:42-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":null,"modifiedBy":null,"modifiedByUser":null,l,"points":10,"color":"ab5959","events":{"1":{"id":1,"type":"email.send","name":"Send email","description":null,"order":1,"properties":{"email":21}}}}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points/triggers`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger).
### Create Point Trigger[](https://developer.mautic.org/#create-point-trigger)
```
<?php 

$data = array(
    'name' => 'test',
    'description' => 'created as a API test',
    'points' => 5,
    'color' => '4e5d9d',
    'trigger_existing_leads' => false,
    'events' => array(
        array(
            'name' => 'tag test event',
            'description' => 'created as a API test',
            'type' => 'lead.changetags',
            'order' => 1,
            'properties' => array(
                'add_tags' => array('tag-a'),
                'remove_tags' => array()
            )
        ),
        array(
            'name' => 'send email test event',
            'description' => 'created as a API test',
            'type' => 'email.send',
            'order' => 2,
            'properties' => array(
                'email' => 1
            )
        )
    )
);

$trigger = $triggerApi->create($data);

```

Create a new point trigger.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /points/triggers/new`
**Post Parameters**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger). Point Trigger events can be created/edited via the point trigger event arrays placed in the point trigger array.
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger).
### Edit Point Trigger[](https://developer.mautic.org/#edit-point-trigger)
```
<?php

$id   = 1;
$data = array(
    'name' => 'test',
    'description' => 'created as a API test',
    'points' => 5,
    'color' => '4e5d9d',
    'trigger_existing_leads' => false,
    'events' => array(
        array(
            'name' => 'tag test event',
            'description' => 'created as a API test',
            'type' => 'lead.changetags',
            'order' => 1,
            'properties' => array(
                'add_tags' => array('tag-a'),
                'remove_tags' => array()
            )
        ),
        array(
            'name' => 'send email test event',
            'description' => 'created as a API test',
            'type' => 'email.send',
            'order' => 2,
            'properties' => array(
                'email' => 1
            )
        )
    )
);

// Create new a point trigger of ID 1 is not found?
$createIfNotFound = true;

$trigger = $triggerApi->edit($id, $data, $createIfNotFound);

```

Edit a new point trigger. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a point trigger if the given ID does not exist and clears all the point trigger information, adds the information from the request. Point Trigger events will be also deleted if not present in the request. **PATCH** fails if the point trigger with the given ID does not exist and updates the point trigger field values with the values point trigger the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a point trigger and return a 404 if the point trigger is not found:
`PATCH /points/triggers/ID/edit`
To edit a point trigger and create a new one if the point trigger is not found:
`PUT /points/triggers/ID/edit`
**Post Parameters**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger). Point Trigger events can be created/edited via the point triggers event arrays placed in the point trigger array.
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the point trigger was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger).
### Delete Point Trigger[](https://developer.mautic.org/#delete-point-trigger)
```
<?php

$trigger = $triggerApi->delete($id);

```

Delete a point trigger.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /points/triggers/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger).
### Delete Point Trigger Events[](https://developer.mautic.org/#delete-point-trigger-events)
The following examples will show how to delete events with ID 56 and 59.
```
<?php

$trigger = $triggerApi->deleteFields($triggerId, array(56, 59));

```

Delete a point trigger events.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /points/triggers/ID/events/delete?events[]=56&events[]=59`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Point Trigger](https://developer.mautic.org/#get-point-trigger).
### Get Point Trigger Event Types[](https://developer.mautic.org/#get-point-trigger-event-types)
```
<?php

$point = $pointApi->getEventTypes();

```

Get array of available Point Trigger Event Types
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /points/triggers/events/types`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
```
{"eventTypes":{"campaign.changecampaign":"Modify contact's campaigns","lead.changelists":"Modify contact's segments","lead.changetags":"Modify contact's tags","plugin.leadpush":"Push contact to integration","email.send":"Send an email"}}
```

## Reports[](https://developer.mautic.org/#reports)
Use this endpoint to obtain details on Mautic’s reports.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth  = new ApiAuth();
$auth      = $initAuth->newAuth($settings);
$apiUrl    = "https://your-mautic.com";
$api       = new MauticApi();
$reportApi = $api->newApi("reports", $auth, $apiUrl);

```

### Get Report[](https://developer.mautic.org/#get-report)
```
<?php

//...
// Simple get all with default options:
$report = $reportApi->get($id);

// Or define exactly what rows you want:
$limit    = 100;
$page     = 2;
$dateFrom = \DateTime('1 week ago');
$dateTo   = \DateTime('now');
$report   = $reportApi->get($id, $limit, $page, $dateFrom, $dateTo);

```
```
{"totalResults":3990,"data":[{"id2":"12","email1":"john@doe.email","firstname1":"","lastname1":""},{"id2":"23","email1":"johnatan@doe.email","firstname1":"","lastname1":""},{"id2":"24","email1":"johny@doe.email","firstname1":"","lastname1":""},{"id2":"25","email1":"johan@doe.email","firstname1":"","lastname1":""},{"id2":"26","email1":"jane@doe.email","firstname1":"","lastname1":""}],"dataColumns":{"address11":"l.address1","address21":"l.address2","attribution1":"l.attribution","attribution_date1":"l.attribution_date","city1":"l.city","company1":"l.company","companyaddress11":"comp.companyaddress1","companyaddress21":"comp.companyaddress2","companycity1":"comp.companycity","companyemail1":"comp.companyemail","companyname1":"comp.companyname","companycountry1":"comp.companycountry","companydescription1":"comp.companydescription","companyfax1":"comp.companyfax","id1":"comp.id","companyphone1":"comp.companyphone","companystate1":"comp.companystate","companywebsite1":"comp.companywebsite","companyzipcode1":"comp.companyzipcode","id2":"l.id","country1":"l.country","custom_select1":"l.custom_select","date_identified1":"l.date_identified","email1":"l.email","facebook1":"l.facebook","fax1":"l.fax","firstname1":"l.firstname","foursquare1":"l.foursquare","gender1":"l.gender","googleplus1":"l.googleplus","ip_address1":"i.ip_address","instagram1":"l.instagram","is_primary1":"companies_lead.is_primary","lastname1":"l.lastname","linkedin1":"l.linkedin","mobile1":"l.mobile","multiline1":"l.multiline","multiselect1":"l.multiselect","owner_id1":"l.owner_id","first_name1":"u.first_name","last_name1":"u.last_name","phone1":"l.phone","points1":"l.points","position1":"l.position","preferred_locale1":"l.preferred_locale","timezone1":"l.timezone","skype1":"l.skype","state1":"l.state","title1":"l.title","twitter1":"l.twitter","website1":"l.website","zipcode1":"l.zipcode",},"limit":5,"page":3,"dateFrom":"2017-01-01T00:00:00+00:00","dateTo":"2018-10-24T11:55:29+00:00",}
```

Get an individual report by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /reports/ID`
Or define query params like this:
`GET /reports/3?dateFrom=2017-01-01&dateTo=2018-01-01&limit=5&page=3`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Report Properties**
Name | Type | Description  
---|---|---  
totalResults | int | Amount of results in the defined date range. Default date range is from 30 days ago to now  
data | array | Holds rows of the report specific to each report data type and selected columns  
dataColumns | array | Array of supported column names for the report data type  
limit | int | Currently applied limit  
page | int | Currently applied page  
dateFrom | datetime | Currently applied date from filter  
dateTo | datetime | Currently applied date to filter  
### List Reports[](https://developer.mautic.org/#list-reports)
```
<?php

//...
$reports = $reportApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":8,"reports":[{"id":1,"name":"Contacts","descriptionn":"lists all contacts","system":false,"isScheduled":false,"source":"leads","columns":["l.id","l.email","l.firstname","l.lastname"],"filters":[],"tableOrder":[],"graphs":[],"groupBy":[],"settings":{"showGraphsAboveTable":0,"showDynamicFilters":0,"hideDateRangeFilter":0},"aggregators":[],"scheduleUnit":null,"toAddress":null,"scheduleDay":null,"scheduleMonthFrequency":null},[...]]}
```

Returns a list of contact reports available to the user. This list is not filterable.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /reports`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Report Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the report  
name | string | The report name  
description | string | The report description  
system | boolean | If true then the report is visible to all users. If false then only creator can see this report  
isScheduled | boolean | Scheduled reports send report emails as the user defines  
source | string | Report data source type  
columns | array | List of selected columns for this particular report  
filters | array | Filters applied on this report  
tableOrder | array | Ordering applied on this report  
graphs | array | Graphs defined for this report. API won’t return graphs  
groupBy | array | Group by rules applied for this report  
settings | array | Additional settings for the UI layout  
aggregators | array | Aggregation rules applied on this report  
scheduleUnit | string or null | Unit for the scheduler  
toAddress | string or null | Email address for the scheduler  
scheduleDay | string or null | Day for the scheduler  
scheduleMonthFrequency | string or null | Frequency for the scheduler  
## Roles[](https://developer.mautic.org/#roles)
Use this endpoint to obtain details on Mautic’s roles (administrators).
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$roleApi  = $api->newApi("roles", $auth, $apiUrl);

```

### Get Role[](https://developer.mautic.org/#get-role)
```
<?php

//...
$role = $roleApi->get($id);

```
```
{"role":{"isPublished":true,"dateAdded":"2016-11-09T15:24:32+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":13,"name":"API test role","description":"created via AIP","isAdmin":false,"rawPermissions":{"email:emails":["viewown","viewother"]}}}
```

Get an individual role by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /roles/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Role Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the contact  
dateAdded | datetime | Date/time contact was created  
createdBy | int | ID of the role that created the contact  
createdByRole | string | Name of the role that created the contact  
dateModified | datetime/null | Date/time contact was last modified  
modifiedBy | int | ID of the role that last modified the contact  
modifiedByRole | string | Name of the role that last modified the contact  
name | string | Name of the role  
description | string | Description of the role  
isAdmin | boolean | Whether the role has full access or only some  
rawPermissions | array | List of roles  
### List Contact Roles[](https://developer.mautic.org/#list-contact-roles)
```
<?php

//...
$roles = $roleApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":9,"roles":[{"isPublished":true,"dateAdded":"2016-08-01T11:51:32+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":2,"name":"view email","description":null,"isAdmin":false,"rawPermissions":{"email:emails":["viewown","viewother"]}},[...]]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /roles`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Role Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the contact  
dateAdded | datetime | Date/time contact was created  
createdBy | int | ID of the role that created the contact  
createdByRole | string | Name of the role that created the contact  
dateModified | datetime/null | Date/time contact was last modified  
modifiedBy | int | ID of the role that last modified the contact  
modifiedByRole | string | Name of the role that last modified the contact  
name | string | Name of the role  
description | string | Description of the role  
isAdmin | boolean | Whether the role has full access or only some  
rawPermissions | array | List of roles  
### Create Role[](https://developer.mautic.org/#create-role)
```
<?php 

$data = array(
    'name' => 'API test role',
    'description' => 'created via AIP',
    'rawPermissions' => array (
        'email:emails' => 
        array (
            'viewown',
            'viewother',
        ),
    )
);

$role = $roleApi->create($data);

```

Create a new role.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /roles/new`
**Post Parameters**
Name | Description  
---|---  
name | string  
description | string  
isAdmin | boolean  
rawPermissions | array  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Role](https://developer.mautic.org/#get-role).
### Edit Role[](https://developer.mautic.org/#edit-role)
```
<?php

$id   = 1;
$data = array(
    'name' => 'API test role',
    'description' => 'created via AIP',
    'rawPermissions' => array (
        'email:emails' => 
        array (
            'editown',
            'editother',
        ),
    )
);

// Create new a role of ID 1 is not found?
$createIfNotFound = true;

$role = $roleApi->edit($id, $data, $createIfNotFound);

```

Edit a new role. Role that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a role if the given ID does not exist and clears all the role information, adds the information from the request. **PATCH** fails if the role with the given ID does not exist and updates the role field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a role and return a 404 if the role is not found:
`PATCH /roles/ID/edit`
To edit a role and create a new one if the role is not found:
`PUT /roles/ID/edit`
**Post Parameters**
Name | Description  
---|---  
name | string  
description | string  
isAdmin | boolean  
rawPermissions | array  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the role was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Role](https://developer.mautic.org/#get-role).
### Delete Role[](https://developer.mautic.org/#delete-role)
```
<?php

$role = $roleApi->delete($id);

```

Delete a role.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /roles/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Role](https://developer.mautic.org/#get-role).
## Segments[](https://developer.mautic.org/#segments)
Use this endpoint to obtain details on Mautic’s contact segments or to manipulate contact memberships.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth   = new ApiAuth();
$auth       = $initAuth->newAuth($settings);
$apiUrl     = "https://your-mautic.com";
$api        = new MauticApi();
$segmentApi = $api->newApi("segments", $auth, $apiUrl);

```

### Get Segment[](https://developer.mautic.org/#get-segment)
```
<?php

//...
$segment = $segmentApi->get($id);

```
```
"list":{"id":47,"isPublished":1,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"name":"Segment A","alias":"segment-a","description":"This is my first segment created via API.","filters":[{"glue":"and","field":"city","type":"text","filter":"Prague","display":null,"operator":"=",}],"isGlobal":true}
```

Get an individual segment by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /segments/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Segment Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the segment  
isPublished | boolean | Whether the segment is published  
dateAdded | datetime | Date/time segment was created  
createdBy | int | ID of the user that created the segment  
createdByUser | string | Name of the user that created the segment  
dateModified | datetime/null | Date/time segment was last modified  
modifiedBy | int | ID of the user that last modified the segment  
modifiedByUser | string | Name of the user that last modified the segment  
category | object/null | Object with the category details  
name | string | Segment name  
alias | string | Segment alias  
description | string | Segment description  
filters | array | Smart filters for the segment. See filter properties bellow  
isGlobal | boolean | Whether the segment is global. 0 means only the author will see it.  
**Segment Filter Properties**
Name | Type | Description  
---|---|---  
glue | string | How to glue the filters to others. Possible values: `and`, `or`  
field | string | Alias of the contact or company field to based the filter on  
object | string | Object which have the field. Possible values: ‘lead’ (for contacts), `company`  
type | string | Type of the field. Possible values: 'boolean’, `date` (format `Y-m-d`), `datetime` (format `Y-m-d H:i:s`), `email`, `country`, `locale`, `lookup`, `number`, `tel`, `region`, `select`, `multiselect`, `text`, `textarea`, `time`, `timezone`, `url`  
operator | string | Operator used for matching the values. Possible values: ’=’, `!=`, `empty`, `!empty`, `like`, `!like`, `regexp`, `!regexp`, `startsWith`, `endsWith`, `contains`  
### List Contact Segments[](https://developer.mautic.org/#list-contact-segments)
```
<?php

//...
$segments = $segmentApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":13,"lists":[{"id":47,"isPublished":1,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","category":null,"name":"Segment A","alias":"segment-a","description":"This is my first segment created via API.","filters":[{"glue":"and","field":"city","type":"text","filter":"Prague","display":null,"operator":"=",}],"isGlobal":true},...]}
```

Returns a list of contact segments available to the user. This list is not filterable.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /segments`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Segment Properties**
Name | Type | Description  
---|---|---  
total | int | Count of all segments  
id | int | ID of the segment  
isPublished | boolean | Whether the segment is published  
dateAdded | datetime | Date/time segment was created  
createdBy | int | ID of the user that created the segment  
createdByUser | string | Name of the user that created the segment  
dateModified | datetime/null | Date/time segment was last modified  
modifiedBy | int | ID of the user that last modified the segment  
modifiedByUser | string | Name of the user that last modified the segment  
category | object/null | Object with the category details  
name | string | Segment name  
alias | string | Segment alias  
description | string | Segment description  
filters | array | Smart filters for the segment. See filter properties bellow  
isGlobal | boolean | Whether the segment is global. 0 means only the author will see it.  
**Segment Filter Properties**
Name | Type | Description  
---|---|---  
glue | string | How to glue the filters to others. Possible values: `and`, `or`  
field | string | Alias of the contact or company field to based the filter on  
object | string | Object which have the field. Possible values: 'lead’ (for contacts), `company`  
type | string | Type of the field. Possible values: 'boolean’, `date` (format `Y-m-d`), `datetime` (format `Y-m-d H:i:s`), `email`, `country`, `locale`, `lookup`, `number`, `tel`, `region`, `select`, `multiselect`, `text`, `textarea`, `time`, `timezone`, `url`  
operator | string | Operator used for matching the values. Possible values: ’=’, `!=`, `empty`, `!empty`, `like`, `!like`, `regexp`, `!regexp`, `startsWith`, `endsWith`, `contains`  
### Create Segment[](https://developer.mautic.org/#create-segment)
```
<?php

$data = array(
    'name'        => 'Segment A',
    'alias'       => 'segment-a',
    'description' => 'This is my first segment created via API.',
    'isPublished' => 1,
    'filters' => array(
        array(
            'glue' => 'and',
            'field' => 'email',
            'object' => 'lead',
            'type' => 'email',
            'filter' => '*@gmail.com',
            'operator' => 'like',
        ),
    ),
);

$segment = $segmentApi->create($data);

```

Create a new segment.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /segments/new`
**Post Parameters**
Name | Description  
---|---  
name | Segment name is the only required field  
alias | Name alias generated automatically if not set  
description | A description of the segment.  
isPublished | A value of 0 or 1  
isGlobal | boolean  
filters | array  
**Segment Filter Properties**
Name | Type | Description  
---|---|---  
glue | string | How to glue the filters to others. Possible values: `and`, `or`  
field | string | Alias of the contact or company field to based the filter on  
object | string | Object which have the field. Possible values: 'lead’ (for contacts), `company`  
type | string | Type of the field. Possible values: 'boolean’, `date` (format `Y-m-d`), `datetime` (format `Y-m-d H:i:s`), `email`, `country`, `locale`, `lookup`, `number`, `tel`, `region`, `select`, `multiselect`, `text`, `textarea`, `time`, `timezone`, `url`  
operator | string | Operator used for matching the values. Possible values: ’=’, `!=`, `empty`, `!empty`, `like`, `!like`, `regexp`, `!regexp`, `startsWith`, `endsWith`, `contains`  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Segment](https://developer.mautic.org/#get-segment).
### Edit Segment[](https://developer.mautic.org/#edit-segment)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New segment name',
    'isPublished' => 0
);

// Create new a segment of ID 1 is not found?
$createIfNotFound = true;

$segment = $segmentApi->edit($id, $data, $createIfNotFound);

```

Edit a new segment. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a segment if the given ID does not exist and clears all the segment information, adds the information from the request. **PATCH** fails if the segment with the given ID does not exist and updates the segment field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a segment and return a 404 if the segment is not found:
`PATCH /segments/ID/edit`
To edit a segment and create a new one if the segment is not found:
`PUT /segments/ID/edit`
**Post Parameters**
Name | Description  
---|---  
name | Segment name is the only required field  
alias | Name alias generated automatically if not set  
description | A description of the segment.  
isPublished | A value of 0 or 1  
isGlobal | boolean  
filters | array  
**Segment Filter Properties**
Name | Type | Description  
---|---|---  
glue | string | How to glue the filters to others. Possible values: `and`, `or`  
field | string | Alias of the contact or company field to based the filter on  
object | string | Object which have the field. Possible values: 'lead’ (for contacts), `company`  
type | string | Type of the field. Possible values: 'boolean’, `date` (format `Y-m-d`), `datetime` (format `Y-m-d H:i:s`), `email`, `country`, `locale`, `lookup`, `number`, `tel`, `region`, `select`, `multiselect`, `text`, `textarea`, `time`, `timezone`, `url`  
operator | string | Operator used for matching the values. Possible values: ’=’, `!=`, `empty`, `!empty`, `like`, `!like`, `regexp`, `!regexp`, `startsWith`, `endsWith`, `contains`  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the segment was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Segment](https://developer.mautic.org/#get-segment).
### Delete Segment[](https://developer.mautic.org/#delete-segment)
```
<?php

$segment = $segmentApi->delete($id);

```

Delete a segment.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /segments/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Segment](https://developer.mautic.org/#get-segment).
### Add Contact to a Segment[](https://developer.mautic.org/#add-contact-to-a-segment)
```
<?php

//...
$response = $segmentApi->addContact($segmentId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually add a contact to a specific segment.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /segments/SEGMENT_ID/contact/CONTACT_ID/add`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Add Contacts to a Segment[](https://developer.mautic.org/#add-contacts-to-a-segment)
```
<?php

//...
$contactIds = ['ids'=>[ 1, 45, 39]];
$response = $segmentApi->addContact($segmentId, $contactIds);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true,"details":{"1":{"success":true},"45":{"success":true},"39":{"success":false}}}
```

Manually add contacts to a specific segment.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /segments/SEGMENT_ID/contacts/add`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Remove Contact from a Segment[](https://developer.mautic.org/#remove-contact-from-a-segment)
```
<?php

//...
$response = $segmentApi->removeContact($segmentId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually remove a contact to a specific segment.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /segments/SEGMENT_ID/contact/CONTACT_ID/remove`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
## Text messages[](https://developer.mautic.org/#text-messages)
Use this endpoint to obtain details on Mautic’s Text Messages (SMSes).
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$smsApi   = $api->newApi("smses", $auth, $apiUrl);

```

### Get Text message[](https://developer.mautic.org/#get-text-message)
```
<?php

//...
$sms = $smsApi->get($id);

```
```
{"sms":{"isPublished":true,"dateAdded":"2016-09-14T12:14:45+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":1,"name":"Message A","message":"Hello","language":"en","category":null,"publishUp":null,"publishDown":null,"sentCount":0}}
```

Get an individual sms by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /smses/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Text message Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the sms  
name | string | Title of the sms  
message | string | Message of the sms  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the sms should be published  
publishDown | datetime/null | Date/time the sms should be un published  
dateAdded | datetime | Date/time sms was created  
createdBy | int | ID of the user that created the sms  
createdByUser | string | Name of the user that created the sms  
dateModified | datetime/null | Date/time sms was last modified  
modifiedBy | int | ID of the user that last modified the sms  
modifiedByUser | string | Name of the user that last modified the sms  
language | string | Language locale of the sms  
sentCount | int | How many times the SMS was sent  
### List Text messages[](https://developer.mautic.org/#list-text-messages)
```
<?php
// ...

$smses = $smsApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"smses":[{"isPublished":true,"dateAdded":"2016-09-14T12:14:45+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":1,"name":"Message A","message":"Hello","language":"en","category":null,"publishUp":null,"publishDown":null,"sentCount":0}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /smses`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Text message](https://developer.mautic.org/#get-sms).
### Create Text message[](https://developer.mautic.org/#create-text-message)
```
<?php 

$data = array(
    'name'        => 'Text message A',
    'message' => 'This is my first sms created via API.',
    'isPublished' => 1
);

$sms = $smsApi->create($data);

```

Create a new sms.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /smses/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the sms  
name | string | Title of the sms  
message | string | Message of the sms  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the sms should be published  
publishDown | datetime/null | Date/time the sms should be un published  
dateAdded | datetime | Date/time sms was created  
createdBy | int | ID of the user that created the sms  
createdByUser | string | Name of the user that created the sms  
dateModified | datetime/null | Date/time sms was last modified  
modifiedBy | int | ID of the user that last modified the sms  
modifiedByUser | string | Name of the user that last modified the sms  
language | string | Language locale of the sms  
sentCount | int | How many times the SMS was sent  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Text message](https://developer.mautic.org/#get-sms).
### Edit Text message[](https://developer.mautic.org/#edit-text-message)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New sms name',
    'isPublished' => 0
);

// Create new a sms of ID 1 is not found?
$createIfNotFound = true;

$sms = $smsApi->edit($id, $data, $createIfNotFound);

```

Edit a new sms. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a sms if the given ID does not exist and clears all the sms information, adds the information from the request. **PATCH** fails if the sms with the given ID does not exist and updates the sms field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a sms and return a 404 if the sms is not found:
`PATCH /smses/ID/edit`
To edit a sms and create a new one if the sms is not found:
`PUT /smses/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the sms  
name | string | Title of the sms  
message | string | Message of the sms  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the sms should be published  
publishDown | datetime/null | Date/time the sms should be un published  
language | string | Language locale of the sms  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the sms was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Text message](https://developer.mautic.org/#get-sms).
### Delete Text message[](https://developer.mautic.org/#delete-text-message)
```
<?php

$sms = $smsApi->delete($id);

```

Delete a sms.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /smses/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Text message](https://developer.mautic.org/#get-sms).
### Send SMS to Contact[](https://developer.mautic.org/#send-sms-to-contact)
```
<?php

$sms = $smsApi->sendToContact($smsId, $contactId);

```

Send a predefined sms to existing contact.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /smses/ID/contact/CONTACT_ID/send`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties** `json {     "success": 1,     "status": "Delivered" } `
## Stages[](https://developer.mautic.org/#stages)
Use this endpoint to obtain details on Mautic’s contact stages.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$stageApi = $api->newApi("stages", $auth, $apiUrl);

```

### Get Stage[](https://developer.mautic.org/#get-stage)
```
<?php

//...
$stage = $stageApi->get($id);

```
```
"stage":{"id":47,"isPublished":1,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","name":"Stage A","category":null,"description":"This is my first stage created via API.","weight":0,"publishUp":"2015-07-21T14:12:03-05:00","publishDown":"2015-07-21T14:12:03-05:00"}
```

Get an individual stage by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /stages/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Stage Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the stage  
isPublished | boolean | Whether the stage is published  
dateAdded | datetime | Date/time stage was created  
createdBy | int | ID of the user that created the stage  
createdByUser | string | Name of the user that created the stage  
dateModified | datetime/null | Date/time stage was last modified  
modifiedBy | int | ID of the user that last modified the stage  
modifiedByUser | string | Name of the user that last modified the stage  
name | string | Stage name  
category | int | Stage category ID  
description | string | Stage description  
weight | int | Stage’s weight  
publishUp | datetime | Date/time stage should be published  
publishDown | datetime | Date/time stage should be unpublished  
### List Contact Stages[](https://developer.mautic.org/#list-contact-stages)
```
<?php

//...
$stages = $stageApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":4,"stages":[{"id":47,"isPublished":1,"dateAdded":"2015-07-21T12:27:12-05:00","createdBy":1,"createdByUser":"Joe Smith","dateModified":"2015-07-21T14:12:03-05:00","modifiedBy":1,"modifiedByUser":"Joe Smith","name":"Stage A","category":null,"description":"This is my first stage created via API.","weight":0,"publishUp":"2015-07-21T14:12:03-05:00","publishDown":"2015-07-21T14:12:03-05:00"},...]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /stages`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Stage Properties**
Name | Type | Description  
---|---|---  
total | int | Count of all stages  
id | int | ID of the stage  
isPublished | boolean | Whether the stage is published  
dateAdded | datetime | Date/time stage was created  
createdBy | int | ID of the user that created the stage  
createdByUser | string | Name of the user that created the stage  
dateModified | datetime/null | Date/time stage was last modified  
modifiedBy | int | ID of the user that last modified the stage  
modifiedByUser | string | Name of the user that last modified the stage  
name | string | Stage name  
category | int | Stage category ID  
description | string | Stage description  
weight | int | Stage’s weight  
publishUp | datetime | Date/time stage should be published  
publishDown | datetime | Date/time stage should be unpublished  
### Create Stage[](https://developer.mautic.org/#create-stage)
```
<?php 

$data = array(
    'name'        => 'Stage A',
    'weight'      => 5,
    'description' => 'This is my first stage created via API.',
    'isPublished' => 1
);

$stage = $stageApi->create($data);

```

Create a new stage.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /stages/new`
**Post Parameters**
Name | Description  
---|---  
name | Stage name is the only required field  
weight | int  
description | A description of the stage.  
isPublished | A value of 0 or 1  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Stage](https://developer.mautic.org/#get-stage).
### Edit Stage[](https://developer.mautic.org/#edit-stage)
```
<?php

$id   = 1;
$data = array(
    'name'        => 'New stage name',
    'isPublished' => 0
);

// Create new a stage of ID 1 is not found?
$createIfNotFound = true;

$stage = $stageApi->edit($id, $data, $createIfNotFound);

```

Edit a new stage. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a stage if the given ID does not exist and clears all the stage information, adds the information from the request. **PATCH** fails if the stage with the given ID does not exist and updates the stage field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a stage and return a 404 if the stage is not found:
`PATCH /stages/ID/edit`
To edit a stage and create a new one if the stage is not found:
`PUT /stages/ID/edit`
**Post Parameters**
Name | Description  
---|---  
name | Stage name is the only required field  
alias | Name alias generated automatically if not set  
description | A description of the stage.  
isPublished | A value of 0 or 1  
weight | int  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the stage was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Stage](https://developer.mautic.org/#get-stage).
### Delete Stage[](https://developer.mautic.org/#delete-stage)
```
<?php

$stage = $stageApi->delete($id);

```

Delete a stage.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /stages/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Stage](https://developer.mautic.org/#get-stage).
### Add Contact to a Stage[](https://developer.mautic.org/#add-contact-to-a-stage)
```
<?php

//...
$response = $stageApi->addContact($stageId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually add a contact to a specific stage.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /stages/STAGE_ID/contact/CONTACT_ID/add`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
### Remove Contact from a Stage[](https://developer.mautic.org/#remove-contact-from-a-stage)
```
<?php

//...
$response = $stageApi->removeContact($stageId, $contactId);
if (!isset($response['success'])) {
    // handle error
}

```
```
{"success":true}
```

Manually remove a contact from a specific stage.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /stages/STAGE_ID/contact/CONTACT_ID/remove`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
## Stats[](https://developer.mautic.org/#stats)
This endpoint is useful for downloading a full statistical table.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$statsApi = $api->newApi("stats", $auth, $apiUrl);

```

### Get Available Stat Tables[](https://developer.mautic.org/#get-available-stat-tables)
```
<?php

//...
$tables = $statsApi->get();

```
```
{"availableTables":["asset_downloads","audit_log","campaign_lead_event_log","campaign_leads","channel_url_trackables","companies_leads","dynamic_content_lead_data","dynamic_content_stats","email_stat_replies","email_stats","email_stats_devices","focus_stats","form_submissions","ip_addresses","lead_categories","lead_companies_change_log","lead_devices","lead_donotcontact","lead_event_log","lead_frequencyrules","lead_lists_leads","lead_points_change_log","lead_stages_change_log","lead_utmtags","page_hits","page_redirects","plugin_citrix_events","point_lead_action_log","point_lead_event_log","push_notification_stats","sms_message_stats","stage_lead_action_log","tweet_stats","video_hits","webhook_logs"],"tableColumns":{"asset_downloads":["asset_id","code","date_download","email_id","id","ip_id","lead_id","referer","source","source_id","tracking_id"],"audit_log":["action","bundle","date_added","details","id","ip_address","object","object_id","user_id","user_name"],"campaign_lead_event_log":["campaign_id","channel","channel_id","date_triggered","event_id","id","ip_id","is_scheduled","lead_id","metadata","non_action_path_taken","rotation","system_triggered","trigger_date"],"campaign_leads":["campaign_id","date_added","date_last_exited","lead_id","manually_added","manually_removed","rotation"],"channel_url_trackables":["channel","channel_id","hits","redirect_id","unique_hits"],"companies_leads":["company_id","date_added","is_primary","lead_id","manually_added","manually_removed"],"dynamic_content_lead_data":["date_added","dynamic_content_id","id","lead_id","slot"],"dynamic_content_stats":["date_sent","dynamic_content_id","id","last_sent","lead_id","sent_count","sent_details","source","source_id","tokens"],"email_stat_replies":["date_replied","id","message_id","stat_id"],"email_stats":["copy_id","date_read","date_sent","email_address","email_id","id","ip_id","is_failed","is_read","last_opened","lead_id","list_id","open_count","open_details","retry_count","source","source_id","tokens","tracking_hash","viewed_in_browser"],"email_stats_devices":["date_opened","device_id","id","ip_id","stat_id"],"focus_stats":["date_added","focus_id","id","lead_id","type","type_id"],"form_submissions":["date_submitted","form_id","id","ip_id","lead_id","page_id","referer","tracking_id"],"ip_addresses":["id","ip_address","ip_details"],"lead_categories":["category_id","date_added","id","lead_id","manually_added","manually_removed"],"lead_companies_change_log":["action_name","company_id","date_added","event_name","id","lead_id","type"],"lead_devices":["client_info","date_added","device","device_brand","device_fingerprint","device_model","device_os_name","device_os_platform","device_os_shortname","device_os_version","id","lead_id","tracking_id"],"lead_donotcontact":["channel","channel_id","comments","date_added","id","lead_id","reason"],"lead_event_log":["action","bundle","date_added","id","lead_id","object","object_id","properties","user_id","user_name"],"lead_frequencyrules":["channel","date_added","frequency_number","frequency_time","id","lead_id","pause_from_date","pause_to_date","preferred_channel"],"lead_lists_leads":["date_added","leadlist_id","lead_id","manually_added","manually_removed"],"lead_points_change_log":["action_name","date_added","delta","event_name","id","ip_id","lead_id","type"],"lead_stages_change_log":["action_name","date_added","event_name","id","lead_id","stage_id"],"lead_utmtags":["date_added","id","lead_id","query","referer","remote_host","url","user_agent","utm_campaign","utm_content","utm_medium","utm_source","utm_term"],"page_hits":["browser_languages","city","code","country","date_hit","date_left","device_id","email_id","id","ip_id","isp","lead_id","organization","page_id","page_language","query","redirect_id","referer","region","remote_host","source","source_id","tracking_id","url","url_title","user_agent"],"page_redirects":["checked_out","checked_out_by","checked_out_by_user","created_by","created_by_user","date_added","date_modified","hits","id","is_published","modified_by","modified_by_user","redirect_id","unique_hits","url"],"plugin_citrix_events":["email","event_date","event_desc","event_name","event_type","id","lead_id","product"],"point_lead_action_log":["date_fired","ip_id","lead_id","point_id"],"point_lead_event_log":["date_fired","event_id","ip_id","lead_id"],"push_notification_stats":["click_count","click_details","date_clicked","date_read","date_sent","id","ip_id","is_clicked","last_clicked","lead_id","list_id","notification_id","retry_count","source","source_id","tokens","tracking_hash"],"sms_message_stats":["date_sent","id","ip_id","lead_id","list_id","sms_id","source","source_id","tokens","tracking_hash"],"stage_lead_action_log":["date_fired","ip_id","lead_id","stage_id"],"tweet_stats":["date_sent","favorite_count","handle","id","is_failed","lead_id","response_details","retry_count","retweet_count","source","source_id","tweet_id","twitter_tweet_id"],"video_hits":["browser_languages","channel","channel_id","city","code","country","date_hit","date_left","duration","guid","id","ip_id","isp","lead_id","organization","page_language","query","referer","region","remote_host","time_watched","url","user_agent"],"webhook_logs":["date_added","id","note","runtime","status_code","webhook_id"]}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /stats`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Stats Properties**
Name | Type | Description  
---|---|---  
availableTables | array | List of available tables which can be used in this endpoint  
stats | array | An empty array of stats, because no table was defined  
### Get Stats from a table[](https://developer.mautic.org/#get-stats-from-a-table)
```
<?php
// Example setup variables:
$table = 'asset_downloads';
$start = 0;
$limit = 50;
$order = array(
    array(
      'col' => 'id',
      'dir' => 'asc'
    )
);
$where = array(
    array(
      'col' => 'id',
      'expr' => 'gt',
      'val' => 3,
    )
);

$stats = $statsApi->get($table, $start, $limit, $order, $where);

```
```
{"stats":[{"id":"1","asset_id":"1","ip_id":"1","lead_id":"31","date_download":"2016-06-30 08:51:22","code":"200","tracking_id":"b3259e7709f35b7428b7bffcbb3d1d713ac1526c"},[...]]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /stats/TABLE`
**Request Properties**
Name | Type | Description  
---|---|---  
start | int | Which row to start on  
limit | int | How many rows to return  
order | array | An array of arrays which contain ordering (example above)  
where | array | An array of arrays which contain where conditions (example above). As the `expr` param can be used most of the methods from   
If using cURL, a query parameter may look something like `where%5B0%5D%5Bcol%5D=id&where%5B0%5D%5Bexpr%5D=eq&where%5B0%5D%5Bval%5D=3` which is the equivalent to the following:
```
array(
    array(
        'col'  => 'id',
        'expr' => 'eq',
        'val'  => 3,
    )
);

```

#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Stats Properties**
Different for every table. It simply returns rows or requested table.
## Tags[](https://developer.mautic.org/#tags)
Use this endpoint to obtain details on Mautic’s tags. Implemented in Mautic 2.12.0.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth        = new ApiAuth();
$auth            = $initAuth->newAuth($settings);
$apiUrl          = "https://your-mautic.com";
$api             = new MauticApi();
$tagApi = $api->newApi("tags", $auth, $apiUrl);

```

### Get Tag[](https://developer.mautic.org/#get-tag)
```
<?php

//...
$tag = $tagApi->get($id);

```
```
{"tag":{"id":34,"tag":"tagA",}}
```

Get an individual tag by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /tags/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Tag Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the tag  
tag | string | Title of the tag  
### List Tags[](https://developer.mautic.org/#list-tags)
```
<?php
// ...

$tags = $tagApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"tags":[{"id":34,"tag":"tagA",}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /tags`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Tag](https://developer.mautic.org/#get-tag).
### Create Tag[](https://developer.mautic.org/#create-tag)
```
<?php

$data = array(
    'tag' => 'Tag A',
);

$tag = $tagApi->create($data);

```

Create a new tag.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /tags/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the tag  
tag | string | Title of the tag  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Tag](https://developer.mautic.org/#get-tag).
### Edit Tag[](https://developer.mautic.org/#edit-tag)
```
<?php

$id   = 1;
$data = array(
    'tag' => 'Tag B',
);

// Create new a tag of ID 1 is not found?
$createIfNotFound = true;

$tag = $tagApi->edit($id, $data, $createIfNotFound);

```

Edit a new tag. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a tag if the given ID does not exist and clears all the tag information, adds the information from the request. **PATCH** fails if the tag with the given ID does not exist and updates the tag field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a tag and return a 404 if the tag is not found:
`PATCH /tags/ID/edit`
To edit a tag and create a new one if the tag is not found:
`PUT /tags/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the tag  
tag | string | Title of the tag  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the tag was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Tag](https://developer.mautic.org/#get-tag).
### Delete Tag[](https://developer.mautic.org/#delete-tag)
```
<?php

$tag = $tagApi->delete($id);

```

Delete a tag.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /tags/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Tag](https://developer.mautic.org/#get-tag).
## Themes[](https://developer.mautic.org/#themes)
This endpoint is useful for working with Mautic themes.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$themesApi = $api->newApi("themes", $auth, $apiUrl);

```

### Get theme[](https://developer.mautic.org/#get-theme)
Returns directly the zip file in the response with the `application/zip` header on success or a JSON response body with error messages on fail. The PHP API library will save the zip file to the system temporary directory and provides you with the path.
```
<?php
$response = $themesApi->get($themeName);

```
```
{"file":"/absolute/path/to/the/system/temp/dir/with/the/theme/zip/file"}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /themes/THEME_NAME`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
### Set Temporary File Path[](https://developer.mautic.org/#set-temporary-file-path)
Changes the default temporary directory where the zip file is created. The directory is created if it does not exist.
```
<?php
$themesApi->setTemporaryFilePath("/absolute/path/to/a/different/temp/dir");
$response = $themesApi->get($themeName);

```
```
{"file":"/absolute/path/to/a/different/temp/dir/zipfile"}
```

### Get List of themes[](https://developer.mautic.org/#get-list-of-themes)
Lists all installed themes with the detailes stored in their config.json files.
```
<?php
$response = $themesApi->getList();

```
```
{"themes":{"blank":{"name":"Blank","key":"blank","config":{"name":"Blank","author":"Mautic team","authorUrl":"https:\/\/mautic.org","features":["page","email","form"]}},...}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /themes`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Response Properties**
Name | Type | Description  
---|---|---  
themes | array | List of installed themes and their configs  
### Create Theme[](https://developer.mautic.org/#create-theme)
Creates a new theme or updates an existing one (based on the file name) from provided zip file.
```
<?php
$data = array(
    'file' => dirname(__DIR__).'/'.'mytheme.zip' // Must be a path to an existing file
);

$response = $themeApi->create($data);

```

The file is sent via regular POST files array like a browser sends it during file upload.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /themes/new`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "success": true } `
### Delete File[](https://developer.mautic.org/#delete-file)
```
<?php
$response = $themeApi->delete($themeName);

```

Delete a theme. The stock themes cannot be deleted
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /themes/THEME_NAME/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {     "success": true } `
## Tweets[](https://developer.mautic.org/#tweets)
Use this endpoint to obtain details on Mautic’s tweets. Implemented in Mautic 2.8.0.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth        = new ApiAuth();
$auth            = $initAuth->newAuth($settings);
$apiUrl          = "https://your-mautic.com";
$api             = new MauticApi();
$tweetApi = $api->newApi("tweets", $auth, $apiUrl);

```

### Get Tweet[](https://developer.mautic.org/#get-tweet)
```
<?php

//...
$tweet = $tweetApi->get($id);

```
```
{"tweet":{"isPublished":true,"dateAdded":"2017-02-03T17:51:58+01:00","dateModified":"2017-03-28T11:03:03+02:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"Thank you tweet","text":"Hi {twitter_handle}\n\nThanks for ...","language":"en","category":{"createdByUser":"John Doe","modifiedByUser":null,"id":185,"title":"Thank you tweets","alias":"thank-you-tweets","description":null,"color":"244bc9","bundle":"global"},"tweetId":null,"mediaId":null,"mediaPath":null,"sentCount":3,"favoriteCount":0,"retweetCount":0,"description":"Used in the Product A campaign 1"}}
```

Get an individual tweet by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /tweets/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Tweet Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the tweet  
name | string | Title of the tweet  
text | string | Message of the tweet  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the tweet should be published  
publishDown | datetime/null | Date/time the tweet should be un published  
dateAdded | datetime | Date/time tweet was created  
createdBy | int | ID of the user that created the tweet  
createdByUser | string | Name of the user that created the tweet  
dateModified | datetime/null | Date/time tweet was last modified  
modifiedBy | int | ID of the user that last modified the tweet  
modifiedByUser | string | Name of the user that last modified the tweet  
language | string | Language locale of the tweet  
category | null/object | Category  
### List Tweets[](https://developer.mautic.org/#list-tweets)
```
<?php
// ...

$tweets = $tweetApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"tweets":[{"isPublished":true,"dateAdded":"2017-02-03T17:51:58+01:00","dateModified":"2017-03-28T11:03:03+02:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":1,"modifiedByUser":"John Doe","id":1,"name":"Thank you tweet","text":"Hi {twitter_handle}\n\nThanks for ...","language":"en","category":null,"tweetId":null,"mediaId":null,"mediaPath":null,"favoriteCount":0,"retweetCount":0,"description":"Used in the Product A campaign 1"}]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /tweets`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Tweet](https://developer.mautic.org/#get-tweet).
### Create Tweet[](https://developer.mautic.org/#create-tweet)
```
<?php 

$data = array(
    'name'    => 'Tweet A',
    'heading' => 'Hello World!'
    'message' => 'This is my first tweet created via API.',
);

$tweet = $tweetApi->create($data);

```

Create a new tweet.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /tweets/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the tweet  
name | string | Title of the tweet  
text | string | Message of the tweet  
url | string | URL to go to when the tweet is clicked  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the tweet should be published  
publishDown | datetime/null | Date/time the tweet should be un published  
language | string | Language locale of the tweet  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Tweet](https://developer.mautic.org/#get-tweet).
### Edit Tweet[](https://developer.mautic.org/#edit-tweet)
```
<?php

$id   = 1;
$data = array(
    'name' => 'Tweet A',
    'text' => 'This is my first tweet created via API.',
);

// Create new a tweet of ID 1 is not found?
$createIfNotFound = true;

$tweet = $tweetApi->edit($id, $data, $createIfNotFound);

```

Edit a new tweet. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a tweet if the given ID does not exist and clears all the tweet information, adds the information from the request. **PATCH** fails if the tweet with the given ID does not exist and updates the tweet field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a tweet and return a 404 if the tweet is not found:
`PATCH /tweets/ID/edit`
To edit a tweet and create a new one if the tweet is not found:
`PUT /tweets/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the tweet  
name | string | Title of the tweet  
text | string | Message of the tweet  
url | string | URL to go to when the tweet is clicked  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the tweet should be published  
publishDown | datetime/null | Date/time the tweet should be un published  
language | string | Language locale of the tweet  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the tweet was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Tweet](https://developer.mautic.org/#get-tweet).
### Delete Tweet[](https://developer.mautic.org/#delete-tweet)
```
<?php

$tweet = $tweetApi->delete($id);

```

Delete a tweet.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /tweets/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get Tweet](https://developer.mautic.org/#get-tweet).
## Users[](https://developer.mautic.org/#users)
Use this endpoint to obtain details on Mautic’s users (administrators).
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth = new ApiAuth();
$auth     = $initAuth->newAuth($settings);
$apiUrl   = "https://your-mautic.com";
$api      = new MauticApi();
$userApi  = $api->newApi("users", $auth, $apiUrl);

```

### Get User[](https://developer.mautic.org/#get-user)
```
<?php

//...
$user = $userApi->get($id);

```
```
{"user":{"isPublished":true,"dateAdded":"2016-11-09T14:23:44+00:00","createdBy":1,"createdByUser":"John Doe","dateModified":null,"modifiedBy":null,"modifiedByUser":null,"id":6,"username":"apitest","firstName":"John","lastName":"Doe","email":"john@doe.com","position":null,"role":{"createdByUser":null,"modifiedByUser":null,"id":1,"name":"Administrator","description":"Full system access","isAdmin":true,"rawPermissions":null},"timezone":null,"locale":null,"lastLogin":null,"lastActive":null,"onlineStatus":"offline","signature":null}}
```

Get an individual user by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /users/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**User Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the contact  
dateAdded | datetime | Date/time contact was created  
createdBy | int | ID of the user that created the contact  
createdByUser | string | Name of the user that created the contact  
dateModified | datetime/null | Date/time contact was last modified  
lastActive | datetime/null | Date/time when the user last active  
modifiedBy | int | ID of the user that last modified the contact  
modifiedByUser | string | Name of the user that last modified the contact  
username | string | Username which can be used for log in to Mautic.  
firstName | string | First Name of the user  
lastName | string | Last Name of the user  
email | string | Email of the user  
position | string | User’s position title  
role | object | Role details  
timezone | string | Timezone of the user  
onlineStatus | string | Online status of the user  
signature | string | Signature of the user which can be used in the emails  
### List Contact Users[](https://developer.mautic.org/#list-contact-users)
```
<?php

//...
$users = $userApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":2,"users":[{"isPublished":true,"dateAdded":"2016-08-01T11:52:15+00:00","createdBy":null,"createdByUser":" ","dateModified":"2016-09-26T15:02:32+00:00","modifiedBy":null,"modifiedByUser":" ","id":2,"username":"test","firstName":"John","lastName":"Doe","email":"john@doe.com","position":null,"role":{"createdByUser":"John Doe","modifiedByUser":null,"id":4,"name":"edit own contacts","description":null,"isAdmin":false,"rawPermissions":{"lead:leads":["viewown","editown","create","deleteown"],"lead:lists":["viewother"]}},"timezone":null,"locale":null,"lastLogin":"2016-09-26T15:03:25+00:00","lastActive":"2016-09-26T15:19:15+00:00","onlineStatus":"offline","signature":"Best regards,&#10;Yours&#10;|FROM_NAME|"},[...]]}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /users`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**User Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the contact  
dateAdded | datetime | Date/time contact was created  
createdBy | int | ID of the user that created the contact  
createdByUser | string | Name of the user that created the contact  
dateModified | datetime/null | Date/time contact was last modified  
lastActive | datetime/null | Date/time when the user last active  
modifiedBy | int | ID of the user that last modified the contact  
modifiedByUser | string | Name of the user that last modified the contact  
username | string | Username which can be used for log in to Mautic.  
firstName | string | First Name of the user  
lastName | string | Last Name of the user  
email | string | Email of the user  
position | string | User’s position title  
role | array | List of roles of the user  
timezone | string | Timezone of the user  
onlineStatus | string | Online status of the user  
signature | string | Signature of the user which can be used in the emails  
### Create User[](https://developer.mautic.org/#create-user)
```
<?php 

$data = array(
    'username' => 'apitest',
    'firstName' => 'John',
    'lastName' => 'Doe',
    'email' => 'john@doe.com',
    'plainPassword' => array(
        'password' => 'topSecret007',
        'confirm' => 'topSecret007',
    ),
    'role' => 1,
);

$user = $userApi->create($data);

```

Create a new user.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /users/new`
**Post Parameters**
Name | Description  
---|---  
username | string  
firstName | string  
lastName | string  
email | string  
position | string  
role | int  
timezone | string  
onlineStatus | string  
signature | string  
plainPassword | array  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get User](https://developer.mautic.org/#get-user).
### Edit User[](https://developer.mautic.org/#edit-user)
```
<?php

$id   = 1;
$data = array(
    'lastName' => 'Doeboe',
);

// Create new a user of ID 1 is not found?
$createIfNotFound = true;

$user = $userApi->edit($id, $data, $createIfNotFound);

```

Edit a new user. User that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a user if the given ID does not exist and clears all the user information, adds the information from the request. **PATCH** fails if the user with the given ID does not exist and updates the user field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a user and return a 404 if the user is not found:
`PATCH /users/ID/edit`
To edit a user and create a new one if the user is not found:
`PUT /users/ID/edit`
**Post Parameters**
Name | Description  
---|---  
username | string  
firstName | string  
lastName | string  
email | string  
position | string  
role | int  
timezone | string  
signature | string  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the user was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get User](https://developer.mautic.org/#get-user).
### Delete User[](https://developer.mautic.org/#delete-user)
```
<?php

$user = $userApi->delete($id);

```

Delete a user.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /users/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get User](https://developer.mautic.org/#get-user).
### Get Self User[](https://developer.mautic.org/#get-self-user)
```
<?php

$user = $userApi->getSelf();

```

Get a self user.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /users/self`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
**Properties**
Same as [Get User](https://developer.mautic.org/#get-user).
### Check User Permissions[](https://developer.mautic.org/#check-user-permissions)
```
<?php
$permission = array('user:users:create', 'user:users:edit');
$user = $userApi->checkPermission($id, $permission);

```

Get a self user.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /users/ID/permissioncheck`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200` `json {   "user:users:create":true,   "user:users:edit":true } `
**Properties**
array of requested permissions of string in case of just one
## Webhooks[](https://developer.mautic.org/#webhooks)
Use this endpoint to obtain details on Mautic’s webhooks. Implemented in Mautic 2.8.0.
```
<?php
use Mautic\MauticApi;
use Mautic\Auth\ApiAuth;

// ...
$initAuth        = new ApiAuth();
$auth            = $initAuth->newAuth($settings);
$apiUrl          = "https://your-mautic.com";
$api             = new MauticApi();
$webhookApi      = $api->newApi("webhooks", $auth, $apiUrl);

```

### Get Webhook[](https://developer.mautic.org/#get-webhook)
```
<?php

//...
$webhook = $webhookApi->get($id);

```
```
{"hook":{"isPublished":false,"dateAdded":"2017-06-07T08:54:46+00:00","dateModified":"2017-06-09T07:16:23+00:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":null,"modifiedByUser":" ","id":31,"name":"test","description":"Created via API","webhookUrl":"https:\/\/johndoe.com","secret":"webhookSecretKey","eventsOrderbyDir":"DESC","category":{"createdByUser":"John Doe","modifiedByUser":"John Doe","id":1,"title":"Important","alias":"important","description":null,"color":null,"bundle":"Webhook"},"triggers":["mautic.lead_post_delete","mautic.lead_points_change","mautic.lead_post_save_new","mautic.lead_post_save_update"]}}
```

Get an individual webhook by ID.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /hooks/ID`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Webhook Properties**
Name | Type | Description  
---|---|---  
id | int | ID of the webhook  
name | string | Title of the webhook  
description | string | Description of the webhook  
webhookUrl | string | Url to send the webhook payload to  
secret | string | Secret key used for authenticity verification  
eventsOrderbyDir | Order direction for queued events in one webhook. Can be “DESC” or “ASC”  
isPublished | bool | Published state  
publishUp | datetime/null | Date/time when the webhook should be published  
publishDown | datetime/null | Date/time the webhook should be un published  
dateAdded | datetime | Date/time webhook was created  
createdBy | int | ID of the user that created the webhook  
createdByUser | string | Name of the user that created the webhook  
dateModified | datetime/null | Date/time webhook was last modified  
modifiedBy | int | ID of the user that last modified the webhook  
modifiedByUser | string | Name of the user that last modified the webhook  
category | null/object | Category  
triggers | array | List of triggers available in Mautic  
### List Webhooks[](https://developer.mautic.org/#list-webhooks)
```
<?php
// ...

$webhooks = $webhookApi->getList($searchFilter, $start, $limit, $orderBy, $orderByDir, $publishedOnly, $minimal);

```
```
{"total":1,"hooks":{"31":{"isPublished":false,"dateAdded":"2017-06-07T08:54:46+00:00","dateModified":"2017-06-09T07:16:23+00:00","createdBy":1,"createdByUser":"John Doe","modifiedBy":null,"modifiedByUser":" ","id":31,"name":"Deleted contact","description":"Notify me when a contact is deleted","webhookUrl":"https:\/\/johndoe.com","secret":"webhookSecretKey","eventsOrderbyDir":"DESC","category":null,"triggers":["mautic.lead_post_delete",]}}}
```

#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /hooks`
**Query Parameters**
Name | Description  
---|---  
search | String or search command to filter entities by.  
start | Starting row for the entities returned. Defaults to 0.  
limit | Limit number of entities to return. Defaults to the system configuration for pagination (30).  
orderBy | Column to sort by. Can use any column listed in the response.  
orderByDir | Sort direction: asc or desc.  
publishedOnly | Only return currently published entities.  
minimal | Return only array of entities without additional lists in it.  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
See JSON code example.
**Properties**
Same as [Get Webhook](https://developer.mautic.org/#get-webhook).
### Create Webhook[](https://developer.mautic.org/#create-webhook)
```
<?php

$data = array(
    'name' => 'test',
    'description' => 'Created via API',
    'webhookUrl' => 'http://some.url',
    'secret': 'webhookSecretKey',
    'eventsOrderbyDir' => "ASC",
    'triggers' => array(
        'mautic.lead_post_save_update',
        'mautic.lead_post_save_new',
    )
);

$webhook = $webhookApi->create($data);

```

Create a new webhook.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`POST /hooks/new`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the webhook  
name | string | Title of the webhook  
description | string | Description of the webhook  
webhookUrl | string | URL to send the webhook payload to  
secret | string | (Optional) Secret key used for authenticity verification  
eventsOrderbyDir | Order direction for queued events in one webhook. Can be “DESC” or “ASC”  
isPublished | bool | Published state  
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 201`
**Properties**
Same as [Get Webhook](https://developer.mautic.org/#get-webhook).
### Edit Webhook[](https://developer.mautic.org/#edit-webhook)
```
<?php

$id   = 1;
$data = array(
    'name' => 'Rename webhook 1 to this',
);

// Create new a webhook of ID 1 is not found?
$createIfNotFound = true;

$webhook = $webhookApi->edit($id, $data, $createIfNotFound);

```

Edit a new webhook. Note that this supports PUT or PATCH depending on the desired behavior.
**PUT** creates a webhook if the given ID does not exist and clears all the webhook information, adds the information from the request. **PATCH** fails if the webhook with the given ID does not exist and updates the webhook field values with the values form the request.
#### HTTP Request[](https://developer.mautic.org/#http-request)
To edit a webhook and return a 404 if the webhook is not found:
`PATCH /hooks/ID/edit`
To edit a webhook and create a new one if the webhook is not found:
`PUT /hooks/ID/edit`
**Post Parameters**
Name | Type | Description  
---|---|---  
id | int | ID of the webhook  
name | string | Title of the webhook  
description | string | Description of the webhook  
webhookUrl | string | Url to send the webhook payload to  
secret | string | Secret key used for authenticity verification  
eventsOrderbyDir | Order direction for queued events in one webhook. Can be “DESC” or “ASC”  
isPublished | bool | Published state  
#### Response[](https://developer.mautic.org/#response)
If `PUT`, the expected response code is `200` if the webhook was edited or `201` if created.
If `PATCH`, the expected response code is `200`.
**Properties**
Same as [Get Webhook](https://developer.mautic.org/#get-webhook).
### Delete Webhook[](https://developer.mautic.org/#delete-webhook)
```
<?php

$webhook = $webhookApi->delete($id);

```

Delete a webhook.
#### HTTP Request[](https://developer.mautic.org/#http-request)
`DELETE /hooks/ID/delete`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
Same as [Get Webhook](https://developer.mautic.org/#get-webhook).
### List available webhook triggers[](https://developer.mautic.org/#list-available-webhook-triggers)
```
<?php

$webhook = $webhookApi->getTriggers();

```

List webhook triggers
#### HTTP Request[](https://developer.mautic.org/#http-request)
`GET /hooks/triggers`
#### Response[](https://developer.mautic.org/#response)
`Expected Response Code: 200`
```
{"triggers":{"mautic.lead_post_delete":{"label":"Contact Delete Event","description":"mautic.lead.webhook.event.lead.deleted_desc"},"mautic.lead_points_change":{"label":"Contact Point Change (Increase \/ Decrease) Event","description":"mautic.lead.webhook.event.lead.points_desc"},"mautic.lead_post_save_update":{"label":"Contact Updated Event","description":"mautic.lead.webhook.event.lead.update_desc"},"mautic.email_on_open":{"label":"Email Open Event","description":"mautic.email.webhook.event.open_desc"},"mautic.form_on_submit":{"label":"Form Submit Event","description":"mautic.form.webhook.event.form.submit_desc"},"mautic.lead_post_save_new":{"label":"New Contact Event","description":"mautic.lead.webhook.event.lead.new_desc"},"mautic.page_on_hit":{"label":"Page Hit Event","description":"mautic.page.webhook.event.hit_desc"}}}
```

# Webhooks[](https://developer.mautic.org/#webhooks)
Webhook is a universal way how to send data about leads, pages, forms and events. The data is sent in real-time when an action occurs so the system which listens form Mautic webhook data can process them without the need for a periodic scanning if Mautic has some new data.
## Available webhook actions[](https://developer.mautic.org/#available-webhook-actions)
Mautic can send webhook payload on these actions:
  * Email open
  * Form submit
  * Lead delete
  * Lead point change
  * Lead update
  * Lead create
  * Page hit


## The webhook workflow[](https://developer.mautic.org/#the-webhook-workflow)
The example workflow below describes a real-life workflow to get an idea how the webhooks can be used. Let’s imagine we have a project management system (PMS) and we want to create a new issue when a lead submits a form.
  1. A lead submits a Mautic form.
  2. Mautic saves the form.
  3. Mautic checks if there is a webhook with the _Form submit_ event. If there is, Mautic sends the data to the URL address defined in the webhook.
  4. PMS receives the data about the form submission and creates a new issue from it.


## Create a webhook[](https://developer.mautic.org/#create-a-webhook)
It is possible to create multiple different webhooks. That will allow you to send different information to different apps/scripts.
  1. Open the right hand side menu (click the cog icon in the top right corner) and select _Webhooks_.
  2. Create a new webhook.
  3. Fill in a _Name_ , _Webhook POST Url_ (see the next paragraph if you don’t have one) and select which _Webhook Events_ should trigger this webhook.


## Test a webhook[](https://developer.mautic.org/#test-a-webhook)
The easiest way how to test a webhook payload is to use a service like `Webhook POST Url` in Mautic. Then click the _Apply_ button to save it and then click the _Send Test Payload_ button. That will send a test payload data to RequestBin and you will be able to see it at your RequestBin.
When you have created your testing webhook, you can test the real data it sends when a defined action is triggered.
## Immediate or queued webhooks[](https://developer.mautic.org/#immediate-or-queued-webhooks)
There is an option to queue webhooks for background execution. The reason behind it is that every time an action like contact update happens which has the webhook listener attached to it, the action has to wait for the webhook response until the webhook response returns or when it times out after 10 seconds. So it is up to the webhook receiver how fast the contact update is.
This lag can be more visible when you do a CSV import. It may be slow when it is waiting a second or two for webhook response for every imported contact.
If you want to avoid this lag in the user interface, configure the Webhook queue in the configuration and add this command to your cron tab: `bin/console mautic:webhooks:process`. This way every time the Webhook is triggered, the information is only stored as a new row into database, so it is much faster than sending the information to another service via HTTP. Then the command (cron job) will read the records from the database and make the requests which may take some time, but it is not slowing down the Users or Contacts. The command will also send 10 events in 1 Webhook request so this communication needs 10 times less HTTP requests. The caveat to this optimization is that the Webhooks are not fired every time the action happens, but every time the command (cron job) runs.
## Queued event order[](https://developer.mautic.org/#queued-event-order)
Mautic will send several events in one webhook if they happen before the queue trigger command runs. Mautic’s default order of those events is chronological. But Zapier integration which use webhooks heavily requires reverse chronological order. Therefore the new option to configure the order was added to webhooks as well as to the global configuration. Webhook configuration overwrites the global configuration, but if not set, the global configuration order value is applied.
## Authenticity verification[](https://developer.mautic.org/#authenticity-verification)
During webhook creation you can provide a secret key, if no secret key is provided it will be automatically generated. This secret has to be shared with third-party application which will receive webhooks from mautic. Indeed, in order to verify authenticity of the data provided in a webhook, Mautic add an header `Webhook-Signature` on every webhook call. A third-party application can compute a base64 encoded HMAC-SHA256 signature with the webhook secret on the (raw) payload body to verify this signature and prove authenticity of the webhook data.
## Examples webhook script[](https://developer.mautic.org/#examples-webhook-script)
If you need an idea about how to receive Mautic webhook data in your app, this script can be used as a starting point. The script will log the request and return the payload. Place this script on a publicly accessible URL (i.e. `http://yourwebsite.com/webhookTest.php), then fill in the Mautic _Webhook POST Url_ to this script.
```
<?php
// webhookTest.php

/**
 * A helper class to log and get the Mautic webhook request
 */
class webhookTest {
    /**
     * Log a message to a file
     *
     * @param  mixed $message
     * @param  string $type [info|error|request]
     */
    public function log($message, $type = 'info')
    {
        $prefix = 'webhookLog_';
        $file = $type . '.log';
        $date = new DateTime();
        error_log($date->format('Y-m-d H:i:s') . ' ' . $message . "\n\n", 3, $prefix . $file);
    }
    /**
     * Get the request JSON object and log the request
     *
     * @return object
     */
    public function getRequest()
    {
        $rawData = file_get_contents("php://input");
        $this->log($rawData, 'request');
        return $rawData;
    }
}

$secret = 'mySecret';
$webhook = new webhookTest;
$rawData = $webhook->getRequest();

// optional signature verification
$headers = getallheaders();
$receivedSignature = $headers['Webhook-Signature'];
$computedSignature = base64_encode(hash_hmac('sha256', $rawData, $secret, true));

if ($receivedSignature === $computedSignature) {
    $webhook->log('Webhook authenticity verification OK', 'request');
} else {
    $webhook->log('Webhook not authentic!', 'request');
}

// @todo Process the $requestData as needed
$requestData = json_decode($rawData);

```

Additionally here are another example in NodeJS (with express): “`javascript ‘use strict’;
const express = require('express’); const crypto = require('crypto’); const app = express(); const port = 3000; const SECRET = 'mySecret’;
// save raw body app.use ((req, res, next) => { let data = ”; req.setEncoding('utf8’);
req.on('data’, chunk => data += chunk); req.on('end’, () => { req.body = data; return next(); }); });
app.post(’/webhook’, (req, res) => {
// optional signature verification const receivedSignature = req.headers['webhook-signature’]; console.log('Received signature (in header):’, receivedSignature);
const computedSignature = crypto.createHmac('sha256’, SECRET).update(req.body).digest('base64’); console.log('Computed signature (from body):’, computedSignature);
if (receivedSignature === computedSignature) { console.log('Webhook authenticity verification OK’); } else { console.log('Webhook not authentic!’); }
// TODO: process body const body = JSON.parse(req.body);
res.send(); });
app.listen(port, () => console.log(`App listening on port ${port}!`)); “` If you’d like to extend the webhook functionality with your plugin, read more in [the plugin docs](https://developer.mautic.org/#extending-webhooks).
# MauticJS API[](https://developer.mautic.org/#mauticjs-api)
Mautic provides a means for plugins to inject custom JavaScript into mtc.js, the PHP generated script that manages Mautic’s tracking pixel, dynamic web content, etc. mtc.js is embedded in 3rd party websites to manage communication between those and Mautic.
## mtc.js[](https://developer.mautic.org/#mtc.js)
```
<?php

namespace Mautic\PageBundle\EventListener;

use Mautic\CoreBundle\CoreEvents;
use Mautic\CoreBundle\Event\BuildJsEvent;
use Mautic\PageBundle\Event\TrackingEvent;
use Mautic\PageBundle\PageEvents;
use Symfony\Component\EventDispatcher\EventSubscriberInterface;

class TrackingSubscriber implements EventSubscriberInterface
{
    public static function getSubscribedEvents()
    {
        return [
            CoreEvents::BUILD_MAUTIC_JS    => ['onBuildJs', 0],
            PageEvents::ON_CONTACT_TRACKED => ['onContactTracked', 0],
        ];
    }

    public function onBuildJs(BuildJsEvent $event)
    {
        $event->appendJs(
            <<<JS

        document.addEventListener('mauticPageEventDelivered', function(e) {
            var detail   = e.detail;
            if (detail.response && detail.response.events && detail.response.events.tracked) {
                console.log(detail.response.events.tracked);
            }
      });

JS
        );
    }

    public function onContactTracked(TrackingEvent $event)
    {
        $contact  = $event->getContact();
        $response = $event->getResponse();

        $response->set(
            'tracked',
            [
                'email' => $contact->getEmail()
            ]
        );
    }
}

```

To inject custom Javascript into mtc.js, use an [event listener](https://developer.mautic.org/#events) for the `CoreEvents::BUILD_MAUTIC_JS` event. This event receives a `Mautic\CoreBundle\Event\BuildJsEvent` object where `$event->appendJs($js, $sectionName);` can be used to inject the script’s code.
Note that the code that triggers the tracking call to Mautic has a priority of -255. Thus, any listener to this event should use a priority greater than -255.  Only native Javascript or [MauticJs API functions](https://developer.mautic.org/#mauticjs-api-functions) should be used since jQuery and other libraries are not guaranteed to be available in 3rd party websites. 
## Hooking into the Tracking Process and Returning Custom Responses[](https://developer.mautic.org/#hooking-into-the-tracking-process-and-returning-custom-responses)
If it’s desired to do something during the request to track the contact (`/mtc/event`) or append to the payload returned to the tracking code which can be leveraged by custom javascript injected through `CoreEvents::BUILD_MAUTIC_JS`, subscribe to the `PageEvents::ON_CONTACT_TRACKED` event. The listener can inject a custom payload through the `Mautic\PageBundle\Event\TrackingEvent::set` method. This will expose the payload to the tracking code’s `mauticPageEventDelivered` event in the `detail.response.events` object. See the PHP code example. 
## JS Form Processing Hooks[](https://developer.mautic.org/#js-form-processing-hooks)
```
if (typeof MauticFormCallback == 'undefined') {
    var MauticFormCallback = {};
}
MauticFormCallback['replaceWithFormName'] = {
    onValidateEnd: function (formValid) {
         // before form submit
    },
    onResponse: function (response) { 
         // after form submit
    }
};


```

If you wish execute additional code to execute as form is being processed create a `MauticFormCallback` object. In the example code replace `replaceWithFormName` with the name of your form. 
`onValidateEnd` and `onResponse` are actions called by `Form.customCallbackHandler`. 
### onValidate()[](https://developer.mautic.org/#onvalidate\(\))
```
MauticFormCallback['replaceWithFormName'] = {
    onValidate: function () {
        // before form validation
        var formIsGood = True;
        var dontUpdate = False;
        if(dontUpdate){
            return null;
        }else if(formIsGood){
            return True;
        }else if(!formIsGood){
            return False;
        }
    },
};

```

Called before default form validation and can be used to override default form validation.
Return `True` to skip the default form validation continue with form processing. Return `False` to skip the default form validation and prevent the form submission. Return `null` to execute default form validation.
### onValidateStart()[](https://developer.mautic.org/#onvalidatestart\(\))
```
MauticFormCallback['replaceWithFormName'] = {
    onValidateStart: function () {
         // before default validation
    },
};

```

Called at the beginning of the default form validation. Receives no values and return value is not required and not processed.
onValidateStart may not be executed if the default form validation is handled during the `onValidate` callback 
### onValidateEnd(formValid)[](https://developer.mautic.org/#onvalidateend\(formvalid\))
```
MauticFormCallback['replaceWithFormName'] = {
    onValidateEnd: function (formValid) {
         // before form submit
    },
};

```

Called after all form validation is complete (default and/or `onValidate` callback) and before the form is submitted. Receives `formValid` to determine if form is valid. Return value is not required and not processed.
### onErrorMark(callbackData)[](https://developer.mautic.org/#onerrormark\(callbackdata\))
```
var callbackData = {
    containerId: containerId,
    valid: valid,
    validationMessage: callbackValidationMessage
};

MauticFormCallback['replaceWithFormName'] = {
    onErrorMark: function (callbackData) {
         // called during error marking
    },
};

```

Called during error marking. Receives a `callbackData` object. Return `True` to skip the default error marking.
### onErrorClear(containerId)[](https://developer.mautic.org/#onerrorclear\(containerid\))
```
MauticFormCallback['replaceWithFormName'] = {
    onErrorClear: function (containerId) {
         // called to clear an existing error
    },
};

```

Called to clear an existing error. Receives `containerId` with the id of the element containing the error. Return `True` to skip the default error clearing.
### onResponse(response)[](https://developer.mautic.org/#onresponse\(response\))
```
MauticFormCallback['replaceWithFormName'] = {
    onResponse: function (response) {
         // called to process the response to the form submission
    },
};

```

Called prior to default form submission response processing. Receives `response` containing the form submission response. Return `True` to skip the default form submission response processing.
### onResponseStart(response)[](https://developer.mautic.org/#onresponsestart\(response\))
```
MauticFormCallback['replaceWithFormName'] = {
    onResponseStart: function (response) {
         // called to process the response to the form submission
    },
};

```

Called at the beginning default form submission response processing. Receives `response` containing the form submission response. Return value is not required and not processed.
onResponseStart may not be executed if the default response processing is handled during the `onResponse` callback 
### onResponseEnd(response)[](https://developer.mautic.org/#onresponseend\(response\))
```
MauticFormCallback['replaceWithFormName'] = {
    onResponseEnd: function (response) {
         // called to process the response to the form submission
    },
};

```

Called at the end default form submission response processing. Receives `response` containing the form submission response. Return value is not required and not processed.
onResponseEnd may not be executed if the default response processing is handled during the `onResponse` callback 
### onMessageSet(messageObject)[](https://developer.mautic.org/#onmessageset\(messageobject\))
```
var messageObject = {
    message: message,
    type: type
};

MauticFormCallback['replaceWithFormName'] = {
    onErrorMark: function (messageObject) {
         // called prior to default message insertion
    },
};

```

Called prior to default message insertion. Receives a `messageObject` containing the message and message type. Return `True` to skip the default message insertion.
### onSubmitButtonDisable(messageObject)[](https://developer.mautic.org/#onsubmitbuttondisable\(messageobject\))
```
MauticFormCallback['replaceWithFormName'] = {
    onErrorMark: function (messageObject) {
         // called prior to default message insertion
    },
};

```

Called prior to default disabling of the submit button. Receives no values. Return `True` to skip the default disabling of the submit button.
### onSubmitButtonEnable()[](https://developer.mautic.org/#onsubmitbuttonenable\(\))
```
MauticFormCallback['replaceWithFormName'] = {
    onErrorMark: function (messageObject) {
         // called prior to default message insertion
    },
};

```

Called prior to default enabling of the submit button. Receives no values. Return `True` to skip the default enabling of the submit button.
### onShowNextPage()[](https://developer.mautic.org/#onshownextpage\(\))
```
MauticFormCallback['replaceWithFormName'] = {
    onShowNextPage: function (pageNumber) {
         // called prior to going to the next page
    },
};

```

Called prior to going to the next page in the form. Useful to adjust the DOM prior to making the page visible.
### onShowPreviousPage()[](https://developer.mautic.org/#onshowpreviouspage\(\))
```
MauticFormCallback['replaceWithFormName'] = {
    onShowPreviousPage: function (pageNumber) {
         // called prior to going back to previous page
    },
};

```

Called prior to going back to a previous page in the form. Useful to adjust the DOM prior to making the page visible.
## MauticJS API Functions[](https://developer.mautic.org/#mauticjs-api-functions)
### MauticJS.serialize(object)[](https://developer.mautic.org/#mauticjs.serialize\(object\))
This method will transform an object properties into a key=value string, concatenating them with an ampersand. It is used when submitting data via MauticJS.makeCORSRequest.
```
var obj = {firstname: "John", lastname: "Doe"};

var serialized = MauticJS.serialize(obj);

alert(serialized); // Shows "firstname=John&lastname=Doe"

```

### MauticJS.documentReady(functionName|function)[](https://developer.mautic.org/#mauticjs.documentready\(functionname|function\))
This method will check if the document has finished rendering, then execute the given function. The function argument can be the name of a function or an anonymous function.
```
function test() {
    alert('test');
}

MauticJS.documentReady(test);

```

### MauticJS.iterateCollection(collection)(functionName|function)[](https://developer.mautic.org/#mauticjs.iteratecollection\(collection\)\(functionname|function\))
This method will iterate over the provided collection (array, object, HTMLCollection, etc) using the provided function argument. The function argument can be the name of a function or an anonymous function. The function will receive the collection node and the iteration number as arguments.
```
var videos = document.getElementsByTagName('video');

// Add a custom data attribute to all videos
MauticJS.iterateCollection(videos)(function(node, i) {
    node.dataset.customAttribute = 'test';
});

```

### MauticJS.log(arguments)[](https://developer.mautic.org/#mauticjs.log\(arguments\))
This method is a lightweight wrapper around `console.log`. It exists because some browsers do not provide this functionality. It takes any number of arguments, logs them, then passes those same arguments to the `console.log` method if it exists.
```
MauticJS.log('Something happened');

```

### MauticJS.createCORSRequest(method, url)[](https://developer.mautic.org/#mauticjs.createcorsrequest\(method,-url\))
This method creates an `XMLHttpRequest`, then checks to see if it supports the `withCredentials` property. If not, we are probably on windows, so it then checks for the existence of `XDomainRequest`, then creates it if found. Finally, it opens then returns the xhr. It can be used to send cross domain requests that include the cookies for the domain. It is used internally within the `MauticJS.makeCORSRequest` method.
```
MauticJS.createCORSRequest('GET', 'https://mymautic.com/dwc/slot1');

```

### MauticJS.makeCORSRequest(method, url, data, callbackSuccess, callbackError)[](https://developer.mautic.org/#mauticjs.makecorsrequest\(method,-url,-data,-callbacksuccess,-callbackerror\))
This method uses `MauticJS.createCORSRequest` to open a cross domain request to the specified URL, then sets the callbackSuccess and callbackError values appropriately. You may omit either of the callbacks. If you do, the callbacks are replaced with a basic function that uses `MauticJS.log(response)` to log the response from the request. The callback methods receive the server response and the xhr object as arguments. If the response is determined to be a JSON string, it is automatically parsed to a JSON object. The data argument will be serialized using `MauticJS.serialize(data)`, then sent with the request to the server. All requests made this way have the `X-Requested-With` header set to `XMLHttpRequest`.
```
MauticJS.makeCORSRequest('GET', 'https://mymautic.com/dwc/slot1', [], function (response, xhr) {
    if (response.success) {
        document.getElementById('slot1').innerHTML = response.content;
    }
});

```

### MauticJS.parseTextToJSON(maybeJSON)[](https://developer.mautic.org/#mauticjs.parsetexttojson\(maybejson\))
This method will take a text string and check to see if it is a valid JSON string. If so, it parses it into a JSON object and returns. If not, then it will simply return the argument passed to it.
```
var text = '{"firstname": "John", "lastname": "Doe"}';

var json = MauticJS.parseTextToJSON(text);

alert(json); // Will show [object Object]

var text = 'not valid json';

var json = MauticJS.parseTextToJSON(text);

alert(json); // Will show 'not valid json'

```

### MauticJS.insertScript(scriptUrl)[](https://developer.mautic.org/#mauticjs.insertscript\(scripturl\))
This method will insert a script tag with the provided URL in the head of your document, before other scripts.
```
MauticJS.insertScript('http://google.com/ga.js');

```

[php](https://developer.mautic.org/) [json](https://developer.mautic.org/)
