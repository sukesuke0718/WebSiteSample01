# WebSiteSample01

Djangoの使い方を勉強するためのプロジェクトです

# メモ
<p>〇構成</p><br>
<p>・設定ディレクトリ</p><br>
<p>manage.py</p>
<p>[設定ファイル] -- __init__.py</p><br>
<p>              -- settings.py</p><br>
<p>              -- urls.py</p><br>
<p>              --wsgi.py</p><br>
              
<p>・アプリケーション</p><br>
<p>[機能名] -- __init__.py</p><br>
<p>         -- admin.py</p><br>
<p>         -- apps.py</p><br>
<p>         -- [mygrations] -- __init__.py</p><br>
<p>         -- models.py</p><br>
<p>         -- tests.py</p><br>
<p>         --views.py</p><br>

<p>django-admin startproject [プロジェクト名] [ディレクトリ]<br>
でアプリケーション全体の設定を行う部品を作成<br>
→1つ</p><br>
<p>（補足）</p>
<p>・ディレクトリに”.”を指定することで現在のフォルダに作成される</p>


<p>python manage.py startapp [アプリケーション名]<br>
で各アプリケーション用の部品を作成<br>
→実装したい機能ごとに作成していく<br>
→複数</p>
