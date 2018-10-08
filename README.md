# WebSiteSample01

Djangoの使い方を勉強するためのプロジェクトです

# メモ
<h1>〇構成</h1>
<h2>・設定ディレクトリ</h2>
<p>manage.py</p>
<p>[設定ファイル] -- __init__.py</p><br>
<p>              -- settings.py</p><br>
<p>              -- urls.py</p><br>
<p>              --wsgi.py</p><br>
              
<h2>・アプリケーション</h2>
<p>[機能名] -- __init__.py</p><br>
         -- admin.py
         -- apps.py
         -- [mygrations] -- __init__.py
         -- models.py
         -- tests.py
         --views.py

<p>django-admin startproject [プロジェクト名] [ディレクトリ]<br>
でアプリケーション全体の設定を行う部品を作成<br>
→1つ</p><br>
<p>（補足）</p>
<p>・ディレクトリに”.”を指定することで現在のフォルダに作成される</p>

<p>python manage.py startapp [アプリケーション名]<br>
で各アプリケーション用の部品を作成<br>
→実装したい機能ごとに作成していく<br>
→複数</p>
