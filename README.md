## Introduction

LessConfigDump is an alternative for the app:config:dump command. It only dumps config values needed for deployment without database connection. 

### Installation
```
composer require sannehoogmans/lessconfigdump
```

### Usage
```
bin/magento weprovide:config:dump
```

Dumps scopes, groups, stores and themes in your config.php. 
