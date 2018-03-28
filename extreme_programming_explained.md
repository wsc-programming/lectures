"Extreme Programming Explained"　by Kent Beck

# request
もしよければ、一度みんなも読んでください。

# background
- プログラミング教育に必要な基礎知識の習得のために読み始める。
- ソフトウェア開発（共同開発）の流儀を学ぶ。

# impression
- "Extreme Programming Explained" はプログラミングを学ぶ意義を教えてくれる良本。
- 本を読みながら、すでに「価値：value」「原則：principle」「プラクティス：practice」を意識することができる。
- 「原則：principle」は 「価値：value」 と「プラクティス：practice」を橋渡しする。
- "Extreme Programming Explained" とは異なる 「価値：value」があり得るなら、それは新たな「原則：principle」を考えうるし、新たな「プラクティス：practice」を考えることができる。いずれも 「価値：value」の達成への、最適化の先に自ずと可能になる。
- それぞれの章節は、作者の経験、ストーリーから始まっており、 難解な語句もほとんどなく、 理解しやすい。（一部カタカナ英語が難解：トレーサビリティ→ traceablity とか）
- ソフトウェアの開発をかじっていれば、さらに納得感が増す。
- Kent Beckの "Extreme Programming Explained"を始める至ったストーリーをYoutubeで見れば、猶、納得感が増す。
- "Extreme Programming Explained"は単にfollowして、実践すればプラクティスではなく、Kent Beckという一人のプログラマが考え、誰にでも改善、改良の余地があるという意味で、 "Extreme Programming Explained" 自体もインクリメンタルなプラクティスである。

# conclusion
シェアハウスに住みながらソフトウェア開発 + Extreme Programming ができれば、一般IT企業には到達できない生産性を達成できる。

# keywords（翻訳ではない、概要）
## Story
- ソフトウェアにおいて実装、達成しようとする機能。
- あるいは機能の仕様。（タスクよりも粒度が大きい）

## Values
- Communication

Often when a problem arises, someone knows the solution but knowledge doesn’t get around to person who needs it.
> （問題が生じた時、チームの一人は解決策を知っていることがよくある）

- Simplicity

Making a bet that it is better to do a simple thing today and pay a little more to change it if it needs it, than to do a more complicated thing today that may never be used.
> （まずは、きっとシンプルにできると信じ、必要な複雑さだけを追加、許容していく）

- Feedback

No fixed direction stays valid for long.
> （固定された方法、方向性は、長くはもたない。）

- Courage

Effective action in the face of fear.
> （勇気は恐怖（失敗や難問への）を向き合うときに効果的である）

- Respect

Team members must care about each other and the project.
> （ソフトウェアを開発する上で（ソフトウェアの開発に関わる人は等しく重要なので）お互いと、プロジェクト自体を気にかけなければならない）

## Principles
- Humanity （人間性）

Software development is a people-based activity. Beck states that processes and practices of software development need to “address human needs, acknowledge human frailty, and leverage human strengths.” Humanity also requires finding the balance between the needs of individuals and needs of the team.
> （個人とチームの欲求を両方が叶うようにしよう。どちらかだけを大きく犠牲にすることのないように）

- Economics （経済性)

Software development and maintenance must have value, meet business goals and needs or no one will pay for it.
> （ビジネスニーズを最初に解決すれば、チームのバリューを最大化できる）

Mutual benefit（相互利益）

Every activity should benefit all concerned, i.e. win-win solutions both in the future and now.
> （個人にも、チームにも有益な活動であろう）

Self-similarity （自己相似性）

Patterns are a tool that humans have always used for efficiency and safety. Most cognitive biases (shortcuts) are a reflection of the principle of self-similarity. We find a shape or pattern that works and then use it as a place to start. Software development is no different.（
> （上手くいった解決策に似た方法で解決できないかと、まず検討することで、問題解決がよりスマートにできる場合がある）

- Improvement（改善）

Perfect is a verb not an adjective. Beck suggests, “Find a starting place, get started, and improve from there.” Retrospectives are an improvement opportunity.
> （完璧は行うこと。完璧な設計はないが、設計を（現状で）完璧にすることはできる）

- Diversity（多様性）

Teams rarely are effective if they have a homogenous set of skills, attitudes, and perspectives. Teams with a diversity of capabilities are able see the problems and pitfalls required to solve and to implement solutions. Teams need people with a variety of skills and perspectives to reach maximum effectiveness.
> （同じような経路の人が集まると、やりやすいが、異なる視点を持ったメンバーが、時間内で最もバリューの高いソフトウェア作り出すという目標を達成する)

