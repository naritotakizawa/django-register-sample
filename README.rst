======================
django-register-sample
======================

メールアドレスをユーザー名として使うようにし、ログイン画面、仮登録、メールクリックで本登録、ユーザー情報変更ページ、パスワード変更ページ、パスワードを忘れた際の再設定...などなど、よくある一連の機能を実装します。

`解説ブログ <https://torina.top/detail/288>`_

確認した環境
----------

:Python: 3.6以上
:Django: 2.2以上


使い方
-----
1. インストールする。::

    git clone https://github.com/naritotakizawa/django-register-sample
    pip install django

2. 動かす。::

    python manage.py migrate
    python manage.py runserver
    python manage.py createsuperuser

