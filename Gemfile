source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4', '>= 5.2.4.1'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  # 追加gem
  gem 'rspec-rails' # テストコード用
  gem 'factory_bot_rails' # テストコード用
  gem 'rails-controller-testing' # コントローラーのテスト用
  gem 'capybara', '>= 2.15' # 統合テスト用

  gem 'capistrano' # デプロイ関連
  gem 'capistrano-rbenv' # デプロイ関連
  gem 'capistrano-bundler' # デプロイ関連
  gem 'capistrano-rails' # デプロイ関連
  gem 'capistrano3-unicorn' # デプロイ関連

end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15' # 統合テスト用
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'

  # 追加gem
  gem 'faker' # ダミーデータ作成

end

# 本番環境でのみ動作するgem
group :production do
  gem 'unicorn', '5.4.1' #Webサーバー
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# 追加gem
  gem 'haml-rails' # haml変換
  gem 'erb2haml' # hamlにerb記述
  gem 'font-awesome-sass' # アイコンを追加
  gem 'devise' # ユーザー登録関連
  gem 'pry-rails' # binding.pry
  gem 'carrierwave' # 画像アップロード機能
  gem 'mini_magick' # 投稿画像のサイズ変更
  gem 'jquery-rails' # jqueryの追加
  gem 'kaminari' # ページネーション用
  gem 'rspec-rails' # テストコード用
  gem 'fog-aws' # Web上で画像の保存先の指定をする
  gem 'jp_prefecture' # 都道府県情報の追加
  gem 'impressionist' # PV数チェック
  gem 'ancestry' #カテゴリー多階層構造
  gem "gretel" # パンくず機能 カテゴリー誘導表示
  gem 'rails-i18n' # エラーメッセージの日本語化
  gem 'payjp' # クレジットカード用
  gem 'dotenv-rails' # 環境変数を簡単に定義できるENVファイルを対応させるgem
  gem 'omniauth-facebook' #フェイスブック対応のOmniAuth
  gem 'omniauth-google-oauth2' #グーグル対応のOmniAuth
  gem "omniauth-rails_csrf_protection" #OmniAuthの脆弱性に対応するためのGem