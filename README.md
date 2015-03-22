# ruby-sample

This is a barebones Ruby app using the [Sinatra](http://www.sinatrarb.com) framework.

## Running Locally

Asumming you have [Ruby](https://www.ruby-lang.org), [Bundler](http://bundler.io) and [Heroku Toolbelt](https://toolbelt.heroku.com) installed on your machine:

```sh
git clone git@github.com:heroku/ruby-sample.git # or clone your own fork
cd ruby-sample
bundle
foreman start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

## Documentation

For more information about using Ruby on Heroku, see these Dev Center articles:

- [Ruby on Heroku](https://devcenter.heroku.com/categories/ruby)
- [Getting Started with Ruby on Heroku](https://devcenter.heroku.com/articles/getting-started-with-ruby)
- [Getting Started with Rails 4.x on Heroku](https://devcenter.heroku.com/articles/getting-started-with-rails4)
- [Heroku Ruby Support](https://devcenter.heroku.com/articles/ruby-support)


## heroku 導入手順

1. https://www.heroku.com/ アカウント作成
2. heroku toolbar(https://toolbelt.heroku.com/) インストール
3. ターミナルで  
```
$ heroku login
```  
  で１で作成したアカウントを入力してログイン  

今回はruby-sample(https://github.com/heroku/ruby-sample)を使用  
bundleが入ってなければ  
```
$ sudo gem install bundler
```  
でインストール  

**ソース**  
```sh  
$ git clone git://github.com/heroku/ruby-sample.git   
$ bundle   
$ heroku create   
$ git add .   
$ git commit -m 'initial commit'   
$ git push heroku master   
```
