# awesome-physics-ja

無料で入手可能な物理の学習教材（日本語）の一覧。敬称略。例えば["グランドカノニカル分布"](https://www.google.com/search?q=%E3%82%B0%E3%83%A9%E3%83%B3%E3%83%89%E3%82%AB%E3%83%8E%E3%83%8B%E3%82%AB%E3%83%AB%E5%88%86%E5%B8%83), ["測地線方程式"](https://www.google.com/search?q=%E6%B8%AC%E5%9C%B0%E7%B7%9A%E6%96%B9%E7%A8%8B%E5%BC%8F)など、その科目の見出しとして使われる語のうち、後の方に出てくるのもので検索すると、有用なページが出てくる。

| サイト名                                                                                                 | 著者        | 学位                             | 備考                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------- | ----------- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [長旅Pの物理メモ](https://nagatabi-p.jimdofree.com/)                                                     | 長旅P       | 修士（理学）[^2]/物理学/?        | 各回10分程度、全10回程度の簡潔な解説動画がYoutubeおよびニコニコ動画にアップロードされており、有名。 |
| [らむねの物理法則](https://ramune-physics.blogspot.com/p/index.html)                                     | ?           |  (学部生（工学）)[^5]/?/?                            |                                                                                                                                                           |
| [ホーム - Understanding Theory of Relativity](https://home.hirosaki-u.ac.jp/relativity/)                 | 葛西真寿    | 博士（理学）/宇宙物理学/広島大学[^7]                                 | 相対論限定。                                                                                                                                                              |
| [武内　修 - 武内＠筑波大](https://dora.bk.tsukuba.ac.jp/~takeuchi/?%E6%AD%A6%E5%86%85%E3%80%80%E4%BF%AE) | 武内修      | 博士（工学）/薄膜・表面界面物性/東京大学[^6]                                | 講義用。量子力学、電磁気学限定。                                                                                                                                                                  |
| [物理とはずがたり – 物理学を学びたい人に向けて](https://storytellphys.wordpress.com/)                    | QuantumAtsu | 修士（理学）/物理学/京都大学[^4] |                                                                                                                                                           |
| [物理メモ](https://butsurimemo.com/)                                                                     | ?           | ?                                | ブログ風。これだけでは試験対策としては不足。                                                                                                                                |

| サイト名                                                                                                                | 著者      | 学位                                | 備考                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------- | -------------------------------------------------------------------------------------- |
| [EMANの物理学](https://eman-physics.net/)                                                                               | K. Hiroe  | 修士（理学）/物理学[^1]/?           |                                                                                        |
| [物理のかぎしっぽ](http://hooktail.sub.jp/)                                                                             | (多数)    | (多数)                              |                                                                                        |
| [ときわ台学/応用数学と応用物理，物性論の講義ノート（教材）](http://www.f-denshi.com/)                                   | 藤枝卓也  | ?/物理化学・材料工学/京都大学大学院 |                                                                                        |
| [KAWAMURA AKIRA'S CYBER WORLD](https://web.archive.org/web/20210512013149/http://home.p07.itscom.net/strmdrf/index.htm) | Stromdorf | ?（理学）/解析学[^3]                | 初めから相対論・量子論を駆使するため、初学者には厳しい。論理がサイト内で完結している。 |

[^1]: <https://eman-physics.net/greeting.html>
[^2]: <https://twitter.com/NagatabiP/status/1331080982414323712?s=20&t=kEy30ufi9nPZAo6AAi9b9g>
[^3]: <https://web.archive.org/web/20080509101159/http://home.p07.itscom.net/strmdrf/profile.htm>
[^4]: <https://storytellphys.wordpress.com/author-bio/>
[^5]: https://twitter.com/ramune_physics
[^6]: https://trios.tsukuba.ac.jp/researcher/0000000689
[^7]: https://hue2.jm.hirosaki-u.ac.jp/html/569_ja.html https://researchmap.jp/read0167806

## 数式を正しく反転しダークモードで表示できる拡張機能
数式は通常背景が透明であり、ほとんどの拡張機能では反転すべき画像として認識されない。そのため、数式を直接生成しておらず画像を使用している一部のサイトでは、cssを変更する必要がある。
```
img {
   -webkit-filter: invert(1);
   filter: invert(1);
}
```
### cssを変更できる拡張機能の例
- [Dark Reader](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)
   - 開発者ツールを開き、以下のコードを最後に追加し、Applyを押す。
<!---アルファベット順に並び替えられるため、後に編集しやすくするためにzzz.zzzを追加したが、削除しても良い。--->
```

================================

nagatabi-p.jimdofree.com
storytellphys.wordpress.com

CSS
img {
   -webkit-filter: invert(1);
   filter: invert(1);
}
```
- [Dark Mode - Night Eye](https://chrome.google.com/webstore/detail/dark-mode-night-eye/alncdjedloppbablonallfbkeiknmkdi)
   - Custom Code に上のスクリプトを入力すると、サイトごとに設定が可能だが、ro版を購入しなければホワイトリスト機能が使えないため、他の拡張機能を使っている場合、競合する可能性がある。

### cssを変更する必要のない拡張機能（非推奨）
- [Dark mode / night reader](https://chrome.google.com/webstore/detail/dark-mode-night-reader/hmafjphdklmdjfcnljjeonfpgafanjjc)
### 表示できない
- [Darkling Dark mode](https://chrome.google.com/webstore/detail/darkling-dark-mode/enofnamganfiiidbpcmcihkihfmfpobo)
<!---
- [Dark Mode](https://chrome.google.com/webstore/detail/dark-mode/dmghijelimhndkbmpgbldicpogfkceaj)
- [Super Dark Mode](https://chrome.google.com/webstore/detail/super-dark-mode/nlgphodeccebbcnkgmokeegopgpnjfkc/)
- [Dark Mode For Chrome]()
--->
