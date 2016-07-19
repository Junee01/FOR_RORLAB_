#ko.yml + devise gem

This File is 'ko.yml' for Rails users.
- Rails 4 + devise gem

All English were translated to Korean(한글).

But not all conditions were handled so if you have a problem to use this .yml file, please contact to me and you can find standard ko.yml file at https://github.com/svenfuchs/rails-i18n#rails-locale-data-repository.

"How to use these yml file?"

If you don't override .yml file then, en.yml would be compiled, so You need following steps.

1. insert this file into /config/locales/ko.yml
2. write "config.i18n.default_locale = :ko" into /config/application.rb
3. restart server

이 파일은 Rails에서 기본적인 Alert 문장을 한국어로 번역한 내용입니다.
ko.yml에 적혀있는 내용을 확인하시고, 각각의 상황에 따라 원하시는 메시지로 바꾸어 사용하시면 됩니다.

Thank you. 감사합니다.