- Reflection（振り返り）

Excellence requires that teams not only execute, but think about how work is done and why they are working. Reflection can be done at any time and include both reviewing data as well as thinking.
> （優れたチームは、なぜ仕事をしているのか、どうやって仕事しているのかを意識している）

- Flow（流れ）

Deliver a steady flow of valuable software. Problems are more effectively solved incrementally versus a big bang approach. I have always suggested that if a team is having trouble meeting its goals that they take smaller bites (shorten the increment they are using and move closer to a continuous flow of delivery).
> （流れを滞らせいないために、小さなバリューを細かくデプロイする）

- Opportunity（機会）

To reach excellence, problems need to be turned into opportunities for learning and improvement. Problems are often addressed as survival events, which rarely translate into increased capabilities. Think of turning lemons into lemonade.
> （ その場しのぎの問題解決（サバイバル）では不十分、問題が起きたらそれを学習の機会に変えよう。強みを最大化し、弱みを最小化する）

- Redundan（冗長性）

The critical, difficult problems and software development should be solved in several different ways. Said differently, create scenarios where you can test your options and choose the best one.
> （問題は複数の解決策での解決を試みるべきである。一つが失敗してもほかでカバーできる）

- Failure（失敗）

Experiment and learn so that you can get the data needed to decide which option will better provide a path for success. Failure provides value it if it imparts knowledge (assuming we failed because we did not know better).
> （失敗が回避可能な無駄だとは限らない。例えば学習の機会になるかもしれない）

- Quality（品質）

One of the things I learned from working with Capers Jones was that quality saves time, money and builds trust. Focusing on quality does not mean a team should not try new things, fail sometimes, learn, and get better.
> （本来的には低品質を宇受け入れることでプロジェクトは高速化しないし、高品質を追求することで、プロジェクトが遅れることもない）

- Baby step（ベビーステップ）

Incremental delivery of value generates feedback, is less dangerous and creates momentum. From a practical point of view, baby steps reduce the amount of overhead required to make any change.
> （小さなステップ（変更）を重ねて、積み重なったものが多いな飛躍に見える）

- Accept responsibility（責任の引き受け）

Responsibility can only be accepted, not assigned. When responsibility and authority are not aligned people often act in a passive aggressive manner. The classic example is the activity of estimating. If the people doing the work are assigned an estimate they are far less likely to act as if they own the estimate.
> （責任は分散させたり、割り当てることはできない。責任は引き受けるか否かの問題である。責任は権限が伴わなければならない）


## Practices
- 価値によって目的の与えられた、チームとして実践すべきことこと。

### Primary Practices
主要なプラクティス

- Sit together （全員同席）

Ennncourage conversation by sitting together. XP recommends an open work space for you and your team, but If you're not used to it you can get there eventually. The point is increasing the amount of face-to-face interactions. This also works for distributed teams.
> （チーム全体が十分な広さのオープンスペースで開発する）

- Whole team（チーム全体）

As with many other SDLC methods and practices, Extreme Programming promotes the inclusion of customers and clients throughout the entire process, using their feedback to help shape the project at all times.
> （プロジェクトに必要なスキルや視点を持った人たちをチームに集めること）

- Ten-Minute build（10分間ビルド）

It’s worth developing an automated, reliable and reproducible build for your project that builds the system and runs all the tests. Any longer than ten minutes and the build won’t be used as often and won’t provide as much feedback.
> （自動的にシステム全体をビルドして、全てのテストを10分以内に実行させること）

- Continuous integration （継続的インテグレーション）

Another common practice in modern development, the idea behind continuous integration is that all code developed across the entire team is merged into one common repository many times a day. This ensures that any issues with integration across the entire project are noticed and dealt with as soon as possible.
> （数時間以内に変更箇所のインテグレーションとテストをすること）

- Energized work （活発な仕事）

We've all been there, too many extra hours of work for a long period of time and you'll burn out. Get enough rest, and work as much as you can while being productive, otherwise it's best to call it a day. You might think it's ok to spend extra hours to finish a project or meet a deadline, but you need to work at a sustainable pace. Unrealistic deadlines can't be met, and it's not your fault. Work the best you can at a constant, predictable pace, and let other people manage their expectations.
> （生産的になれる時間だけ働くこと）

