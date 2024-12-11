# colab-github-connect-test
Google ColaboratoryとGitHub（主にプライベートリポジトリ）を繋ぐテストをするリポジトリです。  
https://github.com/tsunrise/colab-github を参考にして作成しました。

# 使い方
- すぐに使いたい方 ->  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mokroke/colab-github-connect-test/blob/main/connect_test.ipynb)


- ある程度中身を理解しつつ、セキュリティを意識しながら設定したい方 ->  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mokroke/colab-github-connect-test/blob/main/use_my_python_file.ipynb)

# ファイル詳細
- connect_test.ipynb
  - 最も簡単にGitHubとColabratoryを接続する方法
  - 「https://github.com/tsunrise/colab-github 」上のfileをwgetして利用する。
- use_my_python_file.ipynb
  - Google Driveにssh設定用の.pyファイルを格納した上で接続する方法。
  - 「https://github.com/tsunrise/colab-github 」を使わずに、にssh設定用の.pyファイルを利用する。
- colab_ssh_setthings
  - Google Driveにssh設定用の.pyファイルとして格納する用のcolab_github_setting.pyがあるフォルダ。
  - use_my_python_file.ipynbを利用するために、Google Driveには「 /content/drive/MyDrive/colab_ssh_settings/」に保存しています。
- my_module_test
  - 「connect_test.ipynb」や「use_my_python_file.ipynb」の動作確認として利用する「my_function.py」があるフォルダ。
