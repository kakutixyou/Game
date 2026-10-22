{
  "name": "VS Code シンボル検索と移動機能",
  "description": "VS Code内でのシンボル（関数・クラス・変数等）への移動機能およびショートカットの解説",
  "category": "vscode_knowledge",
  "retrieval": {
    "keywords": [
      "シンボル",
      "移動",
      "検索",
      "Ctrl+Shift+O",
      "@",
      "#",
      "アウトライン",
      "関数一覧"
    ],
    "intents": [
      "ファイル内の関数やクラスにジャンプしたい",
      "ワークスペース全体のシンボルを検索したい"
    ],
    "message_examples": [
      "ファイル内の特定関数に移動したい",
      "シンボル検索のショートカットを教えて",
      "コマンドパレットでの@や#の意味は？"
    ],
    "weight": 2.0,
    "priority": 5.0
  },
  "content": {
    "policy_explanation": "本情報はVS Codeの公式機能および標準操作法に基づき、外部書籍やドキュメント等の直接転載を避けて要約・再構成したオリジナル解説です。",
    "topic": "シンボルナビゲーション",
    "summary": "パレットからの記号入力やショートカットを活用することで、コード内の特定の構成要素（関数・変数・クラス等）へ即座にアクセスできます。",
    "navigation_methods": [
      {
        "scope": "ファイル内シンボル移動",
        "shortcut": "Ctrl + Shift + O",
        "command_prefix": "@",
        "description": "現在開いているファイル内のシンボル一覧を表示し、名前でフィルタリングして移動します。"
      },
      {
        "scope": "ワークスペース全体シンボル移動",
        "command_prefix": "#",
        "description": "プロジェクト全体から該当するシンボル名を部分一致で検索して移動します。"
      }
    ]
  }
}

"content": { "policy_explanation": "回答でお伝えしている情報は、複製や転載が禁止されているVS Code関連の市販書籍等の内容を、AIが直接引用・複製することなく要約・再構成（独自解釈）してお届けしているものです。", "recommended_books": [ "徹底解説Visual Studio Code" ] }
