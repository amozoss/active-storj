# README
How to setup Rails 7 Active Storage to Storj DCS

[Video walk-through](https://youtube.com/live/a8SlyTuoIwI)

Here's a step by step summary

```shell
rails active_storage:install
```


[Add AWS S3 SDK Gem](https://github.com/amozoss/active-storj/blob/main/Gemfile#L6)

[Add :storj to storage.yml](https://github.com/amozoss/active-storj/blob/main/config/storage.yml#L10-L16)

[has_attached_image](https://github.com/amozoss/active-storj/blob/main/app/models/name.rb) 

[Use :storj config](https://github.com/amozoss/active-storj/blob/main/config/environments/development.rb#L37)

[Update view](https://github.com/amozoss/active-storj/blob/main/app/views/names/_form.html.erb#L14-L21)

[Pin ActiveStorage javascript](https://github.com/amozoss/active-storj/blob/main/config/importmap.rb#L7)

[Start javascript activeStorage](https://github.com/amozoss/active-storj/blob/main/app/javascript/controllers/application.js#L4-L5)
