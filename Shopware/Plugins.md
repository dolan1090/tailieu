#Tao Module 

 

bin/console plugin:create RecentlyViewedProducts 

 

Sửa file composer.json 

 

{ 

  "name": "swag/plugin-skeleton", 

  "description": "TM Recently Viewed Products", 

  "version": "1.0.0", 

  "type": "shopware-platform-plugin", 

  "license": "MIT", 

  "autoload": { 

    "psr-4": { 

      "RecentlyViewedProducts\\": "src/" 

    } 

  }, 

  "extra": { 

    "shopware-plugin-class": "RecentlyViewedProducts\\RecentlyViewedProducts", 

    "label": { 

      "de-DE": "TM Recently Viewed Products", 

      "en-GB": "TM Recently Viewed Products" 

    } 

  } 

} 

 

Viết code 

Khởi động plugin 

 

php bin/console plugin:list 

 

php bin/console plugin:activate                                              

php bin/console plugin:create                                                

php bin/console plugin:deactivate                                            

php bin/console plugin:install                                               

                                                  

php bin/console plugin:refresh                                               

php bin/console plugin:uninstall                                             

php bin/console plugin:update                                                

php bin/console plugin:zip-import                                            

php bin/console secrets:remove 

 

Hoặc: 

Extenstion -> My extensions 