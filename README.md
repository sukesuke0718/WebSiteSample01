# WebSiteSample01

Djangoの使い方を勉強するためのプロジェクトです

# メモ
##〇構成  
######・設定ディレクトリ  
manage.py  
[設定ファイル] -- __init__.py  
              -- settings.py  
              -- urls.py  
              --wsgi.py  

######・アプリケーション
<p>[機能名] -- __init__.py</p><br>
<p>         -- admin.py</p><br>
<p>         -- apps.py</p><br>
<p>         -- [mygrations] -- __init__.py</p><br>
<p>         -- models.py</p><br>
<p>         -- tests.py</p><br>
<p>         --views.py</p><br>

##〇コマンド
django-admin startproject [プロジェクト名] [ディレクトリ]  
でアプリケーション全体の設定を行う部品を作成  
→1つ  
（補足）  
・ディレクトリに”.”を指定することで現在のフォルダに作成される  

python manage.py startapp [アプリケーション名]  
で各アプリケーション用の部品を作成  
→実装したい機能ごとに作成していく  
→複数  
