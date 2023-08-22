GelSightManipulation
====================

codes for GelSight-uSkin research

Project Organization
--------------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like`make data` or `make train`. 
    │                           (「make data」や「make train」などのコマンドを含む Makefile)
    ├── README.md          <- The top-level README for developers using this project. 
    │                           (このプロジェクトを使用する開発者向けのトップレベルの README)
    ├── data
    │   ├── external       <- Data from third party sources. 
    │   │                       (サードパーティソースからのデータ)
    │   ├── interim        <- Intermediate data that has been transformed. 
    │   │                       (変換された中間データ)
    │   ├── log            <- Log files. (ログファイル)
    │   ├── processed      <- The final, canonical data sets for modeling. 
    │   │                       (モデリング用の最終的な正規データセット)
    │   └── raw            <- The original, immutable data dump. 
    │                           (元の不変のデータダンプ)
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details 
    │                           (デフォルトの Sphinx プロジェクト．詳細については sphinx-doc.org を参照)
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries. 
    │                           (トレーニングおよびシリアル化されたモデル，モデル予測，またはモデルの概要)
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                           the creator's initials, and a short `-` delimited description, e.g.
    │                           `1.0-jqp-initial-data-exploration`
    │                           (Jupyterノート．命名規則は，「番号-作成者イニシャル-簡易的な説明」であること．
    │                           (例:「1.0-jqp-initial-data-exploration」))
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials. 
    │                              (データ辞書，マニュアル，その他各種説明資料)
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc. 
    │   │                          (HTML，PDF，LaTeXなどとして生成された分析．)
    │   └── figures        <- Generated graphics and figures to be used in reporting. 
    │                              (レポートに使用するために生成されたグラフィックスと図)
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                              generated with `pip freeze > requirements.txt`
    │                              (分析環境を再現するための要件ファイル)
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported. 
    │                              (プロジェクトを `pip install -e .`　
    │                              コマンドによりインストール可能にするためのスクリプト)
    ├── src                <- Source code for use in this project. 
    │   │                          (このプロジェクトで使用するソースコード)
    │   ├── __init__.py    <- Makes src a Python module. (src を Python モジュールにする)
    │   │
    │   ├── data           <- Scripts to download or generate data. 
    │   │   │                      (データをダウンロードまたは生成するスクリプト)
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling. 
    │   │   │                      (モデリング用の生データを特徴量に変換するスクリプト．)
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                      predictions. 
    │   │   │                      (モデルをトレーニングし，トレーニングされたモデルを使用して予測を行うスクリプト)
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and 
    │       │                      results oriented visualizations. 
    │       │                      (探索的で結果指向の視覚化を作成するスクリプト)
    │       └── visualize.py
    │
    ├── tests           <- Test codes for each scripts 
    │                           in src directory. 
    │                           (src ディレクトリ内の各スクリプトのテストコード)
    │
    └── tox.ini            <- tox file with settings for running tox
                                   see tox.readthedocs.io. (tox を実行するための設定を含む tox ファイル)
    

---

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