- Weekly cycle （週次サイクル）

Get used to have a meeting at the beginning of every week to plan a week's worth work. XP recommends writing tests for the features you expect to get done, and spend the rest of the week making them pass. If you notice you're not going to make it, adjust your plan and let go of the less important tasks.
> （一週間分の仕事の計画をまとめてたてること。週の初めにミーティングを入れること）

- Slack （ゆとり）

This one is tricky because most managers won't be happy if you tell them "Hey, we need to add 3 extra months in case something goes wrong". Plans can give you a pretty good idea of the challenges involved when solving a given problem. They also help you understand tasks dependencies and in what order to tackle them. Plans are a necessary evil. You need to do some planning in order to start working on a problem, but if you try to plan too much ahead they become only as good as guesses, and they may be used against you when you don't meet a deadline. XP recommends you include some minor tasks to drop in case you get behind schedule. If you commit to more than you can handle, you'll start ditching your best practices for the sake of meeting a deadline and fulfilling the expectations you set, and if you repeat this behavior over and over you'll end up with an inferior and unmanageable product.
> （どのような計画にも、遅れたときに外せるような重要度の低いタスクを含めること）

- Test-first programming （テストファースト・プログラミング）

Testing first is a form of guiding design. When you're about to tackle a technical problem, you need to think through what you're trying to solve, and laying out a suite of tests can help you get a better idea of where you want to go. The challenge is writing the right tests, which are simple enough to get you moving in the correct direction, and let you take baby steps to arrive at a complete solution.
> （コードを変更する前に、失敗する自動テストを書くこと）

- Incremental design （インクリメンタルな設計）

One of my favorite practices. There is only so much you can plan ahead that will actually be useful. Work in small iterations, grow your design as you implement and understand the system's needs. Do only what's absolutely necessary and provides the most value. Use the feedback you get to make better and more informed decisions of what to implement.
> （システムの設計に毎日てを入れること。システムの設計は、その日のシステムのニーズにうまく合致させること）

### Corollary Practices
導入プラクティス
（これ以下は参考程度でもよい）

- Real customer involvement 

Get feedback directly from the customer at least once a week. The point is to avoid and reduce wasted development effort by making sure we're on the right track, and always adding value.

- Incremental deployment

Replace existing systems one step at a time. Big deployments are a high-risk bet and rarely work. Instead, swap pieces of functionality or find a way to run both systems in parallel. Users will probably have to duplicate some effort, but consider it the price to pay for ensuring the project succeeds.

- Team continuity

Teams that are effective and trust each other should work together. If you ignore the value of the relationships that develop it could result in reduced productivity. Encourage a reasonable amount of rotation to spread knowledge and experience across the company.

- Shrinking teams

Effective teams will get better over time, and eventually do more in less time. Keep the workload constant and reduce the team size once they've eliminated enough waste and improved their workflow.

- Root-cause analysis

Don't put a "band-aid" every time your team makes a mistake. Instead, learn from it and why it happened, and think of ways to ensure the same kind of mistake won't ever happen again. This analysis often uncovers problems at a higher level of the company, which result in a change/fix of a broken policy or practice.

- Shared code

Anyone in the team should be able to improve any part of the system. Before attempting to do this the team should have a deep sense of responsibility and pride of their code.

- Code and tests

Code and tests are the only permanent and accurate description of the system. They are the most important form of documentation because they're always up to date, and should be treated accordingly.

- Single code base

The team should strive to work on a single code base and avoid long-lived temporary branches. Different versions of the code often result in conflicts and duplicated efforts.

- Daily deployment

The gap between development and production code should be kept small by deploying frequently. The larger this gap is, the larger the risk of failure when you deploy. Small, iterative deployments also result in faster feedback for the business to make better decisions.n

- Negotiated scope contract

In software projects, time and costs are usually fixed. Add quality to that list and you can negotiate on scope. The reason why quality should be non-negotiable is because as soon as you drop it, the project starts to deteriorate. A few weeks or months in and the system becomes unmaintainable. The risk of failure is high for projects with spaghetti codebases, where even adding small features has a high cost. Avoid long contracts and commit to smaller releases by signing a set of short contracts. As the project moves forward and you get feedback from customers, you want to be able to respond to change and integrate new features if needed instead of seeing yourself forced to work on old requirements because the contract says so.
