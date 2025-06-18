# AWS の AI サービス体験会

---
## ハンズオンの Sandbox 環境 へのアクセス 

* インストラクターより案内します。

---

## Amazon Rekognition ハンズオン

1. **割り当てられた Sandobox** 環境の AWS マネジメントコンソールにサインインして下さい。
1. **東京リージョン** を選択している状態にして下さい。
1. ページ上部の検索入力エリアに `reko` と入力し、Amazon Rekognition のコンソールを開いて下さい。
1. 以降、インストラクターのガイドに基づき操作してください。

* 猫の画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/cat.jpg`
* 桜の画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/cherry.jpg`
* ギターを演奏している画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/guitar.png`
* 自動車の画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/car-woods.jpg`
* トランプ大統領の画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/Trump.jpg`
* ジェフ・ベゾスの画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/jeff2.jpg`  
* 岸田元首相の画像 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/kishida.jpeg`  
* 文字を含む画像 1 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/blog-title1.png`  
* 文字を含む画像 2 : `https://tnobep-demo-public.s3.ap-northeast-1.amazonaws.com/blog-title2.png`  

---
## Amazon Polly ハンズオン

* Amazon Polly の機能を体験できるアプリケーションを使ってみましょう。
    - インストラクターより案内します。
 
---
## Amazon Transcribe ハンズオン
  
1. **割り当てられた Sandobox** 環境の AWS マネジメントコンソールにサインインして下さい。
1. **東京リージョン** を選択している状態にして下さい。
1. ページ上部の検索入力エリアに `transcribe` と入力し、Amazon Rekognition のコンソールを開いて下さい。
1. 以降、インストラクターのガイドに基づき操作してください。

* 音声ファイル： `s3://tnobep-demo-public/edo.mp3`

---

## Amazon Bedrock ハンズオン

* Amazon Bedrock の基盤モデルを使用し、チャットや画像生成を試してみましょう
        - URL や ログイン ID とパスワードはインストラクターよりご案内します。
        - サインイン後、下記のメッセージが表示されたら、**スキップ** を選択して下さい。
            - 「アカウントの復旧には確認済みの連絡先が必要です」
        - チャットで以下のプロンプトを試してみましょう
            - 正しい回答が得られているかも確認してみましょう。同じ質問を何度か繰り返してきいてみましょう。
            - 1.
                ```
                ショッピングサイトで有名なAmazon社を創設したのは誰でしょう？
                ```
            - 2.
                ```
                次の要件を満たす JavaScriptを含むHTMLを生成して下さい。ページの背景色は青です。ボタンをクリックすると、大きな見出しでフォントの色が白のHelloと表示されます。
                ```
            - 3.
                ```
                （ご自身の会社や組織）では社員が結婚するときに何日間休暇をもらえますか？
                ```
            - 4.
                ```
                東京の明日の天気はどうなるでしょうか？
                ```

        - 画像生成で次のプロンプトを試してみましょう。**画像生成数 は 1 にして下さい。**
          ```
          柴犬が草原で楽しそうに走り回っている。
          ```
          - **おすすめの StylePreset** を選択してみましょう
          - **Seed** の値を変更してみましょう

---

## Amazon Bedrock ナレッジベース作成 ハンズオン
* **Sandobox** 環境を使用します。
* [こちらのページ](https://github.com/tetsuo-nobe/bedrock-work/tree/main/knowledgebase) を開いて下さい。

  



