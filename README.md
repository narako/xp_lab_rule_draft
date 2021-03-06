# xp_lab_rule_draft
ラボのタスク周りのルール草案用

# 目的
現状ラボのタスクがプロジェクト(リポジトリ)毎のissue上でのみ管理されている。  
その為、各タスクの進行状況がissueを読むまたは人に確認する等しないと把握することが難しい。  
今回はGithub Projectのかんばんと簡単な運用ルールを作ることで、上記課題を解決したい。  
（*簡単に言うと同じタスクを複数の人がやっていた！とかある（ありそうな）ので、現状のタスク状況を可視化したい*）  

# カードまたはissue作成のルール案
1. カードは必ず該当するプロジェクト(リポジトリ)のissueと紐付けること（該当するプロジェクト(リポジトリ)が無い場合はxpjp/planning
を利用)
2. issueには必ず該当するラベルを付けること。


# カードステータスのルール案
1. カード(issue)を担当する人は必ずissue担当者に自分にすること。
2. 着手中のカードは、Git Project上で(以下省略)[In progress]の状態にすること。
3. 完了カードは、[Done]の状態にすること。
4. 何かしらの理由で中断しているカードは、[ToDo]の状態にすること。（担当から外れる場合は担当者も外すこと)

# xpjp/planningから該当するプロジェクト(リポジトリ)にカードを変更する場合のルール案
1. 該当するプロジェクト(リポジトリ)にカードを新規作成する。
2. xpjp/planningのカードを[Done]の状態にする。

***

# リンク
* XP-JP横断プロジェクト(カンバン) : <https://github.com/orgs/xpjp/projects/1>

***

# 使用例案
## やってほしいことや意見がある場合
1. XP-JP横断プロジェクトのToDoにカードを作る。
2. 該当するプロジェクト(リポジトリ)のIssueにする。（該当するプロジェクト(リポジトリ)が無い場合はxxx※1を利用)
3. 該当するラベル(Labels)を付ける。  
※ Issueには目的（ゴール）を明確にすること。

## カード(Issue)の担当になる場合
1. Issueの担当者(Assignees)に自分を指定する。
2. 着手を開始したらカードを[In progress]に設定する。
3. 作業が完了したらDiscordで連絡すると共にカードを[Done]に設定する。  
※ 何かしらの理由で中断する場合は、カードを[ToDo]に戻す。（担当から外れる場合は担当者も外すこと)
