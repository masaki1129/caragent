# 無線通信を利用した事故予防のための駐車場案内システム

本研究では細かい駐車スペースを無線通信によって特定し, 利用者につたえることで駐車場内で迷うことなく駐車することを可能にするだけでなく, 
ドアパンチなどの自動車同士の接触を予防することで利用者が安心して安全に駐車ができること, さらに渋滞を避けることや店の入り口に近いところに駐車したい人,
ゲート付近にすぐに駐車したい人の意向を考慮した案内をすることで利用者にとって利用しやすい駐車場であることを目的とした駐車場案内システムを提案する.

## 使用するシミュレータ

artisoc4.2 (https://mas.kke.co.jp/artisoc4/)

### Installing

動作する開発環境の実装方法を段階に分けて説明する.

* Step 1: 以上のURLからartisoc4.2をダウンロードする.

* Step 2: Universeを右クリックし, 空間の追加から駐車場の構図を作成する.
universeにuniverse.txtを書き込む

* Step 3: 作成した駐車場を右クリックし, エージェントの追加から以下のエージェントを作成する.
車エージェント(caragent.txtを書き込む)
駐車場マップエージェント(mapagent.txtを書き込む)
壁エージェント
入口エージェント
店入口エージェント

* Step 4:初期値設定
・駐車場マップエージェント
それぞれの駐車スペースに店側優先IDとゲート側優先IDを設定する
・壁エージェント
壁にしたい座標に壁を作る

* Step 5:実行
実際に実行してみる.

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds


## Author

* **masaki nishi

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

