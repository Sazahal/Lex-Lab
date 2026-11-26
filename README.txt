LEX LAB 0.1 試作版
GitHub Pages: ZIPを展開し全ファイルをリポジトリの公開ルートに配置。Settings > Pages > Deploy from a branch で公開。iPhone SafariでURLを開き共有 > ホーム画面に追加。初回オンライン読み込み後にオフラインを確認してください。
教材JSONは {"schema":1,"questions":[...]}。各教材は id,type,topic,subject,format,prompt,steps,explanation,source,basis,version,verified を持つ。stepsは question,options（文字列配列）,answer（0始まりの正解番号配列）。typeは relation,requirements,registration,error,branch,timeline。verifiedは検証済みかの登録者申告。初期教材は全て未検証。バックアップから教材の例を確認できます。同一IDはversionを増やして更新。履歴は保持。
試作版の制限：全演習は共通の選択式ステップエンジン。自由操作の関係図、動的分岐、登記簿編集、日付操作、自由記述自動採点、習得度5段階の自動判定は未実装。iPhone実機・ブラウザ動作未検証。法律内容は条文等で確認してください。端末保存は消去される可能性があるためバックアップ推奨。
