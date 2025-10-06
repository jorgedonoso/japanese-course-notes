---
layout: default
title: Home
---

## About

These are my notes from a course I'm taking in Japan.

## Lessons

<ul>
    <li><a href="{{'/other/counting' | relative_url }}">Counting</a></li>

    {% assign sorted_lessons = site.lessons | sort: "number" %}
    {% for lesson in sorted_lessons %}
        <li>
            <a href="{{ lesson.url | relative_url }}">Lesson {{ lesson.number }}</a>
        </li>
    {% endfor %}

</ul>

## Kanji

| #   | Kanji | Onyomi       | Kunyomi                  | Meaning                 |
| --- | ----- | ------------ | ------------------------ | ----------------------- |
| 1   | 一    | イチ, イツ   | ひと-つ                  | one                     |
| 2   | 二    | ニ           | ふた-つ                  | two                     |
| 3   | 三    | サン         | みっ-つ                  | three                   |
| 4   | 四    | シ           | よん, よっ-つ            | four                    |
| 5   | 五    | ゴ           | いつ-つ                  | five                    |
| 6   | 六    | ロク         | むっ-つ                  | six                     |
| 7   | 七    | シチ         | なな-つ                  | seven                   |
| 8   | 八    | ハチ         | やっ-つ                  | eight                   |
| 9   | 九    | キュウ, ク   | ここの-つ                | nine                    |
| 10  | 十    | ジュウ, ジッ | とお                     | ten                     |
| 11  | 百    | ヒャク       | —                        | hundred                 |
| 12  | 千    | セン         | —                        | thousand                |
| 13  | 万    | マン, バン   | —                        | ten thousand            |
| 14  | 円    | エン         | まるい                   | yen / circle            |
| 15  | 口    | コウ, ク     | くち                     | mouth                   |
| 16  | 目    | モク, ボク   | め                       | eye                     |
| 17  | 耳    | ジ           | みみ                     | ear                     |
| 18  | 手    | シュ         | て, た                   | hand                    |
| 19  | 足    | ソク         | あし, た-りる            | foot / leg / sufficient |
| 20  | 人    | ジン, ニン   | ひと                     | person                  |
| 21  | 子    | シ, ス       | こ                       | child                   |
| 22  | 女    | ジョ, ニョ   | おんな                   | woman                   |
| 23  | 男    | ダン, ナン   | おとこ                   | man                     |
| 24  | 学    | ガク         | まな-ぶ                  | study                   |
| 25  | 校    | コウ         | —                        | school                  |
| 26  | 先    | セン         | さき                     | ahead / previous        |
| 27  | 生    | セイ, ショウ | い-きる, う-まれる, なま | life / birth / raw      |
| 28  | 山    | サン         | やま                     | mountain                |
| 29  | 川    | セン         | かわ                     | river                   |
| 30  | 森    | シン         | もり                     | forest                  |
| 31  | 林    | リン         | はやし                   | woods / grove           |
| 32  | 空    | クウ         | そら, から               | sky / empty             |
| 33  | 天    | テン         | あま                     | heaven / sky            |
| 34  | 雨    | ウ           | あめ, あま               | rain                    |
| 35  | 火    | カ           | ひ                       | fire                    |
| 36  | 水    | スイ         | みず                     | water                   |
| 37  | 木    | モク, ボク   | き                       | tree / wood             |
| 38  | 金    | キン, コン   | かね                     | gold / money / metal    |
| 39  | 土    | ド, ト       | つち                     | soil / earth            |
| 40  | 本    | ホン         | もと                     | book / origin           |
| 41  | 文    | ブン, モン   | ふみ                     | sentence / literature   |
| 42  | 字    | ジ           | —                        | character / letter      |
| 43  | 語    | ゴ           | かた-る                  | language / word / tell  |
| 44  | 話    | ワ           | はな-す, はなし          | talk / story            |
| 45  | 読    | ドク         | よ-む                    | read                    |
| 46  | 書    | ショ         | か-く                    | write                   |
| 47  | 見    | ケン         | み-る                    | see                     |
| 48  | 行    | コウ, ギョウ | い-く, おこな-う         | go / act                |
| 49  | 来    | ライ         | く-る, き-ます           | come                    |
| 50  | 帰    | キ           | かえ-る                  | return (home)           |
| 51  | 会    | カイ, エ     | あ-う                    | meet                    |
| 52  | 社    | シャ         | やしろ                   | company / shrine        |
| 53  | 店    | テン         | みせ                     | store / shop            |
| 54  | 車    | シャ         | くるま                   | car                     |
| 55  | 駅    | エキ         | —                        | station                 |
| 56  | 電    | デン         | —                        | electricity             |
| 57  | 白    | ハク         | しろ, しろ-い            | white                   |
| 58  | 黒    | コク         | くろ, くろ-い            | black                   |
| 59  | 赤    | セキ         | あか, あか-い            | red                     |
| 60  | 青    | セイ, ショウ | あお, あお-い            | blue                    |
| 61  | 色    | ショク, シキ | いろ                     | color                   |
| 62  | 上    | ジョウ       | うえ, あ-がる, のぼ-る   | up / above              |
| 63  | 下    | カ, ゲ       | した, さ-がる            | down / below            |
| 64  | 中    | チュウ       | なか                     | inside / middle         |
| 65  | 外    | ガイ, ゲ     | そと, ほか               | outside                 |
| 66  | 前    | ゼン         | まえ                     | before / front          |
| 67  | 後    | ゴ, コウ     | あと, うし-ろ            | after / back            |
| 68  | 午    | ゴ           | —                        | noon                    |
| 69  | 時    | ジ           | とき                     | time / hour             |
| 70  | 分    | フン, ブン   | わ-かる, わ-ける         | minute / divide         |
| 71  | 間    | カン, ケン   | あいだ, ま               | interval / between      |
| 72  | 南    | ナン         | みなみ                   | south                   |
| 73  | 北    | ホク         | きた                     | north                   |
| 74  | 東    | トウ         | ひがし                   | east                    |
| 75  | 西    | セイ, サイ   | にし                     | west                    |
| 76  | 名    | メイ, ミョウ | な                       | name                    |
| 77  | 天    | テン         | あま                     | sky / heaven            |
| 78  | 気    | キ, ケ       | —                        | spirit / energy         |
| 79  | 安    | アン         | やす-い                  | cheap / safe            |
| 80  | 高    | コウ         | たか-い                  | tall / expensive        |
| 81  | 少    | ショウ       | すく-ない, すこ-し       | few / little            |
| 82  | 多    | タ           | おお-い                  | many                    |
| 83  | 古    | コ           | ふる-い                  | old                     |
| 84  | 新    | シン         | あたら-しい              | new                     |
| 85  | 長    | チョウ       | なが-い                  | long / leader           |
| 86  | 明    | メイ         | あか-るい, あ-ける       | bright                  |
| 87  | 好    | コウ         | す-き                    | like / fond             |
| 88  | 友    | ユウ         | とも                     | friend                  |
| 89  | 入    | ニュウ       | い-る, はい-る           | enter                   |
| 90  | 出    | シュツ       | で-る, だ-す             | exit / leave / go out   |
| 91  | 買    | バイ         | か-う                    | buy                     |
| 92  | 売    | バイ         | う-る                    | sell                    |
| 93  | 食    | ショク       | た-べる                  | eat                     |
| 94  | 飲    | イン         | の-む                    | drink                   |
| 95  | 曜    | ヨウ         | —                        | day of week             |
| 96  | 朝    | チョウ       | あさ                     | morning                 |
| 97  | 昼    | チュウ       | ひる                     | noon / daytime          |
| 98  | 夜    | ヤ           | よる                     | night                   |
| 99  | 家    | カ, ケ       | いえ, うち               | house / home            |
| 100 | 村    | ソン         | むら                     | village                 |
| 101 | 所    | ショ         | ところ                   | place                   |
| 102 | 道    | ドウ         | みち                     | road / way              |
| 103 | 万    | マン         | —                        | ten thousand            |
