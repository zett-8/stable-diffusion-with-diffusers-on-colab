[[English]](https://github.com/zett-8/stable-diffusion-with-diffusers-on-colab)

# Stable Diffusion with diffusers

Stable DiffusionをGoogleのColabを使って簡単に動かすためのnotebookです。  
必要なのはHugging Faceのアカウントとユーザートークンだけです。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zett-8/stable-diffusion-with-diffusers-on-colab/blob/main/Run_Stable_Diffusion_with_HuggingFace_diffusers.ipynb)

## 準備
1. [Hugging Face](https://huggingface.co)にてアカウント登録する
    1. https://huggingface.co
1. メールアドレス確認のメールが来るので認証しておく
1. ユーザートークンを取得する
    1. ログイン後、右上のアカウントボタンをクリック
    1. [settings]をクリック
    1. 左メニューの[Access tokens]をクリック
    5. [get token]をクリックし自分のトークンを作成する。トークン名は任意のものを入力し、Roleは[Write]にしておく
    6. 作成したトークンはあとで使うのでコピーしておく
1. 使用するモデルの利用規約に同意しておく
    1. https://huggingface.co/CompVis/stable-diffusion-v1-4

    
    
## 実行
1. このREADMEの上部にある[Open in Colab]というバッジをクリックしてColabを開く
2. Notebookが開いたら[File]から[google driveにコピー]を選んで自分のGoogle Driveにコピーしておく（任意）
4. 先ほど作成したユーザートークンを最初のセルの`hugging_face_token`にコピーする
    1. `例) hugging_face_token = "YOUR USER TOKEN"`
6. 各セルの左上に再生ボタンのようなアイコンがあるのでそれをクリックして上から順に実行していく
